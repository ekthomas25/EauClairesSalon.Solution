# Eau Claire's Schedul-O-Tron 5000

#### By Liz Thomas

#### _A stylist and client tracking system for Eau Claire's Hair Salon._

## Technologies Used

* _HTML_
* _CSS_
* _C#_
* _.NET_
* _ASP.NET_
* _Entity_
* _Razor_
* _Node_
* _SQL_
* _MySQL Workbench_


## Description

_This web application was created for Eau Claire's Hair Salon to track the salon's stylists and keep a list of their clients. The web application has forms for the user to create, edit, and delete stylists._

## Setup/Installation Requirements

### Your computer will need to have the following installed and set up:
* _[GIT](https://docs.github.com/en/get-started/quickstart/set-up-git)_
* _[Visual Studio Code](https://code.visualstudio.com/download)_
* _[Node](https://nodejs.dev/learn/how-to-install-nodejs)_
* _.NET - [Mac](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.401-macos-x64-installer) or [Windows](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.401-windows-x64-installer)_
* _[MySQL Workbench](https://dev.mysql.com/downloads/file/?id=484391)_


### File Setup

* _Once you have VSCode, Node, and GIT set up, you will need to open up your terminal, navigate to your Desktop and type the command:_
git clone https://github.com/ekthomas25/EauClairesSalon.Solution.git

* _This will clone the repository to your desktop and you will be able to then open the folder in VSCode._
* _Open the terminal in VSCode and navigate to_ EauClairesSalon.Solution > HairSalon _and type the following command:_ touch appsettings.json
* _Copy and paste the following code into the new file:_
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=liz_thomas;uid=root;pwd=[YOUR PASSWORD HERE];"
  }
}
* _You will need to input your own password where it says_ [YOUR PASSWORD HERE]
* _After you have completed the above, open MySQL Workbench and select Data Import/Restore from the Navigator/Administration Window, then select Import from Self-Contained File in Import Options. You will then select the New button under efault Schema to be imported. Enter the name of your database and click ok. Navigate to the Import Progress tab and click Start Import. You will need to click the refresh button for the database to show.
* _Enter_ dotnet run _into the terminal and navigate to_ http://localhost:5000 _in the browser_


## Known Bugs

* _No known issues_

## License

_If you have any questions or would like to reach out for any reason, please don't hesitate to send an email to [thomas.elizabeth.k@gmail.com](mailto:thomas.elizabeth.k@gmail.com)._

MIT License

Copyright (c) 2021 Elizabeth Thomas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.