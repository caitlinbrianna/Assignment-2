# Assignment-2
This assignment is for my Mobile Application Development class using Android Studios. 
The goal of this assignment is to build an application that reads SMS messages and searches them for Ticker symbols. 
The symbol will be added to a bookmark list upon reading a valid Ticker Symbol. 
The user will be able to open the info page of tickers in the watchlist within the app.
This assigment utilizes Fragments and Content Providers.

The Ticker Watchlist Manager is composed of these components:

  - A Main Activity
   -Contains two fragments
    
  -TickerListFragment
    -Three default values
    -Updates list with new Tickers
    -Display maximum of 5 Tickers
    -Sends URL to InfoWebFragment on item check
    
  -InfoWebFragment
    -Loads URL in WebView
    
  -BroadcastReceiver/SMSReceiver
    -Receives new sms broadcast
    -Extracts message from broadcast
  
