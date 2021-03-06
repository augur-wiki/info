<p align="center"><img src="https://avatars1.githubusercontent.com/u/48164410?s=200&v=4" alt="Augur.Wiki logo" style="width: 80px;"/></p>
<h1 align="center" style="border-bottom: none;">Augur.Wiki | Info</h1>
<p align="center" style="margin-top: -10px; padding-left: 10%; padding-right: 10%;">Open-sourced, community-funded analytics, historical database, and developer platform built for Augur. Built to be a unified service enabling easy statistics-backed analytics for the average user.</p>

# Overview

### The problem
As a relatively early-stage platform, Augur has garnered enthusiast usage and is beginning to approach a more user-centric environment through platforms like [Veil](https://veil.co) and [Reporters.Chat](https://reporters.chat/), which aim to simplify the process of using the platform, for the average user.

As it grows though, there are limited expansive analytics resources. While there are niche tools and other web platforms offering specific services (think [Predictions.Global](https://predictions.global/), [Crystal Ball Be](http://crystalball.be/stats/), etc.), there are currently no open-source platforms for analytics, statistics, historical reporting, etc.

### The solution
Augur.wiki is an open-source initative , which aims to build a unified platform for Augur statictics and analytics. In specific, the current plan of action is focused around building:

1. Simple analysis dashboards which display specific network statistics (things like sync data, unique addresses, open interest, finalized markets, etc.)
2. Reporting dashboards which show the latest trades to happen on the platform in live-time.
3. Historical dashboards which allow users to search through past markets with simple keywords, view historical decisions made by other users, and analyze the specific hour-by-hour analysis of each market.
4. GraphQL API to allow developers to easily integrate platform data into their own applications.
5. A clean, easy-to-use User Interface so that the average user is able to easily access the data they need.
6. Plus, a few other small features I'm currently experimenting with (things like cross-platform alerts that you can setup to trigger when market actions occur, etc). More on this in the upcoming weeks, as I work out platform specifics.

# Development milestones
#### First milestone
Estimated date of completion (including testing): April 1st, 2019

Description of tasks to complete by this date:

1. [X] Procure domain name, hosting.
2. [ ] Configure server architecture, load-balancing, auto-deployment, CI, and setup repository with contributing guidelines, and front-end + back-end starting points.
3. [ ] Finish building front-end; up until further back-end integration is required.
4. [ ] Have Express server running and pushing out simple analysis dashboard views.
5. [ ] Have search functionality for historical markets live.
6. [ ] Have minimal viable API functionality working.

#### Second milestone
Estimated date of completion (excluding final testing): April 22nd, 2019

Description of tasks to complete by this date:

1. [ ] Have GraphQL outgoing API fully functional.
2. [ ] Have historical reporting (non-search) built and ready-to-go.
3. [ ] Have livetime reporting dashboards be live-time instead of the WIP synchronous as in the first milestone.
4. [ ] Have developer documentation built and ready to go.
5. [ ] Be ready to go live.
6. [ ] Deploy to IPFS and be running a node to interact with the network in a more decentralized fashion (reducing reliance on third-party API's).
6. [ ] **Begin working on Augur.wiki link**. Let users easily sign a nonce with their frequently used Augur addresses and populate a personal dashboard with their market information, markets they've participated in, statistics, and setup alerts, etc.

# Finances
The following are the finances for the Augur.Wiki project at the moment:
### Active sources of revenue
| Funding Organization        | Type             | Link | Amount | Received? |
|-----------------------------|------------------|------|--------|-----------|
| Forecast Foundation (Augur) | Community Bounty | [Augur Issue #1267](https://github.com/AugurProject/augur/issues/1267)| $2500  | :x:       |