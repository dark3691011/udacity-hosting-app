# Infrastructure

## Database
- Database Engine: We utilize Amazon RDS (Relational Database Service) with PostgreSQL as the database engine. RDS is a managed service by AWS that simplifies database provisioning, operation, and scaling. PostgreSQL is a powerful, open-source object-relational database management system (ORDBMS) known for its reliability and rich feature set.

## Front-end hosting
- Front-end Framework: The front-end application is built using Angular, a popular JavaScript framework for building dynamic and interactive web applications.
- Hosting Platform: Amazon S3 with static website hosting enabled serves the front-end application. S3 is a scalable object storage service offered by AWS. By enabling static website hosting, S3 can directly deliver the static content of the front-end application (HTML, CSS, JavaScript files).

## Backend hosting
- Backend Framework: The backend logic is implemented with Express.js, a popular Node.js framework for building web applications and APIs.
- Deployment Platform: AWS Elastic Beanstalk provides a managed environment for deploying and scaling web applications. It simplifies the deployment process by handling server provisioning, configuration, and load balancing.