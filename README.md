# Playwright Python Test and Code 🎭

## QA Automation Portfolio — Javier Tita

Automation test suite built with Playwright and Python, targeting the Saucedemo e-commerce practice site.

---

## 🛠️ Tech Stack

- **Playwright** — browser automation
- **Pytest** — test framework
- **Python** — programming language
- **CSS Selectors** — #id, [data-test], .class

---

## 📁 Project Structure

```
Playwright-Python-test-and-code/
├── conftest.py         ← shared fixtures (page, logged_page)
├── requirements.txt    ← project dependencies
├── tests/
│   ├── test_login.py
│   ├── test_checkout.py
│   └── test_products.py
└── pages/              ← POM coming soon
```

---

## ⚙️ Setup

```bash
pip install -r requirements.txt
playwright install
```

---

## ▶️ Run Tests

```bash
pytest tests/
```

---

## 🧪 Test Suite

### conftest.py — Shared Fixtures

- **page** — launches Chromium browser
- **logged_page** — launches browser and logs in automatically

---

### test_login.py — Login Suite (5 tests)

| Test | Description |
|---|---|
| test_sucesslogin | Successful login, verifies redirect to inventory |
| test_emptyfields | Both fields empty, verifies error message |
| test_emptyusername | Password filled, username empty, verifies error |
| test_emptypassword | Username filled, password empty, verifies error |
| test_logout | Login and logout, verifies return to login page |

---

### test_checkout.py — Purchase Flow (1 test)

| Test | Description |
|---|---|
| test_checkout | Full purchase flow: add to cart, checkout, verify success |

---

### test_products.py — Product Tests (4 tests)

| Test | Description |
|---|---|
| test_sort | Sort products Z to A, verifies first product |
| test_multi_cart | Add 6 products, verify badge shows 6 |
| test_price | Verify correct price for all 6 products using filter and loop |
| test_removecart | Add 6 products and remove all, verify empty cart |

---

## 📫 Author

- **GitHub:** [JavierTita](https://github.com/JavierTita)
- **Location:** Córdoba, Argentina
- **Open to remote work opportunities**
