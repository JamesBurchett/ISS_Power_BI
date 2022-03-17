# ISS_Power_BI

This project was to create an embedded streaming real-time view for public consumption of the current location of the ISS Space Station in Power BI. Visuals were to incluide  a map, a trajectory history of the ISS and current co-ordinates. 

The station location is taken from a simple API available from http://api.open-notify.org/iss-now.json.  I had initially written a Python script that was able to take in the data from the API and then feed it to the Power BI Streaming Data Set and host to this script on Python Anywhere. I created working script but in doing so discovered that I was able to host the feed via a cloud flow on Power Automate which would also parse the JSON data so used the Power Automate method instead. My thinking was that this would be using a single additional tool rather than two additional tools outside of the Power BI eco-system as Power BI.

Unfortunately although I was able to obtain streaming data on my desk-top this was not available as an embedded file that I could host as HTML on my current license. According to Microsoft documentation embedded real-time analytics are definitely possible in Power BI but don't come out of the box as are not native to the application. 
