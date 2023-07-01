# Access Control (ACL)

- What is Role Based Access Control (RBAC) and why do we care?
>method for managing access to resources within an application

- Describe a Role/Permission heirarchy that you might implement using RBAC.
>1.Admin role: Admin has full control over the system.

>2.Manager role: Manager typically has permissions to manage specific departments within the system,it can view and modify data that related to their respective areas.

>3.Employee role: Employee has limited access ,the employee can view and update relevant data within their assigned department but he does not have administrative privileges.

>4.Guest role: Guest has minimal acces, It may only have read-only access to certain public information within the system.

- What approach might you take to implement RBAC?
>1.determine each role in the system by analyze the system structure, and access requirements to determine the different roles that exist within the system.

> 2.determine permissions by determine the specific operations that can be performed within the system, also determine permissions to roles based on functional requirements.
>3.assign the roles: Assign users to the relevant roles based on their job requirements and their job responsibilities also.

- If Authentication is “you are who you say you are,” what is Authorization?

- Name three primary rules defined for RBAC.
> 1-Role Assignment

> 2-Role Authorization

> 3-Role-Permission Association

- Describe RBAC to a non-technical friend.
>RBAC, which stands for Role-Based Access Control, is a way to manage and control access to different things, like information or features, in a system or organization. Imagine it like a big building with different rooms and areas. RBAC helps ensure that only the right people can enter specific rooms or use certain resources.

- What Are access rights Associated with? The User? or The Role? Explain.
>Access rights in RBAC (Role-Based Access Control) are associated with roles, not individual users.
>In RBAC, access rights or permissions are assigned to roles based on the responsibilities and job functions associated with those roles.

- Access Rights, or Authorization, is activated after a user successfully does what?
> Access rights(authorization) are activated after a user successfully authenticates themselves.

- Explain how RBAC might benefit a business.
>1. Improved Security, RBAC grants access rights based on job roles in the system,This helps protect sensitive information from the risks of unauthorized access.
>2. Enhances productivity: RBAC helps improve efficiency and reduce problems caused by unauthorized actions and operations, it streamline workflows efficient.

