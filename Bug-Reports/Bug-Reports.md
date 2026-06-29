# Bug Reports — Demo Web Shop

This document lists confirmed functional/UI bugs found during manual testing. Each entry follows a standard professional bug-reporting format.

> **Note:** Not every observation is a "bug." Issues are classified as a **Bug** only when they break expected functionality. Cosmetic, usability, or communication gaps that don't break functionality are logged separately under [UI/UX Improvements](../Suggestions/UI-UX-Improvements.md).

---

## BUG-001

| Field | Details |
|---|---|
| **Bug ID** | BUG-001 |
| **Title** | Missing "Add to Cart" button and no stock-status message on certain Books listings |
| **Module** | Books |
| **Description** | On the Books category page, certain products (e.g., "Fiction", "Fiction EX") do not display an "Add to Cart" button. There is also no alternative message such as "Out of Stock" or "Currently Unavailable" to inform the user why the option is missing. |
| **Steps to Reproduce** | 1. Navigate to Demo Web Shop → Books category 2. Observe the product grid 3. Note that some products show a price and rating but no "Add to Cart" button |
| **Test Data** | Affected products: Fiction, Fiction EX |
| **Expected Result** | Every product should either show an "Add to Cart" button (if purchasable) or a clear status message explaining why it cannot be purchased |
| **Actual Result** | Product is displayed with price and rating, but no purchase option and no explanation is shown |
| **Severity** | Medium *(does not crash the app, but impacts core purchase flow understanding)* |
| **Priority** | Medium |
| **Environment** | Chrome, Desktop, Demo Web Shop (demowebshop.tricentis.com) |
| **Screenshots** | See `/Screenshots/Defects/BUG-001.png` |
| **Status** | Open |

**QA Note:** This was evaluated for classification — since it does not break any functionality (the page loads fine, no error occurs) but creates user confusion about product availability, it has also been cross-logged as a UI/UX improvement recommendation. See [SUGG-001](../Suggestions/UI-UX-Improvements.md#sugg-001).

---

*New bugs will be added here as testing progresses, following the same format.*
