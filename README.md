# Generates JPEG email signatures from HTML form submission
Simple PHP APP that generates downloadable JPEG email signatures (images).
Images will have embedded personal data from HTML Webform submissions

# How it works:

- Step 1: User completes HTML form `index.html` (Name, Email, Role, Phone)
- Step 2: User clicks "Download Email Signature"
- Step 3: Webform submits form data via POST to `generate-signature.php`
- Step 4: PHP file will write user submitted data onto a blank image with company logo
- Step 5: Email signature `.jpeg` inside a .ZIP archive will be downloaded

Application does not require build or compile and will work 
on any server with PHP. Application has no dependencies and 
is written in procedural PHP
