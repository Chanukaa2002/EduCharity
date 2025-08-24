# 🎓 EduCharity – Transparent Scholarship & Donation Platform

EduCharity is a **backend system built with Ballerina** that connects **donors, students, and NGOs** in a transparent way.  
It allows donors to fund campaigns, students to apply for scholarships or aid, and ensures transparency by showing exactly how donations are allocated.  

---

## 🌍 Project Overview

In many charity and scholarship platforms, **donors lack visibility** into where their money goes, and **students struggle** to access funds transparently.  
EduCharity solves this by providing a **central backend** that manages:

- **Donations & Campaigns** (track funds and progress)  
- **Scholarship Applications** (students apply for financial aid)  
- **Transparency Reports** (donors and NGOs can see how money is spent)  

This system empowers **trust, accountability, and impact measurement** in the charity + education sector.

---

## ✨ Key Features

### 🏦 Donation & Campaign Management
- Create campaigns (e.g., “Scholarships for Rural Students”)  
- Track donation progress towards goals  
- Accept donations with donor details  

### 🎓 Scholarship Applications
- Students apply for scholarships/aid under a campaign  
- NGOs/admins review and approve applications  
- Mark students as **funded** once aid is allocated  

### 📊 Transparency & Reporting
- Donors see where their money went  
- Campaign reports show **total raised, total funded students, remaining funds**  
- Builds accountability and trust in NGOs  

---

## 👥 System Roles

### 🔹 Donor
- Browse campaigns  
- Donate to a campaign  
- View donation impact via transparency reports  

### 🔹 Student
- Apply for scholarships or financial aid  
- Track application status (pending → funded)  

### 🔹 NGO / Admin
- Create and manage campaigns  
- Review scholarship applications  
- Allocate funds to students  
- Publish transparency reports  

---


## 🎯 Example User Flow (Demo)

1. **Admin creates campaign** → “Scholarships for Rural Students” (Target $5000).  
2. **Student applies** → John (19, requests $500 for tuition).  
3. **Donor donates** → Sarah donates $1000.  
4. **Admin funds student** → John marked as “Funded” with $500 allocated.  
5. **Transparency report** → Shows campaign raised $1000, 1 student funded, $500 remaining.  

---

## 🚀 Tech Stack

- **Backend Language**: [Ballerina]  
- **Database**: Prostage sql 
- **Deployment**: Docker 
- **Other Integrations**: Payment API (Stripe/PayHere), Email/SMS notifications  

---

## 💡 Why EduCharity?

- **Transparency builds trust** → Donors see real impact  
- **Empowers education** → Students get direct access to funds  
- **Hackathon-ready** → Simple, modular backend built in Ballerina  
- **Expandable** → Can add NGO collaboration, volunteer matching, and more  

---


