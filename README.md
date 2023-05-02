# 🖥️Grant-Review-Dashboard🖥️
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

It has been a while since Gitcoin DAO and the public good defendoors have recognised the importance and neccesity of the development of automated tools that assist in the distribution of public goods. The Grant Review dashboard seeks to accelerate the automation of grant reviews in Gitcoin rounds thus empowering grant owners to manage and analyze the grant applications in a more resource efficient way for all the parties involved in the rounds. 

Luckily the ODC has created the Sandbox initiative, thus people that have a pass
- Created from the [sandbox team proposal](https://forum.opendatacommunity.org/t/sandbox-team-proposal/30/2)
- [Discord channel](https://discord.com/channels/1037443230993743902/1087749094207930389)

### 🤔 What is the Grant Review Dashboard? 

An open source dashboard that aims to progresivally lead to the automation of grant reviewing/screening before/during the Gitcoin rounds by using and developing a series of Lego analysis on grants that participate in Gitcoin Rounds. Of course we might adapt and evolve along the way as the program is still in the Beta phase and many aspects of it may change. It is very likely that the Grant Review Dashboard will work together with a review protocol that involves actual reviewers that have experience related to the scope of the rounds or want to participate in the defense of public goods.

### 🎯Objective:

The project aims to build a modular, configurable open source dashboard that will assist round owners by automatically screening grant applications in the Gitcoin rounds by detecting various proven suspicious/malicious behaviors related to grant fraud. Over time we might also add functions that will also signal really good grant applications thus enabling almost instant approval for them. As you may know Gitcoin distributed over 75m$ to public goods and it's very likely this number will only grow in the future => it's more important than ever to develop these tools as the program grows.


### 🤖Who can use this:  

Gitcoin is the best web3 crowdfunding platform and it recently launched the Allo [protocol](https://docs.allo.gitcoin.co/getting-started/introduction). By using this tool all the round owners of the Allo protocol will save time and resources by screening out bad grants from their rounds. Grantees hugely benefit also because by filtering out bad grant applications in time they get more matching allocated to them. It will also save time/resources for Gitcoin DAO would as it with take the load of the people that are working on grant reviews/approvals(currently PGF workstream).


### ℹ️ Useful information for future contributors(also important for hackaton participants):  

Well, if you like challanges you are in for a huge one, the Grant Review Dashboard is a very complex project because:

1.sybil attacks are an unsolved problem 
2.grant reviews or reviews of any kind have never been automated in this manner
3.it is a red team-blue time scenario in which even if you lived in a universe where sybils are completely destroyed and grant reviews are automated, people will still find ways to emulate the behaviour of real project as long as the incentives are appealing
4.anti grant fraud automation, involving turning signals into [Legos](https://gov.gitcoin.co/t/public-goods-legos-roadmap/12546) was never battle tested in a live environment
5.the LEGO logic that will flag the grants with a level of accuracy and precission that make the dashboard trustworthy needs extensive testing
6.pulling and working with onchain data that can be visualized on the Dashboard in a timely manner can be tricky


📶Examples of signals for Grant Review legos:

1.Github activity of the grant creator
2.Check if the website is online
3.analyze website data

Check out more info about Sybil Legos [here](https://opendatacommunity.org/docs/legos/) to get inspired


###🎖️Going the extra mile: 
-------------------------
If you managed to read until here and still are confused?(which is very likely, we are also sometimes 🙃) we would recommend taking a look at these anti-sybil dashboards built by the amazing people that participated in past ODC Hackatons:
[GrantLooker-by Kikura](https://www.grantlooker.xyz/projects) - this project provides a interesting functional solution overall, read more about it [here](https://github.com/kikura3/gtclooker)
[Anti-Sybil Dashboard - by Rayfront](https://dashboard-e9cf.vercel.app/) - this one is a cool example of a clean way to visualize the grant round data from past rounds


###Rough milestones*

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Developing more legos and creating an accurate lego logic 
2. Creating a grant review dashboard that clearly signals which grants are clear NOs(MVP)
2. Creating a grant review dashboard that clearly signals which grants are clear NOs(MVP) and can function properly
3. Developing a grant review dashboard that can be used as a reliable source in the next Gitcoin Round(at least for one of the rounds)
4. Enlarging the scope and making sure the dashboard is configurable enough and can be used by multiple round owners to signal bad grant applications
*modifications can appear along the way 
