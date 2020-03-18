---
layout: post
title:  "Third post | Understanding whats needed"
date:   2020-03-18 12:50:00 +1200
---

All settled in now, I have been wrapping around how i need to manipulate the invoice data Pulled from BlueBerry's provider into the format required by the xero API. 

* The fields on the left represent the data needed to be pulled from CSPs invoice spreadsheet
* Data on the right represents the Fields as required by the Xero Invoice API 
* "Line item" is a collection which is part of the JSON file sent to Xeros API
* There are Several "Static fields" which remain constant for each invoice.. account number, tax type etc.

![Data comparison table](/assets/invoice.PNG)

Fortunately, the CSV tool I created earlier is useful here as the CSP invoice data is a CSV  :

CSPs api call to pull the data seems straightforward but at the moment, the system is still in beta and not live yet. (Pulls only the headers, not the customer data)
I called blueberryITs contact for CSP and asked for an explanation. He tells me there is an issue with microsoft services which use EST time and our time NZT which is preventing them from having the service function 

He estimates that at the end of the month the system will be operational. 


Signing out for now..



    
