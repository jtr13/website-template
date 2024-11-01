# website-template

[Video tutorial](https://youtu.be/YN75YXaLFGM)

This is a template for creating a Quarto web site using RStudio.

To use it effectively you need to know how to push and pull from GitHub to RStudio using the Git panel buttons, which requires a working GitHub personal access token (PAT). If you don't have one setup, following [these instructions](https://happygitwithr.com/https-pat.html#tldr) in *Happy Git and GitHub for the useR* to set one up. (In short you will create a token for HTTPS and store it using **gitcreds**.)

In addition open RStudio and update to the latest version by clicking "Help" "Check for Updates". (This is necessary to ensure that Quarto is installed.)

## ABSOLUTE ESSENTIALS

*If you have any difficulties or have feedback of any kind, please file an issue or communicate through [Discussions](https://github.com/jtr13/website-template/discussions).*

### Copy this template (GitHub)

- [ ] 1. Click the green "Use this template" button above. (You need to login to GitHub to see this option). Choose the "Create a new repository" option. DO NOT FORK THE REPO. Choose a descriptive name for your repo based on your content. (Unlike when you fork a repo, you get to choose the name. If you change your mind before you do any work, delete your new repo and start over.) Leave the "Public" option checked or else GitHub Pages won't work.

### Set up Pages (GitHub)

- [ ] 1. You've now left the template page and are viewing your new repo on GitHub. On the home page, click Settings. Click the "Pages" section on the left. In the **Build and Deployment** section, set **Source** to "Deploy from a branch" (Classic Pages experience) and **Branch** to **main** with **/docs** folder. Click Save. 

- [ ] 2. Click the little gear button near "About" on the top right side of the home page of the repo and check the "Use your Github Pages website" box under "Website". Click "Save changes". Test the link and you should see a web site with a stick figure on it. It may take a few minutes to build so if it's not working do a few more steps and then come back to check.

### Copy the repo link (GitHub)

- [ ] 1. Click the green Code button, choose "HTTPS" and copy the link below. It should have the format: `https://github.com/[USERNAME]/[REPO NAME].git`

### Clone the repo (RStudio)

- [ ] 1. Clone your new repo with *File, New Project..., Version Control, Git* in RStudio. You will need to paste the link from the previous step in the Repository URL box. If it's not automatically populated, enter the repo name in the "Project directory name:" box. Choose the location of the project

### Edit `_quarto.yml` (RStudio)

Tip: From the file pane in RStudio, open `README.md`, which contains these instructions. You can delete steps as you complete them.

- [ ] 1. Edit the all caps info in  `_quarto.yml` to your info. It's very important to maintain the indenting structure in this file precisely as is -- be careful!

### Render the web site (RStudio)

- [ ] 1. If you haven't already, click "Help" "Check for Updates" to make sure you have the latest version of RStudio (and thus have Quarto installed.)

- [ ] 2. Render the web site locally by clicking the "Build" tap on the right and then "Render Website".

- [ ] 3. Use `browseURL("docs/index.html")` to view your site locally (or just open `docs/index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)

### Next steps

- Add content to `index.qmd` as desired.

- Add content to `projects.qmd` as desired.

- Change the photo in the `img` folder to your photo.

- Choose a theme from [https://bootswatch.com/](https://bootswatch.com/) and replace "cerulean" in `_quarto.yml` with your prefered theme.

- Add additional tabs/sections by creating new `.qmd` files and listing them in `_quarto.yml` under `projects.qmd`.

### Additional features

Please consult the official guide to **quarto** web sites: [https://quarto.org/docs/websites/](https://quarto.org/docs/websites/)

### Last but not least

Once you've completed these steps, delete the content of this **README** and add a short description of your project with a link to the book URL. It would be appreciated if you add the following to the end:	

*This repo was initially generated from a Quarto template available here: https://github.com/jtr13/website-template.*

(If you found this helpful, please let us know by starring the repo. ⭐ 😄)

