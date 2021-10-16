## cit wwek 6 

## 6.01 what is cyber security?
_Cybersecurity is the art of protecting networks, devices, and data from unauthorized access or criminal use and the practice of ensuring confidentiality, integrity, and availability of information._

_what are the risks of having poor cyber secutiry?_
* There are many risks, some more serious than others. Among these dangers are malware erasing your entire system, an attacker breaking into your system and altering files, an attacker using your computer to attack others, or an attacker stealing your credit card information and making unauthorized purchases. There is no guarantee that even with the best precautions some of these things won't happen to you, but there are steps you can take to minimize the chances.

## 6.04 AWS Shared Responsibility Model
_Security and Compliance is a shared responsibility between AWS and the customer._

_AWS responsibility “Security of the Cloud”_

_AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services._
* Physical security of data centers with controlled, need-based access; located in nondescript facilities, with 24/7 security guards; two-factor authentication; access logging and review; video surveillance; and disk degaussing and destruction.
* Hardware infrastructure, such as servers, storage devices, and other appliances that AWS relies on.
* Software infrastructure, which hosts operating systems, service applications, and virtualization software.
* Network infrastructure, such as routers, switches, load balancers, firewalls, and cabling. AWS also continuously monitors the network at external boundaries, secures access points, and provides redundant infrastructure with intrusion detection.

_Customer responsibility “Security in the Cloud”_
* While the cloud infrastructure is secured and maintained by AWS, customers are responsible for security of everything they put in the cloud.
* The customer is responsible for what is implemented by using AWS services and for the applications that are connected to AWS. 
* The security steps that you must take depend on the services that you use and the complexity of your system. 
* Customer responsibilities include selecting and securing any instance operating systems, securing the applications that are launched on AWS resources, security group configurations, firewall configurations, network configurations, and secure account management.

## 6.06 Introduction to IAM

##### What is Identity and Access Management?
_AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources for your users. You use IAM to control who can use your AWS resources (authentication) and what resources they can use and in what ways (authorization)._

##### Authorization in IAM
* Authorization is the process of determining what permissions a user, service or application should be granted. After a user has been authenticated, they must be authorized to access AWS services.
* By default, IAM users do not have permissions to access any resources or data in an AWS account. Instead, you must explicitly grant permissions to a user, group, or role by creating a policy, which is a document in JavaScript Object Notation (JSON) format. A policy lists permissions that allow or deny access to resources in the AWS account.
* To assign permission to a user, group or role, you must create an IAM policy (or find an existing policy in the account). 
* The principle of least privilege is an important concept in computer security. It promotes that you grant only the minimal user privileges needed to the user, based on the needs of your users.

## 6.07 Features of IAM

_IAM gives you the following features:_
* Shared access to your AWS account: You can grant other people permission to administer and use resources in your AWS account without having to share your password or access key.
* Granular permissions: You can grant different permissions to different people for different resources. 
* Secure access to AWS resources for applications that run on Amazon EC2: You can use IAM features to securely provide credentials for applications that run on EC2 instances.
* Multi-factor authentication (MFA): You can add two-factor authentication to your account and to individual users for extra security.
* Identity federation: You can allow users who already have passwords elsewhere—for example, in your corporate network or with an internet identity provider—to get temporary access to your AWS account.

## 6.08 Essential Elements of IAM

##### IAM User
_An IAM user is a person or application that is defined in an AWS account, and that must make API calls to AWS products._

* Programmatic access via the AWS Command Line Interface (CLI) or AWS Software Development Kit (SDK)
* AWS Management Console access via IAM were a 12 digit Account ID, IAM Username, and IAM Password are assigned with optional multi-factor authentication (MFA).

##### IAM Group

_An IAM group is a collection of IAM users. You can use IAM groups to simplify specifying and managing permissions for multiple users._

_Some important characteristics of IAM groups include:_
* A group can contain many users, and a user can belong to multiple groups.
* Groups cannot be nested. A group can contain only users, and a group cannot contain other groups.
* There is no default group that automatically includes all users in the AWS account. If you want to have a group with all account users in it, you need to create the group and add each new user to it.

##### IAM Policy
_An IAM policy is a document that defines permissions to determine what users can do in the AWS account. A policy typically grants access to specific resources and specifies what the user can do with those resources. Policies can also explicitly deny access._

##### IAM Role
_An IAM role is a tool for granting temporary access to specific AWS resources in an AWS account. An IAM role is similar to an IAM user because it is also an AWS identity that you can attach permissions policies to, and those permissions determine what the identity can and cannot do in AWS._ 

## 6.09 Four Ways to use IAM

##### AWS Management Console
_The console is a browser-based interface to manage IAM and AWS resources. For more information about accessing IAM through the console_

##### AWS Command Line Tools
_You can use the AWS command line tools to issue commands at your system's command line to perform IAM and AWS tasks. Using the command line can be faster and more convenient than the console._

##### AWS SDKs
_AWS provides SDKs (software development kits) that consist of libraries and sample code for various programming languages and platforms (Java, Python, Ruby, .NET, iOS, Android, etc.)_

##### IAM HTTPS API
_You can access IAM and AWS programmatically by using the IAM HTTPS API, which lets you issue HTTPS requests directly to the service_

## 6.12 Securing Accounts
_Securing the cloud is about more than just using Identity and Access Management._

##### AWS Organizations
_AWS Organizations is an account management service that helps you centrally govern your environment as you grow and scale your workloads on AWS_
* Ability to centrally manage policies across multiple aws accounts
* Automation of aws account creation and management
* Consolidation of billing across multiple aws accounts
* Ability to govern access to aws services, resources, and regions
* Ability to configure aws services across multiple accounts

## 6.13 Securing Data
_Careful consideration must be taken when protecting data as it is often worth more than the hardware it is stored on_

## Data at Rest
_Data at rest is any information that is stored on a disk, tape or any medium in which it is not moving from system to system:_

_You have the following options for protecting data at rest in Amazon services:_

* Server-Side Encryption – Request Amazon to encrypt your data before saving it on disks in its data centers and then decrypt it when you download the data.
* Client-Side Encryption – Encrypt data client-side and upload the encrypted data to an Amazon data center. In this case, you manage the encryption process, the encryption keys, and related tools.

1. Summarize a few key points made in the readings or videos.
_cyber secutiry is really important to keep the data safe from people or sofware viruses._
2. Identify two quotes that were made, that you found interesting.
_"Among these dangers are malware erasing your entire system, an attacker breaking into your system and altering files, an attacker using your computer to attack others, or an attacker stealing your credit card information and making unauthorized purchases". i think it is so crazy your life can change so much from all that_
3. What new facts did you learn from this section?
_"There is no guarantee that even with the best precautions some of these things won't happen to you"_
4. What questions remain in your mind after reading this section?
_what is cyber security? is my only questioni feel_
