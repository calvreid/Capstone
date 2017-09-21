# Capstone


I choose to frame my Capstone project as a business case. A family member of mine is choosing to start a gin distillery in Toronto. LCBO sells data to producers/distributors, however only of a few brands or stores, and it costs. At the same time, the LCBO has a website that you can access to tell you which LCBOs have your favourite wine in stock, or where to find your favourite scotch. An individual has spent +600 hours developing an API to scrape all the information from the LCBO website. This API, which also provides free and open daily datasets of LCBO data, scrapes all of the information from their system into three files:
•	Stores
•	Products
•	Inventories

Research questions that require answering include:
•	Which LCBOs have the highest sales of gin?
•	Which LCBOs have the most gin brands available?
•	Which LCBOs sell more gin as a ratio of spirits sales? As a ratio of overall sales?
•	Which LCBOs, based on geography, are likely to see an increase in gin sales? (this can be done by analyzing consumption of vodka, or non-gin craft Canadian spirits likely to convert or overlaying the data with environicsanalytics.ca to understand demographic tendencies and indicators towards new gin drinkers)
Deliverables include:
•	A recommender system that informs the client of what quantities to supply to which LCBOs. 

https://github.com/calvreid/Capstone/blob/master/LCBOAPI
lcboapi.com 
It is an open data set that requires an access key (free and unlimited access). I currently have a ‘Backend / Server – PHP, ASP, Python, Java, Ruby,etc’ Access Type



import urllib2
import json

req = urllib2.Request('https://lcboapi.com/stores')
req.add_header('Authorization', 'Token MDo5OTU4ZWVjMC05YmQ5LTExZTctODFiZS0xNzIxYjVmNGM3NDE6Z0JsS3QwNzZxZ1JMNUx3T1B2R0xUaTVkSk96SlVhQkJmYXRh')

data = json.load(urllib2.urlopen(req))

print data



Intend to do analysis in Apache Spark (PySpark)

Hive?



market analysis of liquor in Ontario?

What about wine vs beer vs liquor?
  


Login as: root
root@127.0.0.1’s password: CIND719hdp
hadoop fs -put /root/

hive


