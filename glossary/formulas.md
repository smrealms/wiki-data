<!-- TITLE: Various Formulae -->
<!-- SUBTITLE: A quick summary of Various Formulae -->

# Combat

**Weapons**

**Player**

BaseAccuracy = Base accuracy of weapon currently firing, can be found on the weapon list
WeaponPlayer = Player currently shooting.
TargetPlayer = Player currently being shot at.
MR_FACTOR = 15

PlayerLevelAccuracyMod(Player) = (Player->Level*Player->Level/60 + Player->Level/2 + 2) / 100

PlayerAccuracy = BaseAccuracy + BaseAccuracy * PlayerLevelAccuracyMod(WeaponPlayer);

**Player vs Forces** = PlayerAccuracy
**Player vs Port** = PlayerAccuracy - BaseAccuracy * PortLevel/50
**Player vs Planet** = PlayerAccuracy - BaseAccuracy * PlanetLevel/350

GetMR(Ship) = round( 700 - ( ( Ship->Shields +Ship->Armour +Ship->CDs*3 )/25 +( Ship->CargoHolds/100 -Ship->Speed*5 +Ship->Hardpoints*5 +Ship->CDs/5 ) ) )

PVPAccuracy = PlayerAccuracy - BaseAccuracy * PlayerLevelAccuracyMod(TargetPlayer) / 2
MRDiff = (Max(0,GetMR(TargetShip) - GetMR(WeaponShip))/MR_FACTOR)/100

**Player vs Player** = PVPAccuracy - BaseAccuracy * MRDiff
Can also be found at: Google Docs Spreadsheet**(INSERT LINK?)**


**Port**

**Port vs Player** = BaseAccuracy * Port->Level - BaseAccuracy * PlayerLevelAccuracyMod(TargetPlayer)

**Planet**

**Planet vs Player** = BaseAccuracy + Planet->Level / 2 - BaseAccuracy * PlayerLevelAccuracyMod(TargetPlayer)

# Forces
## Combat Drones

BaseAccuracy = 3

**Player**

Damage = 2
Random(Min,Max) = Random inclusive integer
DroneAccuracy = BaseAccuracy + (Random(3,54) + Random(WeaponPlayer->Level / 2, WeaponPlayer->Level) - (TargetPlayer->Level - WeaponPlayer->Level)/3)/1.5
**Player vs Player** = Max(0,Min(100, DroneAccuracy - BaseAccuracy * MRDiff ))
**Player vs Forces** = BaseAccuracy + Random(3,54)
**Launched** = RoundUp(TotalCDs * XvsX / 100);
Can also be found at: Google Docs Spreadsheet**(INSERT LINK?)**


**Port**

Damage = 1
**Port vs Player** = 100


**Planet**

Damage = 1
**Planet vs Player** = 100


(???)
Damage = 2
**Forces vs Player** = BaseAccuracy + Random(3,54)


## Mines

Sector->Connections = Number of connections the sector has, including warps.
TOTAL_ENEMY_MINES_MODIFIER = 25
Damage = 20
Damage vs Fed Ships = 10 (50%)

BaseAccuracy = 100
Accuracy = BaseAccuracy - (TargetPlayer->Level + Random(1,7) * Random(1,7))
If player bumped mines: Accuracy = Accuracy / Sector->Connections^0.6

**Mines vs Player** = Max(0,Min(100, Accuracy + TotalEnemyMinesInSector / TOTAL_ENEMY_MINES_MODIFIER ))
**Launched** = RoundUp(TotalMinesOnStack * XvsX / 100);


# Experience

## Loss On Death

**Player % **= Max(0, 12 + (WeaponPlayer->Level + (TargetPlayer->Level - WeaponPlayer->Level)) * 0.25)
Exp Loss Spreadsheet**(INSERT LINK?)**

**Port %** = 31 - PortLevel

**Planet %** = 27 - PlanetLevel/10

**Forces %** = 30


## Gain

**Player Kill %** = 0.04875 + 0.03 * (TargetPlayer->Level - WeaponPlayer->Level) / max(TargetPlayer->Level, WeaponPlayer->Level)

**Player Damage** = Round(TotalDamage / 4)

**Port Damage** = Round(TotalDamage / 20)

**Planet Damage** = Round(TotalDamage / 20)

**Force Damage** = Round(TotalDamage / 20)


# Attack/Defence Rating

**Attack Rating** = (Shield Damage + Armour Damage) / 40
**Defence Rating** = (Shields + Armour) / 100
Note: CDs count as a total of 2 damage each and 3 armour, so CDs/20 for their component of the attack rating and CDs*3/100 for the defence rating.




# Ports

## Upgrading

Cost To Upgrade = Port->Level * 1,000,000
Upgrade Credits Added On Buy = Min(Goods * 1,000, BuyPrice)
Upgrade Credits Added On Sell = 0

## Downgrading

Number Of Downgrade Chances = RoundDown(DamageDone / 200)
Downgrade Successful = Random(1,100) <= 3

## Looting

```
Start Credits = (Port->Level - 1) * 2,000,000
```

## Restocking

**Tier 1**
150 * game speed per hour.

**Tier 2**
110 * game speed per hour.

**Tier 3**
70 * game speed per hour.

**Restock By Trading**

For every 10 goods of tier 1 you trade, then the supply/demand of tier 2 goods will increase by 9 each. When trading tier 2 goods it will restock tier 3 instead and tier 3 do not restock anything.



# Movement

**Sectors**
Turns = 1

**Warps**
Turns = 5

**Jumping**

**PerLevelFactor** = 0.02
TurnsDiffFactor = 1.2
TurnsPerSector = 0.65
MinimumTurnsToJump = 10
**TurnsToJump** = Max(MinimumTurnsToJump, Round(TurnsToWalk * TurnsPerSector))
**Max Misjump **= Max(0, Round( (TurnsToWalk - TurnsToJump) * TurnsDiffFactor / (1 + Player->Level * PerLevelFactor) ) )
Jump Formula Spreadsheet [Jump Formula Spreadsheet](https://docs.google.com/spreadsheets/d/1QCp7sfXHFfePiLLrYIosSW_xnRrzhLtvE1fFUJE9SQA/edit#gid=2) 



# Planets

**Inhabitable**

**Inhabitable Time** = Game->StartDate + Random(45, 85) ^3
This is equivalent to between 1d 1h18m 45s and 7d 2h35m 25s.



# Federal Space

**Relations**

You must have greater than or equal to 0 total relations to park in a race's federal space.
You get 72 hours notice in which to evacuate a race's federal space after a war vote has been declared, if you lose relations by some means other than a war vote then you do not get any notice to leave.

**Attack Rating**

**Safe Attack Rating** = Max(0, Min(8, RoundUp(Player->Alignment/150 + 3)))
0: <= -450
1: <= -300
2: <= -150
3: <= 0
4: <= 150
5: <= 300
6: <= 450
7: <= 600
8: > 600

**Illegals**

You may not have any illegal goods on you in order to be protected (slaves, weapons and narcotics are the illegal goods).