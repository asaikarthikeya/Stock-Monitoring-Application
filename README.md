# Stock Monitoring Application.
- Stock Monitoring application that helps you to search and track the NASDAQ listed companies.
 
- The Stock information is fetched from Alpha Vantage API and is presented in a graphical way.
 
- ObjectBox database is used to store the watchlists and Fire base is used for User Authentication.

- Watchlists are User specific, each user has a different watchlist. 

- Followed Model-View-Presenter (MVP) architecture and other good practices.


## Screenshots

| Stock Representation | Stock Search | User Watchlist | User Authentication |
| :------------------: | :----------: | :------------: | :-----------------: |
| <img src="https://github.com/asaikarthikeya/stockmonitor-androidapp/assets/70392921/b55867e7-8673-435a-a643-ff37f10b41b1" alt="Stock Representation" style="width:200px; height:400px;" /> | <img src="https://github.com/asaikarthikeya/stockmonitor-androidapp/assets/70392921/b47e6893-3ea9-48f2-ac48-dbe809d3f8e4" alt="Stock Search" style="width:200px; height:400px;" /> | <img src="https://github.com/asaikarthikeya/stockmonitor-androidapp/assets/70392921/ab26d89c-ad8b-4725-9a90-3b06fff05cf0" alt="User Watchlist" style="width:200px; height:400px;" /> | <img src="https://github.com/asaikarthikeya/stockmonitor-androidapp/assets/70392921/f1233d76-7f49-4448-888b-3f02a5b884d3" alt="User Authentication" style="width:200px; height:400px;" /> |

## App Flow 



https://github.com/asaikarthikeya/stockmonitor-androidapp/assets/70392921/c9608f19-9040-47bf-87af-e8fbf01764f6


## Setup
- Clone/download the repo into the Android Studio.
- Obtain an API key from [here](https://www.alphavantage.co/support/#api-key). And place it in  [App.kt](https://github.com/crazzyghost/stockmonitor/blob/master/app/src/main/java/com/crazzyghost/stockmonitor/app/App.kt)
- Run the project

