# Horizeon

**Description**:
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

**Define**
*GIVEN a webpage meets accessibility standards
*WHEN I view the source code
*THEN I find semantic HTML elements
*WHEN I view the structure of the HTML elements
*THEN I find that the elements follow a logical structure independent of styling and positioning
*WHEN I view the icon and image elements
*THEN I find accessible alt attributes
*WHEN I view the heading attributes
*THEN they fall in sequential order
*WHEN I view the title element
*THEN I find a concise, descriptive title

**Mock-Up**

The following image shows the web application's appearance and functionality:


> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.

## Changes made:

1. `(HTML)` Renamed div tags to make them more legible.
   ```
   a. assigned Header, Body, and Footer
   b. assigned sections within Header (nav) and Body (article, aside)
   c. added classes and ids to tags to help consolidate CSS elements

   ```
2. `(CSS)` Cleaned up redundancy
   ```
   a. Consolidated redundant selectors
    -.header div ul {} and .header div ul li {}
    -benefit-lead, benefit-brand, benefit-cost
    -benefit h3
    -.online-reputation-management, .social-media-marketing, .search-engine-optimization
    -corresponding img selectors
    -h2 within <aside>
   b. changed class/id/names for selectors to match changes in HTML
   ```

## Review



* The URL of the deployed application.
https://hayden1773.github.io/Horizeon/

* The URL of the GitHub repository, with a unique name and a README that describes the project.
https://github.com/hayden1773/Horizeon