Create simple serverless projects using [AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html) or using |

#### Projects 
- serverless image resizing: accepts an image upload, uses lambda to resizes the image and uploads to s3
- contact form submission: provide a front end to submit a form, which uses API gateway to expose the endpoint, AWS lambda as the backend service and send a email AWS SES to send an email.
- data pipeline: develop using AWS lambda and step functions, the pipeline can process and transform data using various sources, perform analytics and store results in a database or data warehouse. (advanced)

###### Production ready project: E-commerce Application

Description: Build an end-to-end serverless e-commerce application that allows users to browse products, add items to their cart, and complete purchases. The application should handle high traffic, scale automatically, and ensure a secure and seamless shopping experience for customers.

Key Components and Services:

1. AWS Lambda: Use Lambda functions to handle various functionalities, such as product catalog management, user authentication and authorization, cart management, and order processing.
2. Amazon API Gateway: Create RESTful APIs to expose the application's functionalities securely.
3. AWS DynamoDB: Use DynamoDB to store product information, user data, and shopping cart details.
4. AWS S3: Store product images and static website content.
5. AWS Cognito: Implement user authentication and authorization using Cognito User Pools, allowing users to register, log in, and manage their accounts.
6. AWS Step Functions: Build a serverless workflow to handle order processing, including payment validation, inventory management, and order fulfillment.
7. AWS SES: Send transactional emails, such as order confirmation and shipping notifications, to customers.
8. AWS CloudFront: Use CloudFront to deliver the application's static assets and provide low-latency content delivery.
9. AWS Route 53: Configure DNS routing for your application's domain name.
10. AWS CloudWatch: Set up monitoring and logging to gain visibility into the application's performance, usage, and errors.
11. AWS X-Ray: Implement distributed tracing to monitor and analyze the application's performance and identify bottlenecks.

Key Features:

1. Product Catalog: Allow users to browse and search for products, view detailed product information, and add items to their cart.
2. User Management: Enable user registration, login, and account management functionalities.
3. Shopping Cart: Implement a persistent shopping cart to allow users to add, remove, and update items in their cart across sessions.
4. Order Placement: Allow users to complete purchases, process payments securely, and receive order confirmation.
5. Order Processing: Build a serverless workflow to manage the order fulfillment process, including inventory management and integration with third-party payment gateways.
6. Notifications: Send transactional emails to customers for order confirmation, shipping updates, and other relevant notifications.