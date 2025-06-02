# aws-restart-journey-
My learning journey through the AWS re/Start bootcamp.
## 📚 AWS re/Start Study Diary – Databases (DynamoDB & Aurora)
🗓️ Date: 2nd June 2025

Today I explored both **DynamoDB** and **Amazon Aurora**, two powerful database services on AWS. I gained a strong theoretical foundation in DynamoDB, followed by a hands-on lab introducing me to Aurora.

---

### 🔹 DynamoDB – Core Concepts

#### 📁 Tables
- Data is stored in **tables**, similar to relational databases.
- Each table must have a **primary key** to uniquely identify items.

#### 🔑 Primary Keys
- **Simple key**: one attribute (partition key).
- **Composite key**: two attributes (partition key + sort key).
- Determines **uniqueness** and **data placement**.

#### 🧱 Attributes
- Equivalent to columns in relational databases.
- Can vary in type and quantity between items.

#### 📦 Items
- A single record in the table (like a row).
- Flexible schema: items don’t need the same attributes.
- Must have a primary key.

#### 📊 Partitions
- Data is distributed across partitions based on the partition key.
- Improves scalability and performance.
- DynamoDB automatically adds partitions as needed.

#### 🌍 Global Tables
- Automatically replicate data across multiple AWS Regions.
- Improve latency and availability for global applications.
- Fully managed data syncing between replica tables.

---

### 🔹 Amazon Aurora – Intro Lab Summary

I also completed a practical lab where I worked with **Amazon Aurora**, a high-performance relational database built for the cloud.

#### ✅ Topics Covered:

- **Created an Amazon Aurora instance**
- **Connected to a pre-created Amazon EC2 instance**
- **Configured the EC2 instance to connect to Aurora**
- **Ran SQL queries on the Aurora database**

#### 🧠 Key Learnings:
- Aurora supports MySQL/PostgreSQL engines.
- You can interact with Aurora from an EC2 instance via a MySQL-compatible client.
- This setup simulates how back-end services connect securely to a cloud database.

---

✅ **Summary:**
Today, I solidified my understanding of **DynamoDB** concepts (NoSQL) and got hands-on with **Amazon Aurora** (relational). This helped me compare different types of AWS databases and how to use them in real-world scenarios.

