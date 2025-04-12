**OCI Day 1**

**Instal VS Code and Setup Github**
1. Go to https://code.visualstudio.com/download
2. Open installer.exe and agree the terms and conditions and finish the setup
3. Open VScode
4. Search and install Github copilot from extensions menu
![image](https://github.com/user-attachments/assets/8b5b4391-8668-4eaf-8fca-61656367ff75)
5. Click sign in with github
![image](https://github.com/user-attachments/assets/72ddb5ca-948e-462d-8dc6-574bcb654d34)
else sign up with email ID:
![image](https://github.com/user-attachments/assets/04ac9c40-cc40-4482-b5ca-ef3d68048e53)
6. Sign in with Github
7. On the dashboard click on new
![image](https://github.com/user-attachments/assets/99bdb66c-db5a-4c3f-8053-d36094348c96)
This will create a new repo
![image](https://github.com/user-attachments/assets/73d0e97a-ca74-4129-b754-d9dfa97ba01b)
8. Select the wiki option from the tab
![image](https://github.com/user-attachments/assets/a215cffe-bdcc-4d21-8bb1-9ad5394a66f7)
9. Click on Add File -> Create new File ->
![image](https://github.com/user-attachments/assets/0ddda393-9caf-40ef-b90b-9c850bd21fbc)
10. Rename the file and Commit to Save changes

**CREATE ACCOUNT IN OCI**
1. Go to https://signup.cloud.oracle.com/
2. Fill the below form and verify email
   ![image](https://github.com/user-attachments/assets/8437c8dc-99e9-44ed-80ed-1bf6ea9aba47)
3. Verify the email from mail address
4. Provide the Password and select the region and account name
5. Select account type as Individual and give an account name
6. Select region as US East(Ashburn) because most services are available there
7. Select next and on the next page provide the billing address mentioned in the credit card
8. Select verify payment by providing your credit card details.
9. Wait for your account to get created
10. Login to your default tenancy and add Oracle authenticator


Q: What is oracle cloud?
A: Oracle Cloud is Oracle Corporation’s comprehensive suite of cloud computing services that helps businesses build, deploy, and manage applications and workloads in a secure and scalable environment. It includes Oracle Cloud Infrastructure (OCI), which provides core infrastructure services like compute, storage, networking, and databases, and is designed to compete with other major cloud providers like AWS and Azure. Oracle Cloud also offers platform services (PaaS) for developers and data professionals, along with a wide range of SaaS applications for enterprise needs such as ERP, HCM, and CRM. Known for its high-performance infrastructure and strong support for Oracle databases and applications, Oracle Cloud is widely used by enterprises looking for reliable, secure, and integrated cloud solutions.

Q: Difference between On-Prem and cloud
A: On-Premises infrastructure is owned, operated, and maintained by the organization itself, giving complete control over hardware, security, and data, but also requiring high upfront costs, ongoing maintenance, and scalability limitations. Cloud computing, on the other hand, allows businesses to rent resources like storage, compute power, and databases on demand from third-party providers, offering greater scalability, reduced capital expenditure, and faster deployment, while shifting the responsibility for hardware management and upgrades to the provider.

Q: What is Tenancy
A: In Oracle Cloud Infrastructure (OCI), a Tenancy represents your organization's primary cloud account and acts as the top-level container for all your resources. When you subscribe to OCI, a Tenancy is automatically created with a unique Oracle Cloud Identifier (OCID), and it serves as the foundational space where you manage all services, resources, and configurations. Within this Tenancy, you create compartments to logically segment and organize resources such as compute instances, databases, and storage, while access controls and policies are applied at both the Tenancy and compartment levels. Essentially, the Tenancy sets the boundary for all your cloud operations, ensuring that your environment is properly structured, secure, and manageable.

Q: Difference between region vs Ad and Fd
Concept	Region	Availability Domain (AD)	Fault Domain (FD)
Definition	A geographical area (e.g., India West)	A data center within a region	A logical group within an AD for fault isolation
Scope	Broadest (contains multiple ADs)	Part of a region	Subset of an AD
Purpose	Enable global distribution	Provide high availability across data centers	Increase resilience within an AD
Redundancy Level	Global	Regional (data center-level)	Rack/power unit-level
Failure Isolation	Region-wide events	Isolated from failures in other ADs	Isolated from failures in other FDs
Example	us-ashburn-1, india-hyderabad-1	AD-1, AD-2, AD-3 (in a region)	FD-1, FD-2, FD-3 (inside one AD)
Deployment Use Case	Disaster recovery & global scaling	High availability within a region	Resilience against hardware failure
