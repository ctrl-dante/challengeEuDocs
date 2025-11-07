# Staging & Testing Workflow

This document outlines the **staging and testing workflow** for the Challenge EU website, covering content, plugins, and code management.

---

## 1. Overview

The staging environment allows the team to safely test **content, plugins, and code** before publishing changes to the live site.  

There are multiple ways to implement a staging environment:

- **Internal Staging**: Using a subfolder or slug like `/staging`  
- **Professional Staging**: Dedicated staging server or subdomain  
- **Local Development**: Using LocalWP or Docker to test the site locally  

**Key principle**: Content and code changes are tested independently before merging into live.

---

## 2. Website Structure

WordPress stores content and code in separate locations:

- **Content**: `wp-content/uploads` (images, media) and the database  
- **Themes**: `wp-content/themes/your-theme`  
- **Plugins**: `wp-content/plugins`  

Code changes (themes/plugins) are tracked via **Git**, while content changes are database-driven.

---

## 3. Staging Workflow

### 3.1 Content Staging

- Create draft pages, templates, and forms in a **staging area**  
- For example: `/wp-content/staging` or private pages within WordPress  
- Steps:

1. **Playground Page (Private)**  
   - Test Elementor designs, forms, and page layouts  
2. **Export Templates/Forms**  
   - Once verified, export Elementor templates or forms  
3. **Publish Live Content**  
   - Import verified templates/forms to the live site  
   - Content goes live safely without breaking existing pages

### 3.2 Plugin Staging

- Test new plugins in **LocalWP or staging environment**  
- Steps:

1. Clone the live website to LocalWP  
2. Install and configure the plugin  
3. Test functionality thoroughly  
4. Only push tested plugins to staging or live site

### 3.3 Code Staging

- Manage themes and custom code via **Git**  
- Workflow:




- Ensure that **tested code changes** are merged to staging before deploying live  

---

## 4. Recommended Practices

- **Design Approvals**: All visual changes should be designed in **Figma** and approved before staging  
- **Content Testing**: Draft content and media should be staged in `/wp-content/staging`  
- **Plugin Testing**: Use LocalWP to experiment without affecting live site  
- **Export & Import**: Only move tested templates, forms, and plugins to live  
- **Team Access**: Only team members with access to staging and Git should manage changes  

---

## 5. Tools & Options

- **LocalWP**: Local WordPress development environment for plugin and design testing  
- **Docker**: Optional containerized staging environment  
- **GitHub Actions**: Optional CI/CD pipeline for automated deployment of themes/plugins  

---

## 6. Summary

| Stage                 | Location / Tool        | Purpose                                     |
|-----------------------|----------------------|---------------------------------------------|
| Content Staging       | `/wp-content/staging` | Draft templates, forms, and media          |
| Plugin Testing        | LocalWP               | Test plugin functionality                   |
| Code Changes          | Git                   | Manage themes and custom code              |
| Staging Server        | Subdomain / Folder    | Test live-like environment safely          |
| Live Site             | Production            | Publish verified content and code          |

This workflow ensures that **content, plugins, and code are tested independently** before reaching the live site, reducing errors and downtime.

