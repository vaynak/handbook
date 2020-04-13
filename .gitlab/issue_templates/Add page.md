# Adding a new page

## Finding the Right Place

Identify what type of content you intend on making and create an issue to work on it using this template.

Once you have selected where in the tree it needs to go, answer the following questions:

 - [ ] Can this page be a section on an existing page? (if yes, switch to the `Content change` template)
 - [ ] Should this page be included in the menu? (if no, `bookHidden: true` in front matter)
 - [ ] Is the change drafted? (if yes, create a comment below and use the markdown preview to see if it looks correct)
 - [ ]
 - [ ] Who should approve and merge this change? (create an MR and assign to them when it's time)



 ## Drafting Steps

 - [ ] Create a new branch for example `infra-gitlab-workflow` to store IAC code
 - [ ] Create a merge request for merging `infra-gitlab-workflow` into master, leave `WIP` enabled
 - [ ] Create a new company page or department page as a blank text document or using `hugo new dept/engineering/infrastructure/gitlab-workflow.md`
 - [ ] Use the markdown preview in the WebIDE, GitLab Issue, or GitLab Merge Request descriptions or comment fields to get the majority drafted
 - [ ] Spelling and grammar check
 - [ ] Identify apropriate front matter (see next section)


### Front Matter Options

```toml
---
bookHidden: true
bookCollapseSection: true
weight: 11
title: GitLab Workflow with Infrastructure as Code
---
```

*  `bookHidden`: if set to true, hides the page from the left navigation
*  `bookCollapseSection`: if set to true, it only shows this page in the left nav and child pages only appear when navigated to.
*  `weight`: Sets the order in the left navigation with 1 at the top and 10000 at the bottom.
*  `title`: the text that shows in the left navigation for the title