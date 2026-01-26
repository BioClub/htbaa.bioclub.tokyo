+++
title = 'Documentation at HTGAA 2026'
draft = false
+++

For 2026 HTGAA _Committed Listeners_ are required to submit their homework and documentation with and through the [HTGAA 2026 Documentation Server](https://edit.htgaa.org).

## Access

Registered participants of HTGAA 2026 will be given access to the [HTGAA Documentation Server](https://edit.htgaa.org) after Class #1 on Feburary 3rd.

- Screenshot (TODO)

## Editing

### Markdown

### Online Editor (easy)

### Cloning your repo and runnig a local instance of Hugo (advanced)

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

