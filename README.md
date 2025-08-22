# 🛒 Product Listing Tool  

A lightweight and user-friendly system to manage and showcase products.  
Includes an **Admin Panel** for adding/editing products and a **Front-End** for displaying them beautifully on your website.  

---

## 📌 Features  
- Simple and intuitive **Admin Panel**  
- Customer-facing **Front-End**  
- Firebase authentication (Email/Password login)  
- Firebase Realtime Database for product storage  
- Image upload support  
- Responsive and clean design  

---

## 🖼️ Add Logo  
To customize your site’s logo:  
1. Place your image in the same folder as `index.html` and `admin.html`  
2. Rename the file to: `logo.png`

---

## ⚡ Setup Guide  

1. Go to [Firebase Console](https://console.firebase.google.com) and create a new Firebase project  
2. Enter your **Project Name** and **Project ID**, then create the project  
3. Navigate to **Build > Authentication** → click **Get started**  
4. Under the **Sign-in method** tab, enable **Email/Password** and save  
5. Open **Project Settings** → scroll to **Your apps** → add a **Web app**  
6. Choose an **App Nickname**, then click **Register app** (skip SDK setup and continue)  
7. Copy the Firebase config details and paste them into the `firebaseConfig` variable in **both**:  
   - `index.html`  
   - `admin.html`  

---

## 🚀 Deployment  
Once setup is complete, deploy your files to your favorite hosting provider (e.g., Vercel, Netlify, Firebase Hosting) and start using it instantly.  
