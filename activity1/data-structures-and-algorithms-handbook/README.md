# Introduction

Welcome to our Data Structures and Algorithms Handbook!

## Updating this handbook

### Pre-requisites

Some tips may require terminal shell access on macOS/Linux. Ensure that your environment is working and that you have cloned the [data-structures-and-algorithms-handbook](https://gitlab.com/christianvisaya/data-structures-and-algorithms-handbook) project, for example.

- [Git by Traversy Media](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
- [Git Cheat Sheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)
- [Markdown by Traversy Media](https://www.youtube.com/watch?v=HUBNt18RFbo)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

#### 1. Clone repository

```
git clone https://gitlab.com/christianvisaya/data-structures-and-algorithms-handbook.git

git clone git@gitlab.com:christianvisaya/data-structures-and-algorithms-handbook.git
```

Sync it. Ensure that you stash away local changes not yet committed.

```
cd data-structures-and-algorithms-handbook
git stash
git checkout main
git pull
```

#### 2. Install honkit

1. Install [Node.JS LTS Version](https://nodejs.org/en/)
2. Install Honkit with NPM

```
npm install
```

3. Preview and serve your book using:

```
npx honkit serve
```

#### 3. Modify existing document

This handbook uses Honkit and Markdown. To continue with editing, you may refer to [Honkit documentation](https://github.com/honkit/honkit)

#### 4. Commit changes

Add and commit your changes to a new branch; for example, the branch name is **bsis-2-visaya-christian**. Push it to GitLab, create a new merge request, add screenshots of how your pages look like, and assign your MR Reviewer to Christian Visaya.

### Task 1: Know yourself

1. Add your entry to the "Meet the Team" section
2. Alphabetical order of the first name
3. Add your "pang-malupitan" image to the "team/images" directory with a file name like bsis_2_visaya_christian in .jpg format, camel case
4. Follow the template for other fields; make sure to fill out all of them
5. Add your 16Personalities link
6. Commit, push, and create a merge request
7. Deadline is September 24 @ 7 am
