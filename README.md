# Unit Test for `Calculator` Class

## **Overview**
This project includes unit tests for the `Calculator` class, written using JUnit 5. The tests verify the correctness of basic arithmetic operations and the handling of division by zero.

---

## **Tests Overview**
- **Tested methods:**
  - `add`: Addition of two numbers.
  - `subtract`: Subtraction of two numbers.
  - `multiply`: Multiplication of two numbers.
  - `divide`: Division of two numbers.
  - `divideByZero`: Handling division by zero.

---

## **Execution Results**
- **Total Test Cases:** 5
- **Passed Test Cases:** 5
- **Failed Test Cases:** 0
- **Execution Time:** 1.978 seconds
- **Build Status:** `BUILD SUCCESS`

![Test Results](pic.png)

---

## **Test Cases**
1. **`testAdd`**
   - **Description:** Tests addition of `2 + 3`.
   - **Expected Result:** `5`.
   - **Actual Result:** Pass.

2. **`testSubtract`**
   - **Description:** Tests subtraction of `3 - 2`.
   - **Expected Result:** `1`.
   - **Actual Result:** Pass.

3. **`testMultiply`**
   - **Description:** Tests multiplication of `2 * 3`.
   - **Expected Result:** `6`.
   - **Actual Result:** Pass.

4. **`testDivide`**
   - **Description:** Tests division of `6 / 3`.
   - **Expected Result:** `2`.
   - **Actual Result:** Pass.

5. **`testDivideByZero`**
   - **Description:** Tests division of `6 / 0`.
   - **Expected Result:** Throws `IllegalArgumentException`.
   - **Actual Result:** Pass.

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone git@github.com:ngoducthuan/JavaCalculatorTest-JUnit.git
   cd JavaCalculatorTest-JUnit
   mvn compile
   mvn test
