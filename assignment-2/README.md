# Assignment 2: The Ultimate Form

## Overview
This repository contains a single-page HTML form built for a Student Internship application. It demonstrates comprehensive usage of HTML5 form controls, linked labels, validation attributes, and semantic field grouping.

## Form Elements & Requirements Implemented
- **Text Inputs:** `text`, `email`, `password`, `tel`, `url`, `number`
- **Choice Controls:** `radio` (Gender selection), `checkbox` (Skills selection), `select` dropdown (Course choices), and `datalist` (City auto-suggestions)
- **Special Inputs:** `date` (Available from), `time` (Interview time slot), `file` (Resume upload), `range` (Stipend slider), `color` (Colour picker), `textarea` (Open query)
- **Accessibility:** Every form control is explicitly bound to a `<label>` element using matching `for` and `id` attributes.
- **Grouping:** Logically organized into three distinct sections using `<fieldset>` and `<legend>`.
- **Form Validation:** Configured with `required`, `placeholder`, `min`, `max`, `minlength`, and regex `pattern` validation rules.
- **Action Buttons:** Native `<button type="submit">` and `<button type="reset">`.

## Folder Location
```text
web-development/
    └── assignment-2/
        ├── index.html
        └── README.md