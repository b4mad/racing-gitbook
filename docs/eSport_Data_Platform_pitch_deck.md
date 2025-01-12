# \#B4mad eSport Data Platform

## Summary

B4mad eSports is conceptualized as a comprehensive platform designed to support competitive gaming services by providing a robust infrastructure. The initial focus is on the growing sim-racing market, supported by a viable prototype. The founder has 25+ years of background in Open Source Software development and building AI and data platforms at Red Hat.

## Simracing Coaching

Sim racers enjoy the process of data collection, skill enhancement, and engaging in spirited competition. Mastering a track and consistently improving lap times requires tenacity, discipline, and a significant time investment.
B4mad Racing is designed to chronicle a driver's history across various games, enabling racers to refine their skills via innovative products and comparing their performance with competitors. The user base spans from casual players to more committed enthusiasts.

### Prototype

Sim racing games offer a wealth of telemetry data, such as speed, lap times, and motor data. We collect this telemetry, storing it securely in a cloud-based platform.
By analyzing aggregated data from all drivers, we can construct models for racing tracks. This telemetry data stream is harnessed during a racing session to provide personalized recommendations, helping drivers enhance their lap times. This is delivered via a text-to-speech system \- reminiscent of having a personal driving coach in the passenger seat. The existing prototype integrates with 5 sim-racing titles and has 200,000+ recorded laps and 90 active users.

### Simracing Platform

The coaching application is just the inaugural product of a broader platform that specializes in sim-racing data collection, processing, and hosting sim-racing applications.
Currently, most sim-racing services, including coaching sessions, telemetry collection, and live race dashboards, operate independently, each needing to build and maintain its own infrastructure.
Our platform intends to streamline this process by serving as a comprehensive base, catering to a wide range of services and providing the underlying architecture necessary for each service. This model aligns with established patterns seen in successful platforms like OpenStack in the telecommunications industry.

## Please describe your startup in a few sentences so we can get a first overview.

B4mad eSports is conceptualized as a comprehensive platform designed to support competitive gaming services by providing a robust infrastructure. The business model is a platform economy where developers, gamers and eSport professionals transact.
The initial focus is on the growing sim-racing market, supported by a viable prototype.
The founding Team has a long track record Open Source Software development and building AI and data platforms at Red Hat and other start ups.

#### Who is your biggest competitor, and how are you different?

[https://grid.gg/](https://grid.gg/) \- provides an eSports data platform. Our approach is rooted in open source and community building. We aim to support more games and let gamers craft free services for outreach and awareness. While a gamer might not know grid.gg \- they should know us and our marketplace and discover services.

#### Why has the problem you're solving not been solved before?

With current improvements in AI it has become viable to build niche services and extract insights from raw data at relatively low cost. [https://huggingface.co/](https://huggingface.co/) became successful by democratizing access to AI – similarly the current tooling available to the mediocre coding skills of gamers just sucks. We’ll make it suck less

#### What is your vision? Where will \#B4mad eSports Data Platform be in 10 years time?

A service running on our platform will be used in every gamers daily live. We will be the go-to destination for any problems related to eSports and gaming that could be solved by data.

#### How much are you looking to raise (in EUR)?

#### EUR 2-4 Million

####

# Pitch Deck

### Introduction

* Data and Application Platform for eSport services
* Application platform for building data-driven eSport services
* Application platform for building intelligent and data-driven eSport services for the masses
* A community-driven application platform for building intelligent data services for the eSports community
* **An open application platform for building intelligent and data-driven services for the eSports community**

\--ChatGPT

* An open platform for crafting intelligent, data-driven eSport services for the entire gaming community.

Absolutely; based on the instructions provided, here are five concise variations for your intro pitch sentence:

1\. "Redefining eSport analysis: An open platform for data-driven gaming insights."
2\. "The Airbnb for eSport analysis: Connect, analyze, and improve with community-driven data."
3\. "Turning raw game data into actionable insights for every gamer."
4\. "Your eSport coach in the cloud: Data-driven, intelligent, and tailored for every player."
5\. "Beyond gameplay: A platform harnessing data for smarter eSport strategies."

Each of these aims to provide clarity while avoiding jargon and ensuring that the business's core offering is immediately understood.

Certainly\! Here are five additional variations for your intro pitch sentence:

1\. "Unlocking eSport potential: A platform for data-infused gaming excellence."
2\. "From novice to pro: Harnessing data to elevate every eSport journey."
3\. "Game, analyze, improve: The definitive platform for data-driven eSport enhancement."
4\. "Transforming eSport with intelligence: Where data meets game mastery."
5\. "Empowering gamers with insights: The nexus of eSport data and performance."

Each variation aims to emphasize your platform's transformative and empowering nature while keeping it succinct and clear.

#### Slide 1

**Large statement:** An open application platform for building and hosting intelligent apps and data-driven services for the eSports community
**Subtitle:** Transforming eSport with Intelligence: Where data meets game mastery.

/Slide 1

**Problem**

* ESport lacks the same professional analysis as physical sports
* Esport tools build the supporting infra repeatedly, lacking a common platform
* Tooling for the masses does not exist

Building services for games is hard because getting in-game data is challenging, and analyzing in-game data is hard. Existing services duplicate the non-differentiating lower part of the stack.

Therefore, only narrow solutions exist, either providing shallow in-game data, e.g. just results, or only category-specific trainers, e.g. aiming trainers. Providers spend a lot of effort on data retrieval and lack application breadth and depth.

The service providers are left with non-scalable (1:1 training) or shallow and non-interactive (video tutorials, just data visualization) solutions.

Professional eSport athletes get better training than aspiring gamers.

**\--- ChatGPT**
Certainly, based on the provided information, here are bullet points for the Problem slide in your investor pitch deck:

\*\*Problem Statement\*\*

\- \*\*Inconsistent eSports Analysis\*\*: Unlike physical sports, eSports lack comprehensive, professional analysis tools.

\- \*\*Redundant Infrastructure\*\*: Many eSport tools reinvent the wheel, building duplicate infrastructures rather than leveraging a unified platform.

\- \*\*Limited Tool Availability\*\*: A significant void in broad-based tooling for the average gamer—current tools cater mostly to professionals.

\- \*\*Complex Data Retrieval\*\*: Building services for games is challenging due to the difficulties in accessing and analyzing in-game data.

\- \*\*Duplication Efforts\*\*: Current services overlap significantly, wasting efforts on the lower, non-differentiating parts of the stack.

\- \*\*Narrow, Shallow Solutions\*\*: Most solutions are either too narrow (like specific trainers) or provide only superficial data (e.g., just results).

\- \*\*Non-Scalability & Depth Issues\*\*: Service providers often offer non-scalable services like 1:1 training or shallow solutions like mere data visualization.

\- \*\*Pro-Am Disparity\*\*: Professional eSports athletes receive high-quality training, but aspiring gamers are left with sub-par resources.

Remember to structure these points visually to make them easy to read and digest. You may also consider using icons or graphics to illustrate each point and make your slide more engaging.

#### Slide 2

Headline: Problem

* **Complex Data Retrieval** challenges in accessing and analyzing in-game data
* **Redundant Infrastructure** tools reinvent the lower part of the stack and support only one genre
* **Narrow, Shallow, Non-scalable services** too specific trainers, superficial data, 1:1 training/coaching
* **Pro-Am Disparity** lack of support for amateur players and comprehensive analysis tools

/Slide 2

### Solution

A platform to make building game-specific intelligent services easy.
Common infrastructure to collect and store in-game data at scale and a runtime to create services that work on live game data and support live feedback to players.
Tapping into advances in AI (LLM, CV) and gaming infrastructure (discord, twitch), the collection, analysis and feedback loop building blocks have been commoditized.
A platform that embraces the gaming community to build free services for growth and awareness and commercial services for eSport professionals.

**\--ChatGPT**
Of course, here are the bullet points for the Solution slide based on your provided information:

\*\*Our Solution\*\*

\- \*\*Unified Gaming Platform\*\*: Simplify the creation of game-specific intelligent services with a streamlined platform.

\- \*\*Scalable Data Infrastructure\*\*: Common infrastructure designed for efficiently collecting and storing vast amounts of in-game data.

\- \*\*Live Game Runtime\*\*: Advanced runtime environment to facilitate services that operate on live game data and offer real-time feedback to players.

\- \*\*AI-Driven Insights\*\*: Leverage the latest AI technologies, such as Large Language Models and Computer Vision, for in-depth game data analysis.

\- \*\*Integrated Gaming Ecosystem\*\*: Seamlessly interconnect with key gaming platforms like Discord and Twitch for holistic service provision.

\- \*\*Commoditized Feedback Loop\*\*: Establish a consistent and efficient feedback mechanism for enhanced player training and improvement.

\- \*\*Community-Centric Approach\*\*: Foster a platform where the gaming community can craft free services for outreach and awareness.

\- \*\*Tailored for All\*\*: While embracing the masses, we also offer specialized, commercial solutions for eSport professionals.

These points aim to provide a concise, easy-to-follow overview of your solution that captures the attention of potential investors. Make sure to use a design that complements the content and aids in its digestibility.

#### Slide 3

Headline: Solution

* **Unified Platform** Simplify the creation of game-specific intelligent services with a streamlined platform
* **Scalable Data Infrastructure** designed for collecting and storing vast amounts of in-game data efficiently
* **AI-Driven Insights** in-depth game analysis beyond pure in-game data
* **Community-Centric** the community can craft free services for outreach and awareness
* **Platform Economy** a marketplace where developers, gamers, and eSport professionals collaborate and transact

/Slide 3

### Market

* Size: competitive gaming (Fortnite) \+ esports games (dota2)
* Share: 10% play competitively \-\> 10% would pay for services

The global esports market size has been growing significantly over the years. Here are some insights from various reports:

* The esports market was valued at **USD 1.45 billion in 2022** and is projected to grow to **USD 1.72 billion in 2023**, eventually reaching **USD 6.75 billion by 2030** with a compound annual growth rate (CAGR) of **21.5%** during the forecast period [1](https://www.fortunebusinessinsights.com/esports-market-106820#:~:text=The%20global%20esports%20market%20size,during%20the%20forecast%20period) .
* Another report estimated the esports market size at **USD 1.88 billion in 2022**, with a predicted CAGR of **26.8% from 2023 to 2030** [2](https://www.grandviewresearch.com/industry-analysis/esports-market#:~:text=Report%20Overview%20The%20global%20esports,from%202023%20to%202030) .
* The market size 2022 was also reported as **USD 1.45 billion**, with an anticipated growth to **USD 1.72 billion in 2023** by Statista [3](https://www.statista.com/statistics/1256162/global-esports-market-size/#:~:text=Jul%2013%2C%202023%20In%202022%2C,forecast%20to%20reach%20a%20value) .
* A report by Mordor Intelligence indicated that the esports market size is expected to grow from **USD 2 billion in 2023 to USD 4.39 billion by 2028**, at a CAGR of **20.05%** during the forecast period (2023-2028) [4](https://www.mordorintelligence.com/industry-reports/esports-market#:~:text=The%20eSports%20Market%20size%20is,for%20casual%20gamers%20to) .
* In another forecast, the esports market was valued at **USD 2.11 billion in 2022** and is expected to grow at a rate of **24.4 % CAGR from 2023 to 2029**, reaching almost **USD 9.75 billion in 2029** [5](https://www.maximizemarketresearch.com/market-report/global-esports-market/36686/#:~:text=Esports%20Market%20was%20worth%20US%24,factors%20for%20driving%20the%20market) .

These reports suggest a robust growth trajectory for the esports market over the next several years, although the exact market size and growth rates vary slightly among different sources. This growth is driven by factors such as increasing audience engagement, rising live-streaming activities, and a growing interest in competitive video gaming.
To calculate the market size specifically for competitive games within the esports domain, you might want to delve further into sub-segments of the esports market, such as game sales, in-game purchases, tournament prize pools, and other revenue streams associated with competitive gaming.

[https://www.demandsage.com/esports-statistics/](https://www.demandsage.com/esports-statistics/)
There are 532.1 million e-sports audiences worldwide as of 2023

* huge and emerging market
  * \# of market participants and \#revenue
  * \# of business models
* Highly fragmented – easy to find, and repeatable to find a niche
  * Characteristics of games
  * Active-passive ratio
  * Pro-Am ratio
* Democratizing access to eSports
  * It's hard to become a real F1 driver (financial investment, access to decision-makers)
  * Providing opportunities for 'the average guy' to freak out as a star

* ~~Emerging eSports market~~
  * ~~Participants player base is set to hit 3.38 billion~~
  * ~~Revenue is poised to reach USD 3.8 billion with diversified and evolving business models fueling sustainable growth \[pay2learn2win\]~~
* **~~Fragmented eSports Landscape~~** ~~enables niche market opportunities~~
  * **~~Game Characteristics:~~** ~~Diversity in game genres (e.g., FPS, racing) .~~
  * **~~Participant Engagement:~~** ~~Varying active-passive ratios among gamers and viewers provide distinct market segments.~~
  * **~~Skill Levels:~~** ~~A broad spectrum from professionals to amateurs offers multiple entry points for startups~~

* **~~Democratizing eSports Access:~~**
  * **~~Low Entry Barriers:~~** ~~Unlike traditional sports like F1, esports requires minimal financial investment, opening doors for many.~~
  * **~~Open Opportunities:~~** ~~The digital nature of esports democratizes access, allowing the 'average guy' to aspire for success.~~

#### Slide 4

Headline: Market

* **Emerging Esports Market:**
  * **Participants:** $3.38 billion player base.
  * **Revenue:** $3.8 billion, fueled by diversified business models \[pay2learn2win\].
* **Fragmented Esports Landscape** enables niche market opportunities**:**
  * **Genres:** Diverse, e.g., FPS, racing
  * **Engagement:** Varying active-passive gamer and viewer ratios.
  * **Skill Levels:** Wide range from professionals to amateurs.
* **Democratizing Esports Access:**
  * **Entry Barriers:** Lower than traditional sports like F1.
  * **Opportunities:** Digital nature enables success for the 'average guy'.

/Slide 4

[https://chat.openai.com/share/7b05d07c-0cc4-4307-aa7e-114dcd2e192e](https://chat.openai.com/share/7b05d07c-0cc4-4307-aa7e-114dcd2e192e)

### Product / Proof of concept

This is one proof of concept for the Sim Racing context (that is the one closest to our hearts)

#### Slide 5

Headline: Product / Proof of concept

* End-to-end application prototype for the sim racing genre
  * Web user interface for the end-user of the app
  * In-game coaching feedback to the end-user
  * Interface and SDK for the app creator
  * Data collection, analysis, and storage
  * Content creator's application for in-game insights

* Community and adoption
  * \# of laps stored / \# of active drivers
  * Embedded in \#1 racing tool (CrewChief)
  * 18 months years of development

* Architecture and development path
  * 18 months of continued experimentation, applying our professional expertise
  * Based on industry best practices and professional experience of team
  * Identifying the platform idea as the enabler

/Slide 5

### ~~Validation / Traction~~

~~Timeslot~~
~~Animated presentation~~
~~video~~
~~Screenshots~~
~~demo~~

### Team

#### Slide 6

Alle 3 auf ein Slide, jeweils mit Headshot
Headline: Team
Marcel Hild

* Red Hat and Start-Ups
* Management / Engineering / Sales / Research
* AI and Data processing
* 25 years in Open source
* Gaming end-user

/Slide 6

### Competition

#### Slide 7

Headline: Competition

* eSports game results data – shallow – used for 3rd party apps, e.g. betting \[grid.gg\]
* Genre-specific trainers and services \[aimlab, vrs school\]
* YouTube / Twitch for non-interactive tutorials and marketing
* Self-marketed professionals on coaching marketplaces \[[https://ww](https://www.proguides.com/)w.proguides.com/ [https://g](https://gamersensei.com/)amersensei.com/

/Slide 7

### Example Services

#### Slide 8

Headline: Example Services

* Your Racing Career
  * Achievements across racing games document. Going beyond game specific achievements and badges.
* Club Leaderboards
  * Record results for closed groups of gamers
* Personalized Race Track Guide
  * Learn the track while driving. Let the AI coach explain the track while you drive
* Driving School
  * A full interactive course, that teaches you to drive a like a pro. In any simulator you choose.
* Chat with the adventure game.
  * Stuck? Can’t find the golden egg? Instead of browsing the web, just ask your friendly AI companion.
* MontanaBlack reacts
  * Live in-game reactions from your favourite YouTube Celebrety. Reaction Videos on the next level
* StarCraft strategy explainer
  * Boost your real-time strategy with live and post game in depth strategy analysis. Hit your opponents faster and harder.
* Tutorials tailored to your skills
  * No more lengthy or sparse tutorials. Let the AI watch you play and give usability hints when and if you need them
* Full API access
  * Build a complex service offering, by leveraging dedicated components of our stack.
* White Labeling
  * Don’t re-invent the wheel. Adapt common solutions to your corporate identity.
* ~~Transport Fever: where is my bottleneck?~~
* ~~Promotional announcements from sponsors~~

/Slide 8

### Financial Projections

#### Slide 9

Headline: Financial Projections
TBD

* S.u.
* Excel / s.u.

/Slide 8

### ~~The Ask~~

*

# Wildsammelstelle

## Vorlagen OneDrive

* Pdf (to see font preview)
  * [https://1drv.ms/b/s\!AgUxa3uA9D0E1jV2oI9a3AYAl-3r?e=qR575R](https://1drv.ms/b/s!AgUxa3uA9D0E1jV2oI9a3AYAl-3r?e=qR575R)
* ttf
  * [https://1drv.ms/u/s\!AgUxa3uA9D0E1jTZZV1LQ9houu2X?e=zvHJ3K](https://1drv.ms/u/s!AgUxa3uA9D0E1jTZZV1LQ9houu2X?e=zvHJ3K)
* ppt
  * [https://1drv.ms/p/s\!AgUxa3uA9D0E1hr9CvD-ohsy\_2db?e=VSlqdx](https://1drv.ms/p/s!AgUxa3uA9D0E1hr9CvD-ohsy_2db?e=VSlqdx)
* doc
  * [https://1drv.ms/w/s\!AgUxa3uA9D0E1h6\_pqewPhQr8GUb?e=SmdVss](https://1drv.ms/w/s!AgUxa3uA9D0E1h6_pqewPhQr8GUb?e=SmdVss)

Controlling rules to check competitors and own features

* The right thing
* At the right quality
* At the right amount
* At the right place
* At the right time

## Steps to make it comfy

* **Integration with Games:** Ensure that your platform seamlessly integrates with popular games. This might involve developing plugins, overlays, or apps that work within the game environment. Consider collaborating with game developers or modding communities to make the integration as smooth as possible.
* **Connecting Professionals and Gamers:** Build a user-friendly interface that allows professional guides, experienced gamers, pro-gamers, and influencers to offer their assistance. Implement a system for scheduling sessions, whether they are one-on-one coaching, group sessions, or webinars. Ensure that communication between professionals and gamers is secure and efficient.
* **Database and Knowledge Center:** Create a robust database that stores a wealth of gaming knowledge, best practices, and guides. Develop algorithms to recommend relevant content to gamers based on their needs and preferences. You might also consider integrating AI-driven features to provide real-time in-game tips and guidance.
* **Easy Content Sharing:** Make it simple for professionals and guides to upload their knowledge. Consider providing templates or predefined structures for different types of content, whether it's written guides, videos, or interactive tutorials. Offer support for content creation, including video editing tools or content management systems.

## 3 areas to connect

![][image1]


## 3 phases to grow

### Phase 1: One Platform, One Game/Genre, No third party

Niche, Highprice, PoC with own product
Investing
![][image2]
![][image3]

### Phase 2: One Platform, One Genres, Third parties Break Even, Let's go

![][image4]

### Phase 3: One Platform, Multiple Games/Genres,Third parties with own marketing

Growing without extra action
![][image5]

![][image6]

Stabile kosten fuer platform – line graph  \-  title: **platform costs**
Primary revenue via 3rd party apps – bar chart color – title: **platform revenue racing genre**
Scale via multiple genres – same bar stacked colors title: platform revenue FPS genre / X genre
Poc App – **bar chart in green.**
3rd party apps – **bar chart green shades**
\# FTE

![][image7]

![][image8]

[https://www.frontiersin.org/research-topics/14921/the-future-of-sport-business\#articles](https://www.frontiersin.org/research-topics/14921/the-future-of-sport-business#articles)

# Case Study: B4mad Technologies Application Platform

## The Sim Racing Challenge

**Gamer: Paul's Situation**

* **Profile:** Paul, 43, dedicated family man with a deep passion for sim racing.
* **Struggle:** Wants to improve his racing skills but finds self-training methods time-consuming, causing a strain on family commitments.
* **Aspiration:** To excel in sim racing competitions more efficiently, without compromising family time.

**Coach: Steve's Challenge**

* **Profile:** Professional sim racing coach with a popular YouTube tutorial channel.
* **Limitation:** Desires to expand reach and provide personalized coaching but is capped by the current manual coaching methods.
* **Vision:** To leverage technology for scalable, personalized coaching experiences.

## B4mad Technologies Application Platform

**For Coaches like Steve**

* Utilizes the SDK to develop a Coaching Application with his unique style.
* Gains access to a robust infrastructure that supports the app's requirements, from telemetry data to real-time feedback.
* Benefits from an integrated transaction and billing system, simplifying the business aspect.

**For Gamers like Paul**

* Discovers Steve's Coaching Application on the B4mad platform.
* Receives personalized, AI-enhanced coaching during gaming sessions, minimizing downtime.
* Quickly improves performance with targeted advice, maximizing gaming and family time.
* Engages with a community-centric marketplace that fosters continuous learning and improvement.

## Transformative Results

**For Paul**

* **Before:** Juggling between self-improvement in sim racing and family life.
* **After:** Achieves a balanced lifestyle with significant skill improvement through the B4mad-enabled Coaching App, delighting both his competitive spirit and family.

**For Steve**

* **Before:** Struggling to scale his coaching business due to time and resource constraints.
* **After:** Successfully multiplies his coaching outreach without additional time investment by leveraging the B4mad platform, resulting in increased revenue and customer satisfaction.

**Growth Potential**

* With the success seen by Steve, the B4mad Technologies Application Platform is poised to attract more professional coaches and developers, facilitating a richer, more diverse marketplace for gamers and a robust revenue model for coaches and developers alike.
