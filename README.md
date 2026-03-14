# 🎮 AWS S3 Static Gaming Website

A simple **gaming dashboard website** hosted using **AWS S3 Static Website Hosting**.

This project demonstrates how to deploy a **static web application** using cloud storage without running a traditional web server.

---

# 🌐 Live Architecture Overview

This project uses **Amazon S3 static website hosting** to serve HTML files directly to users.

## Architecture Diagram

```
        User
         │
         ▼
    Web Browser
         │
         │ HTTP Request
         ▼
 AWS S3 Static Website Endpoint
         │
         ▼
      S3 Bucket
(index.html, images, assets)
         │
         ▼
  HTML Response to Browser
```

---

# 🔁 S3 Request Flow

Step-by-step process when a user opens the website:

1. User enters the S3 website endpoint URL

2. The browser sends an HTTP request

3. Amazon S3 Static Hosting receives the request

4. S3 searches for the requested file:

```
index.html
```

5️⃣ S3 returns the file to the browser

6️⃣ Browser renders the website UI

---

# 🧱 Technologies Used

| Technology  | Purpose               |
| ----------- | --------------------- |
| HTML        | Website structure     |
| CSS         | Styling               |
| AWS S3      | Static file hosting   |
| GitHub      | Version control       |
| Screenshots | Project documentation |

---

# 📂 Project Structure

```
aws-s3-static-gaming-website
│
├── index.html
├── error.html
├── Battle.jpg
├── Racing_Thunder.jpg
├── zombie.jpeg
├── spaceshooter.jpg
│
├── screenshots
│   ├── 01-aws-console.png
│   ├── 02-open-s3.png
│   ├── 03-create-bucket.png
│   ├── ...
│   └── 27-error-page-working.png
│
└── README.md
```

---

# ⚙️ AWS Deployment Steps

## 1️⃣ Create S3 Bucket


# 📚 What I Learned

Through this project I learned:

• AWS S3 bucket creation
• Static website hosting configuration
• Bucket policy configuration
• Public access permissions
• Hosting HTML applications in the cloud

---

# 🚀 Future Improvements

Possible improvements for this project:

• Add CloudFront CDN for faster content delivery
• Use custom domain with Route 53
• Enable HTTPS using AWS Certificate Manager
• Add JavaScript-based game interactions

---

# Author

Korada Jaikishan

Cloud Computing Learner | AWS Beginner
