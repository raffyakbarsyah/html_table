# 🌍 Planet Data Table Challenge

This project is a solution to the [Structuring a Planet Data Table](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data) challenge from MDN Web Docs.

## 📘 Overview

In this challenge, the goal is to convert raw planetary data into a readable and accessible HTML table. The context is educational — to help students easily explore and understand the key facts about the planets in our solar system.

## 🗂️ Files Included

- `blank-template.html` 
- `minimal-table.css`
- `planets-data.txt` 
- `index.html` 

## ✅ Completed Tasks

- [x] Created an HTML `<table>` to display planet data
- [x] Added a `<caption>` describing the purpose of the table
- [x] Added a header row with column titles
- [x] Properly used `<th>` for row and column headers
- [x] Used `rowspan` and `colspan` to logically group rows (e.g. Terrestrial vs. Jovian planets)
- [x] Ensured semantic use of header cells for accessibility (using `scope` where appropriate)
- [x] Applied a black border to the planet name column.
- [x] Did **not** use `<thead>` and `<tbody>` — structure kept simple and readable

## 💡 Key Notes

- The first cell in the header row is left **blank** and spans **two columns**
- Group row headers like “Jovian planets” use `rowspan` to span vertically
- Planet names are placed in the first column using `<th scope="row">`
- Accessibility is supported through appropriate use of `scope` attributes

## 🔗 References

- [MDN Challenge Description](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data)

---

✅ This project was built as part of HTML learning and practice — feel free to use it for study or inspiration!
