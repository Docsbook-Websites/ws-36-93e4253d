```markdown
---
title: WebStudio Command Reference for Website Creation
description: Discover WebStudio commands to customize your website effectively. Build and manage your site without coding skills.
---

# WebStudio Command Reference

This reference guide provides a comprehensive list of commands you can use in WebStudio to create and manage your website. Each command is categorized for easy navigation.

## Site Configuration

| Parameter/Command       | Type          | Description                                          | Example                     |
|-------------------------|---------------|------------------------------------------------------|-----------------------------|
| `setSiteTitle`          | String        | Sets the title of your website.                      | `setSiteTitle("My Business")` |
| `setSiteDescription`    | String        | Defines the meta description for SEO.               | `setSiteDescription("Best services in town")` |
| `setSiteLogo`           | Image URL     | Uploads a logo for your site.                        | `setSiteLogo("https://mybusiness.com/logo.png")` |
| `setFavicon`            | Image URL     | Sets the favicon for your website.                   | `setFavicon("https://mybusiness.com/favicon.ico")` |

## Page Management

| Parameter/Command       | Type          | Description                                          | Example                     |
|-------------------------|---------------|------------------------------------------------------|-----------------------------|
| `createPage`            | String        | Creates a new page on your website.                 | `createPage("About Us")`   |
| `deletePage`            | String        | Deletes an existing page.                            | `deletePage("Contact")`     |
| `setPageContent`        | String        | Sets the content for a specific page.                | `setPageContent("About Us", "We offer...")` |
| `setPageVisibility`     | Boolean       | Sets the visibility of a page (public/private).     | `setPageVisibility("About Us", true)` |

## Design Customization

| Parameter/Command       | Type          | Description                                          | Example                     |
|-------------------------|---------------|------------------------------------------------------|-----------------------------|
| `setTheme`              | String        | Applies a theme to your website.                     | `setTheme("Modern")`       |
| `setFont`               | String        | Changes the font style for your site.                | `setFont("Arial")`         |
| `setColorScheme`        | Array         | Defines the primary and secondary colors.            | `setColorScheme(["#000000", "#FFFFFF"])` |
| `addCustomCSS`          | String        | Adds custom CSS styles to your website.              | `addCustomCSS(".header { color: red; }")` |

## SEO Settings

| Parameter/Command       | Type          | Description                                          | Example                     |
|-------------------------|---------------|------------------------------------------------------|-----------------------------|
| `setMetaKeywords`       | Array         | Sets keywords for SEO optimization.                  | `setMetaKeywords(["web design", "small business"])` |
| `enableAnalytics`       | String        | Integrates Google Analytics for tracking.            | `enableAnalytics("UA-XXXXX-Y")` |
| `setRobots`             | String        | Configures robots.txt settings for search engines.   | `setRobots("User-agent: * Disallow: /private")` |

Use these commands to leverage the full potential of WebStudio and create a customized website that meets your business needs. For further assistance, refer to the WebStudio user guide or contact support.
```