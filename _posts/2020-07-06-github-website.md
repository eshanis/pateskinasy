---
published: true
thumbnail: /assets/images/website.PNG
---
## Setting up a static website/blog on Github Pages using Jekyll

This is my first github page, was a lot of fun and a bit stressful to set up, learning new stuff, so I am sharing some notes for others. I found this great template [Jekyll Starter Template](https://github.com/mmistakes/mm-github-pages-starter) to use as a starting point for the base framework called [Jekyll-Now](https://github.com/barryclark/jekyll-now)

**Step 1**: Select a  Jekyll template. The one I picked is minimal mistakes, it works nicely with github, and eshnil2000 made some nice changes to allow images on the post summary page.

[mmistakes](https://github.com/eshnil2000/mm-github-pages-starter)

**Step 2** : The next step is to Fork it. Doing this makes a copy. You can then make the changes you need. The Fork button is to the left of the screen.

![]({{site.baseurl}}/assets/images/fork2_pointer.png)


**Step 3** : Customize and change the repository name to youname.github.io To do this, click on the settings button. 
         
![setting_changename.PNG]({{site.baseurl}}/assets/images/setting_changename.PNG)

To customize your profile go to [config.yml](https://github.com/eshanis/eshanis.github.io/blob/master/_config.yml) and edit your name, website etc. Save the changes made and click commit. 
![]({{site.baseurl}}/assets/images/setting_changename.PNG)

To add photographs the easiest way to is to upload images in the /assets/images folder and then use [markdown](https://guides.github.com/features/mastering-markdown/) to include the picture in your blogpost.
example: 
	![]({{site.baseurl}}/assets/images/fork2_pointer.png)
I like to use the [Prose.io](https://prose.io/) to edit the files and images so I dont have to worry about remembering markdown.
    
   
	

**Step 4** : Scroll down to the Github pages to publish
        
**Step 5** : To edit the pages Use a third party GitHub content editor, like Prose by Development Seed. It is optimized for use, making markdown editing, writing drafts and uploading images really easy.   
          
**Step 6** : GitHub Pages to rebuild your site with mmistakes. Your rebuilt site will be viewable a few seconds later at https://yourgithubusername.github.io - if not, give it ten minutes as GitHub suggests and it'll appear soon
