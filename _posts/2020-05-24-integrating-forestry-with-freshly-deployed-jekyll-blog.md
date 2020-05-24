---
title: Integrating Forestry with freshly deployed Jekyll blog
layout: post

---
## Integrating Forestry with freshly deployed Jekyll blog 

----------------------

### The scenario

----------

Recently *Karen* deployed his new jekyll blog without any hassles by following [this guide](https://eniamza.github.io/2020/05/23/deploy-your-jekyll-blog-without-console-and-gem-using-github.html) . But he doesn't want to write in plain markup file and set layout manually for each post and them uploading them to github. He wants a CMS (Content Management System) which can do the leg work for him. So he just needs to write and post to github. <br>

So he was looking for a workaround.. 

--------------------

### The Solution

-------------

Forestry.io is a well-known CMS mostly for Bloggers. Today we are going to use the magic of it so it will bear all the hassles for us. <br>

**Steps** :  

- OF COURSE sign up with forestry from [HERE](https://app.forestry.io/signup) 
- After that Click `Add site` on upper right. A green button.
- Here you will be given a list of static site generators. BUT we want `jekyll` so Tap on that. scroll down  and tap `next`
- Our git provider is **GitHub** . So go on select that and tap `Next` .
- **If** you have followed previous [Guide](https://eniamza.github.io/2020/05/23/deploy-your-jekyll-blog-without-console-and-gem-using-github.html) , forestry will automatically detect your jekyll installation directory . If it does not detect config file your installation may be broken. Tap NEXT

And we have successfully integrated forestry with our jekyll blog. <br>

----------------

### Remember 

----------------

Remember to set front matters. Which is basically a title and page layout for your each post. Forestry has a nice looking doc which can be found [Here](https://forestry.io/docs/settings/front-matter-templates/) . <br>

You can also deploy your **Admin Panel** on your site so you can access it by `site.com/admin` . For that <br>

Go to settings > General > scroll down to project paths > In admin path field write `/admin/` and tap on **Deploy Admin** 

-----------------------------------------

## Happy Blogging

