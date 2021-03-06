# # NOM NOM CHEESEBURGERS

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The purpose of this repository is to demonstrate a functioning express application that utilizes a MySql database along with a custom ORM and handlebars.

![Main](./readme_assets/main.PNG)

---

## Table of Contents

- [Installation](#installation)
- [Usage](#Usage)
- [Building the Application](#building-the-application)
- [Minimum Requirements](#minimum-requirements)
- [Credits](#credits)
- [Resources](#resources)
- [Links](#Links)
- [License](#license)

---

## Installation

1. Follow the GitHub Repository Link in the [links](#Links) section below.
1. Clone the repository using an SSH key.
1. Open GitBash and use "git clone" to clone the repository.
1. Run npm install to install associated modules.

---

## Usage

Edit using VSCode after [installation](#installation). Config, controllers, db, models, public, and views folders are included along with server file and package.json files. This application is deployed to Heroku, see [links](#Links) section below.

---

## Building the Application

When the user visits this application they will be presented with a home screen where they can add different types of burgers that they would like to eat. When burgers are added they will automatically have a set value of "devoured: false" and populate into the left side section of the webpage with a "Devour it!" button next to them. When the user clicks the "Devour it!" button next to a certain burger, that burger's value will then change to "devoured: true" and the burger will then move to the right side section of the webpage. Items in this section will have grayed out formatting and will no longer have a "Devour it!" button next to them.

---

## Minimum Requirements

Application should allow users to create and save new burgers. :heavy_check_mark:

Application should display non-devoured burgers on the left and devoured burgers on the right. :heavy_check_mark:

Application should allow users to devour an existing burger in the left hand non-devoured section. :heavy_check_mark:

When a burger is devoured, it should move from the left to the right side. :heavy_check_mark:

---

## Credits

As always, a huge thanks to our instructional staff for all their hard work!

## Resources

- [w3schools](https://www.w3schools.com)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)

---

## Links

[Repository Link](https://github.com/aimeecesler/nom-nom-cheeseburgers)

[Deployed Application](https://nom-nom-cheeseburger.herokuapp.com/)

---

## License

Copyright &copy; 2020 Aimee Corbin Esler

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
