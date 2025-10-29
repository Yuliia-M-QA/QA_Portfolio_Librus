# 🧪 Test Cases — Librus Family Portal

## 🔍 Overview

This document contains a bit of test cases for the **Librus Parent/Family Portal**
👉 [https://portal.librus.pl/rodzina](https://portal.librus.pl/rodzina)  A full document you can find in Google Sheets 


The goal is to verify login functionality, content display, and navigation consistency.
---

### ✅ TC01 – Verify Login with Valid Credentials

**Preconditions:**
User has a valid parent account.

**Steps:**

1. Hover over “LIBRUS Synergia → Zaloguj”
2. Click “Zaloguj”
3. Enter valid username and password
4. Click “Zaloguj”

**Expected Result:**
User is successfully logged in and redirected to the parent profile dashboard.

---

### ❌ TC02 – Verify Login with Invalid Credentials

**Preconditions:**
User has a valid account.

**Steps:**

1. Hover over “LIBRUS Synergia → Zaloguj”
2. Click “Zaloguj”
3. Enter invalid username
4. Click “Zaloguj”

**Expected Result:**
An error message “Nieprawidłowy login i/lub hasło” appears. User cannot log in.

---

### 🔐 TC03 – Verify Password Reset Functionality

**Preconditions:**
User has a valid account with a registered email.

**Steps:**

1. Hover over to 'LIBRUS synrgia > Zaloguj
2. Click on Zaloguj
3. Click on 'Przypomnij hasło' under the password field
4. Opens the page https://portal.librus.pl/rodzina/synergia/loguj 
5. Follow the rquirement> Enter e-mail>Press 'Wuślij'
6. Check your e-mail

**Expected Result:**

User receives password reset instructions via email


