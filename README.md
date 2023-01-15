Activity 01 - Course Tools
================

This activity is intended to be completed in one week - outside of class
preparation work and two 75-minute class meetings. On our Blackboard
course site you were provided with items to read, watch, and do prior to
attempting this activity. Do not proceed in this activity until you have
minimally:

1.  Completed the short interactive [Markdown
    tutorial](https://commonmark.org/help/tutorial/).
2.  Created a free GitHub account if you do not already have one.
3.  Verified that you can login to GVSU’s [RStudio
    Workbench](https://rstudio.gvsu.edu/). Or (more advanced and I may
    not be able to assist with problem solving), you installed R,
    RStudio, and Git on your computer and enabled RStudio and GitHub to
    communicate. If you choose go have this setup on your computer, I
    recommend following the directions from [Dr. Jenny Bryan *et
    al*](https://happygitwithr.com/).

In this repository/directory, you should see five items:

- `README-img` - a folder containing images that I am embedding within
  this `README.md` file. You do not need to do anything with this.
- `.gitignore` - a file that is used to specify what Git can ignore when
  pushing to GitHub. You do not need to do anything with this.
- `README.md` - the document you are currently reading.
- `day01-github-markdown` - a folder that contains items for you to
  complete during the first 75-minute class meeting.
- `day02-rstudio-rmarkdown` - a folder that contains items for you to
  complete during the second 75-minute class meeting.

We will explore most of these items over this week. Before doing that,
you will first make your own copy of this repository. Note that I will
refer to “repositories” as “repos” (or a single “repository” as a
“repo”) for the rest of the semester.

## Task 1: Forking the Repository

Read these directions first, then work through them. In this GitHub repo
(i.e., my repo):

1.  Click on the ![fork](README-img/fork-icon.png) **Fork** icon near
    the upper-right-hand corner. You will be taken to a **Create a new
    fork** screen.
2.  Verify that your GitHub username is selected under **Owner** and
    that the **Repository name** is `activity01-course-tools` with a
    green check mark (this verifies that you do not already have a
    GitHub repository with this name).
3.  You may provide a **Description** if you would like. This is a way
    to provide some additional, more descriptive, meta information
    related to the things you did. I like to provide a brief description
    of what happened.
4.  Verify that **Copy the `main` branch only** is selected.
5.  Click on the green **Create fork** button at the bottom of this
    page.

You should be taken a copy of this repo that is in your GitHub account.
That is, your page title should be `username/activity01-course-tools`,
where `username` is replaced with your GitHub username. Directly below
this, you will see the following message:

> forked from
> [gvsu-sta631/activity01-course-tools](https://github.com/gvsu-sta631/activity01-course-tools)

You will complete the rest of this activity in **your** forked copy of
the `activity01-course-tools` repo.

![check-in](README-img/noun-magnifying-glass.png) **Check in**

Take a moment to reflect on what this process is like compared to other
methods you have used for sharing documents with others.

- Can you draw a diagram that relates that previous method to this
  GitHub method?
- What was easier about this GitHub method?
- What was more difficult about this GitHub method?

## Task 2: Exploring a GitHub Repository

When you view repos on github.com, most will have a similar set up.
There are a lot of icons, text, regions, etc. in every repo and it can
be confusing what exactly you need to do. Whenever we will use a new
feature on GitHub, I will provide you with details of what to do and
what is happening. For the time being, you can focus on two regions of
your new repo.

Aside, the last time that I taught STA 518 I had students complete this
[Preparation](https://github.com/gvsu-sta518/preparation01) that
includes videos that provide more detail on what Git and GitHub are. You
may find this helpful, but these videos are somewhat old and things in
our current GitHub environment might be slightly different. Also, we
will not worry about Branches or Issues for the time being.

First, if you are currently reading this text that means that you are
viewing the `README.md` file. Folks use this file for various reasons,
but I will use it to describe what is in the repo and provide getting
started directions for how you should interact with it. This file takes
information written in Markdown and formats it to look nice on a
webpage.

Second, directly above the displayed `README.md` document is an area
that looks like a folder/directory that you interact with on your
computer. I like to think of a GitHub repo as a folder system that
others can view/copy/edit (with permission) rather than needing to zip
up a folder on my computer and then email it to another person to work
with. Repos can contain multiple types of files that use various
syntax/text and also include subfolders, sub-subfolders, etc. Read these
directions first, then work through them.

1.  In your `activity01-course-tools` repo folder/directory, locate and
    click into the `day01-github-markdown` subfolder.
2.  In the `day01-github-markdown` subfolder, you will be greeted by a
    new `README.md` file. Do your best to complete the tasks/directions
    provide in this subfolder by **11:59 pm (EST) on Tue, Jan 17**.
3.  In our Teams workspace (linked on Blackboard), find the **General**
    channel and post what was muddiest from these tasks. If someone else
    already posted what you though was muddy, add any clarification to
    their post and give them a “+ 1” 👍. Remember that this space is for
    conversations as well as posting questions. Read through your peers’
    muddy posts and do your best to provide help.

The rest of this `README` document contains tasks/directions for the
second class meeting of this week.

## Task 3: Exploring RStudio

Based on your course histories at GVSU and being enrolled in our Data
Science & Analytics program, I am assuming that you have experience with
R and RStudio. Therefore, I will not spend much time introducing basic R
usage (i.e., base R or foundational `{tidyverse}` packages, like
`{ggplot2}` or `{dplyr}`). I also assume that you have prior experience
with the RStudio IDE. However, I will not assume that you have prior
experience working between RStudio and GitHub and will provide you
directions for my opinionated workflow (which has been adopted from many
R/RStudio power users). If you feel rusty with R or RStudio, my go to
resource would be Chapters 1-8 of [R for Data
Science](https://r4ds.had.co.nz/index.html) by Wickham & Grolemund.
While I am making assumptions about your experiences with using
R/RStudio, please use our Microsoft Teams space to ask questions or seek
help. I do not want you to struggle and I am happy to help or provide
you with additional resources.

For these next tasks, you should minimally remember:

- What the main uses for each region/pane in RStudio:
  <https://r4ds.had.co.nz/introduction.html#rstudio>.
- What an R script is, how to run code in a script or Console, and how
  RStudio helps notify you of potential problems in your code:
  <https://r4ds.had.co.nz/workflow-scripts.html>.
- What RStudio Projects are, determining where things “live” in RStudio,
  and the benefits of beginning each R session from a “vanilla”
  (sessions that do not retain information from previous sessions):
  <https://r4ds.had.co.nz/workflow-projects.html>.

I think it is so **important** that you force RStudio to start from a
clean session, that I kindly ask that you follow the recommendations in
[Section
8.1](https://r4ds.had.co.nz/workflow-projects.html#what-is-real) of R
for Data Science by updating your **Global Options**.

![check-in](README-img/noun-magnifying-glass.png) **Check in**

Verify that you can access GVSU’s [RStudio
Workbench](https://rstudio.gvsu.edu/). Then, see if you can affirm each
of these questions:

- I can create an R script.
- I can create an RMarkdown document.
- I can run a simple calculation (e.g., `2 + 2`) in an R Script, an
  RMarkdown document, and the R Console.
- I can load an R package in an R Script, an RMarkdown document, and the
  R Console (e.g., like `{ggplot2}`)
- I can create a simple data visualization using `{ggplot2}` in an R
  Script, an RMarkdown document, and the R Console (e.g., like a
  scatterplot using the
  [`msleep`](https://ggplot2.tidyverse.org/reference/msleep.html)
  dataset).

## Task 4: Connecting RStudio and GitHub

We will use GitHub to save and share our work in RStudio this semester.
In order to do this, we need to help them communicate with one another.
Read these directions first, then work through them.

1.  In your `activity01-course-tools` repo folder/directory, locate and
    click into the `day02-rstudio-github` subfolder.
2.  In the `day02-rstudio-github` subfolder, you will be greeted by a
    new `README.md` file. Do your best to complete the tasks/directions
    provide in this subfolder by **11:59 pm (EST) on Thu, Jan 19**.
3.  In our Teams workspace (linked on Blackboard), find the **General**
    channel and post what was muddiest from these tasks. If someone else
    already posted what you though was muddy, add any clarification to
    their post and give them a “+ 1” 👍. Remember that this space is for
    conversations as well as posting questions. Read through your peers’
    muddy posts and do your best to provide help.

## Attribution

This document is based on David Keyes’ tutorial at [R for the Rest of
Us](https://rfortherestofus.com/2021/02/how-to-use-git-github-with-r/)
and [Happy Git with R](http://happygitwithr.com/) by Jenny Bryan et al.
