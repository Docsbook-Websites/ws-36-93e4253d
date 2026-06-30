```markdown
---
title: WebStudio Command Reference Guide
description: Discover WebStudio commands for building websites. Learn parameters, types, and examples to enhance your web development experience.
---

# WebStudio Command Reference Guide

This reference guide provides a comprehensive overview of commands available in WebStudio. Use this guide to enhance your website-building experience.

## Design Commands

| Parameter/Command | Type       | Description                                      | Example                     |
|-------------------|------------|--------------------------------------------------|-----------------------------|
| `addElement`      | Function   | Adds a new element to the current page.         | `addElement('header')`      |
| `removeElement`   | Function   | Removes an existing element from the page.      | `removeElement('footer')`    |
| `setStyle`        | Function   | Applies CSS styles to a selected element.       | `setStyle('header', {color: 'blue'})` |
| `setLayout`       | Function   | Defines the layout structure of the page.       | `setLayout('grid')`         |

## Content Management Commands

| Parameter/Command | Type       | Description                                      | Example                     |
|-------------------|------------|--------------------------------------------------|-----------------------------|
| `addText`         | Function   | Inserts text content into a specified element.  | `addText('main', 'Welcome!')` |
| `uploadImage`     | Function   | Uploads an image to the media library.          | `uploadImage('logo.png')`   |
| `linkPage`        | Function   | Creates a hyperlink to another page.             | `linkPage('about', 'About Us')` |
| `setSEO`          | Function   | Configures SEO settings for the current page.   | `setSEO('title', 'My Site')` |

## Customization Commands

| Parameter/Command | Type       | Description                                      | Example                     |
|-------------------|------------|--------------------------------------------------|-----------------------------|
| `addCustomCSS`    | Function   | Adds custom CSS styles to the project.          | `addCustomCSS('.btn {color: red;}')` |
| `addScript`       | Function   | Integrates a JavaScript file into the project.  | `addScript('analytics.js')` |
| `setTheme`        | Function   | Changes the overall theme of the website.       | `setTheme('dark')`         |
| `setResponsive`    | Function   | Enables responsive design for mobile devices.    | `setResponsive(true)`      |

## Publishing Commands

| Parameter/Command | Type       | Description                                      | Example                     |
|-------------------|------------|--------------------------------------------------|-----------------------------|
| `publishSite`     | Function   | Publishes the current website to the web.       | `publishSite()`             |
| `previewSite`     | Function   | Previews the website before publishing.          | `previewSite()`             |
| `setDomain`       | Function   | Assigns a custom domain to the website.         | `setDomain('mywebsite.com')` |
| `rollbackVersion` | Function   | Restores the site to a previous version.        | `rollbackVersion('v1.0')`  |

Use these commands to maximize your efficiency in WebStudio. For more detailed information, refer to the official WebStudio documentation.
```