---
layout: post
title:  "Lockdown"
date:   2020-04-12 10:40:00 +1200
---
As of a couple a weeks ago, following the lock down announcement blueberry IT has pulled the plug on its physical office as all non-essential services are required to be closed, However the team is still working remotely and, I have been directed to continue working on the invoicing project.
I've been working on my CSV tool to handle data from CSP spreadsheet As of now, it seems to be functioning in the way I want it to, renaming necessary fields, renaming fields and entering static data(Eg tax amount, account number) I've also included functions to
* generate a unique id number for every invoice and save a record as persistence (Text file at the moment, best practice would be a database as record is less volatile) 
* Generate the invoice data (1st of following month)
* Generate the due date (20th of following month )


![texture theme preview](/assets/csvreloaded.PNG)


I can also delete entries and modify them via the datagrid view however, these functions will not be useful in the final product. Infact, the program is likely to be devoid of any interface depicting the data as its not necessary for the programs operation, it's simply an easy way to see if the data is manipulating correctly.


Also, this decoupling from windows forms should result in a more portable piece of code and allow me to move from .NET framework to .NET core.. if the organization was to restructure or expand in the future and use MacOS or linux systems this should be easy in theory.
Still no word on CSP's API status.. 
Now onto the xero API..



