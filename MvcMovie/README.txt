﻿2024-01-17
1710
# Project Name: MvcMovie

## Part 1: Adding a Controller to ASP.NET Core MVC App
Created a new ASP.NET Core Web App (.Net 8).....Created a web project....added a controller

## Part 2: Adding a Controller to ASP.NET Core MVC App....
In the Solution Explorer, right-click on the "Controllers" folder.
Choose "Add" -> "Controller..." from the context menu.
In the "Add Controller" dialog, choose "MVC Controller - Empty" and click "Add."
In the Add New Item - MvcMovie dialog, enter HelloWorldController.cs and select Add.
Keep the name of controller as HelloWorldController and click "Add."
Visual Studio will generate a new controller file HelloWorldController
Open the newly created controller file (HomeController.cs) in Visual Studio.

## Part 3: Adding a view to an ASP.NET Core MVC app
Right-click on the Views/HelloWorld folder, and then Add > New Item.
In the Solution Explorer, right-click on the "Views" folder ->New folder and name Helloworld 
Choose "Add" -> "View..." 
Right-click on the Views/HelloWorld folder, and then Add > New Item->Show all Templates 
Select Razor View - Empty
give the Name as Index.cshtml.
Select Add

2024-01-20
1310
## Part 4: README file for
In Solution Explorer, right-click the Controllers folder and select Add > New Scaffolded Item.
In the left pane, select Installed -> Common -> MVC->MVC Controller with views, using Entity Framework->add
In the Model class drop down, select Movie (MvcMovie.Models).
In the Data context class row, select the + (plus) sign.
In the Add Data Context dialog, the class name MvcMovie.Data.MvcMovieContext is generated.
Select Add.
In the Database provider drop down, select SQL Server.
Views and Controller name: Keep the default.
Select Add.

## Part 5, work with a database in an ASP.NET Core MVC app
From the View menu->SQL Server Object Explorer (SSOX).-> Movie table (dbo.Movie) > View Designer
Next,View Data
Create a new class named SeedData in the Models folder and add the neccessary code

2024-01-22
1445
## Part 6, controller methods and views in ASP.NET Core
Create controller classes in the Controllers folder for each entity or feature.
Define actions within these controllers to handle HTTP requests.

1>------ Build started: Project: MvcMovie, Configuration: Debug Any CPU ------
1>Skipping analyzers to speed up the build. You can execute 'Build' or 'Rebuild' command to run analyzers.
1>MvcMovie -> C:\Users\eluri\source\repos\MVcMovie\MvcMovie\bin\Debug\net8.0\MvcMovie.dll
========== Build: 1 succeeded, 0 failed, 0 up-to-date, 0 skipped ==========
========== Build completed at 1:22 PM and took 51.234 seconds ==========
Got the 
2024-01-30
1409
## Part 7,add search to an ASP.NET Core MVC app
Added search capability to the Index action .....Updated the Index method
Added the <form> to Views/Movies/Index.cshtml file
submited a search, the URL contains the search query string...
Added the MovieGenreViewModel class to the Models folder...list of movies dislayed.

## Part 8,add a new field to an ASP.NET Core MVC app
Added a new field to the model...Migrate the new field to the database.
Added a Rating property to Models/Movie.cs...Build the app
Edited the /Views/Movies/Index.cshtml file and added a Rating field.
Added Migration Rating and Updated Database

2024-02-01
0636
## Part 9, add validation to an ASP.NET Core MVC app
Updateed the Movie class...Selected the Create New link to add a new movie.
...Fill out the form with some invalid values. 
As soon as jQuery client side validation detects the error, it displays an error message.
2024-02-06
1507
## Part 10, examine the Details and Delete methods of an ASP.NET Core app
Examined the Details method in Movie controller