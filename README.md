# Development Test

Assemble a small Wordpress site from scratch. DO NOT use any existing themes or plugins, the goal of this exercise is to test your ability at creating a super basic theme.

The expected time for this exercise is 30-60 minutes.

**Use _admin/admin_ as the username/password, so we can log in to the test site you create.**

## Requirements

All content must be editable in WordPress.

- Home page
    - Global menu which collapses on screens narrower than 768px. Page links in the menu can be empty but for a title.
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

## Delivery

A .zip archive containing:

- your site's entire web root including WordPress and uploads.
- a .sql file of the database
