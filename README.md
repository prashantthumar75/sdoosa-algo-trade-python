# sdoosa-algo-trade-python

This project is mainly for newbies into algo trading who are interested in learning to code their own trading algo using python interpreter.

This is in the context of Indian stock exchanges and brokers.

Stock

    o Free API for treading data - https://iexcloud.io/
                                    - API key for free : https://polygon.io/dashboard
    o YouTube : https://www.youtube.com/watch?v=xfzGZB4HhEE
    
    o Blog : https://blog.quantinsti.com/trading-with-python-indian-markets/
    o Blog : https://blog.quantinsti.com/python-trading/
    

    o Book : https://www.google.co.in/books/edition/Python_for_Algorithmic_Trading/gZIIEAAAQBAJ?hl=en&gbpv=1&printsec=frontcover


    o Github : https://github.com/sreenivasdoosa/sdoosa-algo-trade-python/ 
    o youtube : https://www.youtube.com/watch?v=3OuIO5wMkaU


    o Algo trading Full video for basic with Zerodha API with charges ( YouTube channel):  

          - https://www.youtube.com/channel/UCLqEaiHkRGZ-kpgjqsWV9uw     
          
Document for Zerodha:- from youtube: https://www.youtube.com/watch?v=3OuIO5wMkaU&ab_channel=AlgoTrader

   
    o different types of API to use in-app
        - Login APIs: mostly redirect
        - Instruments APIs: underlying instrument code than only place order, in case of file no need
        - Order APIs: placing orders, modifying the order, cancel the order
        - Quotes APIs: For the current market price, all of the prices ie. day high, day low
        - Historical Data APIs:  Time frame for all: 1 min, 3 min, 1 day,
        - Get Positions/Funds Any other: get position and fund


    o basic design ( higher level )
        1) Login and get access token and account 
        2) Fetch all instrument data
        3) Ticker service: forget data two option
                   - get a quote (it has HTTP and use for 3 min, 5 min )
                   - Web socket ( If we want a faster mechanism within seconds then go with web sockets )
        4) Start your strategy: placing an order 
        5) Place an order on conditions met by strategy :  
        6) Place SL and target order if applicable :
        7) Keep tracking the status of all orders and alter if needed
        9) Square off trades before market closing ( for intraday )
        10) Logout 


    - Live demo: https://www.youtube.com/watch?v=R_vKcpuAbVA&list=UUAHU2MpYKl18V2lC_tZ2Brw&index=18

    o Multithreading 
        - 


    o Fetch instruments

    o Get current market price using quotes

    o Placing order

    o Placing SL order

    o Modifying order

    o Cancelling order

    


