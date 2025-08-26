# 🌐 AWS Basics Project – Host a Website on Amazon S3

This project demonstrates how to host a **static website** using **Amazon S3**.  
The project involves creating an S3 bucket, uploading website files, configuring static website hosting, and making objects publicly accessible.

---

## 📖 Project Overview
In this project, I:
- Created an **Amazon S3 bucket** to store website files.
- Uploaded the `index.html` file and supporting assets.
- Configured **static website hosting** in S3.
- Made objects in the bucket publicly accessible.
- Troubleshooted errors until the site displayed correctly.

**Duration:** ~1 hour 30 minutes  
**Challenge:** Fixing the error that appeared on the hosted site.  
**Rewarding part:** Seeing the website successfully display without errors 🎉  

---

## 🛠️ Tools & Concepts Learned
- Amazon S3 bucket creation
- Uploading and managing files in S3
- Static website hosting configuration
- Access Control Lists (ACLs) in S3
- Troubleshooting permissions and errors
- Understanding bucket endpoints

---

## ⚙️ Setup Instructions

### 1. Create an S3 Bucket
- Go to **Amazon S3 Console** → **Create bucket**
- Pick a region close to you (I used **Europe**).
- Bucket names must be **globally unique**.

📸 Example:  
![S3 Bucket Setup](docs/s3-bucket.png)

---

### 2. Upload Website Files
- Upload `index.html` and any supporting assets (e.g., images, CSS, JS).
- Make sure all files are in the same parent folder.

📸 Example:  
![Uploading Files](docs/upload-files.png)

---

### 3. Enable Static Website Hosting
- Go to the **Properties** tab → scroll to **Static Website Hosting**.
- Click **Edit** → Enable static web hosting.
- Set `index.html` as the **index document**.

📸 Example:  
![Website Hosting](docs/website-hosting.png)

---

### 4. Make Objects Public
- Configure permissions so that files are accessible.
- Use **ACLs (Access Control Lists)** or **Bucket Policies** to make files public.

📸 Example:  
![Permissions Settings](docs/make-public.png)

---

### 5. Access the Website
- Once enabled, S3 generates a **bucket endpoint URL**.
- Open the endpoint in your browser to view your hosted site 🎉

📸 Example:  
![Hosted Website](docs/final-website.png)

---

## 📂 Example Files
- `index.html`
- `NextWork-Everyone-love_files.zip` (image & style assets)

---

## 🔗 Useful Resources
- [AWS S3 Documentation](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html)  
- [NextWork Community](https://community.nextwork.org)  

---

## 👤 Author
**Nchindo Boris**  
NextWork Student @ [nextwork.org](https://nextwork.org)