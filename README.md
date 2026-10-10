# Budget Tracker - Week 2 Project

**Student / Project Name:** [Your Name / Project Title]  
**Due Date:** End of Week 2 (Friday, 17:00 EAT)  
**Submission Repository:** [Insert GitHub Repository Link Here]

---

## Project Overview
This project builds directly upon the Week 1 HTML and CSS foundation of the **Budget Tracker**. It incorporates semantic data tables, a structured and interactive form, multimedia elements, collapsible sections, and advanced CSS selectors designed for future JavaScript integration.

---

## Grading Rubric Self-Assessment / Checklist

| Requirement | Description & Implementation Details | Status |
| :--- | :--- | :--- |
| **Correct HTML Table Structure (25%)** | Used `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` without structural errors. Includes 5+ hardcoded expense rows (Name, Amount, Category, Date) and styled with `border-collapse: collapse`, cell padding, and zebra striping (`tr:nth-child(even)`). | **Completed** |
| **Working Form Upgrade (30%)** | Upgraded to a proper `<form>` wrapper containing a `<select>` dropdown with 5 required options (*Food, Transport, Rent, Entertainment, Other*), a `<button type="button">` labeled "Add Expense", and matching `id` attributes on all inputs (`id="expense-name"`, `id="expense-amount"`, `id="expense-category"`). | **Completed** |
| **Multimedia Elements (15%)** | Included an `<img>` tag for the project logo with correct `src`, `alt`, and `width` attributes, alongside an embedded YouTube budgeting guide video via an `<iframe>` with proper attributes (`width`, `height`, `title`). | **Completed** |
| **Advanced CSS Selectors (30%)** | Implemented multiple advanced selectors across the stylesheet: <br>1. Descendant selector (e.g., `.expenses-section td`)<br>2. Direct child selector (e.g., `.add-expense-section > form`)<br>3. Positional pseudo-class (`tr:nth-child(even)` & `tr:hover`)<br>4. Negation pseudo-class (`input:not([type="submit"])`)<br>5. Focus state (`input:focus`) and pointer enhancements (`cursor: pointer`). | **Completed** |

---

## File Structure & Navigation

```text
budget-tracker/
├── index.html    # Contains semantic HTML5 structure, expense table, form, and embedded media
├── style.css     # Contains advanced CSS selectors, layout styling, table borders, and hover states
└── README.md     # Project documentation and submission details
