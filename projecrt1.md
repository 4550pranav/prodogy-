# Calculator Test Cases

## Test Case 1: Addition of Two Positive Numbers

**Test Case ID:** TC_ADD_001  
**Test Description:** Verify that the calculator correctly adds two positive numbers.  
**Preconditions:** Calculator is functional.  
**Test Steps:**  
1. Enter `5` as the first number.  
2. Select the `+` operation.  
3. Enter `3` as the second number.  
4. Click `=` to compute the result.  
**Expected Result:** The result should be `8`.

---

## Test Case 2: Subtraction of a Positive and Negative Number

**Test Case ID:** TC_SUB_002  
**Test Description:** Verify that the calculator correctly subtracts a negative number from a positive number.  
**Preconditions:** Calculator is functional.  
**Test Steps:**  
1. Enter `10` as the first number.  
2. Select the `-` operation.  
3. Enter `-4` as the second number.  
4. Click `=` to compute the result.  
**Expected Result:** The result should be `14`.

---

## Test Case 3: Multiplication of Decimal Numbers

**Test Case ID:** TC_MUL_003  
**Test Description:** Verify that the calculator correctly multiplies two decimal numbers.  
**Preconditions:** Calculator is functional.  
**Test Steps:**  
1. Enter `2.5` as the first number.  
2. Select the `*` operation.  
3. Enter `1.2` as the second number.  
4. Click `=` to compute the result.  
**Expected Result:** The result should be `3.0`.

---

## Test Case 4: Division by Zero

**Test Case ID:** TC_DIV_004  
**Test Description:** Verify that the calculator handles division by zero appropriately.  
**Preconditions:** Calculator is functional.  
**Test Steps:**  
1. Enter `15` as the first number.  
2. Select the `/` operation.  
3. Enter `0` as the second number.  
4. Click `=` to compute the result.  
**Expected Result:** The calculator should display an error message (e.g., `Cannot divide by zero`).

---

## Test Case 5: Complex Expression using BODMAS

**Test Case ID:** TC_BODMAS_005  
**Test Description:** Verify that the calculator correctly evaluates expressions following BODMAS rules.  
**Preconditions:** Calculator is functional.  
**Test Steps:**  
1. Enter the expression `(5 + 3) * 2` in the calculator.  
2. Click `=` to compute the result.  
**Expected Result:** The result should be `16`.

---

## Test Case 6: Input of Non-Numeric Characters

**Test Case ID:** TC_INVALID_006  
**Test Description:** Verify that the calculator does not accept non-numeric input.  
**Preconditions:** Calculator is functional.  
**Test Steps:**  
1. Enter `ABC` as input.  
2. Try performing any operation.  
**Expected Result:** The calculator should display an error message or ignore the input.

---

These test cases ensure that the calculator handles both valid and invalid inputs correctly while adhering to standard arithmetic rules.
