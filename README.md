# Pattern Requirements

This document will describe the structure of each pattern and its behaviour under various screen sizes.

---

## The Grid System

**Description**

- 12 columns
- Responsive, fluid
- Columns will be wrapped in a container .row
- Each column will have the class of .col-$
- Also create a .container class that wraps all content and centers it on the page. The container must be fluid in width.

**Responsive Behaviour**

- In smaller screen sizes (<1024px) the columns will have their gutter width halved
- In mobile sizes (<768px) all columns will get a 100% width