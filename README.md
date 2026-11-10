# SkyGrid-Energy
# SkyGrid Energy Solutions Website

**Module 02 Final Project – HTML Foundations**

**Tagline:** Intelligent Green Energy Solutions

## 1. Project Overview

SkyGrid Energy Solutions is a multi-page business website developed as part of the Module 02 HTML Foundations Final Project.

The website represents a renewable energy solutions company focused on providing reliable, affordable, and sustainable solar energy solutions for residential, commercial, and small industrial customers.

The project demonstrates the practical application of core HTML concepts, including semantic document structure, accessible forms, navigation, hyperlinks, images, tables, and relative file paths.

The website was intentionally developed using **HTML5 only**, without CSS, JavaScript, Bootstrap, Tailwind, React, or other visual frameworks, in accordance with the project requirements.

## 2. Project Objectives

The objectives of this project are to:

- Demonstrate a practical understanding of HTML5 fundamentals.
- Build a complete multi-page website with consistent navigation.
- Apply semantic HTML elements to improve document structure and accessibility.
- Implement working internal, external, email, fragment, and relative links.
- Demonstrate correct handling of images and cross-folder file paths.
- Create accessible HTML forms using labels, fieldsets, legends, and native input validation.
- Present structured information using HTML tables and lists.
- Validate the website using the W3C Nu HTML Checker.

## 3. Website Pages

The website contains six HTML pages:

| Page | Filename | Description |
|---|---|---|
| Home | `index.html` | Introduces the company and its energy solutions. |
| About | `about.html` | Presents the company's identity, mission, vision, and values. |
| Services | `services.html` | Describes solar services, products, and solution packages. |
| Blog | `blog.html` | Provides educational articles about solar energy and renewable technologies. |
| Contact | `contact.html` | Provides contact information and a customer enquiry form. |
| Application | `pages/application.html` | Contains a customer solar energy application form. |

## 4. Project Folder Structure

The project is organised into the following directories and files:

```text
skygrid-energy-solutions-website/
│
├── index.html
├── about.html
├── services.html
├── blog.html
├── contact.html
│
├── pages/
│   └── application.html
│
├── images/
│   ├── skygrid-logo.svg
│   ├── solar-home.svg
│   ├── solar-commercial.svg
│   ├── solar-installation.svg
│   ├── solar-maintenance.svg
│   └── solar-battery.svg
│
├── media/
│   └── solar-maintenance-checklist.txt
│
├── screenshots/
│   ├── home.png
│   ├── about.png
│   ├── services.png
│   ├── blog.png
│   ├── contact.png
│   └── application.png
│
├── validation/
│   └── validation-report.md
│
└── README.md
```

## 5. HTML Features Implemented

The project demonstrates the following HTML features:

### Document Structure and Semantic HTML

- HTML5 document declaration (`<!DOCTYPE html>`).
- Language declaration using the `lang` attribute.
- Character encoding and viewport metadata.
- Meaningful page titles and descriptions.
- Semantic elements such as:
  - `<header>`
  - `<nav>`
  - `<main>`
  - `<section>`
  - `<article>`
  - `<aside>`
  - `<footer>`
  - `<address>`

### Text Formatting and Content Organisation

- Paragraphs using `<p>`.
- Important content using `<strong>`.
- Emphasised text using `<em>`.
- Ordered lists using `<ol>`.
- Unordered lists using `<ul>`.
- Description lists using `<dl>`, `<dt>`, and `<dd>`.

### Hyperlinks and Navigation

- Internal page navigation.
- External website links.
- Relative links between project files.
- Parent-directory navigation using `../`.
- Child-directory navigation using folder paths.
- Email links using `mailto:`.
- Fragment links using element IDs.

### Images and Media

- SVG images.(only one was included for illustrative purpose)
- Descriptive alternative text using the `alt` attribute.
- Image presentation using `<figure>` and `<figcaption>`.
- Organised image and media directories.

### HTML Tables

The services page contains a structured data table demonstrating:

- `<table>`
- `<caption>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`
- Appropriate table header scope attributes.

### HTML Forms

The contact and application pages demonstrate native HTML form elements, including:

- Text input.
- Email input.
- Telephone input.
- Number input.
- Select dropdowns.
- Radio buttons.
- Checkboxes.
- Textareas.
- Labels.
- Fieldsets and legends.
- Required field constraints.
- Minimum input length constraints.
- Submit and reset buttons.

### Accessibility

Accessibility considerations include:

- Semantic HTML landmarks.
- Logical heading hierarchy.
- Descriptive link text.
- Alternative text for images.
- Explicit form labels.
- Native keyboard-accessible controls.
- Meaningful document titles.

## 6. Technologies Used

|         Technology      |               Purpose               |
|-------------------------|-------------------------------------|
| HTML5                   | Website structure and content       |
| SVG                     | Scalable image assets               |
| Markdown                | Project documentation               |
| W3C Nu HTML Checker     | HTML validation                     |
| Visual Studio Code      | Development environment             |
| Google Chrome / Firefox | Browser testing                     |
| Git and GitHub          | Version control and project hosting |

**Development restriction:** No CSS, JavaScript, Bootstrap, Tailwind, React, or other frontend frameworks were used.

## 7. What I Learned

Through this project, I developed practical knowledge of:

1. Creating complete HTML5 documents.
2. Structuring websites using semantic HTML elements.
3. Building navigation across multiple pages.
4. Understanding relative paths and navigating between parent and child directories.
5. Embedding images and writing meaningful alternative text.
6. Creating structured HTML tables.
7. Building forms with different input types and native validation attributes.
8. Applying basic accessibility principles.
9. Organising a website project into meaningful folders and files.
10. Validating HTML documents using the W3C Nu HTML Checker.

## 8. Challenges Encountered

Some of the practical challenges encountered during development included:

- Understanding relative file paths when linking pages located in different directories.
- Ensuring consistent navigation across all website pages.
- Correctly referencing images stored in separate folders.
- Structuring forms with appropriate labels, fieldsets, and input constraints.
- Maintaining semantic HTML structure without relying on CSS or JavaScript.
- Checking and correcting HTML validation issues.

These challenges provided practical experience in debugging, file organisation, accessibility, and standards-compliant HTML development.

## 9. Resources and Media Attributions

The following resources are useful references for the HTML concepts and renewable energy information presented in this project:

### HTML Documentation

- [MDN Web Docs – HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3C HTML Specifications](https://html.spec.whatwg.org/)
- [W3C Nu HTML Checker](https://validator.w3.org/nu/)

### Renewable Energy References

- [International Energy Agency (IEA)](https://www.iea.org/)
- [International Renewable Energy Agency (IRENA)](https://www.irena.org/)
- [United Nations Sustainable Development Goal 7](https://sdgs.un.org/goals/goal7)
- [U.S. Department of Energy – Solar Energy](https://www.energy.gov/eere/solar/solar-energy-technologies-office)

### Media Attribution

The project uses SVG image assets stored in the `images/` directory.

For each asset, its source, author, licence, or creation method should be documented here before submission.

- Company logo: [Insert source or state that it is an original project design.]
- Solar home illustration: [Insert source and licence.]
- Commercial solar illustration: [Insert source and licence.]
- Solar installation illustration: [Insert source and licence.]
- Solar maintenance illustration: [Insert source and licence.]
- Solar battery illustration: [Insert source and licence.]

No third-party media should be presented as original work. All externally sourced assets must comply with their respective licences and attribution requirements.

## 10. HTML Validation and Testing

Each HTML document is intended to be checked using the official W3C Nu HTML Checker.

Validation checklist:

- [ ] `index.html`
- [ ] `about.html`
- [ ] `services.html`
- [ ] `blog.html`
- [ ] `contact.html`
- [ ] `pages/application.html`

Validation results and supporting evidence should be documented in:

`validation/validation-report.md`

Browser testing should also confirm:

- All six pages open correctly.
- Navigation links work.
- Relative paths resolve correctly.
- Images load successfully.
- Forms display correctly.
- Links and fragment navigation work as expected.

## 11. Project Limitations

This project is an HTML-only demonstration developed for educational purposes.

The forms demonstrate frontend structure and native browser validation. They are not connected to a backend service or database and therefore do not currently store or process customer applications.

The website also does not implement styling, responsive layouts, authentication, payment processing, or live solar system monitoring.

These capabilities would require additional technologies beyond the scope of this HTML Foundations assignment.

## 12. Submission Deliverables

The final submission should include:

- Complete project source code.
- All required image and media assets.
- Public GitHub repository link.
- Browser screenshots of all six pages.
- W3C validation evidence for every HTML document.
- Completed project documentation.

## 13. Conclusion

The SkyGrid Energy Solutions website demonstrates the practical application of HTML5 fundamentals through the development of a structured, accessible, and multi-page business website.

The project provides a foundation for future development into a fully functional renewable energy business platform while demonstrating an understanding of the importance of semantic structure, accessibility, file organisation, and web standards.

---

**Project:** SkyGrid Energy Solutions Website  
**Programme:** Module 02 – HTML Foundations  
**Project Type:** Final Project  
**Primary Technology:** HTML5  
**Tagline:** Intelligent Green Energy Solutions
