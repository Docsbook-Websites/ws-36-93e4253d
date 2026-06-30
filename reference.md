```markdown
---
title: WebStudio Command Reference for Website Building
description: Learn WebStudio commands to create customizable websites without coding skills.
---

# WebStudio Command Reference

This reference page provides a comprehensive list of commands and parameters you can use in WebStudio to build your website. Grouped by category, these commands help you customize your site effectively.

## Layout Commands

| Parameter/Command      | Type         | Description                                   | Example                       |
|------------------------|--------------|-----------------------------------------------|-------------------------------|
| `addSection`           | Function     | Adds a new section to your webpage.          | `addSection('header')`       |
| `removeSection`        | Function     | Removes a specified section from your page.  | `removeSection('footer')`     |
| `setColumnLayout`      | Function     | Defines the column layout for a section.     | `setColumnLayout(3)`         |
| `setBackgroundColor`   | Function     | Changes the background color of a section.   | `setBackgroundColor('#fff')` |

## Text Commands

| Parameter/Command      | Type         | Description                                   | Example                       |
|------------------------|--------------|-----------------------------------------------|-------------------------------|
| `addText`              | Function     | Inserts a text element into a section.       | `addText('Welcome to my site!')` |
| `setFontSize`          | Function     | Adjusts the font size of text elements.      | `setFontSize('16px')`        |
| `setTextColor`         | Function     | Changes the color of the text.               | `setTextColor('#333')`       |
| `setTextAlignment`     | Function     | Aligns text within its container.            | `setTextAlignment('center')` |

## Media Commands

| Parameter/Command      | Type         | Description                                   | Example                       |
|------------------------|--------------|-----------------------------------------------|-------------------------------|
| `addImage`             | Function     | Inserts an image into a section.             | `addImage('logo.png')`       |
| `addVideo`             | Function     | Embeds a video from a URL.                   | `addVideo('https://video.url')` |
| `setImageSize`         | Function     | Adjusts the size of an image.                | `setImageSize('100%', 'auto')` |
| `setVideoAutoplay`     | Function     | Enables autoplay for embedded videos.        | `setVideoAutoplay(true)`      |

## Style Commands

| Parameter/Command      | Type         | Description                                   | Example                       |
|------------------------|--------------|-----------------------------------------------|-------------------------------|
| `setBorder`            | Function     | Adds a border around elements.               | `setBorder('1px solid #000')` |
| `setMargin`            | Function     | Sets the margin for elements.                | `setMargin('10px')`          |
| `setPadding`           | Function     | Adjusts the padding within elements.         | `setPadding('5px')`          |
| `setShadow`            | Function     | Applies shadow effects to elements.          | `setShadow('2px 2px 5px #aaa')` |

## Publishing Commands

| Parameter/Command      | Type         | Description                                   | Example                       |
|------------------------|--------------|-----------------------------------------------|-------------------------------|
| `previewSite`          | Function     | Previews your website before publishing.      | `previewSite()`              |
| `publishSite`          | Function     | Publishes your website to the web.           | `publishSite()`              |
| `setDomain`            | Function     | Assigns a custom domain to your site.        | `setDomain('mybusiness.com')` |
| `setSEO`               | Function     | Configures SEO settings for better visibility.| `setSEO({ title: 'My Site', description: 'Best site ever' })` |
```