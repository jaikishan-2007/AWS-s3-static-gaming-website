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
1. Open AWS Console- [aws_Console](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/01-aws_console.jpg)
2. Click on region- [region](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/02-Region.jpg)
3. Select the region Which is near to you- [Select_Region](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/03-Select_nearest_region.jpg)
4. In Search bar search for **S3 Bucket**- [Search for S3](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/04-Search_for_S3.png)
5. CLick on S3 Bucket- [Select S3](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/05-Select-S3.png)
6. Create new bucket- [Create bucket](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/05-Select-S3.png)
7. Enter Bucket name **Note:** Bucket name should be globally unique- [Name](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/07-Enter_Bucket_Name.png)
8. Scroll down and uncheck the **Block all public access** and check the ** Disclamir shown by aws**- [Access](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/08-Public_Access.png)
9. Click on Create Bucket- [Confirm bucket creation](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/09-Create_Bucket_confirm.png)
10. Open your bucket- [Select Bucket](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/10-Select_Bucket.png)
11. Select Upload- [Upload](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/11-Upload.png)
12. Add files to your bucket **Note:** If an HTML file is using images than you need to upload the images that are used in HTML- [Add files](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/12-Add_files.png)
13. Now click upload to proceed further- [upload selected files](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/13-Upload_Selected_files.png)
14. Close the Upload Status Interface -[Close](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/14-Close.png)
15. Go to properties -[properties](https://github.com/jaikishan-2007/AWS-s3-static-gaming-website/blob/main/Demonstration_Via_Screenshots/15-Properties.png)

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
