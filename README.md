# Cloud-Monitoring-and-alerts
Task 2

COMPANY: CLOUDTECH IT SOLUTIONS

NAME: NEHA SATPUTE

INTERN ID: CTIS5002

DOMAIN: CLOUD COMPUTING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

Cloud Monitoring and Alerts Using Amazon CloudWatch

During this task, I implemented cloud monitoring and alerting for a cloud-based application using Amazon Web Services. The main objective of the task was to understand how monitoring tools work in cloud environments and how alerts can be configured to notify administrators when system performance crosses certain thresholds. For this task, I used services such as Amazon EC2, Amazon CloudWatch, and Amazon Simple Notification Service.

First, I created a virtual server using Amazon EC2. I launched an EC2 instance using the Amazon Linux operating system and selected the t2.micro instance type, which is suitable for basic testing and is also included in the AWS free tier. After launching the instance, I verified that the server was running properly and connected to it using the EC2 Instance Connect feature available in the AWS management console.

After successfully launching the EC2 instance, the next step was to configure monitoring using Amazon CloudWatch. CloudWatch automatically collects basic performance metrics from AWS resources such as CPU utilization, network traffic, and disk activity. I navigated to the CloudWatch dashboard and created a custom monitoring dashboard to visualize the performance of my EC2 instance.
While creating the dashboard, I added several widgets to display important system metrics. These included CPU Utilization, Network In, Network Out, and Disk Read/Write metrics. I used line graphs to visualize how these metrics changed over time. This dashboard allowed me to observe the behavior and performance of the instance in real time. The graphical representation made it easier to understand how the server resources were being used.

Next, I configured an alert system to notify me when CPU utilization exceeded a defined threshold. To achieve this, I created a CloudWatch alarm based on the CPU Utilization metric. I set the alarm condition so that if the CPU utilization exceeded 70% for a specific time period, the alarm would be triggered. Once the threshold was crossed, the monitoring system would send a notification.

To receive the alert notifications, I used Amazon Simple Notification Service (SNS). I created an SNS topic and subscribed my email address to that topic. AWS then sent a subscription confirmation email which I confirmed to activate the notification system. After this setup, whenever the alarm condition was triggered, I would receive an email notification informing me about the high CPU usage.

To test the alert system, I connected to the EC2 instance terminal and executed commands that increased CPU usage. This artificially generated a higher workload on the server. As the CPU utilization increased, I observed the changes in the CloudWatch dashboard. After the CPU utilization crossed the defined threshold, the CloudWatch alarm was triggered successfully and I received an email alert through SNS.
Overall, this task provided hands-on experience with cloud monitoring and alert configuration using AWS services. It helped me understand how real-world cloud systems are monitored and managed to maintain reliability, performance, and availability.

#output
<img width="1870" height="682" alt="Image" src="https://github.com/user-attachments/assets/e65110c1-f25d-4026-b610-7375644cf093" />

<img width="1912" height="667" alt="Image" src="https://github.com/user-attachments/assets/3e85a7c2-f03e-4195-a22d-dcf624a76ed5" />

<img width="1782" height="891" alt="Image" src="https://github.com/user-attachments/assets/e2342b77-af83-4797-9274-567d348721d3" />

<img width="1782" height="891" alt="Image" src="https://github.com/user-attachments/assets/c8bf24cd-65fe-4b82-9dc8-96af75ff1ce8" />

<img width="1732" height="903" alt="Image" src="https://github.com/user-attachments/assets/1c08c0a1-f0e9-4f96-a40f-c373e16992d1" />
