# Access Control

## What is Role Based Access Control (RBAC) and why do we care?

a widely used access control mechanism that provides a structured approach to managing permissions and access privileges within an organization's systems or applications. Roles define a set of permissions and privileges that are associated with specific job functions or responsibilities within an organization. Permissions specify the actions or operations that can be performed on a particular resource or system.

## Describe a Role/Permission heirarchy that you might implement using RBAC.

Role: Guest

Permissions:
View products
Register as a new user
Add products to the cart

Role: Customer

Permissions:
All permissions of the Guest role
Purchase products
Manage user profile

## What approach might you take to implement RBAC?

Identify Roles, Determine Permissions, Assign Permissions to Roles, Map Users to Roles, Implement Access Control

## If Authentication is “you are who you say you are,” what is Authorization?

 involves granting or denying access to specific actions, operations, or resources based on an authenticated user's privileges or permissions.

## Name three primary rules defined for RBAC.

 Role Assignment, Role Authorization, Role Permissions

## Describe RBAC to a non-technical friend.

Imagine you have a favorite amusement park with different areas and attractions. The park has many staff members responsible for various tasks, such as ticketing, ride operations, and maintenance. Each staff member has a specific role and set of responsibilities.let's compare this amusement park scenario to Role-Based Access Control (RBAC). In RBAC, an organization's computer system or application is like the amusement park, and the staff members are the users of that system.Just as in the amusement park, each staff member is assigned a particular role, such as ticket seller, ride operator, or maintenance crew. Similarly, in RBAC, each user is assigned to a role, like a customer support representative, manager, or administrator, depending on their job in the organization.

## What Are access rights Associated with? The User? or The Role? Explain.

associated with roles, not individual users. In RBAC, permissions and access privileges are defined at the role level, and users acquire those permissions by being assigned to specific roles.

## Access Rights, or Authorization, is activated after a user successfully does what?

 after a user successfully authenticates or proves their identity. 

 ## Explain how RBAC might benefit a business.

 Enhanced Security, Improved Access Control, Compliance and Auditability, Increased Productivity

 ## What are your learning goals after reading and reviewing the class README?

 I am excited to learn more about authentication and authorization
 
