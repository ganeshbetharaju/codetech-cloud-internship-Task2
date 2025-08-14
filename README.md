---

## Task 2: Cloud Monitoring and Alerts with AWS CloudWatch

**Objective:** To monitor a key metric of a cloud-based resource and configure an alarm to trigger based on a specific threshold. I chose to monitor the CPU utilization of an EC2 virtual server.

### Step 1: Setting Up the Monitored Resource
I launched a new `t2.micro` EC2 instance to serve as the application resource to be monitored.

### Step 2: Configuring the Metric and Alarm in CloudWatch
1.  **Navigated to CloudWatch:** In the AWS Console, I went to the CloudWatch service.
2.  **Selected Metric:** Under "All metrics," I selected the `EC2` namespace, chose "Per-Instance Metrics," and selected the **CPUUtilization** metric for my instance.
3.  **Created Alarm:** From the graphed metric, I created an alarm. I configured it to trigger when the **CPUUtilization** was greater than or equal to a set percentage (e.g., 70%) for a sustained period.

### Deliverable: Dashboard and Configured Alerts

#### 1. Metric Dashboard Showing CPU Utilization and Alert/Alarm
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/318ae118-3ef2-4888-9c31-7de5ab865873" />
