---
title: "Week 7 Worklog"
date: 2026-02-16
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:
* Optimize data and static asset delivery performance using a Content Delivery Network (CDN).
* Analyze and evaluate the cost and security risks of the current system architecture.
* Research alternative architectural solutions for future flexibility and cost savings.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | Resources |
| :--- | :--- | :--- | :--- | :--- |
| Mon | Established a connection between Amazon RDS and the Amplify-hosted Frontend, routed through Amazon CloudFront. | 22/09/2025 | 22/09/2025 | AWS Documentation |
| Tue | Integrated Amazon S3 with CloudFront to accelerate product image fetching, laying the groundwork for future scalable features. | 23/09/2025 | 23/09/2025 | AWS Optimization |
| Wed | Compiled and analyzed the Cost Estimation for the cluster of AWS services currently running in the project. | 24/09/2025 | 24/09/2025 | AWS Pricing Calculator |
| Thu | Evaluated the overall project architecture from two perspectives: User Data Security and System Scalability. | 25/09/2025 | 25/09/2025 | AWS Well-Architected |
| Fri | Began researching Amazon ECS (Elastic Container Service) and the concept of application containerization. | 26/09/2025 | 26/09/2025 | AWS Documentation |

### Week 7 Achievements:
* **Experience Optimization:** The delivery of static content is noticeably faster thanks to the tight integration between S3 and CloudFront.
* **Advanced Systems Thinking:** Learned to view the project at a larger scale, questioning safety and scalability in the face of potential user traffic spikes.
* **Cost Awareness:** Concluded that maintaining traditional Amazon EC2 servers continuously could lead to resource waste and high costs. This set the stage for the team to pivot toward more optimal solutions like ECS (Containers).