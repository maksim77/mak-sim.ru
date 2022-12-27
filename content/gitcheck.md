---
title: "Git User check"
date: 2022-12-27T15:38:00+03:00
draft: false
---
- [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=mak-sim.gitcheck)
- [GitHub](https://github.com/maksim77/gitcheck)

Sometimes, after cloning a repository from a corporate git server and having already sent several commits there, you notice that you forgot to change the user settings in git.  
This extension is written to avoid this.

You only need to define three parameters. The first is the domain that the extension will look for in the origin section of the repository that you opened in VSCode.  
The other two are user settings that must be set for the repository cloned from the domain specified in the first paragraph.
![](/img/gitcheck-settings.png)

That's it! The extension will warn you that you are working with a repository for which user settings should be set (if they are not set). Clicking on the "Overwrite" button will automatically add the necessary parameters to the git settings of the current project.
![](/img/gitcheck-prompt.png)
