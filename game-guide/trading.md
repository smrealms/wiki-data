<!-- TITLE: Trading -->
<!-- SUBTITLE: It wasn't supposed to be this long -->

# A Short Treatise on Trading

## Trade Concepts

Trading is moving goods around.  We buy at one port and sell at another.  The goods only exist at the ports.  Ports do not change much under normal circumstances.  Not every sector in space has a port which creates a sort of scarcity.  That's about as complicated at the economics are in game for the time being.

What ends up being complicated are the thousand side decisions you have to make to realize the concept.  Everything from hazards in space down to ship selection will create situations where there are great and terrible choices to be made.  The bulk of this guide will be consumed with those types of decisions as they collectively drive the success of a trader.

## Port Goods

|Symbol|Good|Tier|Cost|
|------|----|----|----|
|![](https://www.smrealms.de/images/port/1.png "")|Wood|1|19|
|![](https://www.smrealms.de/images/port/2.png "")|Food|1|25|
|![](https://www.smrealms.de/images/port/3.png "")|Ore|1|42|
|![](https://www.smrealms.de/images/port/4.png "")|Metal|1|62|
|![](https://www.smrealms.de/images/port/5.png "")|**Slaves**|**1**|**89**|
|![](https://www.smrealms.de/images/port/6.png "")|Textiles|2|112|
|![](https://www.smrealms.de/images/port/7.png "")|Machinery|2|126|
|![](https://www.smrealms.de/images/port/8.png "")|Circuitry|2|141|
|![](https://www.smrealms.de/images/port/9.png "")|**Weapons**|**2**|**168**|
|![](https://www.smrealms.de/images/port/10.png "")|Computers|3|196|
|![](https://www.smrealms.de/images/port/11.png "")|Luxuries|3|231|
|![](https://www.smrealms.de/images/port/12.png "")|**Narcotics**|**3**|**259**|

**Bold** goods require evil alignment to trade.  These goods are more valuable and therefore more profitable.  Beware: entering a port with illegal goods on your ship will sometimes lead to confiscation and fines.  It is less likely to happen at higher level ports.

## Port Concepts

Every good at every port his a distance factor attached to it.  The distance factor is how many sectors to the nearest port that can complete the trade for that good.  It is shown to you on the buy or sell screen for that good.

Each good has a supply amount.  Tier 1 goods cap at 6000, tier 2 at 5000, and tier 3 at 4000.  Buying or selling a good reduces its supply.  When the port is out of supplies you can no longer trade that good at that port.  Profit margins also get tighter as supplies get lower.

Goods regenerate in two ways.  First, goods regenerate passively over time.  Tier 1 goods at 150 &times; game speed, tier 2 at 100 &times; game speed, and tier 3 at 50 &times; game speed.  Second, trading a lower tier good increases the supply of the next tier by 90% of the amount traded.  Tier 1 goods traded will add 90% of the amount traded to tier 2.  Same with tier 2 and 3.  Tier 3 goods traded do not regenerate anything.

Every port has a level between 1 and 9.  Ports level up primarily through goods being purchased there.  Levels can only be removed through port raids.  Ports can trade a number and type of goods depending on the port level as shown below:

|Port Level|Tier 1 Goods|Tier 2 Goods|Tier 3 Goods|
|-|-|-|-|
|1|3|0|0|
|2|4|0|0|
|3|4|1|0|
|4|4|2|0|
|5|4|3|0|
|6|4|4|0|
|7|4|4|1|
|8|4|4|2|
|9|4|4|3|

While a level 9 port will trade every tier 2 and tier 3 good, one tier 1 good will always be missing.

## Profit Mechanics

Ideal Buy Price = 0.03 &times; (Buy Value &times; Cargo) &times; (Distance Factor ^ 1.3) &times; (2 - (Stock Amount / Stock Max)) &times; (3 - 2 &times; (Relations / 1000))  
Ideal Sell Price = 0.08 &times; (Sell Value &times; Cargo) &times; (Distance Factor ^ 1.3) &times; (1 + (Stock Amount / Stock Max)) &times; (1 + 2 &times; (Relations / 1000))

These are the equations the game uses to calculate ideal buy and sell prices.  Take note the distance factor is the only exponential value.  This feature gives it more control over the equation than the rest of the values.  Though each of the variables can strongly affect prices.


It is possible, by using the equations above, to calculate the perfect value for each transaction.  It is an incredibly effective method to increase experience and profit earlier in the game.  It is also dangerously distracting to sit in a defenseless trade ship while keying in supply and relation numbers for every trade.  Experiment at your own risk.

## Experience Mechanics

Experience Gain = (Cargo Holds / 13) &times; Distance Factor

Moving goods with a greater distance factor is a huge part of gaining experience.  The person who moves the most goods along the longest route will usually end up with the most experience. **Remember**: the "distance factor" is not the distance you traveled, but the distance to the nearest port that has a complementary trade for the good you are buying or selling.

Experience is also tricky because of the bartering process.  There is an ideal price that must be guessed quite accurately in order to get full experience.  However, if your relations are 1000 or above, then the port will give you the best price without needing to barter.  Guessing the correct value is difficult due to the number of variables used in the calculation.  Most people opt simply to work their relations up as fast as possible.

## Relations

Every player has two types of relation numbers for each race.  There are personal relations which are what the members of that race think of you personally.  And there are political relations which represent what races collectively think of each other.  Your own actions directly influence personal relations.  Political relations are adjusted through council actions.

Racial ruling councils are made up with the top 5 experience players from that race.  Each of the 5 members are able to vote to adjust relations with another race each day.  Each of those votes adds or subtracts 15 political relations from one other race.  

The highest experience council member with 150+ alignment is made president.  The president has the power to call or veto votes.  Votes can trigger war, which sets political relations with another race to -400, or peace, which sets political relations with another race to 300.  While the president holds more power in this regard, the majority on the council ultimately has more authority.

The war and peace votes don't matter as much as you may think.  Any race that gets to -300 is considered to be at war.  Any race that gets to 300 is considered to be at peace.  The declaration doesn't have to happen via a vote called by the president. Instead, it can happen slowly over time by the daily relations votes by council members. 

There is a [section on political councils for more detailed information.](https://wiki.smrealms.de/game-guide/politics)

Relations are very important to trading.  It is nearly impossible to turn a profit at a port when your relations are low.  If you are on the council it is imperative that you vote.  Either vote to improve relations with the races who own the ports you trade.  Or vote to reduce relations with others who are sapping your routes.  Remembering to look at the council screen daily is an important part of trading.

The primary way to increase your personal relations is to trade.  Every successful buy or sell action improves relations.  You get one point of personal relations for every 30 cargo you trade up to 300.  This holds true until you have 500 personal relations.  After that you only get one point per trade regardless of other factors.

Some players will trade special routes or use tactics specifically to gain relations quickly.  Trading at two adjacent ports will make more relations per turn than any longer route.  It's a fast way to make it to 500 personal relations.  Remember, after 500 each trade made will generate only 1 more point.  Traders will sometimes then switch to buying or selling one good at a time to finish their relations gain.  You lose some experience and credits by doing this but it gets you through the grind very quickly.

Also take note that effective relations are personal plus political.  Your council may declare war but if you have 2000 personal relations it does not change what ports are open to you.  The opposite may be true if your personal relations are extremely low.  As a trader, you just stay focused on keeping your effective relations above -300 in order to keep ports open to you.  And keep grinding the ports you trade with to 1000 so you get full experience and the best profits.

## Overhead Costs

Federal protection costs no credits but you have to spend turns to get there, which can impact your trading efficiency. How far do you have to go to get from safety to your route?  How far do you have to go to return to a Federal protection after you are done trading?  Do you have to go out of my way to get to the bank?

While overhead values are usually small they will influence ship selection.  If you have to spend 20 turns to trade every day or two that is two hours worth of turns at 10tph or five hours at 4tph.  In that scenario you don't just spend less time getting there.  You use the saved time to trade and turn a profit.

Those of you with stronger math skills will have a nagging idea of the slower ship taking longer to build turns, making fewer trips, and coming out equal.  The concept is correct but it clashes with the limitations of routes.  Namely supply.  There are very few scenarios where you can show up to a route and trade 500 turns with 500 cargo holds.

There is also a noteworthy overhead to buying and selling goods.  Each transaction costs one turn.  For this reason it is always most efficient to trade one type of good at a time

## Finding a Trade Route

Finding a route is a matter of finding ports with good distance numbers.  It's an incredible amount of work to do it by hand so players have built applications to compute the routes for us. 

Download an SMR file using the button on the lower left panel after you have the galaxy fully explored.  Use The Lazy Trader to open the SMR file you downloaded and use the trade routes function to compute routes.  You will have to configure which goods you can trade depending on your alignment and which races you can trade with depending on your relations.

The Lazy Trader can be found at [the game guide page for it](https://wiki.smrealms.de/tools/lazy-trader).

Also realize that scouting the galaxy costs quite a few turns.  Alliances are able to share maps which means the task can be split and the burden reduced.  This is a heavily team based game even when you're trading.

## Trade Ships

The efficiency of a trade ship depends on both its size (number of cargo holds) and its speed. For example: A slow ship with lots of cargo holds may be good, but a ship with fewer cargo holds may be better if it is much faster. This can be referred to as *trade power*.  It is measured by multiplying the number of cargo holds by the turn rate.  Calculate for many vessels to produce a chart like this:

|Ship|Cargo|Turn Rate|Trade Power|
|----|-----|---------|-----------|
|Trip-Maker|235|12|2820|
|Freighter|250|10|2500|
|Planetary Trader|300|8|2400|
|Deep Spacer|300|8|2400|
|Advanced Courier Vessel|235|10|2350|
|Planetary Freighter|450|5|2250|
|Deal-Maker|200|11|2200|
|Inter-Stellar Trader|300|7|2100|
|Stellar Freighter|225|9|2025|
|Planetary Super Freighter|500|4|2000|

These are the top trade ships.  People who are serious about trading will always find their way in to one of them.

|Ship|Cargo|Turn Rate|Trade Power|
|----|-----|---------|-----------|
|Leviathan|240|7|1680|
|Expediter|180|9|1680|
|Favored Offspring|200|8|1600|
|Blockade Runner|175|9|1575|
|Merchant Vessel|170|9|1530|
|Drudge|250|6|1500|
|Vengeance|170|8|1360|
|Ambassador|150|9|1350|

These are mid tier trade ships.  They are a stepping stone towards one of the top ships.  Notice some are poor alternatives to a Merchant Vessel.  Note: the Merchant Vessel has the same trading stats as a Newbie Merchant Vessel. 

|Ship|Cargo|Turn Rate|Trade Power|
|----|-----|---------|-----------|
|Small-Timer|100|9|900|
|Slip Freighter|60|9|540|
|Swift Venture|60|9|540|
|Tiny Delight|60|8|480|
|Medium Cargo Hulk|60|8|480|
|Light Freighter|60|8|480|
|A Hatchling's Due|60|7|420|
|Redeemer|45|9|405|

These are the starting ships for players who have ranked out of a Newbie Merchant Vessel.  Never take a NMV for granted.

Note: I have intentionally left a good number of ships out of these charts for the simple fact that they are either poor traders or circumstantial trading choices outside the scope of this wiki article.

## Ship Selection

|Ship|Cargo|Turn Rate|Trade Power|Credits|Total Health|Combat Drones|Scouts|Mines|S|C|I|J|S|
|----|-----|---------|-----------|-------|------------|-------------|------|-----|-|-|-|-|-|
|Freighter|250|10|2500|5791393|600|0|0|0|Y|N|N|N|N|
|Planetary Trader|300|8|2400|5983335|760|10|5|15|Y|N|Y|N|N|
|Advanced Courier Vessel|235|10|2350|556740|500|0|0|0|Y|N|N|Y|N|
|Planetary Freighter|450|5|2250|6115028|1350|0|5|15|Y|N|N|N|N|
|Inter-Stellar Trader|300|7|2100|5914159|670|15|5|25|Y|N|N|Y|N|
|Stellar Freighter|225|9|2025|7008455|650|0|10|15|Y|Y|N|N|N|
|Planetary Super Freighter|500|4|2000|6235792|1950|0|5|50|Y|N|N|N|N|
|Leviathan|240|7|1680|122251|800|0|25|100|Y|N|N|N|N|
|Expediter|180|9|1680|1272250|850|0|0|0|Y|N|N|N|N|
|Merchant Vessel|170|9|1530|825408|620|15|5|5|Y|N|N|N|N|
|Drudge|250|6|1500|875683|955|10|0|10|Y|N|Y|N|N|

This chart contains all of the more efficient ships along any non Alskant upgrade path.  Regardless of your starting ship the most effective mid tier trader is usually a Merchant Vessel.  The most effective top tier ship will depend highly upon you and the route you mean to trade.

The best mid tier for half the races is a Merchant Vessel.  The few others listed here are also cost effective.  Thevians should be mindful that an Expediter cannot mount any weapons to shoot forces with.

Dangerous routes are best handled by a ship with a lot of defenses (shields and armor). The PSF and PF are the best options for this.  A cloaked SF is sometimes also appropriate but that is circumstantial.

Long routes over about 13 distance are best traded with a jump ship.  The speed of an ACV makes it the most efficient ship for this purpose; however, an IST has forces that help make trading a bit safer.

A freighter is amazing when you aren't going to be shot at.  Use caution.

## Alskant Trade Ships

Alskant ships are the strongest traders in the game.  Every single one of their trade ships is the best in some way.  Here they are in the same format as the neutral traders:

|Ship|Cargo|Turn Rate|Trade Power|Credits|Credits/T.P.|Total Health|Combat Drones|Scouts|Mines|S|C|I|J|S|
|----|-----|---------|-----------|-------|------------|------------|-------------|------|-----|-|-|-|-|-|
|Trip-Maker|235|12|2820|1354955|481|350|0|0|0|Y|N|Y|N|N|
|Deep-Spacer|300|8|2400|5721889|7629|750|50|20|25|Y|N|N|Y|N|
|Deal-Maker|200|11|2200|5727059|2603|540|30|10|15|Y|Y|N|N|N|
|Trade-Master|200|9|1800|12095764|6720|1500|100|25|100|Y|N|N|N|Y|

The Trip-Maker is your mid tier trader.  It is the strongest trader in the game and a death trap with 350 total defenses.  Get in it quickly, trade until people start hunting, and move on to a larger ship before you get podded.

The Deep-Spacer is an excellent general purpose trader as well as the top jump route trader in the game.  This is a common ship to see Alskant traders in because it's often the best choice.

The Deal-Maker is the strongest cloaked trader in the game.  You will not see them often but they fill a fun niche when the game allows for it.

The Trade-Master is a misnomer.  It is surprisingly a bad choice for trading.  It's true purpose is alliance support.  Those roles are covered in a different guide.

## Further Ship Considerations

Remember to calculate and consider overhead.  If you're trading through fed space a slow ship isn't wasting much.  If your route is 25 turns from safety you will fall desperately behind in a slow ship.  At some point you want to look at a jump ship or try to gain enough experience to cloak for protection.

Will you be be fired upon?  Expect to see 200-400 damage per shot incoming depending on what exactly is shooting you.  But every so often the number will be twice that.  Expect to see 1-3 shots per second.  Stay on your toes and expect to get podded once in a while regardless.

Never underestimate forces.  Scouts can provide valuable warning when a hunter enters your space.  Mines slow down anyone who hits them.  A single combat drone is able to absorb all 300 damage from a Nuke.

A well configured illusion generator may confuse someone for just long enough to save your ship.  But hunters quickly learn to expect it.

## Routes Length Is Important

This can't be said enough.  Longer routes allows higher distance factors which helps everything about trading in a major way.

Trade profit increases very quickly with increasing distance factors:

|Distance Number|Multiplier|
|---------------|----------|
|1|1|
|2|2.46|
|3|4.17|
|4|6.06|
|5|8.10|
|6|10.27|

The longer the route, the more each good is worth in terms of credits.

If experience is what you're after, here are some sample values per trade at each distance:

|Route Length|100 Cargo XP|200 Cargo XP|300 Cargo XP|
|------------|------------|------------|------------|
|1|8|15|23
|2|15|31|46
|3|23|46|69
|4|31|62|92
|5|38|77|115
|6|46|92|138

## Dumping Goods

Dumping of cargo can be used to convert experience in to credits.  This is done by manipulating port resupply.  Say you've run out of luxury goods to trade but there are still tier 2 goods in the port.  You can buy the goods and dump them until the luxury goods are resupplied enough to keep trading.

The experience loss I mentioned is indirect.  The buy and loss action is a net 0 for experience but costs you two turns.  Further, the resupply rate is 90% so you need to buy/dump 1.11 times to resupply one trade.  Every buy/dump run effectively tacks on 2.22 turns to the run.  That makes the same route cost 37% more turns on a 1 sector route and a 13% more on a 6 sector.  You can force a lot of cash out of a route like this but it is often better to swap to another route.

The effective way to use dumping is to keep good supplies nearly topped off.  The reason is in the supply portion of the ideal price equation.  If supply is 0 that feeds a 1 multiplier into the equation.  If supply is full then it will be a 3.  Keeping a port full will get you three times the credits.  This can be significant if you're hard up for cash.

## Smuggling

All ships are checked for illegal goods at random, but it is possible to reduce how frequently this occurs.  A port checks 15% of ships for illegal goods by default.  It is possible to reduce the chance by 16%.  There is a 4% reduction for each illegal good a port trades, up to 3 max.  There is also a 4% reduction when flying an evil aligned ship (Thief, Assassin, Death Cruiser).

When you get caught smuggling the goods are confiscated and you are fined by the port authorities.  Smuggling fines are based on the sell value of cargo and the port level.  Smuggling fines can be very expensive.  You also lose 5 alignment points when you are captured.

The Thief is the only evil aligned ship that should be considered a trade vessel.  Here are the stats as compared to the ship section:
|Ship|Cargo|Turn Rate|Trade Power|Credits|Credits/T.P.|Total Health|Combat Drones|Scouts|Mines|S|C|I|J|S|
|----|-----|---------|-----------|-------|------------|------------|-------------|------|-----|-|-|-|-|-|
|Thief|160|12|1920|10802157|5626|640|30|0|5|Y|Y|N|N|N|

It is not a great trade vessel for a couple reasons.  The biggest problem is the trade power is so low.  And what makes it harder to justify is the high cost.  There are stronger trade ships of every variety for less than 2/3 the price.  For these reasons, they are not often used.  The only real benefit you get from buying one is the ability to steal.

If you enter a port with an evil aligned ship you will have the option to steal goods.  If successful, the goods will appear in your hold at no cost and you will receive full experience for the trade.  There is a chance of failing as shown here:

|Port Level|% Chance to be Caught|
|-|-|
|1|9|
|2|8|
|3|7|
|4|6|
|5|5|
|6|4|
|7|3|
|8|2|
|9|1|

When caught stealing goods you will be fined.  Theft fines are based on the ports best price for the goods being stolen.  Because this is the buying side fines are not significant.  You also lose 5 relation points with the race that owns the port.

Stealing has more serious ramifications beyond being caught.  Where a normal trade would build relations stealing does not.  This, in combination with lost relations when you are caught, makes theft a terrible idea when relations are below 1000.  Further, stolen goods do not regenerate higher tier goods.  This can cause your routes to drain early and severely shorten profits.  These effects limit the scenarios where stealing is efficient in terms of profit.

Also remember authorities may remove credits directly from your bank if you haven't got enough to cover the fine.

## Hazards

Hunters are human.  That's one of the things that makes this game interesting.  The problem is this is a trading guide which means we are prey.  You are the prey and you will be hunted by people who learn and adopt new tactics as time goes on.  When caught off guard you will most likely lose your ship in a hail of weapons fire.

One of the simplest ways hunters search for prey is watching the experience of other players.  Experience is only gained from certain actions, and trading has an obvious signature.  The amount of experience you gain give clues as to how large your ship is and where you may be trading.  It is nearly impossible to trade without others knowing it.

The current player list is a fundamental tool for hunters and traders alike.  The count at the top is the number of players who have loaded or refreshed a page in the past 10 minutes.  The list of players are those who have moved in the same time period.  These are a good indicator of people being around but not perfectly accurate.  It is possible to leave the current player list open for much longer than 10 minutes.  You never know who is watching.

The current hall of fame is an absolute goldmine for espionage.  Covering it fully would require a separate guide.  For the scope of this section just be aware of it and take a look to get an idea of what is there.

Trading often means dealing with forces.  Scouts send a message to their owner when a ship passes through.  Combat drones provide armor and deal damage.  Mines deal damage and interrupt you with a combat screen when you enter a sector.

Scouts can be the greatest ship saving tool for a trader.  Place them at the entrance to the galaxy where you're trading.  Place them in key sectors along your route.  You will get a message when someone is coming for you.  That's your air raid warning telling you to take cover.

Scouts are also the front line tool of hunters.  They will stick them anywhere they think people are trading.  Scout drones permit them to accurately map when and where you are trading or even where you seek safe haven.  Depending on the circumstance you may want to spend the turns shooting them down.  No matter what, understand they have alerted someone to your whereabouts.

Mines can be a defensive tool for a trader.  Place one at the ports you are trading.  Hunters entering the sector to fire upon you will hit the mine.  The damage is useless but it causes them to have to load one extra pae before being able to target you.  Sometimes that's enough to survive.

Mines are also used in the same fashion by hunters.  Understand they don't want you to die to the mines.  They don't get any money or experience from that.  But they will lay one or two along your escape route if they can anticipate it.  This will slow you down while running back to safety and may land you in a pod.  Be ready to hit them and keep going when the time is right.
