# Contributing to brianpereboom.github.com

Thank you for your interest in contributing to brianpereboom.github.com! We welcome your contributions to help make this website even better. Below are the steps to follow in order to contribute effectively.

## Table of Contents
1. [Requesting to be a Contributor](#1-requesting-to-be-a-contributor)
2. [Creating a Biography or Articles](#2-creating-a-biography-or-articles)
3. [Organizing Articles](#3-organizing-articles)
4. [Updating the Sitemap](#4-updating-the-sitemap)
5. [Submitting Your Contribution](#5-submitting-your-contribution)

---

### 1. Requesting to be a Contributor

Before you can contribute, you need to request to be added as a contributor. Follow these steps:

1. Visit the [GitHub repository](https://github.com/brianpereboom/brianpereboom.github.io).

2. Click on the "Fork" button in the upper right-hand corner to create a copy of the repository in your GitHub account.

3. Once you have your own fork, navigate to the "Settings" tab of your forked repository.

4. Scroll down to the "Collaborators" section and click on "Add collaborator."

5. Enter the GitHub username of the repository owner or an existing contributor (if applicable) and click "Add collaborator."

6. The owner or collaborator will receive a notification and grant you access to the repository.

### 2. Creating a Biography or Articles

You can contribute by adding a biography or articles to the website. Here's how to do it:

1. Create a new directory with the name of your article (or your name in the case of a biography) in the Articles directory of your forked repository.

2. Inside this directory, create an `index.html` file and any accompanying HTML, CSS, or script files you need for your content.

### 3. Organizing Articles

To keep the website organized, place your biography folder in "Articles/Meet The Creators/" and article folders in the "Articles" directory in the subdirectory that best matches the topic discussed in the article.

For example, if your article is about web development, you could create a directory structure like this:

```
Articles/
├── Meet The Creators/
│   ├── YourName/
│   │   ├── index.html
│   │   ├── styles.css
│   │   └── script.js
├── Web Development/
│   ├── YourArticleName/
│   │   ├── index.html
│   │   ├── styles.css
│   │   └── script.js
```

### 4. Updating the Sitemap

To ensure your article shows up in the navbar, you should add it to the `articlemap.xml` file in the following format:

```xml
<url>
  <loc>category/articleName</loc>
</url>
```

Replace `category` with the relevant category (e.g., "Meet The Creators" or the appropriate subdirectory) and `articleName` with the name of your article directory.

### 5. Submitting Your Contribution

Once you have completed your article or biography and added it to the repository, follow these steps to submit your contribution:

1. Commit your changes to your forked repository.

2. Create a pull request (PR) from your forked repository to the main repository (brianpereboom/brianpereboom.github.io).

3. Provide a clear and concise title and description for your pull request, explaining what your contribution entails.

4. Once your PR is submitted, it will be reviewed by the maintainers, and any necessary feedback or changes will be discussed.

5. Once your PR is approved, it will be merged into the main repository, and your contribution will be live on the website.

Thank you for contributing to brianpereboom.github.com! Your contributions help make this website a valuable resource for our audience.
