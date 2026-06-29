# Test Cases — Demo Web Shop

Detailed test cases derived from [Test-Scenarios.md](../Test-Scenarios/Test-Scenarios.md). Each test case follows a standard QA format used in real-world test management tools.

---

## TC-001

| Field | Details |
|---|---|
| **Test Case ID** | TC-001 |
| **Module** | Books |
| **Title** | Verify "Add to Cart" button visibility for all listed products |
| **Preconditions** | User is on the Demo Web Shop homepage |
| **Steps** | 1. Navigate to Books category 2. Observe each product card 3. Check for "Add to Cart" button on every product |
| **Test Data** | N/A |
| **Expected Result** | "Add to Cart" button should be visible on every product, OR a clear stock-status message should be shown if unavailable |
| **Actual Result** | Some products (e.g., "Fiction", "Fiction EX") do not display the "Add to Cart" button, and no stock message is shown |
| **Status** | ❌ Fail (linked to BUG-001) |

---

## TC-002

| Field | Details |
|---|---|
| **Test Case ID** | TC-002 |
| **Module** | Books |
| **Title** | Verify "Add to Cart" functionality for an in-stock product |
| **Preconditions** | User is on the Books category page |
| **Steps** | 1. Select a product with "Add to Cart" button visible (e.g., "Computing and Internet") 2. Click "Add to Cart" 3. Verify cart icon/count updates |
| **Test Data** | Product: Computing and Internet |
| **Expected Result** | Product should be added to cart and cart count should increase by 1 |
| **Actual Result** | Cart updated correctly with product and count |
| **Status** | ✅ Pass |

---

## TC-003

| Field | Details |
|---|---|
| **Test Case ID** | TC-003 |
| **Module** | Books |
| **Title** | Verify sorting functionality on Books page |
| **Preconditions** | User is on the Books category page |
| **Steps** | 1. Select "Price: Low to High" from Sort by dropdown 2. Observe product order |
| **Test Data** | Sort option: Price Low to High |
| **Expected Result** | Products should be reordered from lowest to highest price |
| **Actual Result** | *(To be filled after execution)* |
| **Status** | ⏳ Not Executed |

---

## TC-004

| Field | Details |
|---|---|
| **Test Case ID** | TC-004 |
| **Module** | Shopping Cart |
| **Title** | Verify cart total updates correctly when quantity is changed |
| **Preconditions** | At least one item is added to cart |
| **Steps** | 1. Go to Shopping Cart page 2. Change quantity of an item 3. Click "Update cart" |
| **Test Data** | Quantity: 2 |
| **Expected Result** | Item subtotal and cart total should recalculate correctly based on new quantity |
| **Actual Result** | *(To be filled after execution)* |
| **Status** | ⏳ Not Executed |

---

## TC-005

| Field | Details |
|---|---|
| **Test Case ID** | TC-005 |
| **Module** | Register/Login |
| **Title** | Verify registration fails with invalid email format |
| **Preconditions** | User is on the Register page |
| **Steps** | 1. Enter all valid details except email 2. Enter invalid email format (e.g., "test@@test") 3. Click Register |
| **Test Data** | Email: test@@test |
| **Expected Result** | System should display a validation error and not create the account |
| **Actual Result** | *(To be filled after execution)* |
| **Status** | ⏳ Not Executed |

---

*New test cases will be added here as more modules are tested.*

**Status Legend:** ✅ Pass &nbsp;|&nbsp; ❌ Fail &nbsp;|&nbsp; ⏳ Not Executed &nbsp;|&nbsp; 🚫 Blocked
