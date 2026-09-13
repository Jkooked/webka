# Assignment 1 — Front-End Development

**Student:** Abitay Ainaz
**Group:** IT-2502
**Course:** Web Technologies — (Front-End Development)
**Date:** 13.09.2026

---

## Objective

The goal of this assignment is to build a personal webpage from scratch using
HTML and CSS. By completing this project, I learned how to:

- Understand the structure and purpose of HTML.
- Use basic and intermediate HTML tags (headings, paragraphs, lists, images,
  links, tables, buttons, and forms).
- Apply CSS styling using inline, internal, and external methods.
- Use CSS selectors (element, class, and ID) and the box model.
- Structure a webpage with `<div>` sections and publish it online via GitHub Pages.

---

## Tools Used

- **VS Code** — code editor
- **Google Chrome** — browser for testing
- **GitHub** — version control and hosting
- **GitHub Pages** — for publishing the final website

---

##  Project Structure

Part 1 — Introduction to HTML

Step 0: HTML Boilerplate

Created index.html with the basic HTML5 structure: <!DOCTYPE html>, <html lang="en">, <head>, <title>My First Webpage</title>, and <body>.

Screenshot — Boilerplate & Page Title:

<img width="599" height="110" alt="image" src="https://github.com/user-attachments/assets/7281e549-6214-483f-b527-78687ab694bd" />

### Step 1: Text Structure

Used headings to organize content:

h1 — my name: Abitay Ainaz

h2 — my group: IT-2502

h3 — short bio: age and birthday

p — a paragraph about my interests (Kazakh stand-up comedy, K-pop)

Screenshot — Headings & Paragraph:

<img width="599" height="97" alt="image" src="https://github.com/user-attachments/assets/acc1491d-8aad-4e0b-aa5d-5f6bafcfa14c" />

### Step 2: HTML Lists

Ordered list ol — hobbies: video games, reading manhwas, baking sweets.

Unordered list ul — favorite colors: blue, white, black.

Screenshot — Ordered & Unordered Lists:

<img width="599" height="213" alt="image" src="https://github.com/user-attachments/assets/6d43af5f-732d-4ac0-8048-503a27cca7a5" />

### Step 3: Images and Links
Inserted my photo using img to my favorite manga site, a TV series, and a music video.

Screenshot — Image & Links:

<img width="920" height="106" alt="image" src="https://github.com/user-attachments/assets/c46b7051-fcc0-475a-b406-c7e43491611f" />

### Step 4: HTML Buttons
Added a simple button with <button type="button">Click Me!</button> (no functionality yet).

Screenshot — Button:

<img width="319" height="48" alt="image" src="https://github.com/user-attachments/assets/90eb3ef9-1f17-4cae-acf3-c9ea310a0028" />

### Step 5: Tables
Created an HTML table using a table element with a border attribute set to 1, containing three columns — Subject, Day, and Time — defined with header cells inside the first row.

Each following row represents one class in my weekly schedule, with values placed in data cells:

Calculus 2 — Monday — 3:00 PM to 5:00 PM

Programming — Tuesday — 2:00 PM to 4:00 PM

Web Development — Wednesday — 6:00 PM to 8:00 PM

Purpose: This step showed how to organize structured data in rows and columns, and how header cells differ visually from regular cells.

Screenshot — Weekly Class Schedule Table:

<img width="326" height="415" alt="image" src="https://github.com/user-attachments/assets/296fcccf-ecc8-4e34-9233-8f5954befa5c" />

### Step 6: Two-Column Layout Using a Table (Optional Challenge)
Built a simple two-column page layout using an HTML table with a layout-table class for styling. The table contains one row split into two cells.

The left cell uses a menu-column class and contains a heading with a clipboard emoji, an unordered navigation menu with five items (home, about, services, contact, login), and a short paragraph label indicating that this is the navigation column.

The right cell uses a main-column class and contains a welcome heading and a paragraph describing how the two-column layout is built using a simple HTML table.
Purpose: This step demonstrated how tables were historically used for page layout before CSS Flexbox/Grid existed. It also introduced the class attribute, which will later be targeted by CSS selectors.

Screenshot — Two-Column Layout Table:

<img width="607" height="439" alt="image" src="https://github.com/user-attachments/assets/60d72ffd-b5d5-4892-9594-a4746b9a5cd0" />

### Step 7: Typing Emojis

Added a paragraph about my mood today that includes more than 3 emojis. The emojis are written using HTML entity codes (&#...;) instead of pasted characters:

Emojis used (5 total):

Entity Code	Emoji	Meaning

127752;	🌈	rainbow

128133;	💅	nail polish

9749;	☕	hot coffee

128564;	😴	sleepy face

128200;	📈	chart increasing

Purpose: Learned that emojis are Unicode characters and can be inserted either by pasting the character directly or by using its numeric entity code (&#code;). Also used a class="mood" on the paragraph so it can be styled later in CSS.

Screenshot — Mood Paragraph with Emojis:

<img width="693" height="118" alt="image" src="https://github.com/user-attachments/assets/21a0d8e0-6aec-4f85-b68c-47d7bca6562d" />

### Step 8: HTML Forms

Created a form using the form element with an action attribute pointing to a submit handler and a method attribute set to POST for sending data.

The form contains three input fields, each paired with a label element:

Name — a text input field, marked as required

Email — an email input field, marked as required

Color — a color picker input, marked as required

Each label is linked to its input using matching for and id attributes, so clicking the label focuses the field. Line breaks are used to separate the fields vertically, and the form ends with a submit button labeled "Submit".

Purpose: This step demonstrated how to build an interactive form with different input types, how to connect labels to inputs for accessibility, and how the required attribute prevents submission until all fields are filled in.

Screenshot — HTML Form:

<img width="495" height="218" alt="image" src="https://github.com/user-attachments/assets/130ae4c7-e6a6-4763-9efe-0000433ab18b" />

### Step 9: Intro to CSS
CSS (Cascading Style Sheets) is used to control the appearance of HTML — 

colors, fonts, spacing, and layout. In this step, I started adding CSS to my page to 

make it look cleaner and more personal. I explored three ways to apply CSS: inline

(Step 10), internal (Step 11), and external (Step 12).

### Step 10: Inline CSS

Changed the color of one paragraph using the inline style attribute. The color was set with an RGB value — rgb(255, 0, 162) — which produces a bright hot pink. Inline CSS applies only to that single element.

Screenshot — Inline CSS Paragraph:

<img width="455" height="43" alt="image" src="https://github.com/user-attachments/assets/07320674-c748-4136-8d28-f0df2d11bb1e" />

### Step 11: Internal CSS
Added a <style> block inside the <head> with a pastel pink background, Quicksand font, pink centered headings, rounded paragraph cards, and a pill-shaped button.

Screenshot — Internal CSS:
 <img width="406" height="28" alt="image" src="https://github.com/user-attachments/assets/f44c4360-ceed-4092-9533-a2a8e00ed8b8" />

### Step 12: External CSS

Created a separate file named style.css and linked it to the HTML document 
using a <link> element inside the <head>, with rel="stylesheet" and href="style.css".
All reusable styling rules were moved into this file, keeping the HTML clean and
separating structure from presentation.

Screenshot — External Stylesheet Link:

<img width="406" height="74" alt="image" src="https://github.com/user-attachments/assets/d8a435a2-a179-4237-881a-2cab71293251" />

<img width="489" height="489" alt="image" src="https://github.com/user-attachments/assets/e5e410b2-d86e-4b3c-a25d-bf5e6aba9cef" />

### Step 13: CSS Syntax & Selectors
Practiced three selector types: an element selector (p {}) that styles every paragraph, 
a class selector (.highlight {}) that can be reused on multiple elements, and an ID selector 
(#main-heading {}) that targets only one unique element. Each selector applied a different color
and font to show the difference clearly.
<img width="745" height="86" alt="image" src="https://github.com/user-attachments/assets/891301e3-569d-4d7f-aa34-d3ecfaee22f4" />

<img width="293" height="236" alt="image" src="https://github.com/user-attachments/assets/72270738-b93e-44ea-b3a1-9b9e636d54fe" />

### Step 14: Classes vs. IDs
Created a .highlight class and applied it to multiple paragraphs to show that classes are reusable. 
Created an #main-heading ID and applied it to the main <h1>, since IDs must be unique per page.
This demonstrated the key difference: classes can repeat, IDs cannot.

<img width="615" height="119" alt="image" src="https://github.com/user-attachments/assets/17021303-ee8f-4c5d-acef-738c5456cded" />
<img width="289" height="209" alt="image" src="https://github.com/user-attachments/assets/0148d889-8b30-4641-8c63-d5495605d293" />

### Step 15: Favicons
Added a favicon using link inside the head.
Created a small 32×32 PNG and placed it in the project folder. The icon now appears in the browser 
tab next to the page title.

<img width="237" height="74" alt="image" src="https://github.com/user-attachments/assets/76fe2f8c-5b0f-4af0-9450-ba5670db4997" />

### Step 16: HTML Divs
Grouped the page into three <div> sections — header, main content, and footer — and styled each with
a different background color and padding. This made the page structure clearer and easier to manage.

<img width="647" height="180" alt="image" src="https://github.com/user-attachments/assets/8f53b1fa-c17d-42d7-8de4-57934834cb03" />

<img width="237" height="388" alt="image" src="https://github.com/user-attachments/assets/8abf10f5-59c1-44ab-824a-18398d9f2ed3" />

### Step 17: Box Model
Applied the three layers of the CSS box model — border, margin, and padding — to paragraphs and headings. Each paragraph now has a pink solid border, 12px of inner padding, and 15px of outer margin. Changing the values showed how spacing affects the overall layout.

<img width="269" height="243" alt="image" src="https://github.com/user-attachments/assets/af49086e-6213-4f9d-8ed1-b128b6a186a4" />

### Step 18: CSS Positioning
Created three boxes demonstrating different position values:

static — default flow, unaffected by offsets

relative — shifted 30px right and 10px down from its normal spot

absolute — pinned to the top-right corner of the page

<img width="216" height="434" alt="image" src="https://github.com/user-attachments/assets/5e41f24d-741b-4fd2-ae6e-7d4862055a8b" />

<img width="380" height="73" alt="image" src="https://github.com/user-attachments/assets/eaa53362-766c-4ffd-b7f5-cde645d19f40" />

### Step 19: CSS Sizing

Used four CSS units to size text and images:

px — fixed pixels (h3)

% — relative to the parent (img)

em — relative to the parent's font size (h2)

rem — relative to the root <html> font size (h1)

This showed how relative units scale better than fixed pixels.

<img width="380" height="73" alt="image" src="https://github.com/user-attachments/assets/38b1f296-2ed6-4830-8350-89c5c4ca98df" />

### Step 20: Float and Clear
Created two boxes — one floated left and one floated right — each
taking 45% of the container width. Added a clear: both element after 
them so that the following paragraph is pushed below both boxes instead of 
wrapping awkwardly around them.

<img width="232" height="360" alt="image" src="https://github.com/user-attachments/assets/3d0fa389-13ec-4330-9bca-0df067f63c44" />
<img width="436" height="95" alt="image" src="https://github.com/user-attachments/assets/27b81348-3a86-4df7-a5f2-757e06c84e19" />

# My web-site: https://jkooked.github.io/webka/








