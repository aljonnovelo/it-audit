# Control Objective: Logical Access Security

## A. Access and Privilege Management
### A.1. Access Approval
- There are procedures (submission, review, approval, logging) for:
  - requesting new access or existing access (OneIdentity)
  - temporary access to customer data and applications, in case of customer support or incident handling (Just-In-Time Access, Break-Glass Accounts, Geneva Actions)
  - physical access to production environments (authorized user request, approval, limited time access, logging)
  - access revocation due to termination (24 hrs)

### A.2. Privileges
- Administrative access requires authentication and appropriate credentials.
- Read and write privileges are based on job responsibilities.

### A.3. Periodic Review
- Access privileges are reviewed quarterly.
- Procedures are in place on a timely basis upon employee termination. Access to the following is revoked:
  - production machines
  - support tools
  - network devices
  - corporate assets
- Inactive accounts are disabled after 90 days.
- Critical access groups are reviewed, and inappropriate access is removed.

## B. Authentication and Authorization
### B.1. Authentication
- Organizations have password policies. These include:
  - expiration
  - length
  - complexity
  - history
- Two-factor authentication is required for remote access.
- Workstations require a password to unlock after 15 minutes of inactivity.
- Access to internal systems requires a password with a security key and/or certificate.
- External users are identified via Google Accounts or BYOID authentication.

### B.2. Authorization
- Only users with a valid user certificate, private key, and authorization can access production systems via SSH.
- There are mechanisms that detect and prevent connections from unauthorized devices.

## C. Logs, Records, and Lists
### C.1. Active Records
- Access to the internal network is not provisioned unless an active record is created by the HR department.

### C.2. Access Control Lists
- Security logs are protected through encryption and access control lists.

## D. Security Measures
### D.1. Internal Investigation Team
- The organization has a team for monitoring, maintaining, managing, and securing the internal systems.

### D.2. Physical Device Security
- There are perimeter devices to protect the network from external network attacks.
- Users are required to lock their workstations when leaving their desks.

### D.3. Encryption
- User authentication and administrator sessions are encrypted.
- Transit between production environments is encrypted.