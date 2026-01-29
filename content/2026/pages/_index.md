+++
title = 'Pages & Documentation at HTGAA 2026'
draft = false
+++

For 2026 HTGAA _Committed Listeners_ are required to submit their homework and documentation with and through the git-based [HTGAA 2026 Documentation Server](https://edit.htgaa.org). Each students will get their own git repository, from which your personal student website will be automatically build.

# Access

Registered participants of HTGAA 2026 will be given access to the [HTGAA Documentation Server](https://edit.htgaa.org) after Class #1 on Feburary 3rd.

_Example Repository:_  
https://edit.htgaa.org/georg-tremmel/webpages

_Example Website: (will be build automatically from the repository)_  
https://pages.htgaa.org/georg-tremmel


{{< callout caution "All content will be public">}}
All your homework and documentation will be publicly accessible.
{{< /callout >}}

- [ ] To Do: Add Screenshots

#  Authoring

### Markdown Syntax

Your content will be written in Markdown, a simple syntax to add formatting to plain text. If you are unfamiliar with Markdown, please have a look at this [Introduction to Markdown](https://mcshelby.github.io/hugo-theme-relearn/authoring/markdown/index.html).

### Editing Files with the Online Editor (easy)

The HTGAA Repositories have a web-based editor:

1. Log into your account
2. Navigate to the file you want to edit
3. Click the `Edit file` icon
4. Edit
5. After Editing, save the changes by clicking `Commit Changes`

- [ ] To Do: Add Screenshots

#### Adding Images

- [ ] To Do: How to add images
- [ ] To Do: How to scale down images

### Cloning your Repo and runnig a Local Instance of Hugo (advanced)


```
cd my-local-directory
git clone https://edit.htgaa.org/georg-tremmel/webpages.git
```

or

`git clone https://edit.htgaa.org/georg-tremmel/webpages.git my-local-directory`

#### Git

Files can now be edited on your computer. To _push_ the changes to the server and update the website, the follow steps are necessary:

| Git&nbsp;Command| |
| :--------- | :--- |
| 1. `git add *` | [Add](https://git-scm.com/docs/git-add) all new and changed files |
| 2. `git commit` | Locally [commit](https://git-scm.com/docs/git-commit) your changed. You will be asked to provide add a short message. Can also be concatenated into `git commit -m 'my message`` |
| 3. `git push` | Uploads and [pushes](https://git-scm.com/docs/git-push) the changes onto the HTGAA Server, the website is rebuilt after a few seconds |

Git is much more powerful - and complex - but these 3 commands will be used most often.

{{< callout caution "Pulling content from the Server">}}
If you change file on the server, make sure to do a `git pull` to download the latest changes.
{{< /callout >}}


#### Running a Local Version of Hugo

1. [Install](https://gohugo.io/installation/) the lastest version of Hugo.


## Technical Details

- [Forgejo] self-hosted lightweight [git](https://git-scm.com)-based software forge', functional similar to GitHub and GitLab
- [Hugo](https://gohugo.io) SSG (Static Site Generator) with the [Relearn](https://themes.gohugo.io/themes/hugo-theme-relearn/) Theme

{{< callout caution "Hugo Theme">}}
You don't need to edit/change your Hugo theme. But if you want, you can.
{{< /callout >}}


## To Do

- [ ] Add Screenshots showing the login process

