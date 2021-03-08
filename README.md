# E-Commerce Back End ![MIT License](https://img.shields.io/badge/mit-brightgreen) ![Javascript](https://img.shields.io/github/languages/top/nielsenjared/badmath)

## Description 🤓

Backend microservice for E-Commerce web site

## Table of Contents 🗒️

- 🔧 [Installation](#installation)
- 🗒️ [Usage](#usage)
- ❤️ [Contributing](#contributing)
- ⚖️ [License](#license)
- 🧐 [Tests](#tests)
- 📩 [Questions](#questions)

## Installation

1. Clone and install dependencies:

```typescript
$ git clone git@github.com:yulduzetta/e-commerce.git
$ cd e-commerce
$ npm install
```

2. Add `.env`file and add the following by updating placeholder values:

```
DB_NAME='ecommerce_db'
DB_USER='YOUR_USERNAME'
DB_PW='YOUR_PASSWORD'
```

3. Add database:

```
  $ mysql -u  root -p
  $ source db/schema.sql;
  $ show databases; ---> should now show your ecommerce_db
  $ exit;
```

4. Seed database:

```
  $ npm run seed
```

## Usage

1. To run in prod mode:

```typescript
$ npm start
```

2. To run in developement mode:

```typescript
$ npm run watch
```

## License

<a href="http://choosealicense.com/licenses/mit/" target="_blank">MIT License</a> ![MIT License](https://img.shields.io/badge/mit-brightgreen)

  <details close>
  <summary>Expand to get full license details</summary>
  <p>MIT License

Copyright (c) [2021] [Yulduz Ibrahim (yulduzetta)]

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

</p>
  </details> 
    
  
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Open new issue with https://github.com/yulduzetta/e-commerce/issues

## Tests

```typescript
$ npm test
```

## Questions

For any questions on this project, or if you want to learn more about me, don't hesitate to:

- View and give your feedback to my GitHub projects: https://github.com/yulduzetta
- Visit my portofolio page: https://github.com/yulduzetta/portfolio
- Send an email to: yulduz83@gmail.com
