# **Hair Salon**

### By _Max Betich_

## Technologies Used

* _C#/.NET v6_
* _HTML_
* _CSS_
* _MySQL 8.0_

## Description
This application uses a database to track a list of stylists employed by Claire's Salon, as well as the clients that are retained by each stylist. It has functionality to allow for adding, removing, and editing the lists of both clients and stylists.

## Setup/Installation Requirements
* Clone project from this [GitHub repository](https://github.com/MaxBetich/hairsalon.git) to your desktop.
* Import the `max_betich.sql` file included in the top level of this repo to a new database with the name `max_betich` in MySQL Workbench.
* Navigate to the HairSalon directory inside this repo in your terminal and create a new file called `appsettings.json`.
* Within `appsettings.json`, put in the following code, replacing the `[UID HERE]` and `[PWD HERE]` values with your own username and password for MySQL.

```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=max_betich;uid=[UID HERE];pwd=[PWD HERE];"
  }
}
```
* Run the command `dotnet restore` in your terminal to initialize the program.
* Within the HairSalon directory run `dotnet watch run` in the command line to start the program in your default browser.

## Known Bugs

None

## License

MIT

Copyright (c) _2023_ _Max Betich_