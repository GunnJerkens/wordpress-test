# Development Test

Assemble a small WordPress site from scratch. DO NOT use any existing themes or plugins, the goal of this exercise is to test your ability at creating a super basic theme.

The expected time for this exercise is 2–4 hours.

**Use _admin/admin_ as the username/password, so we can log in to the test site you create.**

## Requirements

All content must be editable in WordPress.

Try to follow best practices by adding the proper doctype, meta tags, making sure the website is responsive and mobile-optimized, and using semantic HTML where appropriate.

- Home page
    - Global navigation menu which collapses and hides on screens narrower than 768px and shows a menu toggle button that shows/hides the navigation when clicked. Page links in the menu can be empty but for a title.
        - About
        - Products
        - Contact
    - Masthead image, full page width
    - 3 unique blocks of text
    - Newsletter ajax signup form
      - Uses admin-ajax.php
      - One text input: email
      - One button: signup
      - Validate email structure using a regex pattern (just the structure [something]@[something].[something])
      - Report email validation back to the page
    - Basic footer with list of links that open a modal with different dummy copy for each. Include a background overlay so the page content is covered/dimmed and a close button to dismiss the modal. Links in the footer can be empty but for a title.
        - Privacy Policy
        - Terms of Use

### Extra Credit

Create 3 blog posts with masthead image and dummy content and create at least two categories and assign to multiple posts. Create a basic main blog page template that shows all of the posts as previews in columns (image thumbnail, title, date, categories, excerpt and Read More link to the post page. Create a basic single blog post template that shows full-width image, title, date, categories and post content.

## Delivery

A .zip archive containing:

- your site's entire web root including WordPress and uploads.
- a .sql file of the database
