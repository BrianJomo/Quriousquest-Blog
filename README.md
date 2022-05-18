# Quriousquest Blog

##### By Brian Jomo.

### It is a description of the Quriousquest Blog.

## Table of Content

+ [Description](#description)
+ [Installation Requirement](#Installation)
+ [Technology Used](#technology-used)
+ [Reference](#reference)
+ [Licence](#licence)
+ [Authors Info](#author-Info)


## Description
  
<p>This project involves setting up a blog site which contains some personal blogs. Web visitors can read and comment on the blogs as well as get inspired by quotes , that are displayed on the web pages via an API. The API fetches data from a quote database and reflects the data in the blog website. Users can also create secure accounts.</p>


## Installation

To gain acess to this application click on this link: https://github.com/BrianJomo/Quriousquest-Blog

### Requirements

* Either a computer,phone,tablet or an Ipad.

* An access to the Internet.

### Installation Process

To access this application, type the following command in your terminal to have a local copy of the application.
```
git clone https://github.com/BrianJomo/Quriousquest-Blog.git
```
and for SSH, use the following command;
```
git clone git@github.com:BrianJomo/Quriousquest-Blog.git

```

Then run the following commands in the terminal then run the manage.py file in order to run the web application.

```
$ python3.8 -m venv --without-pip virtual

$ source virtual/bin/activate

$ curl https://bootstrap.pypa.io/get-pip.py | python

$ pip3 install -r requirements.txt 

$ python3.8 manage.py db init

$ python3.8 manage.py db migrate -m "Initial Migration"

$ python3.8 manage.py db upgrade

```

Use the following format to configure your local Postresql database: dialect+driver://username:password@host:port/database

To explore the features of this news website navigate to this link on your browser or just click on this link: 

## Technology Used

* Python - Which was used to structure and build the logic hence interactive with the client-side and server-side.

* HTML - which was used to build the structure of the web pages.

* CSS - which was used to style the web pages.

* Bootsrap - which was also used to style the web pages.

* Flask - Which made creating web applications in Python easier.


## Reference

* PEP 8 – Style Guide for Python.
* Materialize CSS.

## Licence

MIT License

Copyright (c) [2022] [Brian Jomo]

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
