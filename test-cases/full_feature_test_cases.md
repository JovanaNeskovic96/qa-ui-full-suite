# Test Cases – Full Feature Set

---

## 🔍 SEARCH BAR

### TC_SRCH_01 – Valid keyword returns results
- **Steps:** Enter a common product keyword and press Enter
- **Expected Result:** Relevant results are displayed

### TC_SRCH_02 – No results for random input
- **Steps:** Enter a gibberish string and search
- **Expected Result:** Message: "No results found"

### TC_SRCH_03 – Special characters input
- **Steps:** Enter "@@@@@" and press Enter
- **Expected Result:** Validation or empty result page

---

## 🔑 PASSWORD RESET

### TC_PWD_01 – Valid email triggers reset flow
- **Steps:** Enter registered email and request reset
- **Expected Result:** Confirmation message appears, email sent

### TC_PWD_02 – Invalid email format
- **Steps:** Enter "test@" and request reset
- **Expected Result:** Email validation error

### TC_PWD_03 – Expired link usage
- **Steps:** Click expired reset link
- **Expected Result:** Error: "Link expired"

---

## 🛒 SHOPPING CART

### TC_CART_01 – Add product to cart
- **Steps:** Click "Add to cart" on product
- **Expected Result:** Item appears in cart with quantity 1

### TC_CART_02 – Update quantity
- **Steps:** Increase quantity to 2
- **Expected Result:** Total updates correctly

### TC_CART_03 – Remove item
- **Steps:** Click remove icon
- **Expected Result:** Item disappears, total = 0

---

## 📱 RESPONSIVE DESIGN

### TC_RESP_01 – View on mobile resolution (375x667)
- **Steps:** Open site on mobile viewport
- **Expected Result:** Menu collapses into hamburger icon

### TC_RESP_02 – UI elements adjust on tablet
- **Steps:** Resize to tablet resolution
- **Expected Result:** Grid adjusts accordingly, no overlap

---

## 👤 PROFILE SETTINGS

### TC_PROF_01 – Update display name
- **Steps:** Change name and click Save
- **Expected Result:** New name is reflected

### TC_PROF_02 – Change email with valid input
- **Steps:** Enter new valid email and save
- **Expected Result:** Email saved successfully

### TC_PROF_03 – Cancel edit restores previous state
- **Steps:** Modify fields and click Cancel
- **Expected Result:** Reverts to original data
