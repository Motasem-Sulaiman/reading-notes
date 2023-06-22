## What is Role Based Access Control (RBAC) and why do we care?


Access Control (RBAC) is a security model used to manage and enforce access permissions in computer systems. It provides a structured and centralized approach to controlling access to resources based on the roles individuals have within an organization.


## Describe a Role/Permission heirarchy that you might implement using RBAC.

Admin: Administrative role with privileges to manage user accounts, roles, and permissions.

Manager: Has access to specific management functions and responsibilities within the system.

Team Lead: Manages a specific team or group within the organization.

User: Basic access to relevant system functionalities based on job responsibilities.



## What approach might you take to implement RBAC?

 - Roles: Defined based on job functions or responsibilities

 - Permissions: Permissions define the specific actions or operations that users can perform within the system.

 - User-Role Assignment: Users are assigned to specific roles based on their job requirements.

 - Role Hierarchy: Roles can be organized in a hierarchical structure, where higher-level roles inherit permissions from lower-level roles.


## If Authentication is “you are who you say you are,” what is Authorization?
Authorization is the process of granting or denying access to specific resources or functionalities based on a user's authenticated identity and their assigned privileges or permissions

## Name three primary rules defined for RBAC.

 - Role assignment: This rule specifies that access rights and permissions are assigned to roles rather than directly to individual users.

  - Role authorization: This rule states that access decisions are based on a user's assigned role. Once a user is authenticated, their access rights and permissions are determined by the role they have been assigned

  - Permission: This rule ensures that access control is enforced based on the permissions associated with a user's assigned role.


  ## Describe RBAC to a non-technical friend.
  if you have a website u need to specify the permission for every user that want to use your website , for example you give admin permission for a user that can make changes in your website like edit content ,and for another one give a permission user that can only read your content 


  ## What Are access rights Associated with? The User? or The Role? Explain.

  access rights in RBAC are associated with roles, and users inherit those access rights by being assigned to specific roles. This approach simplifies access management and provides flexibility for assigning and modifying permissions based on user roles.


 ## Access Rights, or Authorization, is activated after a user successfully does what?

 once a user proves their identity through authentication, the system then checks their authorization to determine what they are allowed to do and what they are not allowed to do .

 ## Explain how RBAC might benefit a business.

 - Improved Security: RBAC enhances security by ensuring that users have access only to the resources and functionalities that are necessary for their roles

 - Increased Productivity: RBAC ensures that users have the necessary access to perform their job responsibilities efficiently.

 - Scalability and Flexibility: RBAC provides a scalable and flexible approach to access control. As businesses grow and change, RBAC allows for the addition of new roles and the adjustment of permissions to match evolving requirements