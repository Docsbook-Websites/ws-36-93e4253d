```yaml
title: WebStudio Command Reference for Creative Professionals
description: Discover WebStudio commands to enhance your website design. Build visually appealing sites with intuitive tools tailored for you.
---

# WebStudio Command Reference

This reference page provides a comprehensive list of commands available in WebStudio, organized by category. Use these commands to streamline your website design process.

## Design Commands

| Parameter/Command      | Type         | Description                                      | Example                     |
|------------------------|--------------|--------------------------------------------------|-----------------------------|
| `addElement`           | Function     | Adds a new design element to your page.         | `addElement('image')`      |
| `removeElement`        | Function     | Removes a specified design element from your page.| `removeElement('header')`   |
| `setBackgroundColor`   | Function     | Sets the background color of the selected section.| `setBackgroundColor('#FFF')`|
| `setFontSize`          | Function     | Adjusts the font size for selected text.        | `setFontSize('16px')`      |
| `alignText`            | Function     | Aligns text within a specified element.         | `alignText('center')`      |

## Layout Commands

| Parameter/Command      | Type         | Description                                      | Example                     |
|------------------------|--------------|--------------------------------------------------|-----------------------------|
| `createGrid`           | Function     | Creates a grid layout for your page elements.   | `createGrid(3, 2)`         |
| `addColumn`            | Function     | Adds a new column to the existing grid layout.  | `addColumn()`              |
| `removeRow`            | Function     | Removes a specified row from the grid layout.   | `removeRow(1)`             |
| `setMargin`            | Function     | Sets the margin for a specified element.        | `setMargin('20px')`        |
| `setPadding`           | Function     | Adjusts the padding within a specified element. | `setPadding('10px')`       |

## Media Commands

| Parameter/Command      | Type         | Description                                      | Example                     |
|------------------------|--------------|--------------------------------------------------|-----------------------------|
| `uploadImage`          | Function     | Uploads an image to your media library.         | `uploadImage('logo.png')`  |
| `addVideo`             | Function     | Embeds a video from a specified URL.            | `addVideo('https://url.com/video')` |
| `setImageAltText`      | Function     | Sets the alt text for an image for accessibility.| `setImageAltText('Logo Image')` |
| `resizeImage`          | Function     | Resizes an image to specified dimensions.       | `resizeImage('300x200')`   |
| `addAudio`             | Function     | Embeds an audio file from a specified URL.      | `addAudio('https://url.com/audio')` |

## Publishing Commands

| Parameter/Command      | Type         | Description                                      | Example                     |
|------------------------|--------------|--------------------------------------------------|-----------------------------|
| `publishSite`          | Function     | Publishes your website to the web.              | `publishSite()`             |
| `previewSite`          | Function     | Previews your website before publishing.         | `previewSite()`             |
| `setSEO`               | Function     | Sets SEO metadata for your website.              | `setSEO('My Website Title', 'Description')` |
| `connectDomain`        | Function     | Connects a custom domain to your website.        | `connectDomain('mydomain.com')` |
| `updateContent`        | Function     | Updates content on your live site.               | `updateContent('new text')` |
```