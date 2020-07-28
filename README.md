# SelfContainedIssueRepro

This repository contains a solution that reproduces the errors and logging of a self-contained AspNet Core app running as an InProcess IIS application.

## How to reproduce

1. Publish the output using the existing 'FolderPublish' publish profile.
2. Copy the publish output to an IIS application
3. Browse to the application using a webbrowser and the below error should be shown

![](https://github.com/RVink/SelfContainedIssueRepro/blob/master/SelfContainedIssueRepro.png)
