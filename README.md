# AWS-Day-43-Security-Implementation

AWS Account Security Implementation
This project covers the basic security setup for a new AWS account, focusing on securing access, enabling authentication controls and turning on essential logging and cost monitoring.

What Was Implemented
1. Root Account Security
•	Enabled MFA on the root account
•	Limited root usage to account-level tasks only

2. IAM Setup
•	Created an IAM admin user for daily use
•	Enabled MFA on the IAM user
•	Created IAM groups for structured access
•	Applied least-privilege permissions

3. Password Policy
•	Enforced strong password requirements (12+ characters, complexity, expiry, no reuse)

4. CloudTrail Logging
•	Enabled CloudTrail in all regions
•	Sent logs to a dedicated S3 bucket

5. Cost Alerts
•	Created an AWS Budget
•	Enabled email alerts for cost thresholds

Summary
This setup establishes a secure baseline for any AWS environment by protecting account access, enforcing MFA, logging all activity and preventing unexpected spend.
