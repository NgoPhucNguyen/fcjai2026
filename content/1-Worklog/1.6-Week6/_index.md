---
title: "Week 6 Worklog"
date: 2026-02-09
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:
* Efficiently store and deliver static assets (cosmetic images) via Amazon S3.
* Explore and test optimal hosting solutions for the platform's Frontend.
* Resolve Production deployment issues using supplementary AWS services.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | Resources |
| :--- | :--- | :--- | :--- | :--- |
| Mon | Uploaded product images to Amazon S3, configured access permissions, and integrated image links into the EC2 system. | 15/09/2025 | 15/09/2025 | AWS Documentation |
| Tue | Conducted an overview study of AWS web/mobile ecosystem services such as AWS Amplify, Amazon CloudFront, and AWS AppSync. | 16/09/2025 | 16/09/2025 | AWS Training |
| Wed | Tested AWS Amplify for hosting the Frontend source code. | 17/09/2025 | 17/09/2025 | Amplify Docs |
| Thu | Addressed errors in the Amplify Production environment; identified limitations and pivoted to using CloudFront as the solution. | 18/09/2025 | 18/09/2025 | AWS Community |
| Fri | Conducted deep research into Amazon CloudFront (CDN), practiced designing Origins, and configured Cache Behaviors. | 19/09/2025 | 19/09/2025 | AWS Documentation |

### Week 6 Achievements:
* **System Architecture Mindset:** Understood the fundamental principles of various AWS services (S3, EC2, Amplify, CloudFront) and how they interact to form a complete system.
* **Static Resource Management:** Successfully integrated S3 for image storage, offloading traffic from the EC2 server.
* **Problem-Solving Skills:** Demonstrated agility in identifying Production limitations of one service (Amplify) and proactively adopting a better alternative (CloudFront) to keep the project on track.