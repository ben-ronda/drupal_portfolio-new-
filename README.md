# My Portfolio [![TeamCity CodeBetter](https://img.shields.io/teamcity/codebetter/bt428.svg?maxAge=2592000)]()
### Created By: Ben Ronda

***

## Description
This is my personal portfolio built with Drupal 7. It is used for storing some of my favorite projects as well as any interesting or new things I have to say, regarding anything from web development, to life, to just thoughts.

***
## Technologies Used
* Drupal 7  
* PHP  
* MAMP  

***
## Custom Modules
* Shift Cipher/Encryption (Caeser Cipher)  
    * A user inserts a shift value, a direction they want to to shift, and a phrase they want to shift.  
    * Example 1: Shift Value: 1, Direction: right, Phrase: "a" => "a" -> "b"
    * Example 2: Shift Value: 3, Direction: left, Phrase: "z" => "w" <- "z"
    * Example 3: Shift Value: 10, Direction: right, Phrase: "The dog jumped over the fence" => "a" -> "b"

***
## Installation and Setup

1. Open your terminal and run `git clone https://github.com/ben-ronda/drupal_portfolio.git`  
2. Download and Install MAMP here: https://www.mamp.info/en/  
3. Launch MAMP and navigate to Preferences>Web Server then Click the little folder icon and choose the folder you cloned from GitHub earlier.  
4. Go to localhost:8888/phpMyAdmin in your Browser  
5. Go to the Import tab and import the database file stored in the sites>db_backup within the project directory  
6. After the Database is imported go to the privileges tab and create a user with the following criteria:
    * Username: bdronda  
    * Password:    
7. Set the Host field to localhost  
8. Hit Go!  
9. Now when you visit localhost:8888 everything should show up!  

***
## Additional Information
* Site Maintenance Info:
    * Username: admin_ronda
    * Password:

***
## License
[![DUB](https://img.shields.io/dub/l/vibe-d.svg?maxAge=2592000)]()  
Copyright (c) Ben Ronda

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
