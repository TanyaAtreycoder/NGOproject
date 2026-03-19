# Anhad Shakti Foundation - Official Website

This is the official website for the **Anhad Shakti Foundation**, a non-profit organization dedicated to community outreach and empowerment in Haryana.

## 🚀 Live Link
[https://anhadshakti.org](https://anhadshakti.org) (Hosted via Netlify)

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Backend/Database:** Google Sheets (via CSV Fetch API)
- **Hosting:** Netlify
- **Domain:** GoDaddy
- **Automation:** Google Apps Script (for Volunteer Forms)

## 📊 How to Update the Website (Client Instructions)

The website is designed to be **dynamic**. You do not need to edit the code to change the content.

### 1. Updating Impact Reports
- Open the **Google Sheet** named `WebsiteData`.
- Change the numbers in the `Value` column (e.g., Change "50+" to "60+").
- The website will update the "Impact at a Glance" section automatically.

### 2. Adding Outreach Photos (Gallery)
- **Upload:** Add your photo to the designated Google Drive folder.
- **Share:** Right-click the photo > Share > Set to "Anyone with the link can view" > Copy Link.
- **Sheet:** Paste the link into **Column A** of the `Gallery` tab in your Google Sheet.
- **Details:** Add a Title and Description in the next columns.
- The new photo will appear in the "Community Outreach" section instantly.

### 3. Volunteer Notifications
- When someone fills out the "Join Us" form, an email is automatically sent to `anhadsf1@gmail.com`.
- All volunteer data is also saved in the `Volunteer Submissions` tab of the Google Sheet.

## 💻 Developer Notes (For Future Maintenance)
- **Auto-Deployment:** This repository is connected to Netlify. Any `git push` to the `main` branch will trigger an instant live update.
- **CSS Pattern:** All dynamic cards (Gallery & Reports) use the `.card` and `.stat-card` classes defined in the HTML/CSS files to maintain brand consistency.

---
Developed with ❤️ for Anhad Shakti Foundation.