DevOps Intern Assignment

In this project, I set up a small cloud-based environment on AWS and automated basic system monitoring tasks using Linux tools and AWS services.

Environment Setup:

Launched a free-tier Ubuntu EC2 instance.

Created a new user devops_intern with sudo access and no password prompt.

Changed the server’s hostname to include my name.

Web Service Setup:

Installed Nginx web server.

Created a simple webpage showing my name, the instance ID, and server uptime.

Monitoring Automation:

Wrote a bash script to log system metrics: date/time, uptime, CPU, memory, disk usage, and top processes.

Scheduled the script with cron to run every 5 minutes and append results to a log file.

AWS Integration:

Created a CloudWatch log group and log stream.

Pushed the system metrics log from the EC2 instance to CloudWatch using AWS CLI.

(Optional) Set up CloudWatch alarms to notify if metrics exceeded thresholds.

Cleanup:

Documented all steps.

Terminated the EC2 instance to avoid charges.


zip file = [DevOps Intern Assignment- powerplay.zip](https://github.com/user-attachments/files/23676529/DevOps.Intern.Assignment-.powerplay.zip)
