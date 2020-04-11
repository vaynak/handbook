# How to Use the Handbook

## Retrieving Information

The handbook is broken into sections for general company information and individual departments.  Each department has a tree of sub-pages with content relevant to that department.

Handbook Table of Contents is on the left side of most pages.

Page-specific Table of Contents is on the right side of some pages.

If any outdated, incorrect, or incomplete information is identified, take a minute to create an edit.

## Minor Content Updates, Single Page

To edit a page, click on the link at the bottom. This will bring you directly to the repository, to the page you are viewing, to be able to make a change.

When you have made your change to the page, enter the `Commit message` and `Target branch` name before submitting the change.

*  Commit message should be concise since you are limited to a single document change, something like "update leave policy to reflect pandemic".
*  Target branch should be a Kebab-case phrase of not more than 40 characters, something like "pandemic-leave-policy"

As soon as the commit is done, click the "Create Merge Request" button to add context to the change and assign it for revuew.

Since the branch will be removed when the change is merged, it doesn't need to tie back to issue names or change request identifiers. This is a simple, short workflow, the purpose of which is to maintain a large amount of documentation.

## Major Content Updates, Multiple Pages

To edit multiple pages, you can use the edit page link, but press the `Cancel` button and then select the `Web IDE` button at the top of the next page.

The Web IDE allows you to open many files at the same time using the tree to the left. The top becomes tabs for each open document.  Changes are saved into browser `local storage` as they're made so reloading the page or navigating away by accident should not result in lost data, though it is still a web browser so be careful.

After editing the places you want, click on the "commit" button to get to the `Commit message` and select `Create a new Branch`.

*  Commit message for larger changes should still be concise but will likely need to include multiple lines to explain why each file was changed.
*  Target branch should be a Kebab-case phrase of not more than 40 characters, something like "pandemic-leave-policy"

You may want to make multiple changes at different times and add muliple commits to the same branch.
At any point, click the "Create Merge Request" button to add context to the change and assign it for review.

## Structure or Theme Change

For a change to the whole site, it is recommended to perform the updates locally using a regular git workflow. The readme file in this repo talks about how to run hugo locally. The Merge Request for these changes will include a link to the local environment to review changes. It will only work for the developer or anyone who checks out the branch and runs Hugo locally.

Be sure to update docs about how to use the handbook for any changes that impact the user worlflow.