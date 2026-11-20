# Bug Report Examples

![Bugs](https://img.shields.io/badge/Bug%20Reports-20-red) ![Tool](https://img.shields.io/badge/Tracking-Jira%20style-blue) ![Status](https://img.shields.io/badge/Project-Demo-orange)

Sample bug reports written by **Aadesh Awasthi** (QA Engineer) to show how I document and report defects.

> **Note:** This is a **demo project**. All bugs were written against [SauceDemo](https://www.saucedemo.com), a public practice website by Sauce Labs. The site provides special test users (`problem_user`, `error_user`, `visual_user`, `performance_glitch_user`) that contain intentional defects for testers to practise on. No company or client data is used. Behaviour of the demo site may change over time.

## What a good bug report contains

1. A clear title that says what is wrong and where
2. Exact steps to reproduce
3. Expected result and actual result
4. Severity and priority
5. Environment details and evidence (screenshot or video)

## Bug Summary by Severity

| Severity | Count |
|---|---|
| Blocker | 1 |
| Critical | 4 |
| Major | 8 |
| Minor | 7 |
| **Total** | **20** |

## Bug List

| Bug ID | Title | Module | Severity | Priority |
|---|---|---|---|---|
| [BUG-001](bug-reports/BUG-001.md) | All products display the same image on Products page | Product Listing | Major | High |
| [BUG-002](bug-reports/BUG-002.md) | Product sort dropdown does not change the product order | Product Listing | Major | High |
| [BUG-003](bug-reports/BUG-003.md) | Typing in Last Name field changes the First Name field on checkout | Checkout | Critical | High |
| [BUG-004](bug-reports/BUG-004.md) | "Add to cart" does not work for some products | Shopping Cart | Critical | High |
| [BUG-005](bug-reports/BUG-005.md) | "Remove" button on Products page does not remove the item | Shopping Cart | Major | High |
| [BUG-006](bug-reports/BUG-006.md) | Clicking a product name opens a different product detail page | Product Details | Major | Medium |
| [BUG-007](bug-reports/BUG-007.md) | "About" menu link opens a 404 error page | Navigation Menu | Minor | Medium |
| [BUG-008](bug-reports/BUG-008.md) | Login takes around 5 seconds for performance_glitch_user | Login | Major | Medium |
| [BUG-009](bug-reports/BUG-009.md) | Sorting shows a "Sorting is broken!" alert | Product Listing | Major | High |
| [BUG-010](bug-reports/BUG-010.md) | "Finish" button does not complete the order | Checkout | Blocker | High |
| [BUG-011](bug-reports/BUG-011.md) | Cart icon is misaligned in the header | Header | Minor | Low |
| [BUG-012](bug-reports/BUG-012.md) | Product prices change on every page load | Product Listing | Critical | High |
| [BUG-013](bug-reports/BUG-013.md) | Checkout button is misaligned on Cart page | Shopping Cart | Minor | Low |
| [BUG-014](bug-reports/BUG-014.md) | User can proceed to checkout with an empty cart | Checkout | Major | Medium |
| [BUG-015](bug-reports/BUG-015.md) | Postal Code field accepts alphabets and special characters | Checkout | Minor | Medium |
| [BUG-016](bug-reports/BUG-016.md) | First Name and Last Name accept numbers and special characters | Checkout | Minor | Low |
| [BUG-017](bug-reports/BUG-017.md) | "Reset App State" does not reset the "Remove" buttons | Navigation Menu | Minor | Medium |
| [BUG-018](bug-reports/BUG-018.md) | Selected sort option is lost after returning from product detail page | Product Listing | Minor | Low |
| [BUG-019](bug-reports/BUG-019.md) | Order confirmation page can be opened directly by URL | Checkout | Major | Medium |
| [BUG-020](bug-reports/BUG-020.md) | Cart items of one user are visible to another user on the same browser | Shopping Cart | Critical | High |

## Folder Structure

```
Bug-Report-Examples
├── README.md
├── Bug_Summary.csv            (all bugs in one sheet, opens in Excel)
├── bug-reports                (one file per bug)
├── screenshots
└── templates
    └── Bug_Report_Template.md
```

## Related Repositories

- [Test-Case-Documentation](https://github.com/AadeshAwasthi/Test-Case-Documentation)
- [Manual-Testing-Portfolio](https://github.com/AadeshAwasthi/Manual-Testing-Portfolio)
