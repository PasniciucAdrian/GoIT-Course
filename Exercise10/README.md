# Exercise10 – JSON and XML Data Representation

This folder contains the solution for Homework 10 of the GoIT Manual QA Course. The task was to describe a list of 4 fictional people using both JSON and XML formats, ensuring that each person had complete and structured personal information.

---

## 🎯 Objective

- Create structured data for 4 individuals using:
  - JSON format
  - XML format
- Each person includes:
  - Unique ID
  - Full name
  - City of residence
  - Address (street, house number, apartment number)
  - Contact details (phone numbers, email, and Skype)
- Verify that both formats are correctly displayed when opened in a web browser

---

## 📁 Files Included

---

## 👤 Sample Data Structure

### 🔸 JSON – `temanr10_json.json`
Each object inside `lista_persoane` includes:
- `id_unic`
- `nume`
- `oras`
- `adresa` (strada, casa, numarul_apartamentului)
- `date_de_contact` (numere_de_telefon, email, skype)

### 🔹 XML – `temanr10_xml.xml`
Each person is defined under a `<persoana_nrX>` tag with identical data fields as above.

Both formats store information for the following fictional individuals:
- Roger Federer
- Rafael Nadal
- Luka Dončić
- Nikola Jokić

---

## ✅ Validation

- Files were opened and rendered correctly in modern web browsers
- No syntax errors detected in either format
- All fields are populated with randomly generated, non-sensitive data

---

## 📌 Notes

- No real personal data was used
- JSON and XML were both manually formatted and verified
- Text versions (.txt) are provided for easier viewing or copying



