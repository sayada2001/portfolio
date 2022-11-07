###### heading6-> Welcome to CSI Community
##### heading5-> Welcome to CSI Community
#### heading4-> Welcome to CSI Community
### heading3-> Welcome to CSI Community
## heading2-> Welcome to CSI Community
# heading1-> Welcome to CSI Community 

This is markdown practice and a paragraph.  
To have a new line or line break in the paragraph simple put two space and press enter to go to the new line. 

 
*use a single asterisks to have italic*  

**This whole line is bold with double asterisks both at start and end**  

***Using three asterisks make both bold and italic*** 

### Ordered Lists
1. Task one
2. Task two
3. Task three
    1. nested task
    2. nested task
4. Task four

### Unordered Lists
- First
- second
- third
    - nested
    - nested
- fourth

### Example of making a list of tasks
- [ ] Task one
- [ ] Task two
- [x] Task three is complete

### index.html starts

    <!DOCTYPE html>
        <html>
            <head>
                <meta name="viewport" content="width=device-width, initial-scale=1">
                <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
                <style>
                    body {
                    margin: 0;
                    font-family: Arial, Helvetica, sans-serif;
                    }

                    .topnav {
                    overflow: hidden;
                    background-color: rgb(60, 215, 243);
                    }

                    .topnav p {
                    float: left;
                    display: block;
                    color: black;
                    text-align: center;
                    padding: 14px 16px;
                    text-decoration: none;
                    font-size: 17px;
                    }

                    .topnav a {
                    float: left;
                    display: block;
                    color: black;
                    text-align: center;
                    padding: 14px 16px;
                    text-decoration: none;
                    font-size: 17px;
                    }

                    .topnav a:hover {
                    background-color: black;
                    color: white;
                    }

                    .topnav a.active {
                    background-color: #e9f88a;
                    color: black;
                    }

                    .topnav .icon {
                    display: none;
                    }

                    @media screen and (max-width: 600px) {
                    .topnav a:not(:first-child) {
                        display: none;
                    }

                    .topnav a.icon {
                        float: right;
                        display: block;
                    }
                    }

                    @media screen and (max-width: 600px) {
                    .topnav.responsive {
                        position: relative;
                    }

                    .topnav.responsive .icon {
                        position: absolute;
                        right: 0;
                        top: 0;
                    }

                    .topnav.responsive a {
                        float: none;
                        display: block;
                        text-align: left;
                    }
                    }
                </style>
            </head>

            <body>

                <div class="topnav" id="myTopnav">
                    <a href="/index.html" class="active">Home</a>
                    <a href="#about">About</a>
                    <a href="/experience.html">Experience</a>
                    <a href="#contact">Contact</a>
                    <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                    <i class="fa fa-bars"></i>
                    </a>
                </div>

                <div style="padding-left:16px">
                    <h1 style="text-align: center;"> This is our Home Page</h1>

                </div>
                <div>
                    In this page we will showcase all our project with links and screenshot of project/coursework outcomes
                </div>

                <script>
                    function myFunction() {
                    var x = document.getElementById("myTopnav");
                    if (x.className === "topnav") {
                        x.className += " responsive";
                    } else {
                        x.className = "topnav";
                    }
                    }
                </script>
        </body>

    </html>


### index.html ends


### experience.html starts

    <!DOCTYPE html>
        <html>
            <head>
                <meta name="viewport" content="width=device-width, initial-scale=1">
                <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
                <style>
                    body {
                    margin: 0;
                    font-family: Arial, Helvetica, sans-serif;
                    }

                    .topnav {
                    overflow: hidden;
                    background-color: rgb(60, 215, 243);
                    }

                    .topnav p {
                    float: left;
                    display: block;
                    color: black;
                    text-align: center;
                    padding: 14px 16px;
                    text-decoration: none;
                    font-size: 17px;
                    }

                    .topnav a {
                    float: left;
                    display: block;
                    color: black;
                    text-align: center;
                    padding: 14px 16px;
                    text-decoration: none;
                    font-size: 17px;
                    }

                    .topnav a:hover {
                    background-color: black;
                    color: white;
                    }

                    .topnav a.active {
                    background-color: #e9f88a;
                    color: black;
                    }

                    .topnav .icon {
                    display: none;
                    }

                    @media screen and (max-width: 600px) {
                    .topnav a:not(:first-child) {
                        display: none;
                    }

                    .topnav a.icon {
                        float: right;
                        display: block;
                    }
                    }

                    @media screen and (max-width: 600px) {
                    .topnav.responsive {
                        position: relative;
                    }

                    .topnav.responsive .icon {
                        position: absolute;
                        right: 0;
                        top: 0;
                    }

                    .topnav.responsive a {
                        float: none;
                        display: block;
                        text-align: left;
                    }
                    }
                </style>
            </head>

            <body>

                <div class="topnav" id="myTopnav">
                    <a href="/index.html" class="active">Home</a>
                    <a href="#about">About</a>
                    <a href="/experience.html">Experience</a>
                    <a href="#contact">Contact</a>
                    <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                    <i class="fa fa-bars"></i>
                    </a>
                </div>

                <div style="padding-left:16px">
                    <h1 style="text-align: center;"> This is our Home Page</h1>

                </div>
                <div style="padding-left:16px">
                    <h1> This is our Experience Page</h1>
                    <ul>
                        <h3>List of experiences</h3>
                        <li>Internships</li>
                        <li>Extra-curricular Activities</li>
                    </ul>
                </div>

                <script>
                    function myFunction() {
                    var x = document.getElementById("myTopnav");
                    if (x.className === "topnav") {
                        x.className += " responsive";
                    } else {
                        x.className = "topnav";
                    }
                    }
                </script>
        </body>

    </html>

### experience.html ends

### Code can be added like the followings
```
$ git init
Initialized empty Git repository in /PortfolioWebsite/.git.
```

### View base of our portfolio [Portfolio Website URL](https://hasanm29.github.io/test/)


##### You can add image like the following one which has been taken from GitHub.
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)




