---
template: BlogPost
path: /create-your-own-blog-using-gatsby
date: 2020-05-01T04:22:44.712Z
title: Create your own blog using Gatsby
thumbnail: /assets/website-rebuilt-in-gatsbyjs.png
metaDescription: Hope you enjoy the article :)!
---
By using Gatsby you can easily create your own blog site in very less time. So here in this blog we learn how we create it.

**To Create Your Own First Blog you have to follow some easy steps :-** 

**Step 1** : - First you have to go on this link.** <https://www.gatsbyjs.org/starters/?v=2>** the official website of Gatsby.

![Screenshot-1](/assets/first.png "Screenshot-1")

**Step 2** :- Now Select any one layout which you like for your among the all and click on the button **Netlify** which you can easily see at the end of the layout.

![Screenshot-2](/assets/second.png "Screenshot-2")

**Step 3** :- It will redirect you to the Netlify official website. Here you have to click on connect to GitHub button.

![Screenshot-3](/assets/third.png "Screenshot-3")

**Step 4** :- Here you can also change your repository name if you want and after it click on Save & Deploy button.

![Screenshot-4](/assets/fourth.png "Screenshot-4")

  After some time it will deploy your site and you can see something like this in your account.

![Screenshot-5](/assets/sixth.png "Screenshot-5")



**Step 5** :- After it go to your GitHub account and you see that there is one new repository with the same name.

![Screenshot-6](/assets/fifthsecond.png "Screenshot-6")

**Step 6** :- Clone or download that repository in any folder on your local system.

**Step 7** :- Now go to package.json file and do some changes.

```
{   
"name": "put the name whatever you want",   
 "description": "your choice",
 "author": "Author Name <Authormailid>",  
      
 "repository": {     "type": "git",
 "url": "url of your git repository"
    },
    
   }
```

**Step 8** :- Now to check the application run it by using commands which are given below

8.1). npm i

8.2). npm start

After the application run successfully you see something like this in your vs code terminal.

![Screenshot-7](/assets/nine.png "Screenshot-7")

To see your blog site paste the http://localhost:8000/

**Step 9** :- If you want to perform any changes in it then do these changes freely.

Like here i want to change the first heading " Sky Lite" by "My first Blog" and change the description line.

![Screenshot-8](/assets/ten.png "Screenshot-8")

So to change it go to vs code.and open the file gatsby-config.js. If you want to perform changes in another file so to that and perform changes.

**Step 10**: - After Changes my file look like this. 

\    

![Screenshot-9](/assets/elevensecond.png "Screenshot-9")

  This is how my application look..

![Screenshot-10](/assets/eleventhree.png "Screenshot-10")