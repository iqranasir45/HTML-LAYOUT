# Explaination of Manual coding

## Ecommerce Product Page:

### Sturcture of the Page:
The page is divided into two main sections:

1. **Header** — Further divided into 3 sections, contains the brand logo, search bar, and navigation links.
2. **Main Content** — Split into two columns:
   - **Left Column:** contains the Product Image gallery which include main image of product (watch) + thumbnail gallery of products
   - **Right Column:** Contains the Product Detail which include Product title, brand, pricing, description, rating, quantity selector, add-to-bag button, and promo banner

### Decisions:

Used Semantic tags for better understanding of sections.

| Element | Reason |
|---|---|
| `<header>` / `<main>` | Semantic elements for better understanding of code structure, improving SEO, and website accessibility |
| `<a>` | used to make the logo a clickable hyperlink that returns the users to homepage. It ensures the users accessability and improves the SEO |
| `<search>` | Improves the accessability for screen readers and helps the search engines to index the site accurately|
| `<nav>` | used for navigation links, helps browsers and screen readers to easily navigate the main menu |
| `<section>`| used to divide the related main content into groups, it makes code structure clear for search engines, browsers, and screen readers |

## Survey Form Page:

### Sturcture of the Page:
1. **Main** — The page contains main content section act as a full page wrapper. Which has further two layers.
- **DIV outer container:** contains the main heading of form page, and acts as a main wrapper for form.  
- **DIV inner container:** contains the subtitle and all form fields.

### Decisions:

| Element | Reason |
|---|---|
| `<main>` | Semantic element for better understanding of code structure, improving SEO, and website accessibility |
| `<div class="outer-container">`/`<div class="inner-container">` | used to divide page content according to the UI layout |
| `<div>` | used div tag to make a separate section for each field of form instead of <br> tag, because <br> just break the line, not separate the sections |
| `for` / `id` on every label | Links label to its input for accessibility and clickable labels |
| `<center>` | used to center the form content on the page (just for the time being, to fulfil the UI layout requirements, because we are not using any CSS decoration yet) |


## Video Recording Link:
I have record the video on loom and I'm goinbg to directly share the loom link:

https://www.loom.com/share/fea86a4ff9a4444c864186e0e3996be0