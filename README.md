# How to Host a Resume on GitHub Pages

Hello,  If you're looking to showcase your professional journey in a sleek, accessible manner, you've come to the right place. This guide will walk you through hosting your resume on GitHub Pages, not just as a task, but as an opportunity to embrace modern technical writing principles as advocated by Andrew Etter in his enlightening book, Modern Technical Writing. By the end of this README, you'll not only have your resume up and running online but also appreciate the simplicity, efficiency, and elegance of using Markdown and static site generators like Jekyll. Let's dive in!

# Introduction

In today's digital age, having an online presence is crucial for professionals across all industries. GitHub Pages offers a free, efficient, and straightforward way to host your resume, providing you with a platform to showcase your skills, experiences, and achievements to the world. By following this guide, you'll learn how to create a Markdown-formatted resume and host it using GitHub Pages, all while incorporating the best practices of modern technical writing.

![Resume GIF](Gifs/myResume.gif)

## Prerequisites

Before starting, ensure you have the following:

1. A resume formatted in Markdown. If you're new to Markdown, consider going through a [Markdown Tutorial](https://www.markdowntutorial.com/).
2. A [GitHub account](https://github.com/signup) - sign up if you haven't already.
3. Familiarity with GitHub Pages. Check out [GitHub Pages documentation](https://pages.github.com/) for a primer.
4. The Visual Studio Code needed, if don't have one please inform [here](https://code.visualstudio.com/), also please read the document [how to set up Visual Studio Code](https://code.visualstudio.com/docs), ensure you know how to create file.

# The Principles of Modern Technical Writing

As we embark on this journey, let's keep in mind the principles outlined by Andrew Etter in his book Modern Technical Writing. These principles will not only guide us through hosting our resume but also ensure we do so in a manner that is efficient, accessible, and maintainable.

  *  Use Lightweight Markup: Markdown is our tool of choice. It's easy to write, read, and convert to other formats.
  *  Stay Platform Independent: By using GitHub Pages, we're ensuring our resume can be accessed anywhere, on any device.
  *  Treat Documentation as Code: We will use version control to manage our resume, embracing the practices of continuous integration and deployment.
  *   Keep it Simple: Our focus is on content. A clear, concise resume is more powerful than one cluttered with unnecessary details.

## Contents

- [Creating the Repository](#creating-the-repository)
- [Selecting a Quick Theme](#embracing-jekyll-themes)
- [Publishing Your Resume on GitHub Pages](#publishing-your-resume-on-github-pages)
- [Principles of Modern Technical Writing](#principles-of-modern-technical-writing)
- [Conclustion](#conclusion)
- [FAQs](#faqs)
- [More Resources](#more-resources)
- [Authors and Acknowledgements](#authors-and-acknowledgements)


---
# Step-by-Step Guide

## Instructions

### Creating the Repository

1. Log into your GitHub account and click on the '**+**' symbol at the top right corner, then select "**New Repository**".
   
   ![Create New Repository](Gifs/clickRepository.gif)

2. Name your repository "`username.github.io`", where `username` is your GitHub username.
   
3. Set the repository to "**Public**" and initialize it with a README file.
   
  ![Naming Repository](Gifs/createRepository.gif)

4. Click on "**Create Repository**".
   
   ![Create Repository](Gifs/createre.jpg)

5. Clone the repository to your local machine using VS Code or your preferred IDE.

---


## Embracing Jekyll Themes

1. Visit [GitHub Pages themes](https://pages.github.com/themes/) to choose a theme for your resume.

![Theme Page](Gifs/themepage.gif)

2. Configure the theme on your repository's settings.
add the new file called "_config.yml" in Visual Studio Code which include the theme commend line we just copied. e.g.
```
remote_theme: pages-themes/hacker@v0.2.0
plugins:
- jekyll-remote-theme # add this line to the plugins list if you already have one
```


## Publishing Your Resume on GitHub Pages

1. Commit and push your changes to the repository.

    *  change the resume file name into "index.md" then drag and drop the file into github respository.
![GitHub Pages Section](Gifs/commit&push.gif)

    * Commit and push your _config.yml as well by using the same step you did in the first step.

3. Enable GitHub Pages in your repository's settings, under the "GitHub Pages" section.

![GitHub Pages Section](Gifs/hostpage.gif)

3. Access your resume at `https://username.github.io`.

---

# Conclusion
Congratulations! You've not only hosted your resume online but also taken a significant step towards modern technical documentation. Your resume is now a testament to your skills and a reflection of your adaptability to modern technical writing practices.

Remember, the key to a great online resume is not just the information it contains, but how easily it can be accessed and navigated. By following the steps outlined in this guide, you've ensured that your professional profile is not just visible, but also presented in a clear, concise, and accessible manner.

Keep learning, keep improving, and let your online resume be the bridge to your next big opportunity.
---

## Principles of Modern Technical Writing

- Use plain language and a minimalist approach for clarity.
- Write in Markdown for easy formatting and conversion.
- Include screenshots and diagrams to explain complex concepts.

---

## FAQs

- **Why is Markdown better than a word processor**     
    * Simple and Efficient: Markdown's syntax is straightforward, allowing you to format text quickly and easily, making it user-friendly.
    * Good for Version Control: Markdown files are just plain text, which works well with version control systems (like Git). This is important for projects with multiple contributors.
    * Portable and Flexible: Since Markdown files are lightweight and text-based, you can open them with any text editor. Also, you can convert Markdown to many formats like HTML, PDF, and Word.
    * Content-focused: Markdown lets you concentrate on your content without worrying about complex formatting, which is especially valuable for technical documentation.
- **Why is my resume not showing up?** 
    * Inappropriate Keywords: Job platforms often use keywords to filter resumes. Make sure your resume includes relevant keywords for your industry.
    * Formatting Issues: Complex formatting may confuse the algorithms of job platforms. Use simple formatting to ensure your resume is read correctly.
    * Profile Visibility Settings: Check your settings on the platform. Your resume might be set to private or invisible to employers.
    * Incomplete Profile: Some platforms prioritize profiles that are complete. Ensure all necessary sections of your profile are filled out.

---

## More Resources

- [Easy Markdown Tutorial](https://www.markdowntutorial.com)
- [GitHub Flavored Markdown Cheat Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- ["Modern Technical Writing" by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

---

## Authors and Acknowledgements

**Author:** Fengfan Bian ([GitHub Profile](https://github.com/Fyfe-c))

Thanks for all my mate:
Jacob Seraspi ([GitHub Profile](https://github.com/jacobseraspi))
Farah Hegazi ([GitHub profile](https://github.com/farahhegazi))

**Acknowledgements:** Special thanks to Anthony Phung and all who provided feedback and support.

