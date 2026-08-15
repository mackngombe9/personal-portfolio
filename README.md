# HTML Website Development Assignment

## Student Information

**Student Name:** Mack Ngombe\
**Student ID:** [2504325487]\
**GitHub Repository:** [https://github.com/mackngombe9/personal-portfolio]

---

# Question 2: HTML Elements

## 2.1 Which 5 elements did you find most challenging to implement and why?

### 1. `<table>`

The `<table>` element was challenging because it required me to understand how rows, columns, headings, and different sections of a table work together. I used `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, and `<td>` to organize my skills information.

### 2. `<form>`

The `<form>` element was challenging because several elements have to work together correctly. I used `<label>`, `<input>`, `<textarea>`, `<fieldset>`, `<legend>`, and `<button>` to create the contact form.

### 3. `<fieldset>`

The `<fieldset>` element was challenging because I had to understand how it groups related form controls. I used it to keep the contact form organized.

### 4. `<details>`

The `<details>` element was challenging because it creates expandable content. I used it to allow visitors to reveal additional information about my future goals.

### 5. `<figure>`

The `<figure>` element was challenging because it is normally used together with an image and a caption. I used `<figure>`, `<img>`, and `<figcaption>` together to present an image and its description.

---

## 2.2 How did you use semantic elements like `<section>`, `<article>`, `<header>`, and `<footer>` to structure your content?

I used semantic HTML elements to give the website a clear and meaningful structure.

The `<header>` contains the website title, introduction and navigation menu.

The `<nav>` contains links that allow visitors to move between the different sections.

The `<main>` contains the primary content of the website.

The `<section>` element divides the main content into areas such as About Me, Interests, Skills, Goals and Contact.

The `<article>` element is used for individual pieces of information within the sections, such as my anime interests, gaming interests and career goals.

The `<aside>` contains additional information related to the website.

The `<footer>` contains the copyright information and a link back to the top of the page.

Using these semantic elements makes the structure easier to understand and maintain.

---

## 2.3 Which element was most useful for organizing your layout and why?

The `<section>` element was the most useful for organizing my layout.

I used separate sections for About Me, Interests, Skills, Goals and Contact. This allowed me to divide the website into clear areas.

It also made navigation easier because each section has a unique `id` that can be linked to from the navigation menu.

---

# Question 3: HTML Attributes

## 3.1 Which 3 attributes were essential for making your website functional?

### 1. `href`

The `href` attribute was essential because I used it to create navigation links. It allows users to move to different sections of the website.

### 2. `id`

The `id` attribute was essential because it gives important sections unique identifiers. The navigation links use these IDs to take users directly to specific sections.

### 3. `src`

The `src` attribute was essential for displaying the image on the website. It specifies the location of the image that the browser should load.

---

## 3.2 How did you use the `class` and `id` attributes differently?

The `id` attribute is used to uniquely identify a specific element on the webpage.

For example:

```html
<section id="about">
```

The `about` ID identifies the About Me section and allows the navigation menu to link directly to it.

The `class` attribute is normally used to group multiple elements that share the same styling or characteristics.

For this HTML-only project, I mainly used `id` attributes because they were useful for navigation between sections.

---

## 3.3 Which attribute helped improve user experience the most and why?

The `alt` attribute helped improve the user experience because it provides alternative text for an image.

If the image cannot be displayed, the alternative text can still explain what the image represents.

It also improves accessibility for users who use screen readers.

The `title` attribute also helped by providing additional information when users interact with navigation links.

---

# Question 4: Development Process

## 4.1 How did you plan your website structure before coding?

Before coding, I first decided what information I wanted my personal website to contain.

I divided the website into several sections:

1. Header and navigation
2. About Me
3. Interests
4. Skills
5. Future Goals
6. Contact
7. Footer

After deciding on the sections, I selected suitable HTML elements for each part.

I then created the basic HTML document structure and added each section one at a time.

---

## 4.2 What was your approach to testing and debugging your HTML?

I tested the website by opening the HTML file in a web browser.

I checked whether:

- The website loaded correctly.
- The navigation links worked.
- The image displayed correctly.
- The form appeared correctly.
- The sections were properly organized.
- The text appeared in the correct places.

When I found errors, I checked my opening and closing tags, indentation, nesting and attributes.

I corrected the errors and then opened the website again to test it.

---

## 4.3 What challenges did you face and how did you overcome them?

One challenge was meeting the requirement of using at least 25 different HTML elements.

I overcame this by selecting different elements for different purposes instead of repeatedly using the same elements.

Another challenge was meeting the requirement of using at least 15 different attributes.

I solved this by using attributes such as `id`, `href`, `title`, `src`, `alt`, `width`, `height`, `action`, `method`, `for`, `type`, `name`, `placeholder`, `rows`, and `cols`.

Another challenge was creating a semantic structure. I overcame this by using elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.

---

# Question 5: Git & GitHub Implementation

## 5.1 What Git commands did you use during development?

The Git commands I used during development were:

```bash
git init
git status
git add .
git commit -m "Initial website structure"
git branch -M main
git remote add origin [Repository URL]
git push -u origin main
```

`git init` was used to initialize the project as a Git repository.

`git status` was used to check the status of the files.

`git add .` was used to stage the files.

`git commit` was used to save changes to the project.

`git branch -M main` was used to set the main branch.

`git remote add origin` connected the local project to the GitHub repository.

`git push` uploaded the project files to GitHub.

---

## 5.2 How many commits did you make and what was your commit message strategy?

I made **5 commits** during the development process.

My commit messages were:

```text
Initial website structure
Added personal information
Added interests and skills sections
Added goals and contact form
Updated README documentation
```

I used short and descriptive commit messages so that each message clearly explained what was changed in that stage of development.

This makes the development history easier to understand.

---

## 5.3 Why is version control important for web development projects?

Version control is important because it keeps track of changes made to a project.

Git allows developers to:

- Save different versions of their work.
- Track changes.
- Recover previous versions.
- Work safely on projects.
- Collaborate with other developers.
- Maintain a history of the project.

GitHub also provides an online platform where the project can be stored, shared and managed.

---

# Question 6: Code Quality & Best Practices

## 6.1 How did you ensure your HTML was valid and error-free?

I checked my HTML by opening it in a web browser and testing the different parts of the website.

I checked that:

- The correct `<!DOCTYPE html>` declaration was used.
- HTML elements were properly opened and closed.
- Elements were correctly nested.
- Attributes were placed correctly.
- Images had alternative text.
- Navigation links pointed to the correct sections.
- The website loaded correctly in the browser.

I also reviewed the code to find missing tags and incorrect nesting.

---

## 6.2 What best practices did you follow for writing clean, readable code?

I followed several HTML best practices, including:

- Using semantic HTML elements.
- Indenting nested elements.
- Using meaningful IDs.
- Using descriptive headings.
- Adding alternative text to images.
- Organizing related content together.
- Keeping the HTML structure clear.
- Using lowercase HTML tags and attributes.
- Keeping the code properly formatted.
- Using comments where necessary.

These practices make the code easier to read, understand and maintain.

---

## 6.3 How would you improve your website if you had more time?

If I had more time, I would improve the website by adding CSS to make it more professional and visually appealing.

I would also add JavaScript to make the website more interactive.

Other improvements I would make include:

- Adding a professional profile image.
- Creating a projects section.
- Adding links to my social media accounts.
- Adding animations.
- Making the contact form fully functional.
- Improving the website's mobile responsiveness.
- Adding more projects to demonstrate my programming skills.
- Improving the overall navigation and design.

---

# Technical Requirements Chechlist
- [X] 25+ different html elements used.
- [x] 15+ different html attributes used.
- [x] semantic html structure implemented.
- [x] website works in a web browser.
- [x] github repository with all code.
- [x] README.md file with documentation.
- [x] instructor added as collaborator.
- [x] instructor followed on github.
- [x] google classroom submission completed.
---

# Submission Information

**Student Name:** Mack Ngombe

**Student ID:** [2504325487]

**GitHub Repository:** [https://github.com/mackngombe9/personal-portfolio]
