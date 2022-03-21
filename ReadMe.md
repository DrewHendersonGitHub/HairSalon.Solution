# _Hair Salon_

### _By Drew Henderson_

#### _This application lets you add stylists and clients to a salon website._

## Technologies Used

* _C#_
* _cshtml_
* _MySQL_
* _Entity Framework_
* _css_
* _Bootstrap_

## Description

_This project uses a one-to-many database to add clients to a specific stylist. The user can add new stylists and clients, as well as edit and delete them and link them to a different client or stylist.

## Setup/Installation Requirements

* _Download or clone ```https://github.com/DrewHendersonGitHub/HairSalon.Solution``` to your computer._
* _In a terminal inside directory `HairSalon`, make a new file `appsettings.json`._
* _Add the follwing code with ```{DATABASE}```, ```{USERNAME}```, and ```{PASSWORD}``` replaced with your choice._
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database={DATABASE HERE};uid={USERNAME};pwd={PASSWORD};"
  }
}
```
* _Install and open MySQL Workbench_
* _In the ```Navigation``` panel, select the ```Administration``` tab, then click `Data Import/Restore` under the management section._
* _Select ```Import from self-contained file``` and locate ```drew_henderson.sql``` from ```HairSalon```._
* _In ```Default Schema to be Imported to``` click new and name the schema the same as you chose in ```appsettings.json```._
* _Click ```Start Import``` from the bottom right, and refresh to check that the schema is there._
* _Run ```dotnet restore``` and ```dotnet run``` in your terminal to build the project and open a local server._
* _CTRL click on the first listed URL, likely to be```http://localhost:5000/```._

## Known Bugs

* I couldn't get CSS styling to load outside of Bootstrap.

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2022 Drew Henderson