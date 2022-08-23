
## IAM credential Reports
* a report that list all your accounts user and the status of their various credentials

## IAM Access Advisiors 
* Access advisor shows the service permission granted to  a user and when those services were last accessed
* You can use this information to revise your policies


# IAM GUIDELINES 

* Donot use the root account except for AWS account setup
* One physical user = One AWS user
* assign users to groups and assign permissions to groups
* Create a strong password
* Use and enforce the use of MultiFactor Authentication
* Creaze and use Roles for giving permission to AWS services
* Use access key for programmtic Access (CLI) ps. these access keys are just like password kep them save
* Audit Permission of your account with IAM credenital report, which gives information about status of the users' credentials, including passwords, access keys, MFA devices, and signing certificates


# IAM Section- Summary

* Users: mapped to a physical user, has password for AWS console
* Better to create Groups (contain user that contain same rights)
* Policies: JSON document that outlines permissions for users or groups
* Roles: They are defined for EC2 instance, Lamda or other AWS services
* Security: MFA + Strong Passowrd
* Access Key: access AWS using CLI or SDK, if you want to do something related to programming (the access keys can be generated and downloaded but must be kept confidential)
* Audit: IAM credenital Reports & IAM Access advisor are use for the audits, for example Access advisor will tell you who access what (updates in four hours)


# Important

* IAM credential is a security tool, it creates a report that lists all your AWS Account's IAM Users and the status of their various credentials.
* IAM User Groups can not be part of other User Groups.
* A statement in an IAM Policy consists of Sid, Effect, Principal, Action, Resource, and Condition. 
* Version is part of the IAM Policy itself, not the statement.

# What IAM policy consist of
