<div align="left">
  <a href="https://instagram.com/otaviomuraca" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
  <a href="mailto:otaviomuraca@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/otaviomuraca/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://pypi.org/project/bankkit/" target="_blank"><img src="https://img.shields.io/badge/PyPI-bankkit-blue?style=for-the-badge&logo=pypi&logoColor=white"></a>
  <a href="https://statlys.com/" target="_blank"><img src="https://img.shields.io/badge/statlys.com-4f46e5?style=for-the-badge&logo=&logoColor=white"></a>
</div>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-AI%20Assisted-blueviolet?style=flat-square&logo=anthropic&logoColor=white)

# Otávio Vicario Muraca
## 🚀 Financial Data & API Engineer
Focusing on **Financial Data Engineering, API integrations, and automation**.

---

## 💹 Financial Focus
- 💰 Currency & Crypto exchange rates
- 🏦 Banking and Payment APIs
- 📊 Investment calculations (FIIs, yields, portfolios)
- ⚡ Automation of financial processes

---

## 🛠️ Projects

### 🏢 [Statlys](https://statlys.com) — SaaS · Live
> Professional bank statement analysis made simple.

Upload PDF bank statements, get instant AI-powered insights, automatic transaction categorization, cash flow visualization, and client management — built for accountants and financial professionals.

[![Website](https://img.shields.io/badge/statlys.com-live-brightgreen?style=flat-square)](https://statlys.com)
[![Free Trial](https://img.shields.io/badge/Free%20Trial-available-blue?style=flat-square)](https://statlys.com/auth/register/)

---

### 🏦 [BankKit](https://github.com/otaviovicario/bankkit) — Open Source · `pip install bankkit`
> Python SDK for validating banking data — built for Latin America, ready for the world.

[![PyPI version](https://img.shields.io/pypi/v/bankkit?style=flat-square)](https://pypi.org/project/bankkit/)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue?style=flat-square)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow?style=flat-square)](https://opensource.org/licenses/MIT)
[![Tests](https://img.shields.io/badge/tests-131%20passing-brightgreen?style=flat-square)]()

Validates CPF, CNPJ, PIX, IBAN, SWIFT, CLABE, CBU, RUT, ABA Routing, card numbers, passports and more — covering Brazil, Argentina, Mexico, Chile, USA, Canada and 80+ countries via IBAN.

```python
from bankkit import BankKit
bk = BankKit()

bk.validate_pix("user@email.com")          # → {"valid": True, "type": "EMAIL"}
bk.validate_iban("GB82WEST12345698765432") # → {"valid": True, "country": "United Kingdom"}
bk.validate_clabe("032180000118359719")    # → {"valid": True, "bank_code": "032"}
```

---

### 💱 [Currency & Crypto Rate API](https://github.com/otaviovicario/Currency-Crypto-Rate-API)
> Real-time exchange rates for any currency or crypto to BRL.

---

## 🌱 Currently Learning
- Advanced Open Banking APIs & fintech integrations (BR + US)
- Cloud architecture for financial applications


