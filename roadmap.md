# Pure Blazor Roadmap

## Overview

This roadmap outlines what features we're locked on and currently building (Working On Now); what features we'll build in the future (Up Next); and what else we're considering even further out (Future). Please, try out our Alpha version and let us know your thoughts - both good and bad. Also, give us feedback on this roadmap and what you'd want us to focus on in the future.

## What We're Working On Now = Q4 2023

### Blazor WASM Static Sites
- **Description**: Host Blazor WASM static sites directly within PureBlazor with your choice of a built-in subdomain (e.g. your-name.wasmhost.dev). 

### Host Static Sites
- **Description**: Host static pages on a PureBlazor custom domain (e.g. your-name.wasmhost.dev).

### Plugins
- **Description**: Extend the CMS with your own custom plugins with C# and Blazor.

### HTTPS
- **Description**: Automatically issue HTTPS certificates on a PureBlazor-custom domain.

### Tailwind CSS Support
- **Description**: Support automatic Tailwind CSS generation.

### Login
- **Description**: Basic Identity/Login with a Local Account. No external/social login Providers (Auth0, Google, etc.).

## What's Coming Up Next = Date TBD

### Visual Page Builder
- **Description**: Implement a drag-and-drop intuitive interface allowing users to create content in a visual fashion, without having to write code. Users will be able to select components like text, buttons, sliders, etc. in a crude approximation to tools like Retool or Bubble.

### API Access
- **Description**: REST API to manage all actions in the CMS using either REST or gRPS.

### Integrate with the Existing Environment
- **Description**: Being able to include the CMS easily in existing B2B applications in the customer's stack.

### Fix Blazor Rendering Deficiency
- **Description**: Fix deficiency with Blazor's refresh to resolve a number of user experience bugs (i.e. Make Blazor PWA auto-detect a newer version of the app; Web Assembly is too big and the signalr connection is not smooth; Failing to reconnect when tabbing away.)

### Blazor Blocks
- **Description**: Add a component library to build pages with code (like Radzen or Devexpress). Support reusable blocks of content across different website sections.

### Native AI
- **Description**: AI support to generate titles, summaries, references, tags, and more.

### Built-in DB for Your Content Type
- **Description**: Custom form builder for customer content type.

### Internationalization and Localization
- **Description**: Support Spanish, German, Portuguese, and French.

### Background Jobs
- **Description**: Support background jobs for adhoc and recurring CMS tasks.

### Blazor Identity
- **Description**: Build Blazor identity, a bespoke openID-complaint identity solution.

### Eject/No Vendor Lockin
- **Description**: Support exporting all data components and pages to use with a different hosting solution without being tied to PureBlazor.

### RTL Support
- **Description**: Support Right to Left language styling for CMS.

### Assets/Media
- **Description**: Support Asset Management to streamline the organization, storage, and retrieval of assets such as photos, animations, videos, documents, etc.

### Security/Permissions
- **Description**: Use roles and claims to create security boundaries and authotization policies such as administrative access, guest/client login, etc.

## What We're Thinking of in the Future = Date TBD

### Markdown Static Sites
- **Description**: Create a full single-page static site with Markdown. Deprioritizing this milestone for now, because we aim to build PB in a way that abstracts all of Azure's infrastructure from the user and creates a container app for them.

### Analytics
- **Description**: Support bespoke analytics for Blazor instead of solutions like GA/Amplitude.

### Logging
- **Description**: Support bespoke logging service for Blazor or bring your own log solution such as Elastic/Datadog/text files.

### Advanced CMS Features
- **Description**: Publish history and rollback (undo or rollback to a previous version if needed).

### Data Hydration
- **Description**: Enable simple fetch and dom manipulation.

### Application Performance Monitoring (APM)
- **Description**: Support bespoke Application Performance Monitoring (APM) or bring your own APM solution such as New Relic, DataDog, etc.

### Automatic Backups
- **Description**: Automatically and securely backup all your content and data.

### Mobile Friendly
- **Description**: Support the following user requests: Be able to format numbers/strings on mobile (not just desktop). Detect which device the app is running on (like Bit Platform does). Preview in different screen layouts before publishing. Extensibility between web and mobile.

### Visual Studio Templates
- **Description**: Support Visual Studio templates.

### E-commerce Store Support
- **Description**: First-party e-commerce support and integration capability for your own ecomm solution such as Shopify, Woo, etc.

### Offline Support
- **Description**: Run the app offline for customers in areas with low/unsteady internet connectivity.

### Live Editor
- **Description**: Text editor built with Blazor, instead of a wrapper around existing JS implementations.

### Workflow
- **Description**: Support for workflow integrations (e.g. trigger actions after certain rules are met, approve content for publishing, etc.).

### Landing Page/Contact Forms
- **Description**: One-click landing page and contact forms (e.g. TypeForm).

### Integrations (Payments, Email, SMS, etc.)
- **Description**: First-party integration for payments, sms, etc.

### Themes Marketplace
- **Description**: Support for a theme marketplace.

### Plugin Marketplace
- **Description**: Share your plugins with others and find others' plugins to add to your CMS.

### Figma to Blazor
- **Description**: Convert Figma files to Blazor.

### Webhooks
- **Description**: Enable CMS webhooks to be notified of new content, analytics, comments, etc.

### Experimentation
- **Description**: Support experimentation, A/B testing, and feature flags all within the Blazor CMS.