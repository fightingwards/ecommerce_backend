# Ecommerce-BackEnd

Build back end with express.js, sequelize, mysql

## Description

Build a back end for an e-commerce site by modifying starter code. Configure a working Express.js API to use Sequelize to interact with a MYSQL database. Create models and back end routes. Utilize insomnia to test routes.

## Table of Contents

- [Usage](#usage)
- [Installation](#installation)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Contribute](#how-to-contribute)

## Usage

Live on [Screencastify](https://drive.google.com/file/d/16SjA2WrMOe_TKYr4-SJ1azgpFcwH61Rb/view?usp=sharing)

![Ecommerce-BackEnd](./assets/ecommerce_backend_screenshot.png)

## Installation

To run via local environment:

- Note: To test end points install Insomnia:
  <https://insomnia.rest/>

1.  Clone the repository

2.  Open terminal, and navigate to the appropriate directory

3.  From command line:

    - `npm init -y`
    - `npm install`

    Install the following dependencies:

    - mysql2 `npm install --save mysql2`
    - sequelize `npm install --save sequelize`
    - dotenv `npm i dotenv-save`

    Continue in command line:

    - `mysql -u root -p`
    - User will be prompted for password

    Once mysql is running

    - `source db/schema.sql;`
    - `quit;`

4.  Seed data: `npm run seed`
5.  Start: `npm run start`

## Credits

UT Web Development Bootcamp

## License

MIT License

Copyright (c) [2022] [fightingwards]

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

## Badges

[![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://bitbucket.org/lbesson/ansi-colors)
[![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
