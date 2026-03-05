# README
# Hosting a Resume using Hugo
This README describes the practical and technical steps of formatting and hosting a resume using Hugo, and publishing it onto GitHub. Hugo is a static site generator that allows you to locally run a website on your computer. This local website can then be uploaded to a forge. A forge is a platform that allows anybody to upload their code, and allows others to create changes to that code. 

## Getting Started 
### Prerequisites
- Must have [Git](https://github.com/git-guides/install-git) and [Hugo](https://www.youtube.com/watch?v=8BrADPJgA-4) installed   
- Some knowledge about markdown
- Ability to do basic operations on the command line (changing directories and running commands)

### Instructions
**Creating the site locally**  

1. Open up Command Line
2. Create a new site using the "*hugo new site yourSiteName*" command
3. Add a theme
4. Create a Markdown file with a resume 
5. Preview using the "*hugo server*" command  

**Pushing the site onto GitHub**  
1. Create a GitHub account if you do not already have one
2. Create a repository 
3. Type these commands in the command line  
git init  
git add .  
git commit -m "inital commit"  
git branch -M main  
git remote add origin  INSERT GITHUB DOMAIN
git push -u origin main

**Deploying**
1. Go to GitHub 
2. Click on Settings > Pages 
3. Change the Source to GitHub Actions
4. Create a file name hugo.yml
5. Copy and paste the [YAML](https://gohugo.io/host-and-deploy/host-on-github-pages/) into hugo.yml
6. Commit the changes
7. Push onto Github





### Further Resources
- A simple to follow [Markdown tutorial](https://commonmark.org/help/tutorial/index.html)
- [Introducing Git and GitHub](https://www.educative.io/blog/git-github-tutorial-beginners?utm_campaign=Pmax_feb25&utm_source=google&utm_medium=ppc&utm_content=&utm_term=&eid=5082902844932096&utm_term=&utm_campaign=%5BMar+25%5D+Pmax.+-+Coding+Interview+Prep&utm_source=adwords&utm_medium=ppc&hsa_acc=5451446008&hsa_cam=22344713166&hsa_grp=&hsa_ad=&hsa_src=x&hsa_tgt=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=22354833079&gbraid=0AAAAADfWLuSU88iFAVyErgbRdt7fiuzSH&gclid=Cj0KCQiA8KTNBhD_ARIsAOvp6DI7uxM-Pxah_8S_N5ntCI08Vc8eAwg50MlejBBUQkLznNdv7X-W9_4aAt_UEALw_wcB)
- [Controlled vs Distributed Version Control Systems](https://www.atlassian.com/blog/software-teams/version-control-centralized-dvcs)
- [Static vs Dynamic Webpages](https://www.educative.io/answers/what-is-the-difference-between-static-and-dynamic-webpages?utm_campaign=Pmax_feb25&utm_source=google&utm_medium=ppc&utm_content=&utm_term=&eid=5082902844932096&utm_term=&utm_campaign=%5BMar+25%5D+Pmax.+-+Coding+Interview+Prep&utm_source=adwords&utm_medium=ppc&hsa_acc=5451446008&hsa_cam=22344713166&hsa_grp=&hsa_ad=&hsa_src=x&hsa_tgt=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=22354833079&gbraid=0AAAAADfWLuSU88iFAVyErgbRdt7fiuzSH&gclid=Cj0KCQiA8KTNBhD_ARIsAOvp6DIyIfEVwkT0sYxuyz06GHeqSR-LKeRblY-hZ_vu9rW4BYwyAkMMogoaAp0gEALw_wcB) 

### FAQ
**Why is Markdown better than writing raw HTML?**  
Markdown is a lightweight markup language, which means that it is human readable in its raw form. It's easier to learn than HTML therefore anybody even with little expirience is able to create a Markdown file.  

**I changed the Markdown version of my resume, so why don't I see the changes when I refresh the website in my browser?**  
Double check to make sure that you are saving those changes, commiting, and pushing onto GitHub. 

### Credits
I would like to give credit to those who have contributed with this project
- **Lara De Leon:** Reviewed the project
- **Palak Patel:** Reviewed the project
- **[Hugo Themes:](https://themes.gohugo.io/)** Allowed me to use a theme
