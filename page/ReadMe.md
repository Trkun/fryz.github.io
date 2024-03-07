---
layout: page
title: ReadMe
permalink: /readme/
markdown: GFM
---

# Hosting and Formatting Your Resume: A Modern Technical Writing Approach

## Purpose

In today's digital age, presenting your professional profile online has become a standard. This README not only walks you through the steps of hosting and formatting a resume online using GitHub Pages or Codeberg Pages but also connects these practical steps with the modern technical writing principles advocated by Andrew Etter in his influential book, "Modern Technical Writing." By the end of this guide, you'll have a sleek, accessible, and easily updatable online resume.

## Prerequisites

-   A basic understanding of version control (specifically Git).
-   A GitHub or Codeberg account.
-   A resume prepared in Markdown format. If you're new to Markdown, don't worry! It's simple to learn, and this guide includes resources to get you started.

**More Resources:** For an in-depth Markdown tutorial, check out Markdown Guide.

## Instructions

### 1. Selecting a Static Site Generator (SSG)

**Etter's Principle:** In "Modern Technical Writing," Etter highlights the benefits of using Static Site Generators (SSGs) for creating documentation. SSGs are fast, secure, and facilitate collaboration.

**Practical Step:** For hosting a resume, we recommend Jekyll due to its direct integration with GitHub Pages, simplifying the hosting process. To start, install Jekyll (follow the official Jekyll documentation) and create a new Jekyll project. This project will serve as the foundation for your online resume.

### 2. Embracing Version Control

**Etter's Principle:** Version control is not just a tool for software development; it's a cornerstone of modern technical writing. It allows you to track changes, revert to previous versions, and collaborate with others.

**Practical Step:** If you haven't already, create a new repository on GitHub or Codeberg for your resume. This repository will be the version-controlled home for your resume, enabling you to track revisions and collaborate if needed. Push your local Jekyll project, including your Markdown-formatted resume, to this repository.

### 3. Markdown: The Why and How

**Etter's Principle:** Etter praises Markdown for its simplicity and portability. A Markdown file can be easily converted to numerous formats, making it ideal for writing documentation—or in this case, your resume.

**Practical Step:** Write your resume in Markdown, utilizing basic syntax for headings, lists, links, and other formatting features to structure your content. Your `resume.md` should include headings for Education, Experience, Skills, and any other relevant sections. For assistance with Markdown syntax, refer to the resources section of this README.

### 4. Hosting Your Resume on GitHub Pages or Codeberg Pages

**Etter's Principle:** The decentralization of publishing platforms is a key theme in "Modern Technical Writing." Using platforms like GitHub Pages, writers can easily distribute their content to a wide audience.

**Practical Step:** Enable GitHub Pages or Codeberg Pages for your repository. This process involves selecting a branch from which your site will build (usually `main`) and, optionally, choosing a theme to enhance the appearance of your resume. Once enabled, your resume will be accessible online through a URL provided by GitHub or Codeberg.

### 5. Demonstrating Your Resume with an Animated Gif

**Practical Step:** Visual aids are crucial for effective technical documentation. Create an animated gif of your resume to include in this README. The gif should demonstrate how users can navigate and interact with your online resume, providing a quick, visual overview of its layout and content.

## More Resources

To further assist you in this journey, here are additional resources:

-   Mastering Markdown: A comprehensive guide to Markdown syntax, perfect for beginners.
-   Jekyll Documentation: Everything you need to know about setting up and customizing your Jekyll site.
-   GitHub Pages Documentation: Detailed instructions on how to host your site using GitHub Pages.
-   Codeberg Documentation: Similar to GitHub, Codeberg offers a platform for hosting your projects and documentation with the added benefit of being an open-source, non-profit service.

## Authors and Acknowledgements

This guide is a collective effort of individuals passionate about modern technical writing and open-source technologies. We extend our gratitude to Andrew Etter for his seminal work, which serves as the backbone of our approach. We also thank the developers behind Markdown, Jekyll, GitHub Pages, and Codeberg for making these tools available and easy to use.

## FAQs

**Q: Why is Markdown better than a word processor for my resume?**

A: Markdown offers several advantages over traditional word processors, especially for online documentation and resumes. Its simplicity ensures that your content is portable and easily converted to various formats, including HTML for web pages. Additionally, Markdown files are lightweight and can be version controlled, allowing for efficient updates and collaboration. This aligns perfectly with Etter's advocacy for using lightweight markup languages in modern technical writing.

**Q: My resume isn't appearing on GitHub Pages. What should I do?**

A: First, ensure you've pushed your `resume.md` file to the correct branch (typically `main` or `gh-pages`) and that GitHub Pages is enabled in your repository settings. Also, check if you've chosen a theme or set up a custom domain, as these can affect how your resume is displayed. If your resume still isn't showing, verify that your Jekyll site is correctly configured and that there are no build errors. GitHub will send an email if there are issues with the page build process.

By following these instructions and leveraging the principles from "Modern Technical Writing," you can effectively host and format your resume, making it accessible and easy to maintain. This approach not only showcases your professional qualifications but also demonstrates your proficiency with modern technical writing practices and tools.
