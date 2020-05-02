<!-- @format -->

<p align="center">
  <a href="" rel="noopener">

<img width=500px height=500px src="https://i.imgur.com/oREkHSw.jpg" alt="Project logo">

</a>

</p>

<h3 align="center">NodeJS URL Shortener</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/RileySeaburg/url-shortener.svg)](https://github.com/RileySeaburg/url-shortener/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/RileySeaburg/url-shortener.svg)](https://github.com/RileySeaburg/url-shortener/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

Write about 1-2 paragraphs describing the purpose of your project.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

Here's what you need to get started

Runtime

```
Nodejs V8+
```

Database

```
MongoDB Atlas
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Create a database on [MongoDB Atlas](mongodb.com)

```
Create a connection string
```

Clone the repository

```
git clone https://github.com/RileySeaburg/url-shortener.git
```

Navigate to cloned project

```
cd url-shortener
```

Replace baseUrl with your localhost url & mongoUri with your mongoDB connection string.

```
vi config/default.json
```

Save file

```
:wq
```

Run Server

```
npm start
```

## 🔧 Running the tests <a name = "tests"></a>

This is just the backend so the best bet is to test with postman.

### Break down into end to end tests

Test the urlshortener

```
POST http://baseUrl/api/url/shorten
Content-Type: application/json

{
    "longUrl": "insert link here."
}
```

### Test New Url

After you create the url it should be available to test.

```
Navigate to "shortUrl"
```

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@rileyseaburg](https://github.com/rileyseaburg) - Project Author

See also the list of [contributors](https://github.com/RileySeaburg/url-shortener/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
