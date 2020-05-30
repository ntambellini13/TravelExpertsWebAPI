# TravelExpertsWebAPI

Travel Experts Web API built with ASP.NET Core v2.2 and Angular v8 and integrated with SQL SERVER database. 
Deployed with Azure at http://tawicotravelexperts.azurewebsites.net/ (currently taken down)

Group Project done in 1.5 weeks during TechCareers Software Developer Certificate at SAIT in September 2019

Steps to Run Locally

1)	There are 2 different project folders within the in the overall TravelExperts Web API Project
a.	TravelExperts.API – contains the ASP.NET CORE portion
b.	TravelExperts-SPA – contains the Angular Portion
2)	Within the overall project folder there is a database file “customTravelExpertsDB.sql” – please install this in your MS SQL Server. Right now it is set to create the database on the C:// drive of your computer but it can be modified if needed
3)	Go to https://dotnet.microsoft.com/download/dotnet-core/2.2 and download and install  v2.2.7 SDK 2.2.109 globally on your computer (this is the version compatible with visual studio 2017 and will not work with visual studio 2019) 
4)	Check the install worked by opening your command prompt terminal and typing dotnet --version
5)	Go to https://nodejs.org/en/ and download and install LTS (recommended for most user) globally on your computer
6)	Check the install worked by opening your command prompt terminal and typing node –version and then npm --version
7)	In your command prompt terminal globally install angular cli to your computer with the command npm install -g @angular/cli
8)	Check the install by typing ng –version in the command prompt terminal
9)	Open the entire project folder in vs code
10)	Open a terminal for the TravelExperts.API folder
11)	Open a terminal for the TravelExperts-SPA folder
12)	In the TravelExperts-SPA terminal type the npm install command to download all required node modules
13)	After this is complete type the npm update command in your TravelExperts-SPA terminal
14)	Go to the TravelExperts.API terminal and type dotnet run
15)	After you get in the terminal message ending with:
Now listening on: http://localhost:5000
Application started. Press Ctrl+C to shut down.
16)	Go to your browser and input http://localhost:5000/ and the application should now be running locally.

