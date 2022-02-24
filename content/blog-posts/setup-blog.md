+++
author = "Dariya Mukhatova"
date = ""
hero = ""
title = "Blog Setup"
type = "blog"

+++
To keep track and post all work done I have created a blog. This blog was done with the use of [Forestry.io](https://forestry.io), [Github](https://github.com), [Netlify](https://www.netlify.com), and [Gridsome](https://gridsome.org).

**Step 1.**

Forestry.io is a nice solution to manage your own website with convenient functions and user-friendly service. It works with Git. It will work with your commits and depending on them it will update the CMS. So to log in I used my GitHub account but there are options like GitLab and Bitbucket.

![](/images/2022-02-24-13-54-57.png)

**Step 2.**

After registering/logging you will have a home page where you can manage your projects globally. Here as well you can create a new site with Add Site option.

![](/images/2022-02-24-13-55-14.png)

**Step 3.**

It will lead to the extra window where you can select different variations for your site generator. I did not have a site yet so I used the option below.

![](/images/2022-02-24-13-55-21.png)

**Step 4.**

If you do not have a website yet and had pressed the option below the previous window, Forestry will propose you a design for your future website. You can filter them by their site generation technique and by the type of website you want to use. For me, I have chosen a blog website so I will look for it.

![](/images/2022-02-24-13-56-12.png)

**Step 5.**

Lately, you can try different propositions and preview them. I prefer this theme:

![](/images/2022-02-24-18-23-10.png)![](/images/2022-02-24-18-23-40.png)Some of the templates have options for site generators. I will choose Hugo in my case.

**Step 6.**

Then there are configuration settings where you will have to attach a new website as your git project. After adding it to Forestry we can use Forestry editor. First you have to chose your git provider and then you can name your repository. 

![](/images/2022-02-24-18-25-11.png)![](/images/2022-02-24-18-25-28.png)

**Step 7.**

So this is it. This is the main page where you will work with your future website and its content. In the sidebar(which you can configure) there are all needed functions for you.

![](/images/2022-02-24-18-26-51.png)

It requires some settings before work tho. But you can always change them in the main settings. 

![](/images/2022-02-24-14-00-01.png)

All the content that appears for the first time is the content of the example site when you were choosing your template.

This is what it looks like. As you can see you can change the Title, main picture, content. You can add a link, picture, tables, list, and other types of content.

![](/images/2022-02-24-18-28-04.png)

The best thing about Forestry is the fact that it allows working with both Raw editor and [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG) editors. It is very convenient to see what you will have in the end as a product(blog post).

![](/images/2022-02-24-15-12-55.png)

![](/images/2022-02-24-15-13-05.png)

### Deployment

To build a site I used Netlify. According to Google, Netlify is:

> **Netlify** is a San Francisco-based cloud computing company that offers hosting and serverless backend services for web applications and static websites.

![](/images/2022-02-24-15-16-43.png)

Like with Forestry you can sign in using your Git account and directly start building your website.  
![](/images/2022-02-24-15-17-04.png)

![](/images/2022-02-24-14-00-42.png)

Since we have already created our website we will have to connect it to the Netlify platform.

Here you have to configure your git profile to access your git project(website) and you are ready to deploy.  All required steps are shown below.

//

//

After you have added your project to deploy you will see it on a platform like this: 

//

It will take some seconds to launch your project in deployment. After you can access it by pressing on it.

//

We can observe the deployment in Netlify by following the deployment details.

//

TA-DAA!

Now you can see your website and all the editing you have done. For now, there is not a lot of my own content. You can buy a domain or set up already one that you have and change the name of your site. As well you can Secure your site with HTTPS.

So here is the template that appear where I build my website:

//