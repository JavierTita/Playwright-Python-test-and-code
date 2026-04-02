# Tests

## Saucedemo Test Suite

### Files

- **test_login.py** — Login and logout tests (5 tests)
- **test_checkout.py** — Complete purchase flow (1 test)
- **test_products.py** — Product tests (4 tests)
  - test_sort — Sort products Z to A
  - test_multi_cart — Add 6 products, verify badge shows 6
  - test_price — Verify correct price for all 6 products
  - test_removecart — Add 6 products and remove all, verify empty cart

### How to run
```bash
pytest tests/
```

