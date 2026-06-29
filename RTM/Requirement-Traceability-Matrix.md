# Requirement Traceability Matrix (RTM) — Demo Web Shop

The RTM maps each requirement/feature to its corresponding test scenarios, test cases, and execution status — ensuring complete test coverage across the application.

| Req ID | Requirement / Feature | Test Scenario ID(s) | Test Case ID(s) | Linked Bug(s) | Coverage Status |
|---|---|---|---|---|---|
| REQ-01 | Users can view all products under Books category | TS-BOOK-01 | TC-001 | BUG-001 | ✅ Covered |
| REQ-02 | Users can add an available product to cart | TS-BOOK-02 | TC-002 | — | ✅ Covered |
| REQ-03 | Unavailable products clearly indicate stock status | TS-BOOK-03 | TC-001 | BUG-001 | ⚠️ Covered — Failed |
| REQ-04 | Users can sort products by price/name | TS-BOOK-04 | TC-003 | — | ⏳ In Progress |
| REQ-05 | Users can update item quantity in cart | TS-CART-02 | TC-004 | — | ⏳ In Progress |
| REQ-06 | Registration form validates incorrect email format | TS-AUTH-02 | TC-005 | — | ⏳ In Progress |
| REQ-07 | Guest checkout completes successfully | TS-CHK-01 | — | — | 🔲 Not Started |
| REQ-08 | Login fails gracefully with invalid credentials | TS-AUTH-04 | — | — | 🔲 Not Started |
| REQ-09 | Search returns relevant results | TS-SRCH-01 | — | — | 🔲 Not Started |

**Legend:**
✅ Covered & Passed &nbsp;|&nbsp; ⚠️ Covered & Failed &nbsp;|&nbsp; ⏳ In Progress &nbsp;|&nbsp; 🔲 Not Started

---

*This RTM will be updated continuously as new test cases are executed and new requirements are identified.*
