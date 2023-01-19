### 🦖CretaceousClients🦖
## By Alex Johnson and Aitana Shough

An MVC client for showing results from a [Cretaceous Animal API](https://github.com/alexiusvdt/cretaceous-api).
Store your 🦣, 🦖, 🦈, and more!

## Technologies Used

   * C#
   * ASP.Net 6
   * EFCore
   * MySQL
   * LINQ
   * Newtonsoft
   * RESTsharp
   * bootstrap

## Project Details

  * Keep track of your favorite dinosaurs from the (objectively) coolest period on earth. This MVC application is designed to pair with the partner API for storing results in a database. 

## Setup/Installation Requirements
 
# Set up the API
* Clone the repository [Cretaceous Animal API](https://github.com/alexiusvdt/cretaceous-api), following the installation guide in the README of that project.
* Run the API 
  
* Clone this repo 
* Navigate to the `CretaceousClient` directory, opening a command line interface
* Enter the following commands:
 ```
 dotnet add package Microsoft.EntityFrameworkCore.Design -v 6.0.0
 dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore -v 6.0.0
 ```
 * In the `CretaceousClient` directory create a file called appsettings.json and enter the following code:
 ```
{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*"
}
 ```
 * run the program with `dotnet run`

## Known Bugs


## Thanks


## License

MIT License

Copyright (c) 2023 Alex Johnson & Aitana Shough

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.