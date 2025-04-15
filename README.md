# 🛍️ UniMart – Campus Marketplace

> A modern platform for students to buy, sell, and connect within their campus community.  
> [🌐 Live Demo](https://quiet-gnome-c7f9cd.netlify.app)

![Netlify](https://img.shields.io/badge/Hosted_on-Netlify-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

---

## ✨ Features

- 🔐 Firebase Auth – Secure login, signup, and forgot password
- 🛒 Post & Browse Listings – Easily add and explore items
- 🖼️ Cloudinary – Upload product images seamlessly
- 📱 Mobile-Friendly – Clean, responsive design
- 🧾 My Listings – Manage your own product posts
- 📇 Contact Request System – Sellers can approve buyer contact requests

---

## 📸 Preview

| Login Page                                                                                | Post Item                                                                                | My Listings                                                                                  |
| ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| ![Login](https://github.com/user-attachments/assets/590f462b-0199-41d7-a5d8-921d52d8d9c8) | ![Post](https://github.com/user-attachments/assets/692ed980-2302-443b-bb56-47317c345f1b) | ![Listings](https://github.com/user-attachments/assets/116d34e0-8b90-415b-be0c-f37491006e24) |

---

## ⚙️ Tech Stack

- **Frontend**: HTML, CSS, Vanilla JavaScript
- **Authentication**: Firebase Auth
- **Database**: Firebase Firestore
- **Image Upload**: Cloudinary (unsigned preset)
- **Hosting**: Netlify

---

## 📂 Folder Structure

```
📦 UniMart/
├── index.html               # Login and Home Page
├── dashboard.html           # User dashboard
├── post.html                # Create a new listing
├── mylistings.html          # View your own listings
├── browselistings.html      # Browse all listings
├── productdetails.html      # Item detail view
├── profile.html             # User profile page
├── request.html             # Contact request system
├── viewlistings.html        # Seller's listing view
├── signout.html             # Sign-out logic
├── logo app.jpg             # App logo
├── config.js                # Firebase/Cloudinary config
├── page0.js                 # Supporting JS
├── page1.js                 # Supporting JS

```

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/riddhighosh087/unimart.git
cd unimart
```

### 2. Set up Firebase

- Go to [Firebase Console](https://console.firebase.google.com/)
- Enable **Authentication** (Email/Password)
- Create a **Firestore Database**
- Copy your Firebase config and paste it in `auth.js`

### 3. Set up Cloudinary

- Create a Cloudinary account
- Go to **Settings > Upload**
- Create an **unsigned upload preset**
- Replace `upload_preset` and `cloud_name` in your upload script

---

## 🧠 Future Plans

- 🗺️ Map integration for item locations
- 🛒 Wishlist & saved items
- 🔔 Push notifications for contact requests

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌐 Live Site

🔗 [https://quiet-gnome-c7f9cd.netlify.app](https://quiet-gnome-c7f9cd.netlify.app)

---
