# Hosting a Static Website on Amazon S3

Welcome to the detailed guide for creating and hosting a static website using Amazon S3. This project document highlights the processes, technologies, skills, and interesting findings I encountered during the project.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Step-by-Step Guide](#step-by-step-guide)
    - [Step 1: Create an S3 Bucket](#step-1-create-an-s3-bucket)
    - [Step 2: Upload Website Content](#step-2-upload-website-content)
    - [Step 3: Configure Static Website Hosting](#step-3-configure-static-website-hosting)
    - [Step 4: Make Objects Public Using ACLs](#step-4-make-objects-public-using-acls)
4. [Deleting Resources](#deleting-resources)
5. [Share Your Work](#share-your-work)
6. [Conclusion](#conclusion)

---

## Project Overview

In this project, I created and hosted a static website using Amazon S3. The main tasks included:

- Creating an S3 bucket
- Uploading HTML and image files
- Configuring the bucket for static website hosting
- Using Access Control Lists (ACLs) to make the website public

The project was a fantastic way to dive into AWS S3 and understand how cloud storage and hosting work.

---

## Prerequisites

- An AWS account
- Basic knowledge of HTML
- Familiarity with AWS Management Console

---

## Step-by-Step Guide

### Step 1: Create an S3 Bucket

1. **Search for S3** in the AWS Management Console.
2. **Create a new bucket**:
   - **Region**: Select the region closest to you.
   - **Bucket Name**: Enter a unique name. This name must be globally unique.
   - **Enable ACLs**: Ensure Access Control Lists are enabled to manage permissions.
   - **Public Access**: Allow public access to the bucket.
   - **Versioning**: Enable versioning to keep track of changes.

**Interesting Finding**: The ability to control access at a granular level using ACLs vs. bucket policies provided a deeper understanding of AWS security features.

### Step 2: Upload Website Content

1. **Open your bucket** in the S3 console.
2. **Upload the following files**:
   - `index.html`
   - Contents of `NextWork - Everyone...love_files.zip` (unzipped)
3. **Ensure all files are uploaded successfully**.

**Interesting Finding**: Learning how HTML structures web content was fascinating. HTML is essentially the blueprint that shapes what you see when you visit a website.

### Step 3: Configure Static Website Hosting

1. **Navigate to the Properties tab** of your bucket.
2. **Enable Static Website Hosting**:
   - **Static web hosting**: Choose "Enable."
   - **Hosting type**: Select "Host a static website."
   - **Index document**: Enter `index.html`.
3. **Save the configuration** and note the provided URL.

**Interesting Finding**: Understanding the process of making a local HTML file accessible on the web through hosting was a key takeaway.

### Step 4: Make Objects Public Using ACLs

1. **Select the uploaded objects** (HTML and images).
2. **Change the permissions** to make them public:
   - Use the ACL settings to grant public read access.
3. **Refresh your website URL** to see your hosted site live.

**Interesting Finding**: The error encountered due to private objects highlighted the importance of understanding default security settings in AWS.

---

## Deleting Resources

1. **Delete the objects** in your bucket:
   - Select the objects and choose "Delete."
2. **Delete the bucket**:
   - Confirm the bucket name and delete it.

**Important**: Deleting resources is crucial to avoid unnecessary charges.

---

## Share Your Work

1. **Download your project documentation**.
2. **Share your achievement** on LinkedIn:
   - Add the project documentation as a PDF.
   - Tag @NextWork and showcase your skills.

**Pro Tip**: Sharing your documented project on LinkedIn is a great way to showcase your hands-on experience and attract potential employers.

---

## Conclusion

Congratulations! You've successfully created and hosted a static website on Amazon S3. This project provided valuable insights into cloud resource management and web hosting.

> **High five!** You're now one step closer to becoming an AWS pro. 🚀

**Note**: Ensure all tasks and screenshots are completed before marking the project as finished. Use the search feature to find any incomplete tasks.

---

Happy Hosting! 🌐

---
