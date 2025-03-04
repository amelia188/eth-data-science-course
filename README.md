# Learning Data Science on the Ethereum Blockchain with the [Omniacs](https://twitter.com/OmniAnalytics)

<p align="center">
<img src="images/omnianalytics-Classroom_gif-optimized.gif">
</p>

## Description

We want to share our joy of data science with the Ethereum eco-system through an informative set of online courses and case studies that merge data analysis, blockchain analytics and statistical programming.

We aspire to create a modular online course to help new blockchain developers understand the principles and best practices of data science. Using open data sources from across the Ethereum landscape (think StateoftheDApps, UniSwap, & Etherscan), the course will teach the topics of data munging, data visualization, exploratory data analysis, machine learning, and dabble in a bit of deep learning and artificial intelligence.  As the course grows, we intend to create case studies around how to apply data science to specific DApps (think machine learning techniques for predicting markets with Numer.ai data or analyzing traits in CryptoKitties).

Our ultimate vision is to spur and inspire the next generation of developers through interesting applications of data science to emerging blockchain technologies.

Gitcoin Grant Link: https://gitcoin.co/grants/562/learning-data-science-on-the-ethereum-blockchain-

## Tentative Course Outline

[Module 1 - Basic Data Structures and Munging](https://github.com/Omni-Analytics-Group/eth-data-science-course/tree/master/courses/Module%201)
* [Motivating Example](https://crypto.omnianalytics.io/eth-data-science-course/courses/Module%201/1-1-Motivating-Example-Crypto-Punk.html)
* [Reading Files](https://crypto.omnianalytics.io/eth-data-science-course/courses/Module%201/1-2-Reading-Files.html)
* [Basics](https://crypto.omnianalytics.io/eth-data-science-course/courses/Module%201/1-3-Basics.html)
* [Data structures](https://crypto.omnianalytics.io/eth-data-science-course/courses/Module%201/1-4-DataStructures.html)

Data Sources: [*CryptoPunks*](https://www.larvalabs.com/cryptopunks), [*Crypto Art Pulse*](https://cryptoartpulse.com/)

Module 2 - Statistical Graphics and Visualization
* Why graph?
* Thinking in layers
* Basic graph types
* Advanced statistical graphics

Data Sources: *Etherscan*

Module 3 - Supervised and Unsupervised Machine Learning
* The ML workflow
* Supervised learning for classification
* Unsupervised learning for grouping
* Forecasting what's next
* Deep learning for sequences

Data Sources: *Numerai Tournament Data, UniSwap*

Module 4 - Case Studies
* [Clustering and segmenting Ethereum validator performance](https://github.com/Omni-Analytics-Group/eth-data-science-course/tree/master/case-studies/validators) ([R](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/validators/#1), [Python](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/validators/Validator%20Case%20Study.html), [Video](https://youtu.be/2JLRnKmlV8I))
* [Visualizing slashings in the Ethereum Medalla testnet](https://github.com/Omni-Analytics-Group/eth-data-science-course/tree/master/case-studies/slashers) ([R](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/slashers/#1), [Python](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/validators/Validator%20Case%20Study.html))
* [Reconstructing the Crypto Sentiment Investment Curve in ggplot2](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/investment-curve/#1) 
* [Interacting with and Analyzing Numerai Network Growth with GraphQL and ggplot2](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-growth/#1)
* [Tornado.Cash Initial Distribution Analysis](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/tornado-cash/#1)
* [Stable Coin Analysis](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/stable-coins/#1)
* [Using R Shiny to explore Numerai tournament data](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/) ([Part 1](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-1-ShinyIntro.html), [Part 2](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-2-ShinyStructure.html), [Part 3](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-3-ShinyTools.html), [Part 4](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-4-BuildShinyAppPart1.html), [Part 5](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-5-BuildShinyAppPart2.html), [Part 6](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-6-BuildShinyAppPart3.html), [Part 7](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-7-BuildShinyAppPart4.html), [Part 8](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-8-BuildShinyAppPart5.html), [Part 9](https://crypto.omnianalytics.io/eth-data-science-course/case-studies/numerai-explorer/9-9-BuildShinyAppFinalPart.html))

Data Sources: *Beaconscan, Numerai Tournament Data*

## Updates

*Gitcoin Grant Round 8*

Like everything else in the world, 2020 flipped our course development plans upside down.  Instead of building the course from the bottom up, we chose to repurpose and refactor our Medalla research into motivating case studies on how to perform data analysis on Ethereum 2.0 blockchain data.  The case studies walk through, in detail, how we performed the analysis that ultimately netted us a [bronze prize](https://blog.ethereum.org/2020/11/17/medalla-data-challenge-results/). We also included a tutorial on how to use R Shiny as an exploration tool for understanding the Numer.ai dApp's tournament data.

Change log
* Restructured the repository for clarity
* Added 3 case studies

*Gitcoin Grant Round 9*

For Round 9 we've doubled down on our "case study first" approach to teaching data science using projects on the Ethereum blockchain as examples. This update includes a look at NFTs, stable coins, market capitalization estimation, and an introduction to GraphQL.  We expanded two of our original case studies to include Python version, so if you are interested in learning more about that language you can check those out here and here.  This update also includes our first attempt at creating video lectures for the eager learners who would like to dive deeper into the concepts. We intend to use funding from this round to further expand out the set of case studies we produce and improve the quality of our video content.

Change log
* Major update to the course aesthetics
* Module 1 updated
* 5 New case studies (with 2 more to be published during the active grant round)
* First video lecture published to Youtube

## FAQ

*Do you all have experience in this stuff?*  
Why yes, we do! Omni Analytics Group is a team of PhD level statistical consultants that have been teaching and solving difficult data science problems for nearly a decade. We are passionate about data science and blockchain technologies. Just check out [our twitter](https://twitter.com/OmniAnalytics).

*Do I need any prior experience before taking this course?*  
Our intention is to start from the beginning and build up not only your data chops, but your statistical intuition and programming knowledge. At the end of these courses, you should be able to match a statistical technique to a blockchain data problem, write a basic script to analyze it and confidently search online for more advanced knowledge.

*What programming languages will the course focus on?*  
We'll initially focus on the statistical language R, but then expand to Python. As the course grows, we hope to include examples with contracts written in Solidity.

*Can I request a topic?*  
Sure! Once we flesh out the initial course material. If funding persists, we'd be more than happy to take suggestions on case studies or topics.

## Testimonials

"This course is like a rain following a drought. It kindly walks you through the process starting from the use of R to introduction of graphs and machine learning concepts with interesting case studies. I strongly recommend it not only to researchers interested in Ethereum blockchain but also to any students or professionals that have interest in learning data analysis and science." - [Will Shin](https://www.linkedin.com/in/wooil-s-51308353/) (Principal Economist at [Klaytn](https://www.klaytn.com))

## Featured Projects

* [CryptoPunks](https://www.larvalabs.com/cryptopunks)
* [Crypto Art Pulse](https://cryptoartpulse.com/)
* [Numerai](https://numer.ai/)
* [Tornado Cash](https://tornado.cash/)

