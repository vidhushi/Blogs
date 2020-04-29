---
template: BlogPost
path: "/create-your-own-blog-using-gatsby "
date: 2020-04-28T21:35:40.103Z
title: "Create your own blog using Gatsby "
thumbnail: /assets/website-rebuilt-in-gatsbyjs.png
metaDescription: A
---
### ***To Create Your Own First Blog you have to follow some easy steps :-***

* Step 1 : -  Go to this think 

  **<https://www.gatsbyjs.org/starters/?v=2>**

  ![ScreenShot -1](/assets/first.png "ScreenShot -1")
* Step 2 :- Now Select any one layout which you like and click on the button Netlify which you easily see at the end of the layout.

  ![]()

  ![Screenshot-2](/assets/second.png "Second")
* Step 3 :- It will redirect you to the Netlify official website. Here you have to click on connect to GitHub Button.

  ![Screenshot-3](/assets/third.png "Three")
* Step 4 :- Here you can also change your repository name if you want and after it click on Save & Deploy button.

  ![Screenshot-4](/assets/fourth.png "Four")
* Step 5 :- After it go to your git hub account and you see that there is one new repository with the same name.

  ![Screenshot-5](/assets/fifthsecond.png "Five")
* Step 6 :- Clone or download that repository in any folder on your local system.
* Step 7 :- Go to package.json file and do some changes.

  ```
  {
    "name": "put the name whatever you want",
    "description": "your choice",
    "author": "Author Name <Authormailid>",
    "repository": {
      "type": "git",
      "url": "url of your git repository"
        },
     }
  ```
* Step 8 :- To run your Application run the following Command.

  8.1).  npm i

  8.2). npm start

  After run application successfully you got something like this in your vs code terminal.

  ![Screenshot-6](/assets/nine.png "Run Successfully")

  Paste the URL http://localhost:8000/ in the browser and you got your blog application.

  ![ScreenShot](/assets/eight.png "First view  of Application")

  * Step 9 :- If you want to perform any changes in it and do these changes freely.

     Like here i want to change the first heading " Sky Lite" by "My first Blog" and change the description line.

    So to change it go to vs code.and open the file gatsby-config.js.

    ![Screenshot-7](/assets/ten.png "Before Changes")

    * Step 10: - After Changes my file look like this..

      ![Screenshot-8](/assets/elevensecond.png "File After changes")

  \    and this is how my application look..

  ![Screenshot-9](/assets/eleventhree.png "Final Look")