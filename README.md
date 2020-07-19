# Google Books

![GitHub followers](https://img.shields.io/github/followers/mjsouthcott?label=Follow&style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/mjsouthcott/21-google-books-react-search)
![GitHub top language](https://img.shields.io/github/languages/top/mjsouthcott/21-google-books-react-search)
![GitHub last commit](https://img.shields.io/github/last-commit/mjsouthcott/21-google-books-react-search)

## Table of Contents

* [Description](#description)
* [Technologies Used](#technologies-used)
* [User Story](#user-story)
* [Installation](#installation)
* [Usage](#usage)
* [Credit](#credit)
* [License](#licence)
* [Contributing](#contributing)

## Description

This application allows users to search for, save and display books using the Google Books API. It's built with the MERN stack and features two pages: _Search_ and _Saved_.

## Technologies Used

* HTML5
* CSS3
* Bootstrap
* Javascript
* MongoDB
* Express.js
* React.js
* Node.js
* Various npm packages

## User Story

```
AS A an avid reader
I WANT to be able to search for, save and display books
SO THAT I can maintain a reading list.
```

## Installation

To install the application, click "Clone or download", copy the URL, launch Git Bash, navigate to your desired directory and use
```
git clone
```
followed by the copied URL. Launch Git Bash and navigate to the application's root directory. Once there, use
```
npm i
```
to install the dependencies, followed by
```
npm start
```
to run the application. If it doesn't do it automatically, open a browser window and go to
```
https://localhost:3000
```

Click on the following URL to launch the deployed application in your browser: https://google-books-react-search-app.herokuapp.com/.

## Usage

To search for a book, click the _Search_ link in the top navbar, enter the title into the _Book_ field in the _Book Search_ card and click the _Search_ button.

![Step 1](https://github.com/mjsouthcott/21-google-books-react-search/blob/master/demo/demo1.PNG)

Following completion of the Google Books API call, the results will be display in the _Results_ card. Results include the book title, author and description. Click the _Save_ button to save the book in your library.

![Step 2](https://github.com/mjsouthcott/21-google-books-react-search/blob/master/demo/demo2.PNG)

Click the _View_ button to open a new browser tab containing the book's page in the Google Play Store.

![Step 3](https://github.com/mjsouthcott/21-google-books-react-search/blob/master/demo/demo3.PNG)

To view your library, click the _Saved_ link in the top navbar. Your library contains the results for all of the books you've saved.

![Step 4](https://github.com/mjsouthcott/21-google-books-react-search/blob/master/demo/demo4.PNG)

## Credits

Matthew Southcott, Full Stack Developer, Broad Peak Web Development

## License

MIT License

Copyright (c) 2020 Matthew James Southcott

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

## Contributing

Feel free to email me if you'd like to contribute.
