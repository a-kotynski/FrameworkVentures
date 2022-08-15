Trying to follow a tutorial for insert/save data to SQL Database: https://www.youtube.com/watch?v=qOQazNEkxsU

Part 1 Steps:
-1.1 I need older .net framework to add ADO.NET Entity Data Model
1.2 video shows .NET 4.6.1
1.3 I get 4.8 to see if it's the same lol
1.4 I install both
1.5 I try to create new project and choose different framework than the latest one or 5.0
1.6 doesn't work -> restarting PC 
1.7 still doesn't work
1.8 googling
1.9 meanwhile doing an update of VS
1.10 downloading database package in VS Installer
1.11 downloading Azure stuff in VS Installer
1.12 installing all the frameworks from VS Installer
1.13 doesn't work, the only other framework that appeared was .net core 3.X
1.14 solution: it's possible to choose different frameworks by choosing different application template i.e. Windows Forms App (.NET Framework) instead of Windows Forms App
- above works also for console

Part 2 Steps:
2.1 I add ADO.NET Entity Data Model
2.2 I choose EF Designer from database
2.3 I choose New Connection
2.4 I pick Microsoft SQL Server Database File
2.5 I browse for Database file
2.6 I choose northwind.mdf
2.7 the result of 'Test Connection' or 'OK' is an error from the file database connection.png
