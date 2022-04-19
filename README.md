Welcome to the iam-privilege-escalation wiki!

This will prevent abuser from creating new users with admin privileges, incase of access keys leaks.
User cannot delete policy, Permission Boundary.
User cannot terminate important Instances,RDS,S3 Bucket based on Tags.
For lambda function have to use predefined lamda function role for every new function. Limitations: Log groups will be in mumbai region for this basic lambda, or have to create another role with policy having log group in another region
