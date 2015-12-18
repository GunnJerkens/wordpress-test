# Development Test

Assemble a small Wordpress site from scratch. Do not use any existing themes or plugins, the test theme should be written by hand to cover all requirements.

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
