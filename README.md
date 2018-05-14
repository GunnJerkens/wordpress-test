# Development Test

Assemble a small Wordpress site from scratch. DO NOT use any existing themes or plugins, the goal of this exercise is to test your ability at creating a super basic theme. 

The expected time for this exercise is 30-60 minutes.

## Requirements

All content must be editable in WordPress.

- home page
    - global menu which collapses on screens narrower than 768px. Pages in the menu can be empty but for a title.
        - About
        - Products
        - Contact
    - masthead image, full page width
    - 3 unique blocks of text
    - newsletter ajax signup form
      - uses admin-ajax.php
      - one text input: email
      - one button: signup
      - validate email structure using a regex pattern (just the structure [something]@[something].[something])
      - report email validation back to the page

## Delivery

A .zip archive containing:

- your site's entire web root including WordPress and uploads.
- a .sql file of the database
