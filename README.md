#LA Homeless Encampments 

Joyce Tao, Christian Fernandez, Orlando Lepe, Dikshant Dhall, and Richardo Flores 
https://chrisfdzl.github.io/Sources.html

Introduction 

Homeless encampments are locations where one or more homeless people live in an unsheltered area. These encampments can be found on properties owned by private individuals or companies, or owned by local, state, and federal governmental agencies. 

Per National Alliance to End Homelessness recorded State of California have a total of 129,972 of people homes on a given night and 33 homeless per 10,000 people in the general population. 

As showed below homeless record in Los Angeles from 2016 to 2018. 

Year 	Total Homeless Population 

2016	39,587

2017	45,978

2018	45,039

Total 	180,125

(Source: https://www.lahsa.org/data?id=13-2019-homeless-count-by-community-city )

Homeless is a crisis point in Los Angeles, we want us data to investigate the following questions:

	Analyze the City’s Homeless encampment cleanup efforts in response to citizen requests. Are those efforts efficient/inefficient? 
	How do City residents report homeless encampments? 
	How can the City better allocate resource? 

MYLA311 Service Request

The City of Los Angeles MYLA311 Service Request created to the general public for non-emergency services, such as bulky items, containers, service not complete, illegal dumpling pickup, metal/household appliances, etc.  

Citizens can connect with MYLA311 Service Request via MYLA311 mobile app, MyLA311 website, by calling or emailing the MyLA311 Contact Center team, or via social media where you can find @MyLA311 on Twitter and Instagram.

Website: http://www.myla311.lacity.org  | E-mail: 311@lacity.org
Twitter	https://twitter.com/MyLA311
Instagram: https://www.instagram.com/myla311/
311 Contact Center:	Dial 311 or (213) 473-3231

Popular Services inclcude: Reporting dumping or trash collection issues, Requesting bulky item pick-up appointments, Reporting potholes, graffiti, street light problems, Parking Enforcement, Animal Services, General City and government information.

Data Description

311 service request and compliant data are being collect by MyLA311.lacity.org and data.lacity.org for Encampment Tracking. We explore the 311 datasets in Los Angeles particular in Encampment Tracking for the periods between from 2016 to 2018. 

We downloaded three years datasets via csv format which contain over 3 Million data. Here are some of the collected data given variable. 

1.	Created Date: Date of received 
2.	Service Date: Date of service preformed 
3.	Closed Date: Completed
4.	Address Verified: Any address provided 
5.	Approximate Address: Any partial address provided 
6.	Address (house number/direction/street name/suffix/zip code): Physical address 
7.	Request Source: Call, City Attorney, Council Office, Driver Self Report, Email, Fax, Mobile App, Queue Initiated Customer Call, Self Service, Twitter, Voicemail, and Web Form.
8.	MobileOS: Android, iOS, and others
9.	Anonymous: Y and N
10.	CD: City District 
11.	CD Member: Name of City Members 
12.	Assign To: Initial of the Persona Assigned To
13.	Zip Code: 5 digit numbers zip code the Los Angeles 
14.	Latitude: Mapping Location
15.	Longitude: Mapping Location 
16.	Location: duplicate entry of the latitude

Other supporting data include City Employee Payroll from Ron Galperin LA Controller at https://controllerdata.lacity.org/Payroll/City-Employee-Payroll/pazn-qyym/data.  This data contain the payroll information for all Los Angeles City Employees including the City’s three proprietary department: Water & Power, Airports and Harbor, which contain 371,455 records. Los Angeles Homesless Service Authority shows record of the homeless count by Community/City. 

Data Cleaning and Analysis 

We used Python and Tableau to perform the data cleaning, data analysis, and visualization. 

•	Python: Pandas, Numpy, Glob, OS, Matplotib, and datetime

• Machine Learning: Prophet (Facebook) and Plotly

•	Tableau: dashboard and heat map 

•	HTML/css for web development 
