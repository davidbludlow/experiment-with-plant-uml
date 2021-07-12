# experiment-with-plant-uml

This is an experiment to try to use GitPod to do real-time collaboration on a plant UML diagram.

## To use

There are two ways to get started, but once you are started, open up a .puml file and press Alt-D to open up a picture preview of it.

### Way 1: If you want to do real-time collaboration

Ask Ludlow for link to join a shared GitPod workspace. All changes made by anyone at that link will be isntantly synced to what everyone else at that link can see.

### Way 2: To work on your own

1. Make an account at https://gitpod.io .
   - You only need to use your real GitHub account if you want to make commits, using your real GitHub account, without having to use the terminal to switch what GitHub thing you are logged in as each time.
2. (Skip this step if you don't want to make any commits. Also skip this step if, on https://github.com/settings/emails , you don't have the "Keep my email addresses private" option turned on.) Go to https://gitpod.io/variables and set the magical environment variables so that when you make commits, it will magically work, and not yell at you that your commit is exposing your private email address. For example, I set my environment variables like what the table below shows. I got the 5985136+davidbludlow@users.noreply.github.com email address by copying it off of https://github.com/settings/emails , because I have the "Keep my email addresses private" option set to true on that page.

| name                  | value                                                                                                                 | scope |
| --------------------- | --------------------------------------------------------------------------------------------------------------------- | ----- |
| `GIT_AUTHOR_EMAIL`    | `5985136+davidbludlow@users.noreply.github.com`                                                                       | `*/*` |
| `GIT_COMMITTER_EMAIL` | `5985136+davidbludlow@users.noreply.github.com`                                                                       | `*/*` |
| `GIT_AUTHOR_NAME`     | `David B Ludlow` (This isn't nessisary to change, but I wanted to, so that it didn't use my GitHub username instead.) | `*/*` |

3. Press this button

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/davidbludlow/experiment-with-plant-uml)

## Don't read below this line

https://code.visualstudio.com/updates/v1_58#_open-in-vs-code-badge offered this badge [![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/davidbludlow/experiment-with-plant-uml)
