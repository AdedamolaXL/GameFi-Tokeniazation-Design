# AILand_Tokenization

## OVERVIEW 
This tokenziation model is loosely based on AILand ( as designed by agwisniewska). Set in a alternate year 2022 where futuristic AI-driven cars are active. Players undergo missions with the purpose of helping habitants of AILand to navigate their daily life by transporting them or their deliveries to their desired destinantion.

This paper will focus on the design of a dual-token system connected with the numeric design of the game, with the aim of monetization which provides monetary and non-monetary benefits to gamers, investors, governors and developers as well.

## UNDERSTANDING THE PROBLEMS
1.  The relationship between the token model and the numeric design.
2.  The distribution of the token 
3.  The DAO governance


### 1. TOKEN MODEL x NUMERICAL SETTINGS 
The token economic model within the GameFi ecosystem involves the tokenization of the in-game currency for exchange of resources and source real-money revvenue. Coupled with the numerical setting, tokens may be used to buy and convert resources as well as serves as the basis of the governance system. 

For AILand, using a dual token system - of utility(AUT) and governance token(AIL).

Numeric system - 
resources you pay for - charging, upgrades, cars, repairs.
points you win - ratings, clean body, passengers/day, beat competition. 

Inflationary model, no cap. 

#### NUMERIC DESIGN
The numeric design will be the basis of the token model. The NEV-CAR is the central resource in this game. The player levels up when the car completes the mission. To complete the mission the player needs to get to the destination in time. Once the mission is completed the player is paid in in-game token (AUT). 

**NEV-CAR & CAR HEALTH**
The core asset of the game is the NEV vehicle. Players get to train with a basic NEV-CAR in L1(which is the tutorial level), after which they will purchase cars and upgrades from the DeAuto garage. Important features of a car includes:

*Charge*, is the electric fuel percentage of the car. All cars have a base charge of 60% when newly bought. Charge is a naturally depletive resource within the game. It depletes with car activity during missions in the game. Charging replenishes it and can be done in DeAuto garage, during this period, the car is not active and can't take part in missions.

*Durability*, refers to how strong/fragile a car is. It's a measure to how much a car can withstand attacks like hits from other vehicles, virus attack, hacks from malevolent traditonal car owners and general obstacles within the game. Highly durable cars are often available in the higher levels than the lower levels because of price and the level of skill needed to acquire it. Hence at level 2, you may have a car with a durability of 30%. Durability takes a hit during attacks and can only be restored through repairs in the DeAuto garage. Highly skilled players or highly durable cars may be able to avoid attacks

*Upgrades*, are tiny but effective improvements to existing car parts which can make the car more durable, charge faster, or store more charge. Beyond car health, upgrades also makes the car faster, have more utility for specific missions and design or more aesthetically beautiful.

All of this features aggregate into the singular most important metric within the game Car Health(CH). CH is a measure of a car capability to carry out a mission, a car with a an high health level of say 92% is faster, stronger, while another with 13% is severly weak. At 0% the car automatically switches off and it's unable to take part in missions, hence earn money. Thus it's important in the game, to watch the car's health and improve it. This means charging it at appropiate times, buying more durable cars as the player progresses through missions.

The calculation for CH;
CH = Charge(50%) + Durability(40%) + Upgrades(10%)

For example to calculate the car health of a NEV-CAR at level 1 in AILand with the following characteristics;
Charge = 60%
Durability = 20%
Upgrades = 0.

Car Health = (60 x 0.5) + (40 x 0.4) + (0) = 38%

If a car runs out of health, it's unable to work and carry out missions. At lower levels where players can't have access to better cars with durability, they may need to focus on keeping their car charged consistently.

**COMPLETING MISSIONS AND GETTING PAID**
Completing missions, means getting paid, failure to complete means you don't get paid. Players are paid in AUT, the in-game currency for purchasing utilities.

Fee calculations is based on the distance covered for and the mission's complexity. For example, a mission of level 2 complexity and distance of 200m;
Fee = Distance x Complexity of Mission = 200 x 2/10 = 40 AUT.
Thus if a player completes this particular mission, they automatically earn 40AUT.

* Distance (m). Minimum distance is 100m. 
*maximum for each level
* L1 = 100m 
* L2 = 300m
* L3 = 600m
* L4 = 1000m
* L5 = 1500m
* L6 = 2100m

Complexity is how hard the mission, there are 10 acts of complexitites for each level, e.g: mission of complexity 2 = 2/10.

Thus, Fee = Distance x Complexity = 100 x 2/10 = 20 AUT

Hence the highest amount a player can earn at the highest level of L6 is 2100 AUT.

For each mission, the distance generated will be random however, to make expected earnings harder to predict for players

100m = 1min
1/10 = x1

Speed = 

Acceleration

**GENERAL NUMERIC METRICS AND THEIR RELATIONSHIP**

**SUPPLY, DEMAND AND MONEY SINKS**


#### Money Sinks.

Electric Charging => 1000mH = 100% = 10mins driving time = 5 AUT.
Solar panels (only accessible after L3) = unlimited driving time = 

Repairs = Number of Hits x Fragility of Cars = 2 x 8 = 16 AUT. 
* the fragility of cars will be one of the key features to consider when buying a car

**Upgrades

* Motor = Top Speed 
* Reducer, Wheels = Acceleration
* Nitro, ECU = Nitro 
* Battery, Charger = Power
* Utility, aesthetic = Design

Unit Price x Class = 10 x 4 = 40 AUT.

Ratings

Durability of the car = 100%
@ 0% car is spoilt and can't move again
thus a car has to repaired whenever it is hit, to continue performing.

governance token can be exchanged for game token but not vice versa directly.

introducing randomness/scarcity to upgrades and cars.

> Profit for player = Fee - (fuel + repairs)

#### Tokenomics 
External Asset Inputs + Internal Asset Inputs = Monetary Gains + Non-monetary Gains

External Asset Input = advert placement, game-cobranding. 

Maintaining the balance between the demand and supply of tokens. 

Demand increases with the more players play the game while supply increases with the more players complete the missions. 

In this game, demand will technically always be higher than the supply because it's impossible for the number of missions completed per day to be higher than the number of missions started per day. What we are really monitoring then is the rate of supply vs rate of demand i.e the rate at which players complete the game vs the rate at which players start the game. Hence as the number of players playing the game decreases, also the lesser the number of players completing the game. Hence in this case, supply is dependent on the demand.

Hence the token price will fall, if players stop playing. The solution to figure out then is how to keep players playing the game. From the pure gamer perspective, this involves making the gameplay as exciting and addictive as possible which engages the player to keep playing, keeping the demand and consumption higher, hence the token price on a high.

1. Controlling inflation and the supply of tokens is directly tantamount to controlling players progression in the game and how much they can earn at every period in time. This involves managing periods of player surge which is likely to occur in the beginning of the game. The gameplay at L1 doesn't provide much earnings, this encourages player investment to progress to L2. Player investment is important because it creates a group of core players who play the game for its own sake of competitiveness, leaving the period of actual earning in the game stimulates this same spirit. Stages between L2 - L3 are quite critical, here players are grinding hard to earn AUT tokens, AUT purpose however is for utility payment within the game and trading in the marketplace. It's only at L4 and beyond that players begin earning real money and by this time their is considerable investment in the game. From L4 and higher, players start earning AIL which is the governance and staking token which is direclty convertable to fiat currency.

2. Introducing probabilities and unpredictability into AIL earnings. 
AIL is calculated by;
AIL = ratings + clean body + beat the opps + passengers per day.
ratings = depends on the % time you are able to save by arriving at your destination earlier. this will always be variable.
clean body = state of the car after a mission = durability - hits * viruses * obstacles (all of this negatives are random but are usually higher as you progress)
passengers per day = no of missions completed/no of passengers carried.
beat competitors = this is the damage you can cause!? * non monetary awards * titles.
upgrades and car prices = price fluctuates with the game state

3. AIL should be harder to acquire than AUT. It should also be consumed at critical stages when progressing to the next level. This aids game-longetivity and internal circulation. Token consumption should be higher than Token acquistion. Token consumption will be consistently spent on in-game resources which players need to get better. All transactions should be done within the game/marketplace using AUT/AIL and cashing out attracts a % levy.
Levy is determined by:

    Time: The longer you sell the equipment after acquiring it, the lower the tax will be
    Quantity: The more quantity sold within a certain period, the higher the tax will be
    Seniority: The more hours a player has spent and the more honors they have earned, the more tax relief they will receive

4. The core asset of the game which is the NEV-CAR should be consistently upgraded and repaired 
5. Players level at any point in the game becomes a source of self-identification and culture which creates a clear structure of different needs, benefits and perks. Tokens are distributed differently for each level.




####SKETCH

What does a token model need?
>input of external assets
>diversified non-monetary gains
>solve the cyclical contradiction of new demand of growing player vs new supply of tokens
>pay attention to the utilization efficiency of the currency as well as game resources.
> The leasing of the economic system

=== external assets input + internal asset input = monetary gains + non monetary gains

external assets input = finding ways in which players play/put in their money not just to make more money also includes alternatives ways of inviting investment; advertisment, sponsorships, partnerships, game-cobranding, IP operation

non-monetary gains = extending game incentives to be beyond money

### 2. TOKEN DISTRIBUTION x CREATOR ECONOMY
> High APR >> Many new users >> APR drops, lack of new users & token consumption >> excessive token in the system >> supply/> demand, price drops.

Distributing tokens amongst players, and recognizing players as co-creators of the in-game assets being traded and used. To start with AILERS will be broadly divided into three groups: Beginner, Grinder, Flayer, Whaler with all AILERS starting as Beginners and then progress up the food-chain to be a whale. 
When you start the game as a beginner, you get 100points(NS) to start with. To become a grinder, you have to grind and make 1000points at which point you can now exchange for utility tokens, 100points = 1 token.
To become a flayer, you need to acquire 20 tokens. 10 utility tokens = 1 governance token.
To become a whale, is just for flex, and you will need to burn 100 tokens = for regenerative NFT.

The whole point of this player stratification is to incentivize the playing of the game itself, control players growth in the game and inflation. Managing player entry surges into the game by putting them through a preliminary stage where they do not have access to the game currency immediately will help solve the discrepancy between demand and supply for tokens. This approach works in the later stages in which selling tokens indsiscrimately is discouraged because you have to stack your coins to a sufficient level to move from a grinder to a flayer with governoship abilities in the DAO. Correspondingly the move to becoming wahle inspires the same principle of holding on to your coins due to the perks available to the whale. Plus, whales won't actually be able to to sell their regenerative NFT due to it being soulbound though it will sure come with goodies and real life merch as well. 

With different level comes differnet needs, which establishes a clear system of self-identification and aspiration. Using user profiles, with unique access to different game modes and types according to their levels. This also includes a diversification of the rewards system. The tokenomics designed for each user profiles will stimulate their spending power in different ways according to their levels. 

The creator economy and the leasing of NFT assets owned by the players. Leasing means lending in-game assets like equipment owned by players to other players so they can make use of it while paying rent on it. 
This has two advantages: one, players don't have to sell their NFTs outright and also solves the liquidity problem for very skilled players who can turn in a little bit of revenue for themselves by renting, it also helps upcoming players to get better and have access to superior game experience above their level. The monetary and non-monetary value for both sides of the divide represents a win-win solution.

For example the repair costs will be different for each level, so will the probability of failure for each level, the gameplay, access to high-level equipmeent
The presence of Whales, Flayers for instance brings in a great inflow of external funds to the game.

Players shoudld be incentiivized to upgrade their core assets, achieving the aim of consuming the original assets which promotes internal circulation of the economy. This will be done is such a way that upgrading means improved game experience.

The governance token has been designed to be harder to come by to curb inflation, also exploiting it in critical stages close to the end of game season by consuming it is useful for internal circulation and game longetivity. Also if inflation becomes too high, it's neccessary to adjust the ratio between game token and governance token. also do they need to be independent of each other?

Make the game formula had to exploit, make the reward system hard to predict. 

Investors 
* Seed Investors
* Governors
* Portfolio Investors
* Crypto Traders

### 3. DAO GOVERNANCE


