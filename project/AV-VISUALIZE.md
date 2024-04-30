# ![Automate](https://raw.githubusercontent.com/AlgoView/.github/main/resources/AV-VISUALIZE_head.jpg)
# Scope of this server
This server is the main server for the AlgoView project, it is the server that will host the main user interface and controller for the project.

Basically it's the frontend for all AV servers and services.<br>
This server will have a backend that will communicate with the other servers and services, and stores the data that is needed for the user interface.

## Visualization of market and alalythical data 
To visualize market data we will use the ```Tradingview charting library```, this library is well known and has a lot of capabilities to visualize data.

To visualize graph data not fittable in the Tradingview library we will use other libraries like ```D3.js library```, ```Gym-Trading-Env```, ```Plotly``` or whatever fits best to our needs. 

## Manual Trading tools
The user interface will have tools to manually trade on exchanges.<br>
These will be completely self designed, as the current tools do not best fit the traders needs and are full of poorly designed features and misrepresentative and useless information.

> For example: lets draw attention in specific to the positions and orders management in futures trading. Currently when a position is opened on cross-margin, the position %PNL is not relative to the full margin available, but rather to some fictitious margin based on the leverage used. Like this there are many more examples of poorly designed features that can be, and should be improved on.

## Automation Tools
The user interface will have tools to apply algorithms on screeners, trading pairs and on portofolio and account management.<br>
> The combination of a good strategy, and good money management is key to success in trading, and we aim to provide the tools to make this as easy as possible.
But also to enable the automated screening of trading pairs to be able to trade on many pairs at the same time, giving the trader bayond human capabilities.

## Guidance and analyses Tools
The user interface will have tools to guide the user in workflow, and to give analyses on the performance of its setup or manual trading.<br>

## Server monitoring and management tools
The user interface will have tools to monitor and manage the servers that are running their AlgoView project.<br>
>These should be limited to tools that control large functions of the servers, and not to the small details that can be managed on the servers themselves.
Monitoring tools should be able to give the user a quick overview of the status of the servers, and the management tools should be able to control the servers in a way that is easy to use and understand.

# Setup 

