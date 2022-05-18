# Kaachonjoblog
​
## Author [David Kahumbi]
​
## Description
Kaachonjoblog is a personal blog app that allows users to make blogs and also display comments of their posts, the app also displays a quote of the day that is randomly generated everytime a logged in user visits the web application to make a new blog post.
​
## Technologies Used
python 3.8
Flask
Html
CSS
Bootstrap

## User Stories
Users will be able to:
*Signup & Register new accounts
*Login to their accounts
*Create a new blog
*Post a Blog
*View all their blogs and the day they were posted
*​View other Blogs as well
*View the quote of the day
*Comment on the Blogs posted
*Delete Blogs and comments they want  

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Register a new account | **Enter username,email & password** | New users can Sign in |
| Login in | **Enter login details login** | Get redirect to log in page |
| Make a new blog | **Click on new post** | Blog is posted |
| Comment & delete | **click on a posted Blog** | Comment or Delete |
​
​
## Known Bugs
If you find a bug please feel free to alert me. To fix the bug:
​
Fork the repository
Open your terminal
Create a new branch
Make the changes, then (git add) to add changes
Commit the changes you have made(git commit -m"Fix bug")
Push changes made and click pull request so that I can access the changes made.
​
​
## SetUp / Installation Requirements
### Prerequisites
* python3.8
* pip
* virtualenv
​
### Cloning
* In your terminal:
​
        $ git clone https://github.com/kahumbi/blog.git
        $ cd Blog
​
## Running the Application
* Creating the virtual environment
​
        $ python3.8 -m venv --without-pip virtual
        $ source virtual/bin/env
        $ curl https://bootstrap.pypa.io/get-pip.py | python
        $ pip install Flask
​

## License
​
License
MIT Copyright (c) 2022 David Kahumbi
​
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
​
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
​
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
​
=======
​
Personal Blog
