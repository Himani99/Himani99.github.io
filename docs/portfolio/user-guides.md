# User Guides

## Docuwiz.io User Guide

**Client:** APIwiz (Technical Writing Assessment)
**Duration:** 3 days
**Role:** Technical Writer Candidate
**Standards:** Microsoft Writing Style Guide
**Format:** This guide is rendered in MkDocs from the original deliverable. [Download the original PDF](../assets/docuwiz-user-guide.pdf)

---

### 1. About This Guide

#### Product Overview

Docuwiz.io is a documentation platform that helps teams create, manage, and publish guides, API references, and recipes from a centralized workspace. It enables technical writers to create live API documentation using OpenAPI specifications.

The platform helps teams:

- Centralize all product documentation in one workspace
- Create user guides and API references
- Import OpenAPI specifications to generate interactive API references
- Organize documentation into categories
- Build step-by-step recipes
- Publish documentation collaboratively
- Maintain consistency across teams

#### Intended Audience

Docuwiz.io is designed for developers, technical writers, QA teams, and product managers. It lets you create and maintain accurate docs from a single source of truth.

#### Prerequisites

- An active Docuwiz.io account and verified workspace
- Site Admin or Editor permissions to create and publish content
- API specification files (OpenAPI, Swagger, or Postman) for the References section

#### What You Will Accomplish

By the end of this guide, you will be able to:

- Set up and navigate your Docuwiz.io workspace
- Create, edit, and organize long-form Guides and detailed API References
- Bundle content into guided Recipes for specific use cases
- Customize your documentation portal and manage team member permissions
- Publish and share your final documentation site

---

### 2. Getting Started

#### 2.1 Create an Account

Docuwiz.io provides multiple sign-up options: Google, GitHub, and manual account creation.

##### Sign Up with Google

1. Open the Docuwiz sign-up page
2. Select **Sign up with Google**
3. Choose the Google account you want to use
4. Enter a workspace name and select **Create workspace**

##### Sign Up with GitHub

1. Open the Docuwiz sign-up page
2. Select **Sign up with GitHub**
3. Authorize Docuwiz to access your GitHub account
4. Enter a workspace name and select **Create workspace**

##### Sign Up Manually

1. Open the Docuwiz sign-up page
2. Select **Create a manual account**
3. Enter the following:
    - Workspace name
    - Username
    - Email address
    - Password
    - Confirm password
4. Select **Sign up**
5. Check your email for a verification link and select **Verify email**
6. Enter your workspace name and select **Create workspace**

!!! note
    Ensure your password meets complexity requirements, which typically include a mix of uppercase letters, lowercase letters, numbers, and special characters.

After the workspace setup is complete, Docuwiz.io redirects you to the dashboard.

#### Optional Configuration

Enable **Load workspace with sample guides and references** to populate the workspace with example content. This option helps new users explore the platform features and workflows more easily.

---

### 3. Onboarding Flow

The Docuwiz dashboard has two main areas: the left navigation panel and the header bar.

#### Left Navigation Panel

The left sidebar provides access to every part of your workspace:

- **Overview** — Workspace activity, content collections, and recent activity
- **Guides** — Write and publish step-by-step documentation
- **References** — Manage API documentation, endpoints, parameters, and response schemas
- **Recipes** — Bundle guides and API endpoints into a single view for readers
- **Categories** — Organize guides and references into logical groups
- **Settings** — Workspace configuration

#### Header Bar

- **Refresh** — Reloads the current view
- **Comments** — Opens comment threads on the current document
- **Notifications** — Shows recent activity and updates
- **Search** — Finds content across your workspace
- **Profile** — Account details and workspace switching

!!! tip
    Press **Alt + T** to open notifications from any page.

#### 3.1 Overview Dashboard

After creating your workspace, Docuwiz opens the Overview dashboard. Use this page to monitor your documentation activity, access existing content, and start creating guides or API references.

**Global Header and Workspace URL:** At the top of the page, you'll find the **Public Documentation URL** (for example, `https://himani.docuwiz.io`). This is the live link where you can view your published documentation.

**Quick Actions:** Jump straight into content creation with four primary functions:

- **New Guide** — Structured, prose-based documentation
- **New API Doc** — Upload OpenAPI specifications or build API documentation from scratch
- **Recipe** — Combinations of specific pages and API endpoints for a specific use case
- **Category** — Organize different sets of documentation into logical groups

**API Guides and References Cards:**

- API Guides — Displays total count of guides created, with page count, last edit time, and version status
- API References — Lists specific APIs managed in the workspace (e.g., Marketstack API, Aviationstack API)

**Team Members and Admin Status:** Located in the bottom right, displays total member count, user profiles (names, emails, roles), and a Manage button to invite or remove team members.

**Recent Activity Timeline:** Shows recent workspace activity including content creation, publishing events, and major updates.

**Categories Management:** Dedicated to information architecture. Group related Guides and API References together to keep documentation organized as content grows.

**Recipes:** Create workflow-based documentation experiences that combine API endpoints with written explanations.

---

### 4. Creating and Managing Guides

The Guides section features a triple-pane layout designed for organization, content creation, and structural navigation.

#### 4.1 Create a Guide

To create a new guide:

1. Select **Guides** from the left sidebar
2. Select **Add guide** (the **+** icon) or select **Create** from the main content area
3. Enter a title for your guide
4. Write your content in the editor (supports Markdown)
5. Add sections, headings, and callouts to structure your guide

#### Organize Guide Content

Each guide contains individual pages that appear in the sidebar when a reader opens the guide. You can reorder pages by dragging them in the sidebar.

- Guide title at the top with a collapse/expand toggle
- Individual pages listed below with headings and content
- Actions menu (three-dot icon) on each page for editing, deleting, or reordering

#### 4.2 Documentation Workspace

The main center area where content is created and formatted:

- **Breadcrumb Navigation** — Located at the top left (e.g., GUIDES > DOCUWIZ DASHBOARD)
- **Rich Content Support** — Mix of text, bolded terminology, and embedded screenshots
- **Import and Templates** — Two floating action buttons at the lower-right corner:
    1. **Import from Local** — Import Markdown (.md) files from your computer
    2. **Browse Templates** — Select from predefined documentation templates

#### 4.3 Manage Revisions

**To publish a guide:**

1. Open the guide
2. Select **Publish** at the top of the editor
3. The guide is now visible on your published documentation site

**To unpublish a guide:** Select **Unpublish** from the same menu. The guide stays in your workspace but is no longer visible to readers.

**Import content** into a guide in two ways:
- **Import from local** — Adds a Markdown (.md) file from your computer
- **Import from repo** — Pulls content from a connected GitHub or GitLab repository

!!! note
    You need to connect source control before using the repository import option. See Source control for setup steps.

#### 4.4 Table of Contents

The right-hand sidebar automatically generates a dynamic Table of Contents for the current page:

- **Auto-Generation** — Pulls from headers used within the document
- **Interactive Links** — Allows authors and readers to jump directly to specific sections

---

### 5. Creating API References

The References module helps developers understand available endpoints, request formats, authentication requirements, and response schemas.

#### 5.1 Create a Reference

1. Select **References** from the left sidebar
2. Select **Add reference** or use the **+** icon
3. Enter a name for the reference (e.g., "Marketstack API v2")
4. Write a description that explains what the API does
5. Add endpoints by selecting **Add endpoint**

#### 5.2 Organize Endpoints

References group related endpoints under categories. Each endpoint shows:

- HTTP method (GET, POST, PUT, DELETE) as a colored badge
- Endpoint path (e.g., `/eod`)
- Short description of what the endpoint returns

#### 5.3 Import API Definitions

You can import OpenAPI, Swagger, or Postman collections:

1. Open the reference
2. Select the import icon in the editor toolbar
3. Choose the file type: `.json`, `.yaml`, or `.yml`
4. Upload your file
5. Docuwiz parses the file and adds the endpoints

!!! tip
    Import from a connected repository to keep your API reference in sync with your codebase.

#### 5.4 Publish a Reference

References follow the same publish workflow as guides. Select **Publish** to make the reference live. Select **Unpublish** to remove it from the public site.

---

### 6. Building Recipes

Recipes bundle guides and API endpoints into a single, focused walkthrough. They help readers follow a specific use case without switching between different pages.

#### 6.1 Create a Recipe

1. Select **Recipes** from the left sidebar
2. Select **Create Recipe**
3. Enter a title and description
4. Under **Select pages**, pick the guide pages to include
5. Under **Select endpoints**, pick the related API endpoints
6. Select **Create Recipe** to save

!!! note
    Recipes need at least one guide page or one endpoint before you can publish them.

#### 6.2 Manage Recipes

All recipes appear on the Recipes page. From here you can edit content, add or remove pages and endpoints, and publish or unpublish any recipe.

---

### 7. Managing Categories

Use categories to group related guides and API references into logical sections. Categories improve navigation and help readers locate related documentation on the published site.

#### Create a Category

1. Select **Categories** from the left sidebar
2. Select **Add category**
3. Enter a name and optional description
4. Drag guides and references into the category
5. Select **Save**

!!! tip
    Keep category names short and descriptive. Readers scan category names to find what they need, so clear names save time.

---

### 8. Configuring Workspace Settings

The Settings section allows admins to customize the documentation portal and manage workspace collaboration. Select **Settings** from the left sidebar.

#### 8.1 General Settings

- **Basic Details** — Update the display name for your workspace
- **Connect Your OpenAI API Key** — Enable AI-powered Swagger enhancement features
- **Search Index** — Select **Sync Now** to refresh the search index
- **Danger Zone** — Contains high-impact administrative actions, including workspace deletion

!!! warning
    Selecting **Delete Workspace** permanently removes the workspace and all associated data. This action cannot be undone.

#### 8.2 Team Members Management

**Invite a Team Member:**

1. Go to **Settings** and select **Team members**
2. Select **Invite**
3. Enter the email address of the person you want to invite
4. Choose a role: **Admin**, **Editor**, or **Collaborator**
5. Select **Send invite**

**Roles and Permissions:**

| Role | Permissions |
|------|-------------|
| Viewer | Read-only access. Cannot change settings or manage members |
| Collaborator | Can create and edit content. Cannot publish or change settings |
| Site Admin | Full access: manage settings, invite members, publish and delete content |

!!! note
    Only admins can change roles and remove team members.

#### 8.3 Source Control Settings

Connect your workspace to a GitHub or GitLab repository to import and sync documentation files — a critical feature for Docs-as-Code workflows.

**Connect a Repository:**

1. Go to **Settings** and select **Source control**
2. Choose **GitHub** or **GitLab**
3. Select **Connect now**
4. Authorize Docuwiz to access your repository
5. Select the repository and branch you want to connect

!!! tip
    Use a dedicated documentation branch (like `docs/main`) rather than your default branch. This keeps your docs separate from your code changes.

#### 8.4 Portal Customization

This section allows you to brand and design the consumer landing page — the first thing users see when they visit your documentation site.

**Hero Section:** Configure site headline, pre-headline, site description, and thumbnail image.

**Header Section:** Configure the navigation bar. Add up to four links to guides, recipes, or references.

**Theme Settings:** Choose between light and dark mode. Set your primary brand color.

**Embedded Resources:** Add custom CSS or JavaScript for analytics, custom fonts, or third-party embeds.

!!! note
    Portal customization changes update your published site after you publish or republish your content.

---

### 9. Troubleshooting

**Cannot sign in to my account —** Select **Forgot password** on the login page to reset your password. Verify your email address after creating your account.

**My published changes aren't showing —** Docuwiz may take a few minutes to update your published site. Wait 2-3 minutes and refresh the page. If changes still don't appear, open the guide or reference and select **Publish** again.

**Imported OpenAPI file shows no endpoints —** Make sure you're uploading a valid OpenAPI, Swagger, or Postman collection in `.json`, `.yaml`, or `.yml` format. Check that your file contains at least one endpoint definition.

**Cannot invite or remove a team member —** Only a Site Admin has permission to invite or remove team members. If you are a Collaborator or Editor, ask an Admin to update the team roster.

**My workspace URL change didn't save —** Changing the Workspace URL in General settings makes the old URL unavailable. Readers and bookmarks that point to the old URL will stop working.

---

### 10. Glossary

| Term | Definition |
|------|------------|
| Category | A logical section used to group related guides and API references on the published documentation site |
| Endpoint | A specific URL in an API that performs an operation, such as retrieving data or submitting a request |
| Guide | Structured, prose-based documentation used to walk readers through a process or concept |
| Markdown | A lightweight markup language for formatting text using plain-text syntax |
| OpenAPI Spec | A standard format (YAML or JSON) for describing RESTful APIs in a machine-readable file |
| Recipe | A guided walkthrough that combines guide pages and API endpoints for a specific use case |
| Reference | API documentation pages that describe endpoints, parameters, request formats, and response schemas |
| Workspace | The centralized environment where teams create, manage, and publish all Docuwiz content |

---

### 11. Contact Support

- **Email:** support@docuwiz.io
- **Documentation:** docs.docuwiz.io
- **In-app:** Select the help icon (?) in the header bar

We aim to respond within 24 hours on business days.

---

**[Download the original PDF version](../assets/docuwiz-user-guide.pdf)**

---

---

## End-User Documentation &amp; Release Notes at Synopsys

**Client:** Synopsys Inc.
**Duration:** Sep 2023 – Dec 2025
**Role:** Technical Product Publication Engineer

### Challenge

Synopsys required comprehensive end-user documentation for complex EDA (Electronic Design Automation) tools. The documentation needed to cover user guides, installation guides, application notes, and Quick Tip videos — all created using structured authoring with DITA-XML.

### Approach

1. **Structured Authoring:** Created end-user documentation and release notes using DITA-XML in Oxygen XML, ensuring consistency across all content types.
2. **UI/UX Writing:** Applied UI/UX writing principles to craft intuitive user-centered content for web and in-app experiences.
3. **Full Documentation Lifecycle:** Managed the complete process from requirement gathering through drafting, review, and publishing.
4. **Cross-Team Collaboration:** Worked with R&amp;D, AE, and QA teams for technical insights and product update alignment.
5. **Multimedia Content:** Produced Quick Tip videos using Camtasia, SnagIt, and iSpeak for visual learners.

### Deliverables

- User guides with DITA-XML structured content
- Installation and configuration guides
- Application notes for specific use cases
- Quick Tip video tutorials
- Release notes for each product version
- Online Help systems

### Impact

- Reduced manual OLH build check-in effort by 40% through automation
- Improved documentation analytics (CTR, engagement, top pages) to guide content strategy
- Consistent content across all documentation types through structured authoring

### Tools Used

DITA-XML, Oxygen XML, Camtasia, SnagIt, iSpeak, Jira, Confluence, CMS tools
