# Meddent Global Solutions Landing Page

This is a **single-file React + Tailwind** landing page for **Meddent Global Solutions** — a UK-based procurement and delivery partner for medical equipment and consumables.

## 🚀 Deploy on Netlify (Drag & Drop)

1. **Get the files**
   - `index.html` (the entire site in one file)
   - `README.md` (this file)

2. **Set your Web3Forms access key**
   - Open `index.html` in a text editor.
   - Find:
     ```js
     const WEB3FORMS_KEY = "REPLACE_WITH_YOUR_ACCESS_KEY";
     ```
   - Replace it with your key from https://web3forms.com/

3. **Deploy**
   - Go to Netlify → **Add new site** → **Deploy manually**.
   - Drag and drop `index.html` (and optionally this `README.md`).

## 🛠 Features

- Responsive React + Tailwind UI via CDN (no build tools)
- Product categories & services
- Interactive quote builder
  - Add/remove items
  - File uploads
  - Download JSON summary
  - Mailto fallback
- Embedded sample video
- Study guide: quiz, essays, glossary
- Clear legal disclaimers and contact info

## ✏️ Quick Customization

- **Logo:** replace the Base64 `LOGO_DATA_URI` in `index.html`.
- **Video:** update the YouTube `src` in the `<iframe>`.
- **Copy:** edit headings, paragraphs, and lists directly in `index.html`.
- **Contact:** update email inside `mailtoLink()` and in the footer.

## ⚠️ Notes

- Submissions require a valid **Web3Forms** key.
- Mailto links can’t send attachments (email client limitation).
- All functionality is client-side so it works on any static host.

## 📄 License

For your business use.
