# ![The Algoview Project](https://github.com/AlgoView/.github/blob/main/resources/AV-PROJECT_banner.jpg)
## Introduction
This is a project for and by algorithmic trading enthousiasts and quantitative analysts that aim to take their creativity to the next level.
On robust systems we aim to create an easy to use environment usings the well known Tradingview charts.

We do this as much of the work in building good algorithms is done with good analyses, and visualisation.
Calculations that are done faster, speeds up the process of this type of developing.

This project is **Opensource** and open for people to join at all times

## Get Involved
Right now, AlgoView is in its starting phase, and there will be excellent "good first issue" opportunities, if you're looking to get involved.
Contact the administrators to get started.

## Main objectives
### [Collect `market and chain data`](https://github.com/AlgoView/.github/blob/main/project/AV-COLLECT.md)
* Store and Access more than OHLCV Data
* Create usefull derivatives
### [Simulate `Backtesting, projection testing, Analythical tools`](https://github.com/AlgoView/.github/blob/main/project/AV-SIMULATE.md)
* Enable unlimited scripting capabilities with python
* Automated adaption & fitiing
* Machine Learning
* ...
### [Automate `Exchange connection with Portofolio management tools`](https://github.com/AlgoView/.github/blob/main/project/AV-AUTOMATE.md)
* Establish a secure two way connection with exchanges
* Automated and manual tools to manage portofolio's
### [Visualize `User interface and controller`](https://github.com/AlgoView/.github/blob/main/project/AV-VISUALIZE.md)
* Chart market/chain/analythical data with Tradingview's charting library
* Automation Tools
  * Apply algoritms on trading pairs
  * Apply algorithms on portofolio management
* Manual Trading tools 
* Server Status tools

![](https://raw.githubusercontent.com/AlgoView/Project-scope/main/img/AVAPI.jpg)

**Main Tasks have been split into 4 servers, for following reasons**
> **Structure :** For to the project and version control of its parts.
>
> **Security :** By using API's between the different task to increase security capabilities. 
> 
> **Stability :** Faults can be isolated easily, versions can be reverted where it is specifically needed.
>
> **Flexibility :** Users can set up servers at home or on a dedicated service, depending on the `uptime`  `connection speed` `Computing Capability` `security needs` required for each task.

## Roadmap
To initiate the project, focus should go to **AV-Visualize** and **AV-Collect**, as **AV-Automate** and **AV-Simulate** are dependent on them. We can visualize historic and live data through API right from the start, using the CryptoCompare API, as shown in the [charting library Tutorial](https://github.com/tradingview/charting-library-tutorial). **AV-Collect** will function as a server that provides the AV-Visualize server with the historic data.

To get basic functionalities working on **AV-Visualize** / **AV-Collect** / **AV-Automate** , The project can first focus on creating manual trading tools in **AV-Visualize** that triggers **AV-Automate** to API the users trading account.

### Phase 0 : Custom Data Charting
**AV-Collect** and **AV-Visualize**
- Provide market data and chart it.

### Phase 1 : Manual trading tool
**AV-Collect** fetches user data from **AV-Automate** to
- store current/historic orders/trades/positioning
- store portofolio balance , fees , pnl

**AV-Visualize**
- Provides user with a trading panel
- visualize historic trades/positioning
- visualize portofolio balance , fees , pnl
- View running positions
- View open orders

### Phase 2 : Automation
**AV-Visualize**
- Control over algorythms
- Visualisation of algorythms

**AV-Simulate** creates
- historic data out of Algo results (backtesting)


### Phase 3 : Expansion
**AV-Collect**
- Adding more trading pairs and exchanges
- Adding Historic market depth
- Adding Blockchain metrics

**AV-Simulate**
- Complete analythical backtesting tools
  - Testing a spread of settings for one or more variables & visualizing the results
- Projection testing
  - Run Algo's on generated noise that mimics normal market movements
  - This noise generating AI could continiously train itself by generating noise and testing how much it fits the actual market, alongside with Larger and uniform metrics and derivatives that describe that market, such as Market cap, #coins, %inflation, %Volatility/lenght ..

**AV-Visualize**
- Add chat functionality
- Add Alerts
- Add data window
- Add watchlist functionality for trading pairs and algorithms
- Add Screener functionality for trading pairs and algorithms