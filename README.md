# Online Resume

Online Resume is a step-by-step tutorial that shows you how to host a resume on GitHub Page.
****
## Getting Started
#### Prerequisites
  - A resume formatted in Markdown  
    - If you are unfamiliar with Markdown, please check out the Markdown tutorial under [More Resources](#More-Resources)
  - A Github account  

## Instructions
####  Create a new Github repository
  1. Click **Your repositories** under your Github avatar
  1. Click on the **New** button
  1. Your repository name should be **_your_name_.github.io**
  1. Make your repository public
    - Private can also work if you have a Github PRO plan on your account.
  1. Toggle **add a README file**
  1. Click on **Create repository**

![repo_demo](/img/create_repo.gif)
Now, you have a brand new repository; the next step is to make a website!

####  Set up a Jekyll theme
  GitHub page is set up to work with Jekyll templates. It is possible to make your own Jekyll website, but we will use the built-in Jekyll features from Github Pages for simplicity.  
  1. Once you have your new repository, click on **Settings** for the repository
  1. Scroll down to find **GitHub Pages**
  1. Click on **Choose a theme**
  1. Click on each theme and find your favourite
  1. Click on **Select theme** once you have decided
  1. Scroll down and click **Commit changes**  
    - This will make a new branch called gh-pages

![theme_demo](/img/create_theme.gif)
You now have a template website hosted. It is time to change its content.
####  Set up GitHub pages
  1. Go to your repository, and change current branch to **gh-pages**
    - You can do so by click **main** below **Actions**
  1. Click on **index.md**
  1. Click on ![Edit this file](/img/pen.PNG)
  1. Replace the content with your Markdown formatted resume
  1. Click **Commit changes**

![content_demo](/img/change_content.gif)
####  View your online resume
Your resume is hosted online now! Let's see where it is hosted.
  1. Click on **Settings** for the repository
  1. Scroll down to find **GitHub Pages**
  1. You will discover **Your site is published at _some link_**
  1. Click on the link  
    - Also, remember to save your link for conveniences
  1. Your beautiful Resume is now hosted online

![view_demo](/img/view.gif)
#### More Resources
- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown tutorial](https://www.markdowntutorial.com/)  
- [Markdown editor](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors)

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
