
# Chapter 2

## 2.1 Introduction (DRAFT)

In this chapter a brief overview of how the bulk electric grid operates and its history is provided. Potential challenges in the current distribution networks are discussed. An introduction into a peer-to-peer (P2P) energy trading solution is provided. Finally the motivation is presented with a broader outline of the covered topics and the structure of the document. 
In recent years, there has been an urgent pursuit of an alternative energy system in which energy production, transmission, distribution, and consumption can take place in an environmentally sustainable fashion. As a result, the development of smart, sustainable, and green solutions is becoming more significant, including the widespread deployment of distributed energy resources (DERs) at residences [1], the introduction of electric vehicles (EVs) [2], and the establishment of various smart energy services, e.g., demand response management [3], for the effective management of energy resources within the electricity grid. Consequently, different signal processing techniques, e.g., machine learning, artificial intelligence (AI) [4], and game theory [5], have been offered as solutions to consumers.


## 2.2 History of Electricity Markets

The electric utility industry was first founded in 1879 and has been subject to many municipal, state, and federal regulations for more than two centuries. The electric utilities are considered "natural monopolies" because the production efficiency would be higher when a single firm supplies the entire market [1]. In 1935 the United States Congress passed a law to regulate electric utilities at the state level. The Public Utility Holding Company Act (PUHCA) [2] enforced state regulation making the utility companies incorporate in the same state they were operating in. They also owned the monopoly of that market and were forced to set prices based on the "fair rate of return" [3]. Then, from the 1940s to the 1960s, the electric industry overgrew because of the demand for energy usage. The increase in use created environmental concerns and concerns about over-dependency on foreign oil. The need for regulation to limit emissions and reduce oil usage led to the 1978 Public Utility Regulatory Policy Act (PURPA) [4]. The law was designed to promote the adoption of renewable resources and efficient generation [2].

The most interesting component of the incoming regulation was that it also forced utilities to buy power from independent companies that could produce power for less than what it would have cost the utility to generate the power, called "avoided cost," promoting competition into the power generation business [5]. A new class of exempt wholesale generators prompted the Federal Energy Regulatory Commission (FERC) to initiate open transmission access. The independent generators could now dive deeper into renewable generation across the country. By the 1990s, the most prominent initiative was in the California Power Exchange (PX), a regional spot market for buyers and sellers to trade electricity. [6] The California ISO was started in 1990 and was designed to operate the state’s power transmission grid and provide open access to all qualified users [7]. Even with competition in the market, the PX prices remained high because of collusion by power producers and power brokers. Order 888 by FERC was passed to introduce competition at a wholesale level, but the market had fluctuating prices and resulted in an energy crisis [8]. Manipulation of the market by nefarious companies such as Enron led to stricter regulation around operating the market. The requirements for the market to be more flexible and capable of integrating renewables is also an inevitable challenge [9].

## 2.3 The Smart Grid

“The grid” refers to the electric grid that consists of a network of transmission lines, substations, transformers, etc., which transfer the electricity from the power plant to the home or business [10]. The average age of power plants in North America is 35 years old. Also, more than half of the electricity in North America is generated through coal, and the delivery efficiency of electricity is an abysmal 35%. Finally, frequent and major blackouts in the past indicate critical vulnerabilities in the electrical infrastructure [11]. The challenges of creating a more efficient grid led to the adoption of smart management systems that can intelligently integrate the actions of all users connected to it, including generators, consumers, and those that do both to efficiently deliver sustainable, economic, and secure electricity supplies. The result is a "Smart grid", an advanced power system that integrates the electrical network with smart digital communication technology. Providing bi-directional communication between the utility and consumers, leveraging smart sensors across the system [11].

Conventional electric power systems in most countries have been designed so that a central power station produces electrical power. Then transformers increase the voltage to high levels, which are suitable for transmission. Once the energy arrives at a community, the voltage is gradually stepped down to lower levels into the distribution network until it is finally dropped into the consumer’s premise. The energy is then measured by a meter that keeps a record of the energy consumption in real-time [12]. The flow of electricity was traditionally uni-directional, but in the age of distributed generation, the grid must also deal with bi-directional flow back to the grid from producers who used to be customers.

The Smart Grid must grow to incorporate the bi-directional flow of electricity between supply and demand sources as penetration of Plug-in Electric Vehicles (PEVs), and distributed energy resources (DERs) like Photo-voltaic Solar Panels (PV) increases in residential sectors. The American Recovery and Reinvestment Act of 2009 (ARRA) [13] was designed to address the smart grid transition improving in the following areas :
	•	Reliability – the reliability of the grid will be improved by several factors, including fewer disturbances and blackouts.
	•	Economics – by reducing the electricity rates and creating new jobs, and enhancing the US gross domestic product
	•	Efficiency – by reducing the costs associated with the generation, transmission, and distribution of the electricity
	•	Environmental – by reducing the number of emissions by increasing the integration of renewable resources.
	•	Security – by reducing the probability of manmade attacks and natural disasters.
	•	Safety – by reducing the consequences of any grid-related events

The reliability, economics, and efficiency of the grid will improve as communication technologies transition into advanced implementations of hardened sensor networks across the grid known as the industrial internet of things (IIoT) [14]. The IIoT improvements to the grid can affect the energy generation efficiency, demand-side management, and even the transmission and distribution of energy for energy carriers. In addition, the more data the grid provides in real-time allows for optimization leading to greater reliability and efficiency, reducing the cost of electricity[15].

The environmental, safety and security aspects of the grid will improve as the adoption of distributed generation and energy storage improves. DG systems are typically renewable as roof-top solar (PV). The environmental benefits of renewables in the short term are attractive, but there is still an environmental cost to create PV technology. The distribution of generation and adoption of microgrids could decentralize the security risk of the current grid, improving its overall reliability and increasing resiliency. The overall challenges of the smart grid are many, but driving technological trends seem to point to a redesign of the infrastructure and the market structure that operates it. The increase of DG and renewables with the rise in retail electricity prices and the decreasing of profitable incentive tariff rates are all challenges for the grid.[16]


## 2.4 Residential Roof-top Solar

In recent years, there has been an urgent pursuit of an alternative energy system in which energy production, transmission, distribution, and consumption can take place in an environmentally sustainable fashion. As a result, the development of smart, sustainable, and green solutions is becoming more significant, including the widespread deployment of distributed energy resources (DERs) at residences [17], the introduction of electric vehicles (EVs), and the establishment of various smart energy services, e.g., demand response management, for the effective management of energy resources within the electricity grid. DERs such as roof-top photovoltaic (PV) systems and energy storage systems promise to alter the electric grid by decarbonizing and decentralizing energy services. The end-users of energy are no longer just consumers of energy but also producers, leading to a new term, "prosumers." DERs are becoming more affordable for the average homeowner. Products such as Tesla's Powerwall and Solar Roof make it likely that the adoption of these technologies will continue to grow.[18] In addition to commercial adoption, political policies are now in place to push the adoption of these technologies to aid in the reduction of dependencies on fossil fuels.

## 2.5 Net Metering

Net Energy Metering (NEM) is a compensation mechanism to encourage the adoption of residential PV systems, commonly referred to as net metering. It allowed the flow of energy to feedback into the utility grid, forcing the negative pricing of electricity to be paid back to the user [19]. The utility would have excess generation from the home that could compensate for the load of neighbors nearby. NEM encouraged consumers to spend money on PV systems without government subsidies. Prosumers with PV could reduce fossil fuels' need and overall electricity cost to ratepayers. The idea spread gradually in the 1980s. In 1981, the Arizona Corporation Commission approved net metering below 100 kW, the first among US public utility commissions (PUC). The following year, the Massachusetts PUC followed suit. In 1983, Minnesota became the first US state to enact a net metering law. More state PUCs and legislatures followed suit: the Indiana and Rhode Island PUCs in 1985, the Idaho and Texas PUCs in 1986, the Maine PUC in 1987, and the New Mexico and Oklahoma commission in 1988 [20]. NEM has been widely implemented currently; 41 states, in addition to Washington, DC, American Samoa, US Virgin Islands, and Puerto Rico, have mandatory net metering policies. Some utilities have voluntarily offered NEM arrangements to customers, as well. For example, Idaho and Texas do not have compulsory NEM policies, but some utilities in those states do offer NEM [21,22]. Many utilities saw NEM break the business model and often lobby against the payback at retail prices because it does not include the transmission losses and operating costs taken on the utility. Despite the benefits of NEM, it can also be seen as a form of “cost-shifting” or subsidy for those who invest in renewables, while others who are unable to invest in it take the cost burden [23,24]. In conclusion, prosumers benefit from NEM, and utilities are forced to implement NEM by Public Commissions in varying states. The retail price of electricity is not ideal as a payback price for the utilities and forces them to lobby to make it more difficult for PV adoption.

## 2.6 Peer-to-Peer Energy Market (DRAFT)

The typical peer-to-peer (P2P) market consists of a physical layer and a virtual layer. The physical layer is the infrastructure that facilitates the generation and metering of energy for the prosumer network. A prosumer has a form of energy generation system with an inverter that converts or steps up the energy to match the home's alternating current (AC) source. An isolation switch for emergencies isolates the connection to most generation systems. The entering energy from the DG system immediately supplies the home load, and any excess energy that flows in the opposite direction (into the grid) is measured by the bi-directional meter installed at the utility distribution drop. A micro-controller with wireless connectivity can relay the meter flow over a wireless communication backhaul to other controllers [25]. The virtual layer consists of software that facilitates interactions between participants in the market. It ensures that all participants have equal access to the platform's historical financial transactions. The virtual layer consists of the messaging protocol and other transmissions of the messages securely to a message broker or a distributed ledger for settlement and trading transactions [26].

### 2.6.1 Overview of the Network Elements

P2P networks can be divided into two layers:

1.  Virtual layer
2.  Physical layer

The virtual layer essentially provides a secured connection for participants to decide on their energy trading parameters. It ensures that all participants have equal access to a virtual platform. The virtual platform facilitates the transfer of buy and sell orders, and financial transactions. The physical layer is a physical network that facilitates the transfer of electricity from sellers to buyers once the financial settlements between both parties are completed over the virtual layer platform. It can be a traditional distributed-grid network maintained by the independent system operator or an additional separate physical microgrid distribution grid, in conjunction with the traditional grid. [Custom Papers/References > Transforming energy networks via peer-to-peer energy trading The potential of game-theoretic approaches](app://obsidian.md/Custom%20Papers/References#Transforming%20energy%20networks%20via%20peer-to-peer%20energy%20trading%20The%20potential%20of%20game-theoretic%20approaches)

### 2.6.2 Overview of Market Structure

Market operations of a P2P network consists of payment rules, and a clearly defined bidding format. The main objective is to enable an efficient energy trading process by matching the sell and buy orders in near real-time granularity. In market operations the generation of each producer influences the thresholds of maximum and minimum energy allocation. Different market-time horizons may exist in the market operation that should be able to produce enough allocation at every stage of operation. [Custom Papers/References > Peer-to-Peer Trading in Electricity Networks An Overview](app://obsidian.md/Custom%20Papers/References#Peer-to-Peer%20Trading%20in%20Electricity%20Networks%20An%20Overview)

#### 2.6.2.1 Fully Decentralized Market

Fully decentralized markets allow for prosumers to independently and directly negotiate with each other to decide on energy trading parameters without any centralized supervision by leveraging bilateral contracts between prosumers.  
In a fully decentralized market the bilateral contracts capture both the upstream-downstream energy balance as well as forward market uncertainty. [Custom Papers/References > Bilateral contract networks for peer-to-peer energy trading](app://obsidian.md/Custom%20Papers/References#Bilateral%20contract%20networks%20for%20peer-to-peer%20energy%20trading)

#### 2.6.2.2 Community Based Market

Community-based market can be applied to community microgrids and group of neighboring prosumers. The members of the community share common interests and goals even though they are not at the same location. [Custom Papers/References > Peer-to-peer and community-based markets A comprehensive review](app://obsidian.md/Custom%20Papers/References#Peer-to-peer%20and%20community-based%20markets%20A%20comprehensive%20review) They may work either in a collaborative or competitive manner. [Custom Papers/References > Energy storage sharing in smart grid A modified auction-based approach](app://obsidian.md/Custom%20Papers/References#Energy%20storage%20sharing%20in%20smart%20grid%20A%20modified%20auction-based%20approach) Participants generally trade energy through a community manager. The community manager manages exchanges outside of the community. Privacy is preserved by the community manager. [Custom Papers/References > Peer-to-peer energy trading in a prosumer-based community microgrid A game-theoretic model](app://obsidian.md/Custom%20Papers/References#Peer-to-peer%20energy%20trading%20in%20a%20prosumer-based%20community%20microgrid%20A%20game-theoretic%20model)

#### 2.6.2.3 Composite Market

Composite market combines the fully decentralized and community-based market designs. An individual prosumer can engage in P2P trading between each other, while also interacting with existing markets like fully distributed markets. [Custom Papers/References > Online energy sharing for nanogrid clusters A Lyapunov optimization approach](app://obsidian.md/Custom%20Papers/References#Online%20energy%20sharing%20for%20nanogrid%20clusters%20A%20Lyapunov%20optimization%20approach) Community manager can also oversee trading inside the community. [Custom Papers/References > A sustainable home energy prosumerchain methodology with energy tags over the blockchain](app://obsidian.md/Custom%20Papers/References#A%20sustainable%20home%20energy%20prosumerchain%20methodology%20with%20energy%20tags%20over%20the%20blockchain)

### 2.6.3 Overview of Existing Challenges

The challenges for the physical layer of P2P is the integration of sensors and smart power systems that can support flexible loads and dynamic generation. The penetration of DERs and energy storage currently provide insignificant shifts in the overall grid operation but will soon grow into more substantial impacts if trends in technology persist. [Custom Papers/References > Transforming energy networks via peer-to-peer energy trading The potential of game-theoretic approaches](app://obsidian.md/Custom%20Papers/References#Transforming%20energy%20networks%20via%20peer-to-peer%20energy%20trading%20The%20potential%20of%20game-theoretic%20approaches) The virtual layer for P2P trading hinges on the information system that communicates the transactions between physical layer and in-between participants.

The P2P Information system needs to be able to:

1.  enable all market participants to communicate with one another for participating in energy trading;
2.  integrate the participants within a suitable market platform;
3.  give the participants equal access to the market;
4.  monitor the market operation;
5.  set restrictions on participant's decisions to ensure network security and reliability.

Examples of information systems for P2P networks include blockchain-based smart contracts [Custom Papers/References > Local electricity storage for blockchainbased energy trading in industrial Internet of Things](app://obsidian.md/Custom%20Papers/References#Local%20electricity%20storage%20for%20blockchainbased%20energy%20trading%20in%20industrial%20Internet%20of%20Things), consortium blockchain [Custom Papers/References > Consortium blockchain for secure energy trading in industrial internet of things](app://obsidian.md/Custom%20Papers/References#Consortium%20blockchain%20for%20secure%20energy%20trading%20in%20industrial%20internet%20of%20things), and Elecbay. [Custom Papers/References > Peer-to-Peer energy trading in a Microgrid](app://obsidian.md/Custom%20Papers/References#Peer-to-Peer%20energy%20trading%20in%20a%20Microgrid)

### 2.6.4 P2P Energy Market Types

Full-P2P configurations are suitable for isolated communities where maintenance of all the infrastructure is maintained through self-forming coalitions. In a fully decentralized market, the bilateral contracts capture both the upstream-downstream energy balance and forward market uncertainty [27]. Systems such as blockchain-based credits are used as distributed ledger accounting to facilitate privacy and fairness. In a Community-P2P, a community manager is chosen to take care of privacy and fairness. The community members who share common interests and goals even though they are not at the same location [28] may work either collaboratively or competitively [29]. Participants generally trade energy through a community manager that manages exchanges outside of the community [30]. Finally, a Hybrid-P2P would leverage the best of both worlds and even create a hierarchal approach to stacking several Full-P2P configurations and managed at a larger scale by a Community-P2P commission [31,32].

### 2.6.5 Existing P2P Energy Markets

Microgrids are known as low voltage grids, which are used to supply electricity to communities that can be operated in an islanding and grid-connected mode. Microgrids can have dispatchable energy resources (DERs) and gain an advantage to continue to operate in the islanding and grid-connected mode [33]. The DERs are managed by prosumers in a microgrid and can sell energy back to the grid with a benefit from the grid. The LO3 blockchain platform has been developed as a community energy market project [34]. The members can buy and sell energy from each other with smart contracts. The Brooklyn Microgrid project used the platform to set up the virtual layer of the market as they connected the physical layer [35]. The Brooklyn Microgrid was an apartment building in New York retrofitted with roof-top solar. The residents were all consumers contributing to the generation and consumption of the microgrid. The microgrid was able to be islanded off the main power grid and service the residents in a sustainable way. It was one of the few successful pilots in North America. Unfortunately, this project has yet to create a wave of adoption across the country. In other countries, efforts around energy trading platforms have yielded varying configurations and services. The German platforms such as Enerchain and Sonnen charge monthly participation fees but provide blockchain-based networks that protect privacy [36]. Many other European solutions established pilots or flat fee participation on a platform [37].


## 2.7 Game Theory (DRAFT)

According to [1] Game theory is a mathematical tool and conceptual framework thatcan be used to study complex, self-interested interactions among rational players. A simpler explanation is that Game theory is the science of decision making. It originated in the minds of great economists like Von Nuemann and Morgeston as early as the 1940's as a way to explain behaviour economics. It was then further developed to be used in financial markets. The theory really thrived in the 1950's when John Nash published several works around non-cooperative Games that where applied more broadly. Unfortunately in later years the discovery that a well-defined value system must be first defined before expecting the solutions derived through Game theory to actually be accurate. The varying nature of human value systems prevented significant in-roads in areas where human players where considered, but it did not stop the application to various fields with defined constraints such as control-loops, war-fare, ecology, etc..[1]

There are many definitions for what a *game* is in Game theory, but lets consider the definition proposed by [2] where they state that a game is any situation involving more than one individual, each of which can make more than one action, such that the outcome to each individual, called the *payoff*, 
is influenced by their action, and the choice of action of at least one other individual. In other words a situation where rational agents take actions according to a strategy to maximize their own utility. Many situations can be arranged in 
this way to solve complex systems involving many decisions. [2]

A way to think of what is meant by *strategy* in Game theory lets consider the analogy proposed by [19] by imagining you where playing a game of chess. The caveat is that you are playing via a representative, so in order to play the game you must create a set of instructions for every possible circumstance that may arise during the game. That means for the first move they make you must design outline the response for every reaction of the opponents move. The entire set of these decisions all the way until the end-game is a strategy for the player. A deterministic game like chess can be mapped out this way (even if it would be a very tedious exercise). These types of games are called finite because there are a limited number of moves. They are also considered a zero-sum game because one players gain equals the other players loss. Also, this game can be considered a competitive game or a *Non-cooperative* game because both players are competing to increase their own utility at the expense of the other. 

Game theory can be categorized into three main branches: *Non-Cooperative* game theory, as mentioned above, *Cooperative* game theory (coalitional game theory) and relatively recent branch called *Evolutionary* game theory (EGT. The contributions to game theory can be found in Figure 1. as presented in [3], it shows cooperative game theory was founded by Neumann and Morgenstern [10], and then the non-cooperative game was represented by Nash’s work [11],[12],[13],[14]. 

John Nash proved the existence of non-cooperative game solution, that is,the existence of Nash equilibrium (further explained later), thus laying the theoretical foundation of the modern non-cooperative game. Non-cooperative game theory essentially studies the settings where multiple payoff-maximizing players, who have partially or totally contradictory interests over the system and/or personal outcomes, interact with each other. 

Cooperative games are based on the Shapely value, a value that calculates the *fair* payoff of a player in a coalition of players. In a cooperative game all players are aware of the strategies chosen by other players. The goal in a cooperative game is to maximize the reward of all players involved. An example would be a group of homes with energy storage capacity and roof-top solar power generation working together to maximize overall revenue by selling energy at peak demand and meeting dynamic loads between them. 

![timeline of GT](./img/timeline_gt.png "Figure 1" =300x)
*Fig. 1. History of Game Theory .*


![class of GT](./img/game_classification.png "Figure 2" =300x)
*Fig. 1. Game classification .*

On the contrary, cooperative game theory could be applied to situations where communication among players is enabled, and the fundamental modelling unit in cooperative game theory is the set of players.[1] As for the evolutionary game, it is generally recognized that it was officially founded by Maynard Smith and Price [15]. This theory can be regarded as an organic combination of general game theory and dynamic evolution process [16]. Among these, the former focuses on the game problem within the framework of *bounded rationality* rather than *complete rationality*, while the latter draws on the biological evolution theory in biology field. In short, the decision-making stakeholders (i.e., players or participants) in an evolutionary game constantly adjust their own strategies according to environmental changes and the strategies of other decision-making stakeholders in order to adapt to the game environment under the conditions of limited knowledge, information and reasoning ability [9], [17].

### 2.7.1 Standard Game Model

#### 2.7.1.1 Basic Elements

A standard game model is a situation when there is more than one intelligent and purposeful agent and it includes at least 4 major elements [2],[9],[4]:

1) Players/Participants :  The  participants  in  the  game  who  can  decide  their  own  strategies.  An  important  assumption  is  that  the  players are rational, which means that they don’t leave things to chance and don’t take advantage of others’ mistakes. If we assume rational agents that have all rationality and all relevant information then the agent can model the game as an optimization problem. Unfortunately people do not always choose the most rational choice in real life. This then reduces the accuracy of classical game theory. Optimization is not just a single value system but many that also optmizes accross social and cultural systems.[1]

2) Strategy : A collection of all the strategies available for all players. According to whether a player’s strategies are finite, we can divide games into three groups: *finite games* and *infinite games*. Sometimes a strategy set can be infinite since it can by almost any option, or only 3 for example in the game of rock, papers, scissors. There are some strategies that do not involve randomness (finite strategy) such as to tic-tac-toe.finite games are also known as *matrix  games*. An  *infinite  game*  is  said  to  be  a *continuous-kernel*  game if  the  action  sets  of the players are continua, and the players’ objective functions are continuous with respect to action variables of all players.[5]

3) Pay-offs/Payment: After each player in the game chooses a  strategy  from  their  own  strategies  set,  a  relevant  result  (a  group of data) is provided to show each player’s gain or loss. A good payoff is the fundamental goal of a player, and is the main basis of a player’s judgment and behavior. Pay-offs are also known as the players preferences described as 'utility' and must be understood clearly for the model to be effective. The payoffs are very subjective. If there is a ranking to the payoff it is called *ordinal* , if it is just a subjective quantity value then it is a *cardinal* payoff.[1]

4) Orders:  When  different  players  are  about  to  decide,  there is a need to decide the orders. Sometimes players make their decisions at the same time to make sure that the game is fair;  sometimes  players  make  decisions  one  after  another;  most times in reality players may choose their strategies more than once.  Different orders result in quite different situations.

#### 2.7.1.2 Common Models

In an *n*-player game, the goal of the participants is usually to minimize payments or maximize incomes. Based on this, a typical *n*-player game [9] can be expressed as

$ G = [N;S_{1},S_{2},...,S_{n};u_{1},u_{2},...,u_{n}]  $ (1)

Where the game is *G*, and *N* represents a set of players in the *n*-player game. The *S* series represents the strategies of each *n*-player. Finally the *u* represents the payment for each *n*-player. 

The normal-form representation for the standard game model is the pay-off matrix as described by [2]. Each column and row represents the associated payoffs for each strategy as a combination of the two players. Given a strategy 'A' and a strategy 'B' a matrix of the game can be drawn to represent the responses of Player1's (P1) decision of strategy A and B while Player 2 (P2) chooses either A or B. The value at each cell then represents the reward/loss of the decision for each player.

|P1 \ P2|  |     |
|:--:|:---:|:---:|
|   | A   | B   |
| A | 1,1 | 0,0 |
| B | 0,0 | 2,2 |

### 2.7.2 Cooperative Games

Cooperative games in game theory are focused on the generic strategy of the game to provide a fairness result for each participant.[5] Since cooperative games are mainly supported by some contractual agreement the idea is tha the agents in the game are acting out of the desire to make the rewards as fair as possible. The complications arise with the decisions of what contributions should result in wieghing the rewards and how parts of the game can have different rewards and thus different weights attributed to make the reward system as balanced and fair as possible. Since there transactions of a cooperative game are not done at the individuals level but as a centralized consensus the details of transactions in cooperative games is typically not analyzed.

in cooperative games, players communicatewith each other and receive utilities. The concept of cooperative game theory provides answer to the question, “What happens when players communicate with each other and decide to cooperate?”[26].Cooperative game theory consists of two parts: Nash bargaining and coalitional game, Nash bargaininginvolves situations in which a group of players must agree on certain conditions under which they can cooperate. Whereas, the formation of cooperative groups or coalitions are discussed in coalitional game. 
By forming coalitions, players can receive more benefits then they would obtain individually. The players involved in the coalition donot always have the same interest and don’t contribute the same value. The players involved in a coalition expect to receive benefits by forming coalitions, depending on the value they contribute. These players are important for the existence of the coalition and are calledthe coreof the coalition [APPLICATION OF COOPERATIVE GAME THEORYINSMART GRIDSbySpandana Vottem,B.S.A thesis submitted to the Graduate Council ofTexas State University in partial fulfillmentof the requirements for the degree ofMaster of Sciencewith a Major in EngineeringDecember 2019Committee Members:George Koutitas,ChairHarold SternMina Guirguis
]

- The elements of a cooperative game theory are a set of players and a characteristic function

- if the set is formed by all the players of the coalition, it is called agrand coalition. The grand coalition may not always be profitable for all the players,thus it is preferable for some players to form small coalition sets.

- In contrast to grand coalition, empty coalition is a set with no players in it. A proper subsetis a coalition which consists of players less than the total number of players. If the coalition is made from one player, then it is called as  singleton coalition

- Depending on the contribution of the players in the cooperative game, they are divided into three types which are Regular, Dummy and Vetoplayers. Regular players are those who expect payoffs by contributing to the coalition, these players are not important for forming the coalition. Dummy players don’t contribute any value to the coalition but are important to a coalition, due to which theyget some payoff at the end of a game.A player i*is said to be a veto player, if he is involved in all winning coalitions. i*is a veto player if𝑣(𝑁∖𝑖∗)=0[32].

- The characteristic functions of a cooperative game are expected to be super-additive, sub-additive or monotonic. A game is said to be super-additive if the value obtained by the players in coalition is greater than the sum of all values that the players would receive individually. 

- When the worthof a coalition is less than the sum of the worth’sobtained by individual players, the game is said to be sub-additive. 

- Monotonicity means that larger coalitions gain more value, when a coalition Tis greater than coalition S it produces highervalues

- One of the solution typesof cooperative game theory is ‘The Core’. It involvesabout the stability of the coalition instead of fair distribution of payoffs

- Sometimesthe players may forma grand coalition,or some playersmaywish to formsmaller coalitions. As, sometimes players in a smaller coalition gain more profits 

- The sum of payoffs obtained by players in a sub-coalition Sshould be at least equal to the payoff obtained by the players by not forming a coalition. In some games, the core defines the empty set. 

- According to Lloyd Shapley, the benefits are divided among players according to their marginal contributions or the payoff received by each individual player is equivalent tothe valuethey add to the coalition.

- Efficiency:The payoffs should add up to v(N), which means that the surplus of the grand coalition should be allocated among the players.

- Symmetry:If two players iand j contributethe samevalue to every coalition, then iand jare said to be interchangeable w.r.t ‘v’

- Additivity:Thesolution to the sum of two TU (Transfer Utility) games must be the sum of the value obtained by each game

- NullPlayers:A player iis said to be a nullplayer if he doesn’t add any value to the coalition

- The Shapley value is the solution concept of cooperative game theory. In a coalitional game (N,v), the Shapley value divides the total payoff among the players of the game

- The Shapley value describes the marginal contributions

### 2.7.3 Non-Cooperative

A sequential game that can be considered is chess. Every step in the game the player needs to understand the possible actions of the other player. Sometimes the best game is when you have all the information available to you to understand the strategy avaialable. Some games do not have all the information available to the player. A game where all the information is avaialable and the players are interchangeable when it comes to rewards then the game is known as a symmetric game. Constant sum games is when all the strategy payoffs can only happen when there is an loss to other players porportionally . A possitive or negative sum game is when all players either benefit or loose given thier available strategies (people working in a company, or competing gangs). In a zero sum game compettition emerges in order to gather the profits at the loss of the other player.

Who wins the game? The idea behind winning a game comes down to identifying the winning strategy and then having the recourses to take actions towards that strategy. In the example provided the question now becomes who will go first player1 or player2 ? If player 1 goes first then player 2 will be forced to take his best course of action and player 1 is assuming this is what player 2 will do because it maximizes its reward. If player 2 goes first the reverse is also true. There are two types of game models Cornout , simultaneous movements between players and Stackelberg is a sequential movement between players. The details of each of these non-cooperative games will be discussed further in subsequent sections.

(Add illustration of 2 games.)
(what a 3 player finite game looks like?)
(ADD MORE DETAIL WHAT THIS IS - and add mathematical examples)


#### 2.7.3.1  Review of Nash Equillibrium

The equilibrium of a non-cooperative game is when either player has no other decisions available that would better thier individual positions. There can be more than one nash equilibrium in a game . An intuitive example is to consider the idea of stop lights in a busy intersection. Both drivers can be considered as players in this game and hte decisions they can take (stop,go) can be expressed in a combinatory manner using the normal-form representation as described before. The rewards for the game can be arbitrarily estimated given the desire of either players. If both players decide to "Go" at the same time then they will end up in a collision. This does not benefit either player so we place the reward for each accordingly (-5,-5). If either of the drivers have to stop to let the other go then the player who is stopped is inconvenience (reward of -1), while the driver who was able to go is now on its way and happy (reward of 1). The final strategy is if both players are stopped and niether move forward wasting time but not in a collision so not as bad but still a loss (reward of -2).

|P1 \ P2|  |     |
|:--:|:---:|:---:|
|   | Go   | Stop   |
| Go | -5,-5 | 1,-1 |
| Stop | -1,1 | -2,-2 |

The possible decisions of the players in the game are mapped out in the game matrix. The strategy for each player can now be assesed. The goal would be to find the best strategies for player 1 and for player 2 respectively. For player 1, the strategy where he is able to go is when player 2 must stop (1,-1). The best strategy for player 2 is the opposite (-1,1). Since there are no better moves for each player to take these are both Nash Equilibriums. The players would decide to move from both of these Nash equilibriums rather than move into any other strategy in the game.

![timeline of GT](./img/3way_intersection.png "Figure 1" =300x)

*Fig. 2. 3-player pay off matrix for 3-way intersection example.*

#### 2.7.3.2 Deeper look at the Stackelberg Model

A Stackelberg Game is a type of noncooperative game that deals with a multi-level decision making process of a number of independent decision makers or players(followers) in response to the decisiont taken by a leading player (the leader) .

- The game has the following components:
  - Followers in the game that respond to a price set by the leader
  - The strategy of each of the followers in terms of satisfying some constraint
  - The utility function of each follower that captures the benefit of consuming the demand
  - The utility function of the leader which captures the total profit
  - The price per unit quantity

The utility function of the follower represents the level of satisfaction of the follower. It is a function of the profit it recieves. The utility function is non-decreasing because each follower is interested in maximizing its profit. The marginal benefit of the follower is also considered a non-increasing function. The marginal benefit gets saturated the closer it gets to the maximum profit. The utility of a follower decreases as the price of a unit or cost of meeting a demand increases .

If the constraint is the same for all players then this gives rise to a noncooperative resource sharing game between the followers. A game like this represents a jointly convex generalized Nash equilibrium problem (GNDP) due to the same shared constraint. In game theory the coupling of the constraints has solution called the Gneralized Nash Equilibirum(GNE).[3]

#### 2.7.3.3 Simulation of Stackleberg Duoply

The stackleberg duoply is a non-cooperative game between two players where one is a leader and the other is a follower. They are the only two players able to supply the needs of the market by creating some quantity of goods. Each player has a utility function that will be satisfied if they can maximize the profit of supply a quantity of goods to the demand curve of the market considering the cost to provide a unit of goods.  [5],[7]

Define a pricing demand as a linear function and call it a "Market Demand Curve"

```
P = a  -  b * Q
```

Where Q is the market quantity demanded and P is the market price in dollars
The firms create the quantity.

The quantity created for the market comes from multiple firms. The firms in a Stackleberg game provide some quantity after the leader firm goes first. The leader firm assumes the moves of the other firms and tries to maximize its profit by incurring the costs to meet the demand that it deems appropriate given its own costs. The demand is met through a total quantity that can be represented by the combination of all of the players quantity. 

```
Q = q1 + q2 + ... qN
```

The cost to meet a single unit of demand per unit qunatity created. This is a pre-defined metric or can be a dynamic value. Knowing the marginal costs is critical to determining the other players moves. The Leader needs to know what it would cost other players to take action.

Begin backward induction to determine what the reaction would be of the other firms. Lets assume two firms A, and B. The procedure to determine the Leaders (firm A) move would be as follows:

1. Calculate Firm B's reaction
2. Calculate Firm A's response to B's reaction
3. Implement Firm A's response
4. Calculate Firm B's response given A's response
5. End Game


$ N_{firms} = 2$ (2)

$ MC_{a} = 10$ (3)


$ MC_{b} = 12$ (4)


$ P_{T} = -Q_{d}m+b$ (5)


$ P_{T} = -Q_{d}*0.5+120$ (6)

By inspecting the demand curve we can see that all the quantity generated by the payers (x-axis) will result in a total price for all the quantity (y-axis) at different levels of demand met. The pricing demand curve can now be used as a total demand and total quantity output that will be presented to the players. At some break even point the price demand for a unit is no longer advantageous considering the cost to the player to meet that demand.

The break even point would be the profit maximizing point for the player . In the stackleberg game the leader tries to maximize its output by looking at the break even point of the secondary player. If the marginal costs are lower for the follower they can generate more quantity and outsell the leader. This means the leader should make enough to break even and just enough to reduce the gains of the follower.

Again, by only looking at the demand curve the leader can only determine a break even point based on its own cost. As soon as it costs more to meet the demand than the price of the demand then the leader stops and no longer produces. If the demand must be met, then the rest of the demand is left for the second player to take on. If the second player looks at the remaining demand and only supplies what it can break even then both players are left supplying demand with diminishing returns.

To avoid having to supply diminishing returns the leader can take into account the maximizing move for the second player and then include that in determining its stake in the market based on its own costs and break even point.

Total Market Quantity Demand:

$ Q_{d}= q_{a} + q_{b}$ (7)

Market Demand Curve:

$ -0.5*Q_{d} + 120 = -0.5*q_{a} + -0.5*q_{b} + 120$ (8)

$ TR_{b} = -0.5*q_{a}*q_{b} - 0.5*q_{b}^2 + 120*q_{b}$ (9)

Marginal revenue can be derived from the derivative of the total revenue equation (9), with respect to the firm.

$ MR_{b} = \frac{\partial d}{\partial q_{b}}(-0.5*q_{a}*q_{b} - 0.5*q_{b}^2 + 120*q_{b})$ (10)

$ MR_{b} = -0.5*q_{a} - q_{b} + 120$ (11)

The reaction of the follower can be estimated by the leader by solving when the marginal cost of the follower will equal the marginal revenue of the follower. Setting them equal and solving for the quantity in terms of the quantity provided by the leader firm A we get the following reactionary quantity for firm B.

$ q_{b}^* = -0.5*q_{a} + 108$ (12)

The leader takes into account all the reactions and creates a leader response to the reactions. The approach is to use back induction to take the forecasted reaction of the follower when the marginal cost is equal to the marginal revenue (profit maximizing). That means that the follower will stop at some break even point that maximizes its profits. Given that information the leader can take that reaction and assume it is what the follower will do. The assumption is used in the price demand formula. By substituting equation (12) into equation (8) the demand for the leader is now shown below in (13). Knowing the demand the total revenue and marginal revenue can also be inferred.

$ P_{leader} = -0.25*q_{a} + 66$ (13)

$ TR_{a} = -0.25*q_{a}^2 + 66*q_{a}$ (14)

$ MR_{a} = \frac{\partial d}{\partial q_{a}}(-0.25*q_{a}^2 + 66*q_{a})$ (15)

$ MR_{a} = -0.5*q_{a} + 66$ (16)

The last step in the backwards induction for the leader is to try to maximize his profit by only providing a quantity where the followers quantity has been considered in the game. The final quantity to be implemented by the leader is done just as before by setting marginal revenue equal to marginal cost and finding quantity.

$ q_{a}^{Final} = 112$ (17)

If we implement the leaders quantity output and then recalculate the resulting quantity for the follower, the follower will have a different output than what was orginally measured by the leader since the leader has now taken its maximum demand.

$ q_{b}^{Final} = 52$ (18)


### 2.7.4 Evolutionary Games

The Crafoord Prize in 1999 (which is the highest prize in Biological Sciences), went  to  John  Maynard  Smith  (along  with  Ernst  Mayr  and  G.  Williams)  “for developing  the  concept  of  evolutionary  biology,”  where  Smith’s  recognized  contributions  had  astrong  game-theoretic  underpinning,  through  his  work  on  evolutionary  games  and  evolutionary stable equilibrium.[5]

Compared with classic game theory, the Evolutionary Game Theory (EGT) takes the population as the research object, and believes that the game individual is bounded rational, and the strategy of the individual game may change due to the variation. Thus, EGT is more inline with the realistic game situation because it adopts the mechanism of natural selection and does not require strict rational assumptions. [5]. The problem with EGT is choosing the selection and mutation mechanisms and making them represent actual issues is very challenging. [9]

A fundamental goal of evolutionary game theory is to understand how the individual organisms in biological system or social system interact with each other, and evolve over time with the environment determine the spatial distribution of populations and the structure of communities. It considers a population of players interacting in a game with fixed strategies and payoff of each individual is interpreted as fitness, and success in the game is translated into reproductive success.[15]


### 2.7.5 Different Game Models

The different types of models as defined in [4] consists of the following:

1) Ordinary non-cooperative game: The establishment of ordinary non-cooperative game model is no longer a difficult thing.  The  basic  idea  is  to  analyze  the  problem,  abstract  the  three  elements  of  modeling,  establish  model,  analyze  the  properties of equilibrium solution and solve the problem.

2) Generalized  Nash  equilibrium  game:  Each  player’s  decision affects not only other players’ payoffs, but also their feasible strategies set.

3) Cournot   game:   It   is   the   earliest   version   of   the   application  of  Nash  equilibrium  and  a  classic  case  in  game  theory,   which   is   also   well-known   as   a   special   case   of   prisoner’s dilemma model.

4) Stackelberg  game:  It  is  the  simplest  model  of  a  leader-follower  game,  in  which  the  follower  can  know  well  about  the  leader’s  behavior  and  previous  game  information  and the leader can predict the follower’s action before making a decision.

5) Bounded  rationality  game:  While  game  theory  has  acquired  great  success,  some  people  have  questioned  the  assumption that the players are completely rational. Bounded rational game is much closer to reality because it is based on the assumption that each player desires the best result but can only get limited payoffs.

6) Repeated game: Made up of a few repeated basic games, each stage of a repeated game is a complete game. Although repeated game is just a repetition of basic games in the form, but the result could be quite different.

### 2.7.6 Repettetive Game Play

A computer simulation playing iterative games of the prisoners dillema in Robert Axelrods book "Evolution of Cooperation" was shown to play a game called Tit-for-Tat that would outperform any other game strategy[2]. In this strategy the simulation would mimic human like behaviour that would act in synchronicity to how anohter player acts towards it i.e. positive reaction would result in a positive reaction and vice-versa, but when a negative reaction occured it would be best to return a negative reaction and then go back to a positive reaction. This strategy would be effective as long as the players did not repeat negative actions towards each other , otherwise it would spiral into repeated negative actions until both are destroyed.

### 2.7.7 Auction Games

Auction games have been proposed to trade storage space and renewable energy from DERs [38]. The real-time implementation of a multi-agent-based game-theoretic reverse auction model for microgrid market operations featuring conventional and renewable DERs is discussed. [39] The proposed methodology was realistically implemented in a smart grid system at Florida International University. The subsequent investigation shows that the proposed algorithm and the industrial hardware-based infrastructure are suitable for implementing the existing electric utility grid. Meanwhile, the authors in [40] utilize an auction game to study the solution of joint-energy-storage ownership sharing between multiple shared facility controllers (SFCs) and those dwelling in a residential community. The auction process possesses both incentive compatibility and individual-rationality properties. It can also enable the residential units (RUs) to decide the fraction of their shared energy storage capacity with the SFCs of the community to assist in storing electricity. For example, in [41,42], a coalitional game is used to study the cooperation between small-scale DERs and energy users to enable direct energy trading without going through retailers. The asymptotic Shapley value is the core of the coalitional game. No small-scale DERs or energy users are incentivized to abandon the coalition, which suggests the stable direct trading of energy for the proposed pricing scheme. Furthermore, numerous case studies demonstrate that the scheme is suitable for practical implementation. The authors in [43] design a three-stage algorithm based on a coalitional game strategy, including request, exchange, merge-and-split, and cooperative transaction stages. The developed algorithm enables microgrids to form coalitions to exchange power directly by paying a transmission fee.



# References

1. B.W.F. Depoorter, “Regulation of Natural Monopoly,” Encycl. Law Econ., (published).
2. W. Troesken, “Regime Change and Corruption. A History of Public Utility Regulation”; pp. 259-82 in Corruption and Reform: Lessons from America's Economic History, Edited by E. L. Glaeser, C. Goldin. University of Chicago Press, United States, 2006. 
3. S. Hunt, Making competition work in electricity.Ch.2 p.27 John Wiley & Sons, New York, 2002. 
4. Public Utility Regulatory Policies Act of 1978. 1980.
5. M.W. White, “Power Struggles: Explaining Deregulatory Reforms in Electricity Markets,” Brookings Pap. Econ. Act. Microeconomics, 201–267 (1996). doi:10.2307/2534749. 
6. L. Cabral, “The California Energy Crisis,” Japan World Econ., 14-3 335–339 (2002). 
7. K. Mcdermott," Cost of Service Regulation In the Investor-Owned Electric Utility Industry A History of Adaptation," Edison Electric Institute, Washington, DC, June 2012. 
8. P. Joskow and E. Kahn, “A quantitative analysis of pricing behaviour in California’s wholesale electricity market during summer 2000,” Spec. Publ. IEEE Power. Soc., 1 392–394 (2001). 
9. C. Weare, The California Electricity Crisis: Causes and Policy Options. Ch. 3 pp. 1- 119. Public Policy Institute of California, USA, 2003
10. Spandana Vottem, B.S. "APPLICATION OF COOPERATIVE GAME THEORY IN SMART GRIDS", A thesis submitted to the Graduate Council of Texas State University in partial fulfillment of the requirements for the degree of Master of Science with a Major in Engineering December 2019.
11. C. Hicks, "The smart grid - where are we today and what the future holds," ERB Institute, University of Michigan, Michigan 2012.
12. National Academies of Sciences, Engineering, and Medicine. “The Power of Change: Innovation for Development and Deployment of Increasingly Clean Electric Power Technologies”, The National Academies Press, Washington D.C., 2016.
13. X. Fang, S. Member, S. Misra, and G. Xue, “Smart Grid – The New and Improved Power Grid : A Survey,” IEEE Commun. Surv. Tutorials, 14 [4] 944–980 (2011).
14. Naser Hossein Motlagh, Mahsa Mohammadrezaei and Julian Hunt and Behnam Zakeri, "Internet of Things (IoT) and the Energy Sector" Department of Computer Science, University of Helsinki, FI-00560 Helsinki, Finland; Energies 2020.
15. L. D. Xu, W. He, and S. Li, “Internet of Things in industries: A survey,” IEEE Trans. Ind. Inform., vol. 10, no. 4, pp. 2233–2243, Nov. 2014.
16. Chenghua Zhang, "Peer-to-Peer Energy Trading in Electrical Distribution Networks," Cardiff University,PHD Thesis, 2017.
17. Nizam, M.; Wicaksono, F.X.R. Design and Optimization of Solar, Wind, and Distributed Energy Resource (DER) Hybrid Power Plant for Electric Vehicle (EV) Charging Station in Rural Area. In Proceedings of the 2018 5th International Conference on Electric Vehicular Technology (ICEVT), Surakarta, Indonesia, 30–31 October 2018.
18. S. Patel, R. Rajagopal, Peer to Peer Sharing of Distributed Energy Resources, 14 Sept. 2018
19. D. E. Krasko V., "Strategic Sequencing for State Distributed PV Policies: A Quantitative Analysis of Policy Impacts and Interactions.," National Renewable Energy Laboratory, Golden, Colorado, 2012.
20. F.-E.-S. Roberto Verzola, Crossing Over: The Energy Transition to Renewable Electricity, Manila Office: Friedrich-Ebert-Stiftung, 2015. 
21. K. P. L. S. O. M.-S. Steve Pociask, "The Unintended Consequences of Net Metering," American Consumer Institute, a nonprofit educational and research organization, Washington, DC, 2019.
22. U. E. I. Administration, "Florida State Energy Profile," US Energy Information Administration, 18 11 2021. [Online]. Available: https://www.eia.gov/state/print.php?sid=FL#34. [Accessed 11 12 2021].
23. F. P. S. Commission, "Find Your Utility," Florida Public Service Commission, 2021. [Online]. Available: http://www.psc.state.fl.us/ConsumerAssistance/FindYourUtility. [Accessed 11 12 2021].
24. EnergySage, "How does Florida Power and Light net metering work?," EnergySage, Inc., 2009. [Online]. Available: https://www.energysage.com/local-data/net-metering/fpl/. [Accessed 11 12 2021].
25. X. Y. W. F. C. H. T. R. Q. C. a. J. Z. N. Liu, "Online energy sharing for nano grid clusters: A Lyapunov optimization approach," IEEE Transactions on Smart Grid, vol. 9, no. 5, p. 46244636, 2018. 
26. I. EnergySage, "How does Florida Power and Light net metering work?," EnergySage, Inc., 2009. [Online]. Available: https://www.energysage.com/local-data/net-metering/fpl/. [Accessed 11 12 2021].
27. T. K. S. C. Y. T. M. M. D. M. H. V. P. K. L. W. W. Tushar, "A motivational game-theoretic approach for peer-to-peer energy trading in smart grid," Applied Energy, vol. 243, pp. 10-20, June 2019.
28. H.-C. L. V. D. A. I. Uribe-Perez Noelia, "State of the Art and Trends Review of Smart Metering in Electricity Grids," Applied Sciences, vol. 6, no. 10.3390, pp. 68-92, 2016. 
29. C. Y. H. M.-R. T. S. H. V. P. ,. K. L. W. W. Tushar, "Transforming Energy Networks Via Peer-to-Peer Energy Trading: The potential of game-theoretic approaches," IEEE Signal Processing Magazine, vol. 35, no. 4, pp. 90-111, July 2020. 
30. N. F. S. J. D. M. D. M. T. Morstyn, "Using peer-to-peer energy-trading platforms to incentivize prosumers to form federated power plants," Nature Energy, vol. 3, no. 2, pp. 94-101, 2018. 
31. Q. A. J. Ni, "Economic power transaction using coalitional game strategy in micro-grids," IET Generation, Transmision Distribution, vol. 10, no. 1, pp. 10-18, 2016. 
32. V. D. M. A. Sakineh Khalili, "Impact of Blockchain Technology on Electric Power Grids - A case study in LO3 
33. Energy," ConnectSmart Research Laboratory, vol. University of Tenesee at Chattanooga, 2020. 
34. Enerchain, "Enerchain® proof of concept," Enerchain, 2019. [Online]. Available: https://enerchain.ponton.de/. [Accessed 2021].
35. Sonnen, "Sonnen," Sonnen, 2019. [Online]. Available: https://sonnengroup.com/sonnencommunity/. [Accessed 2021].
36. S. Vottem, "Application of Cooperative Game Theory in Smart Grids," in Texas State University, San Marcos, Texas., 2019. 
37. Q. A. J. Ni, "Economic power transaction using coalitional game strategy in micro-grids," IET Generation, Transmision Distribution, vol. 10, no. 1, pp. 10-18, 2016. 
38. X. Y. W. F. C. H. T. R. Q. C. a. J. Z. N. Liu, "Online energy sharing for nano grid clusters: A Lyapunov optimization approach," IEEE Transactions on Smart Grid, vol. 9, no. 5, p. 46244636, 2018. 
39. V. D. M. A. Sakineh Khalili, "Impact of Blockchain Technology on Electric Power Grids - A case study in LO3 Energy," ConnectSmart Research Laboratory, vol. University of Tenesee at Chattanooga, 2020. 
40. W. Tushar, B. Chai, C. Yuen, S. Huang, D. B. Smith, H. V. Poor, and Z. Yang, “Energy storage sharing in smart grid: A modified auction-based approach,” IEEE Transactions on Smart Grid, vol. 7, no. 3, pp. 1462– 1475, May 2016.
41. M. H. Cintuglu, H. Martin, and O. A. Mohammed, “Real-time implementation of multiagent-based game theory reverse auction model for microgrid market operation,” IEEE Trans. Smart Grid, vol. 6, no. 2, pp. 1064–1072, Mar. 2015
42. W. Tushar, B. Chai, C. Yuen, S. Huang, D. B. Smith, H. V. Poor, and Z. Yang, “Energy storage sharing in smart grid: A modified auction-based approach,” IEEE Trans. Smart Grid, vol. 7, no. 3, pp. 1462–1475, May 2016.
43. W. Lee, L. Xiang, R. Schober, and V. W. S. Wong, “Direct electricity trading in smart grid: A coalitional game analysis,” IEEE J. Sel. Areas Commun., vol. 32, no. 7, pp. 1398–1411, July 2014.
44. J. Ni and Q. Ai, “Economic power transaction using coalitional game strategy in micro-grids,” IET Generation, Transmission Distribution, vol. 10, no. 1, pp. 10–18, Jan. 2016.