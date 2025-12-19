# Virtually by Nesh - HTML Email Signature

A custom-coded HTML email signature designed for **Virtually by Nesh** (Virtual Assistant Service). 

This project focuses on cross-client compatibility, ensuring the design renders identicaly on desktop, mobile, and legacy email clients (including Outlook for Windows).

## 📸 Preview
![Signature Preview](https://via.placeholder.com/600x200?text=Upload+Screenshot+Here)

## 🛠 Tech Stack & Methodology
* **Structure:** HTML4 Nested Tables (Ghost Tables).
* **Styling:** Inline CSS only (No external stylesheets or `<style>` blocks in body).
* **Assets:** Hosted images with optimized slicing for bandwidth efficiency.
* **Compatibility:** Tested on Gmail, Outlook (Desktop & Web), Apple Mail, and Yahoo.

## 🚀 Installation / Usage
1.  Open `signature.html` in a web browser (Chrome recommended).
2.  Select all (`Ctrl + A`) and Copy (`Ctrl + C`) the rendered visual.
3.  Paste (`Ctrl + V`) directly into the email client's signature settings.

## ⚠️ Key Considerations
* **Why Tables?** Modern Flexbox/Grid layouts break in Outlook's Word rendering engine. Tables are used to enforce structure.
* **Why Inline CSS?** Gmail and other clients strip global CSS classes.
* **Why No JavaScript?** JS is blocked by all email clients for security reasons.

## 👤 Author
Developed by [Nama Anda]
