# Jest Workshop Submission

## Student Details
- Name:ANKIT KUMAR
- Roll Number: 2024-B-05072005D
- GitHub Username:AkkiKrsingh2005

---

## Tests Written

List each test you wrote and briefly explain **what bug or regression it prevents**.

### 1. Test Name:Check for invalid coupon (!FLAT50)
**What it protects against:** Ensures that invalid or malformed coupon codes are rejected and do not apply unintended discounts.
---

### 2. Test Name:Check for invalid coupon (!SAVE10)
**What it protects against:**  Prevents incorrect coupon formats from being accepted, protecting the pricing logic from misuse.

---

### 3. Test Name:Check for no coupon and valid subtotal
**What it protects against:**  Confirms that when no coupon is provided, the function correctly returns the original subtotal without modifying the amount.
---

### 4. Test Name:Check for SAVE10 coupon
**What it protects against:** Verifies that the SAVE10 coupon applies the correct percentage discount and calculates the final amount accurately
---

### 5. Test Name:Check for FLAT50 coupon
**What it protects against:**  Ensures that the flat discount coupon subtracts the correct fixed amount and does not over-discount the subtotal.
---

## CI Pipeline (if implemented)
- Did CI pass successfully? (Yes / No):Yes
- GitHub Actions Run URL:

---

## Reflection (1–2 lines)
What is **one thing** you understood better about testing or CI after this workshop?

