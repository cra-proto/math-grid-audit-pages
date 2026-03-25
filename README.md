# math-grid-audit-pages

*description of the COP*

**COP timeframe** 2026-03-11 - 2026-06-17

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/math-grid-audit-pages](https://cra-proto.github.io/math-grid-audit-pages)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-25

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Payroll)
    node4(T4127 Payroll Deductions Formulas)
    node5(Current year T4127 Payroll deductions formulas)
    node6(T4127-JAN Payroll Deductions Formulas - 122nd Edition - Effective January 1, 2026)
    node7(Payroll Deductions Formulas - 122nd Edition Effective January 1, 2026)
    node1 --> node2
    node2 --> node3
    node3 --x node4
    node4 --> node5
    node5 --> node6
    node6 --> node7
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/payroll/t4127-payroll-deductions-formulas-computer-programs.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/forms-publications/payroll/t4127-payroll-deductions-formulas.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/forms-publications/payroll/t4127-payroll-deductions-formulas/t4127-jan.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/forms-publications/payroll/t4127-payroll-deductions-formulas/t4127-jan/t4127-jan-payroll-deductions-formulas-computer-programs.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node7 inscope
```
