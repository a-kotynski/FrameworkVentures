Trying to follow a tutorial for insert/save data to SQL Database: https://www.youtube.com/watch?v=qOQazNEkxsU

Part 1 Steps:
- I need older .net framework to add ADO.NET Entity Data Model
- video shows .NET 4.6.1
- I get 4.8 to see if it's the same lol
- I install both
- I try to create new project and choose different framework than the latest one or 5.0
- doesn't work -> restarting PC 
- still doesn't work
- googling
- meanwhile doing an update of VS
- downloading database package in VS Installer
- downloading Azure stuff in VS Installer
- installing all the frameworks from VS Installer
- doesn't work, the only other framework that appeared was .net core 3.X
- solution: it's possible to choose different frameworks by choosing different application template i.e. Windows Forms App (.NET Framework) instead of Windows Forms App
- above works also for console

Part 2 Steps:
- I add ADO.NET Entity Data Model
- I choose EF Designer from database
- I choose New Connection
- I pick Microsoft SQL Server Database File
- I browse for Database file
- I choose northwind.mdf
- the result of 'Test Connection' or 'OK' is an error from the file database connection.png
