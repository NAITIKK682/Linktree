# Naitik Kushwaha - Personal Linktree Portfolio

A sleek, animated personal linktree/portfolio page for Naitik Kushwaha, showcasing professional links, social media profiles, and a contact inquiry form with integrated data saving and notifications.

## 🚀 Features

- **Responsive Design**: Optimized for all devices with a mobile-first approach.
- **Animated Background**: Snowfall effect with layered stars for a dynamic visual experience.
- **Professional Links**: Direct links to Portfolio, LinkedIn, GitHub, Instagram, LeetCode, and Email.
- **Contact Form**: Integrated inquiry form with validation, data saving to Google Sheets via SheetDB, email notifications via FormSubmit, and WhatsApp messaging.
- **SEO Optimized**: Includes meta tags, favicon, and preload for better performance.
- **Accessibility**: Proper alt texts, semantic HTML, and keyboard navigation support.
- **Performance**: Lightweight with optimized assets and efficient loading.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure and markup.
- **CSS3**: Custom styles with animations and responsive design.
- **JavaScript (Vanilla)**: Form handling, validation, and API integrations.
- **External Services**:
  - [SheetDB](https://sheetdb.io/) for data storage in Google Sheets.
  - [FormSubmit](https://formsubmit.co/) for email notifications.
  - WhatsApp API for instant messaging.
- **Fonts**: Google Fonts (Inter) for modern typography.
- **Icons & Images**: Custom assets stored in `assets/` directory.

## 📁 Project Structure

```
naitik-linktree/
├── index.html          # Main HTML file
├── README.md           # Project documentation
└── assets/
    ├── css/
    │   └── style.css   # Main stylesheet
    ├── images/         # Icons, logos, and favicons
    │   ├── logo.png
    │   ├── favicon.png
    │   ├── portfolio.png
    │   ├── linkedin.png
    │   ├── github.png
    │   ├── instagram.png
    │   ├── leetcode.png
    │   └── email.png
    └── js/              # (If any JavaScript files are added later)
```

## 🚀 Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NAITIKK682/naitik-linktree.git
   cd naitik-linktree
   ```

2. **Open in Browser**:
   - Simply open `index.html` in any modern web browser.
   - No server required as it's a static site.

3. **Optional: Run Locally with a Server** (for better testing):
   - Use Python: `python -m http.server 8000`
   - Use Node.js: Install `http-server` and run `http-server`
   - Access at `http://localhost:8000`

## 📖 Usage

- **View Links**: Click on any link to navigate to the respective platform.
- **Contact Form**:
  - Fill in Name, Email, Phone (10-digit), and Message.
  - Submit to save data to Google Sheets, send an email, and open WhatsApp with the inquiry details.
  - Form includes spam protection and client-side validation.

## 🔧 Configuration

### Contact Form Integrations

1. **SheetDB Setup**:
   - Create a Google Sheet and connect it to SheetDB.
   - Replace the API endpoint in `index.html` (line ~200): `https://sheetdb.io/api/v1/YOUR_SHEET_ID`

2. **FormSubmit Email**:
   - Update the email in `index.html` (line ~210): `naitikk682@gmail.com`
   - Customize the template and autoresponse as needed.

3. **WhatsApp Number**:
   - Update the phone number in `index.html` (line ~215): `918948866980`

### Styling & Assets

- Modify `assets/css/style.css` for custom styles.
- Replace images in `assets/images/` with your own (maintain file names for consistency).

## 🌟 Key Highlights

- **Snowfall Animation**: CSS-based layered stars for a festive, engaging background.
- **Click-Through Fix**: Ensures background elements don't block link interactions.
- **Form Validation**: Real-time checks for email format and phone number (10 digits).
- **Error Handling**: User-friendly messages for form submission status.
- **Timestamped Data**: Includes Indian Standard Time (IST) for inquiries.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m 'Add your feature'`
4. Push to branch: `git push origin feature/your-feature`
5. Open a Pull Request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 📞 Contact

- **Email**: naitikk682@gmail.com
- **LinkedIn**: [Naitik Kushwaha](https://www.linkedin.com/in/naitik-kushwaha/)
- **GitHub**: [NAITIKK682](https://github.com/NAITIKK682)
- **Portfolio**: [Naitik's Portfolio](https://naitik-portfolio-1.onrender.com/)

---

*Built with ❤️ by Naitik Kushwaha*
