# AWS_Solutions_Architecture_job_simulation
This repository documents my completion of the AWS Solutions Architecture Job Simulation offered by Forage (September 2025).
The task was based on a real-world client scenario: a customer experienced website downtime, and I had to propose a reliable AWS-based architecture to minimize downtime and improve availability.

Objective

- Analyze client requirements in case of downtime.
- Propose an AWS architecture using suitable services.
- Communicate the solution in simple, client-friendly language.

AWS Services Used

- Route 53 → Domain and DNS management.
- Elastic Load Balancing (ELB) → Distributes traffic across healthy servers.
- Elastic Beanstalk with Auto Scaling EC2 Group → Simplifies deployment and ensures scalability.
- RDS (PostgreSQL) → Relational database hosting with standby replication.
- S3 → Object storage for backups.
- CodePipeline → Automates code build and deployment.

Proposed Solution (Client Draft)

- Route 53 connects the domain to AWS and manages DNS routing.
- Traffic is directed through Elastic Load Balancer, which distributes requests across multiple Availability Zones for high availability.
- CodePipeline deploys application code to EC2 Instances within an Auto Scaling Group, ensuring resilience during traffic spikes.
- RDS PostgreSQL is used as the database, with replication to a standby instance for fault tolerance.
- S3 Buckets store backups and static content, reducing risk of data loss.
This setup minimizes downtime by ensuring that if one server or zone fails, traffic is rerouted automatically to healthy resources.

Key Learnings

- How to explain technical solutions in simple terms for non-technical clients.
- Experience in balancing technical accuracy with client-friendly communication.

Certificate

Issued by Forage on September 2025
You can view my [AWS Solutions Architechture Job Simulation](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/pmnMSL4QiQ9JCgE3W/kkE9HyeNcw6rwCRGw_pmnMSL4QiQ9JCgE3W_68c1facde927094fbe809217_1757674415411_completion_certificate.pdf)
