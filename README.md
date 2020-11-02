# Online Resume

Online Resume is a step-by-step tutorial that shows you how to host a resume on GitHub Page and demonstrate [Andrew Etter's modern technical writing principles](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
****
## Summary
  - [Getting Started](#Getting-Started)
  - [Instructions](#Instructions)  
    1. [Create a new Github repository](#Create-a-new-Github-repository)
    1. [Set up a Jekyll theme](#Set-up-a-Jekyll-theme)
    1. [Set up GitHub pages](#Set-up-GitHub-pages)
    1. [View your online resume](#View-your-online-resume)
  - [Authors and Acknowledgements](#Authors-and-Acknowledgements)
  - [FAQ](#FAQ)

## Getting Started
#### Prerequisites
  - A resume formatted in Markdown  
    - If you are unfamiliar with Markdown, please check out the Markdown tutorial under [More Resources](#More-Resources)
  - A Github account  

## Instructions
####  Create a new Github repository
>1. Click **"Your repositories"** under your Github avatar
1. Click on the **"New"** button
1. Your repository name should be **"_your_name_.github.io"**
1. Make your repository public
   - Private can also work if you have a Github PRO plan on your account.
1. Toggle **"add a README file"**
1. Click on **"Create repository"**
>
>![repo_demo](/img/create_repo.gif "Create a new Github repository")
>Now, you have a brand new repository; the next step is to make a website!
>
>>Most technical people (e.g. software developers) use the virtues of distributed version control systems (DVCS) like GitHub. The reason why developers use DVCS is that the system comes with features that are convenient for them. So the reason becomes clear why technical writers would also use the system.
>>
>>When creating a repository, always remember to place a **README.md** file in the root branch (main in this case). The file's primary purpose is to show people what the project is about and how to run the project. The file should also give instructions on how to contribute to the project.

####  Set up a Jekyll theme
  GitHub page is set up to work with Jekyll templates. It is possible to make your own Jekyll website, but we will use the built-in Jekyll features from Github Pages for simplicity.  

>1. Once you have your new repository, click on **"Settings"** for the repository
1. Scroll down to find **"GitHub Pages"**
1. Click on **"Choose a theme"**
1. Click on each theme and find your favourite
1. Click on **"Select theme"** once you have decided
1. Scroll down and click **"Commit changes"**  
   - This will make a new branch called gh-pages
>
>![theme_demo](/img/create_theme.gif "Set up a Jekyll theme")
>You now have a template website hosted. It is time to change its content.
>
>>We do not need a fancy dynamic website for our documentations. Our documentation does not require a database or some server-side applications to support it. So make a static website make sense. A static website is straightforward, you can host them everywhere (GitHub page in this case), and change content is easy to do. To make things even simpler for us, we can use a static site generator to make the website. There are lots of static website generators out there. For more information, please check under [More Resources](#More-Resources).
>>
>>In the steps above, I have used a default theme. If you want to make your product/project successful, you may consider customizing your website. Customization is the chance to distinguish your project from all other similar projects out there. If you are not good at designing a theme (like me) for the website,  you may want to hire a designer or even talk to a designer about colour, spacing, ect..
####  Set up GitHub pages
>1. Go to your repository, and change current branch to **"gh-pages"**
   - You can do so by click **"main"** below **"Actions"**
1. Click on **"index.md"**
1. Click on ![Edit this file](/img/pen.PNG)
1. Replace the content with your Markdown formatted resume
1. Click **"Commit changes"**
>
>![content_demo](/img/change_content.gif "Change content to resume")
> Your resume is hosted online now! Let's see where it is hosted.
>
>>Here the convenience of a static website kicks in. We can easily modify the website through a couple of operations. Since the website is static, there's no worry that someone wants to hack it. It is also possible to test the website on your local machine. In our case, we need to install Jekyll, and then we can preview the page locally.
>>
>>Markdown, on the other hand, works directly with HTML, just put a raw markdown file there, and it works like a charm. It is so simple to compare to write an XML or HTML by hand. As a technical writer, it is crucial to put the most effort into the writing part.

####  View your online resume
>1. Click on **"Settings"** for the repository
1. Scroll down to find **"GitHub Pages"**
1. You will discover **"Your site is published at _some link_ "**
1. Click on the link  
  - Also, remember to save your link for conveniences
1. Your beautiful Resume is now hosted online
>
>![view_demo](/img/view.gif "View your online resume")
>
>>Finally, the website a simple result of Andrew Etter's modern technical writing principles. Of course, there are many detailed principles in the book compare to the summary explained here, so it is highly recommended to read his book.

#### More Resources
- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown tutorial](https://www.markdowntutorial.com/)  
- [Markdown editor](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors)
- [Static website generator](https://snipcart.com/blog/choose-best-static-site-generator)
## Authors and Acknowledgements
-  Andrew Etter
-  Aaron Salo
-  Kyle Lamoureux
-  Sheikh Shafayet Hossain
-  Kevin Davis
-  [Awesome-readme](https://github.com/matiassingers/awesome-readme)
-  [a-good-readme-template](https://github.com/PurpleBooth/a-good-readme-template)
-  [Slate-theme](https://github.com/pages-themes/slate)

## FAQ
- _Why is my resume not showing up_
  - Sometimes, GitHub takes some time to refresh the content due to internet traffics. Please Wait for ten minutes and check again. If your resume still does not show after 10 minutes and you followed the instruction, GitHub's server-side might be the problem.
- _Why is Markdown better than a word processor?_  
  -  Word processors are great tools for creating resumes, but not for publishing resumes online. In short, most word processors' files are incompatible with website format (such as HTML, CSS), and some are platform-dependent and costs money(Microsoft word \*cough\*). On the other hand, Markdown can turn into a website directly, and it is *FREE*.
