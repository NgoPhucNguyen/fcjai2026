---
title : "Executing Data Retrieval with Prisma"
date : 2026-04-02 
weight : 3
chapter : false
pre : " <b> 4.3.3 </b> "
---

### 📑 4.3.3 Executing Queries & Storing Data

Here is an example describing how the Backend system interacts with the Database to handle main business workflows.

#### 1. User Registration and Management Flow
When a new user registers, the system verifies the uniqueness of their Email. If valid, the information is written to the `Customer` table on RDS. Prisma ensures that data constraints (such as email uniqueness) are strictly enforced.

![user-flow](/images/4-Workshop/4.3-DB-setup/user-management-ui.png)

#### 2. Retrieving Analysis and Payment History
Users can view the items they have paid for. The system will display the complete payment and transaction details.

![history-view](/images/4-Workshop/4.3-DB-setup/history-ui.png)

---