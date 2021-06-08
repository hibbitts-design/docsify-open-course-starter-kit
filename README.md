# Docsify Open Course Starter Kit

[![Docsify](https://img.shields.io/npm/v/docsify?label=docsify)](https://docsify.js.org/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/hibbitts-design/docsify-open-course-starter-kit/blob/main/LICENSE)
<a href="https://discord.gg/zT8eS8ZG">
    <img src="https://img.shields.io/badge/chat-on%20discord-7289DA.svg" alt="Docsify Discord Chat" />
</a>

> This is a starter kit to quickly create a Markdown-based open course site with the site generator [Docsify](https://docsify.js.org). Global navigation elements can be hidden for seamlessly embedding pages (i.e., into an LMS). Includes an optional "Edit this Page" link.

📸 Docsify Open Course Screenshots
---
![ Docsify Open Course Starter Kit](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/smartmockups_kokhsfk1.png)
_Figure 1. Docsify Open Course Starter Kit. Explore a demo at [hibbitts-design.github.io/demo-docsify-open-course-starter-kit/](https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/)_

🚀 GitHub Pages Quickstart
---
**Pre-flight Checklist**  

1. GitHub account

**Installation and Deployment**

1. Tap **Use this template** on the source repository (upper-right green button)
![ Docsify Open Course Starter Kit - Install Page 1](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-1.png)

2. Choose the name for your new repository to contain the copied site files and then tap **Create repository from template**
![ Docsify Open Course Starter Kit - Install Page 2](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-2.png)

3. Go to **Settings** of your newly created repository, tap the **Pages** tab (on the left-hand side), choose **main branch**, then **docs folder** and finally tap the **Save** button (see more details in the [Docsify documentation](https://docsify.js.org/#/deploy?id=github-pages))
![ Docsify Open Course Starter Kit - Install Page 3](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-3.png)

4. And you're done! (view your new site using the provided URL on the **Pages** tab - it can take up to 10 minutes for your site to be initially available)
![ Docsify Open Course Starter Kit - Install Page 4](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-install-4.png)

Do you use GitLab? You can also use Docsify with [GitLab Pages](https://docsify.js.org/#/deploy?id=gitlab-pages)!

✏️ Editing Your Docsify Site Pages on GitHub
---  

1. Go to the Docsify Markdown (.md) page in the `docs` folder of your repository you want to edit
![ Editing Your Docsify Site Pages 1](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-page-edit-1.png)

2. Tap the **Pencil Icon** (top left-hand toolbar area) to start the editor
![ Editing Your Docsify Site Pages 2](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-page-edit-2.png)

3. Scroll down to the bottom of the page and tap the **Commit changes** button to save your changes
![ Editing Your Docsify Site Pages 3](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-page-edit-3.png)

[Learn more about creating pages in Docsify.](https://docsify.js.org/#/more-pages)

🔗 Activating the “Edit this Page” Link on Your Docsify Site
---   

1. At the top-level of your GitHub Repository copy the URL
![ Docsify Open Course Starter Kit - “Edit this Page” Link 1](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-1.png)

2. Tap on the **docs** folder
![ Docsify Open Course Starter Kit - “Edit this Page” Link 2](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-2.png)

2. Tap on the **index.html** file
![ Docsify Open Course Starter Kit - “Edit this Page” Link 3](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-3.png)

3. Tap the **Pencil Icon** (top left-hand toolbar area) to start the editor
![ Docsify Open Course Starter Kit - “Edit this Page” Link 4](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-4.png)

4. Find the line `var gitLinkRepoURL = '';` and enter the URL of your own GitHub Repository in between the two quotes and then scroll down to the bottom of the page and tap the **Commit changes** button to save your changes
![ Docsify Open Course Starter Kit - “Edit this Page” Link 5](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-gitlink-5.png)

💻 Locally Editing Your Docsify Site Pages
---  

**Editing Your Docsify Site Pages on Your Desktop**
1. Tap **Code** on your repository (upper-right green button)
2. Choose **Open Desktop** and follow the prompts, installing [GitHub Desktop](https://desktop.github.com/) if not already present
3. You will now be able to edit your Docsify site (in the `docs` folder) using the desktop editor of your choice (e.g. [Atom](https://atom.io/))
4. Use GitHub Desktop to push any changes to your repository.  

[Learn more about using GitHub Desktop](https://help.github.com/en/desktop/contributing-to-projects/committing-and-reviewing-changes-to-your-project).

You can also clone (i.e download) a copy of your repository to your computer and [run Docsify locally](https://docsify.js.org/#/quickstart) to preview your site. See the below video for details.

🖼 Embedding your Docsify Page Content into Other Systems
---  

![ Docsify Open Course Page Embedded into the Canvas LMS](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-oc-canvas.png)
_Figure 2. Docsify Open Course Page Embedded into the Canvas LMS. Explore an example Canvas LMS course using Docsify Open Course pages for content at [https://canvas.sfu.ca/courses/44038/](https://canvas.sfu.ca/courses/44038)_

The optional ‘embedded’ (all lowercase) URL parameter hides a site’s sidebar and optional navbar for seamlessly embedding Docsify page content within another platform such as Canvas LMS, Moodle, Microsoft Teams etc.

To only display Docsify page content, add the following to a Docsify page URL:

`?embedded=true`

For example, https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources would display a standard Docsify page while https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true would only display page content (i.e., no sidebar or optional navbar is shown).

To optionally hide the 'Edit this Page' link, use the following:

`?embedded=true&hidegitlink=true`

For example, https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources would display a standard Docsify page while https://hibbitts-design.github.io/demo-docsify-open-course-starter-kit/#/resources?embedded=true&hidegitlink=true would only display page content (i.e., no sidebar or optional navbar is shown) and also hide the 'Edit this Page' link.

🌐 Using an LMS to Host a Docsify Open Course Site
---

As Docsify Open Course Starter Kit does not require a web server, it can actually be hosted on many LMSs that support file libraries such as Canvas and Moodle.

For example, here is a [Docsify Open Course Site hosted within a Canvas course](https://canvas.sfu.ca/courses/44038/files/15884796/download) and here is a [Docsify Open Course Site hosted within a Moodle course](https://paulhibbitts.net/moodle/mod/resource/view.php?id=25). Single Docsify Open Course site pages can also be embedded while hosted on the same system.

**Hosting a Docsify Open Course Site on your LMS**
1. Tap **Download** on your repository page
2. Upload to your LMS file storage area, and unzip the upload file
3. Based on your LMS, determine the external URL required to load the `index.html` file within the Docsify `Docs` folder. In Canvas, an example URL would look similar to `https://canvas.sfu.ca/courses/44038/files/15884796/download`.

| :warning: | Once hosted within your LMS, changes made to the source GitHub repository are no longer automatically reflected on your hosted Docsify site. Any GitHub repository updates must be manually uploaded to the LMS file library area. |
|---|:--|

📚 Docsify and Markdown Resources
---
**Docsify**  
[Docsify Documentation](https://docsify.js.org/#/?id=docsifyg)  
[Docsify Basics by MichaelCurrin](https://michaelcurrin.github.io/docsify-js-tutorial/#/?id=docsify-basics)  

**Docsify Themable**  
[Docsify Themeable Documentation](https://jhildenbiddle.github.io/docsify-themeable/#/introduction)  
[Docsify Themeable GitHub](https://github.com/jhildenbiddle/docsify-themeable)  

**Markdown**  
[Markdown Cheat Sheet](https://warpedvisions.org/projects/markdown-cheat-sheet/)  
[Markdown Guide](https://www.markdownguide.org/)  

📼 Video Walkthrough of Local Docsify Install/Config
---
[![Generating Documentation Sites with GitHub and Docsify - Alysson Alvaran](youtube.png)](https://www.youtube.com/watch?v=TV88lp7egMw)  
_Video 1. Generating Documentation Sites with GitHub and Docsify - Alysson Alvaran_

🙇‍Credits and Special Thanks
---
[Docsify Themeable](https://github.com/jhildenbiddle/docsify-themeable)   
