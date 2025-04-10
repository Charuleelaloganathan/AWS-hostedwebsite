# 🧢 StyleHub – Static E-Commerce Website

A responsive static fashion-themed website built using **HTML**, **CSS**, and hosted on **AWS (S3 + CloudFront)** for fast and secure delivery. This project explores cloud-based static site deployment and content delivery optimization.

---

## 🚀 Live Demo

- 🪣 **Amazon S3 Website**: [http://stylehub20.s3-website.ap-south-1.amazonaws.com/](http://stylehub20.s3-website.ap-south-1.amazonaws.com/)
- 🌐 **CloudFront Distribution**: [https://d10npahhmwr8gm.cloudfront.net/](https://d10npahhmwr8gm.cloudfront.net/)
- **Live Demo on Vercel**:[https://aws-hostedwebsite.vercel.app/](https://aws-hostedwebsite.vercel.app/)

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS
- **Cloud Services**: Amazon S3, Amazon CloudFront
- **Version Control**: Git, GitHub
- **Optional**: Route 53 for domain management (not used here)

---

## 📦 Features

- Responsive design suitable for all devices
- Static e-commerce storefront layout
- Optimized delivery via AWS CloudFront
- Deployed using real AWS hosting services

---

## ☁️ Deployment Details

### 🗂 Amazon S3
- Static website hosting enabled
- Public bucket policy configured
- Files uploaded at root level (not inside a subfolder)
- Index and error document support

### 🌐 Amazon CloudFront
- Origin set to S3 website endpoint
- HTTPS enabled by default
- Secure, low-latency global content delivery

---

## 🖼 Screenshots

You can find the result screenshots in the resultscreenshots folder

---

## 📎 Notes

- This project was hosted and tested on **AWS S3** and **CloudFront** under the free tier.
- GitHub Pages or Vercel can be used as alternatives to avoid future billing.

---

## 📍 How to Run Locally

```bash
git clone https://github.com/Charuleelaloganathan/AWS-hostedwebsite.git
cd AWS-hostedwebsite
open index.html
