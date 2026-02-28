# **BUG REPORT SAMPLES (Realistic Ones)**

### **BUG 1 \- Critical**

**Bug ID:** BUG\_CART\_001  
**Title:** Total amount not updating after quantity increase  
**Module:** Cart

**Environment:** QA Build v1.0.3  
**Severity:** Critical  
**Priority:** High

**Steps to Reproduce:**

1. Add product (₹1000) to cart  
2. Increase quantity to 2  
3. Observe total

**Expected Result:**  
 Total should update to ₹2000 \+ tax

**Actual Result:**  
 Total remains ₹1000

**Impact:**  
 Incorrect billing calculation

**Status:** Open

### 

### 

### 

### 

### 

### 

### **BUG 2 \- High**

**Bug ID:** BUG\_CHECKOUT\_002  
**Title:** User able to proceed without selecting payment method  
**Module:** Checkout

**Severity:** High  
**Priority:** High

**Expected:**  
 System should show validation message

**Actual:**  
User redirected to confirmation page

**Impact:**  
Business logic failure

### **BUG 3 – Medium**

**Bug ID:** BUG\_ORDER\_003  
 **Module:** Order Confirmation  
 **Title:** Order confirmation email delayed by 20 minutes

**Severity:** Medium  
 **Priority:** Medium

**Impact:**  
 User experience issue

