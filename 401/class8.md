# Reading: Access Control (ACL)

## Reading

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

- What is Role Based Access Control (RBAC) and why do we care?
  - RBAC is the idea of assigning system access to users based on their role in an organization. We care because we dont want somebody who has no permissions to make changes.
- Describe a Role/Permission heirarchy that you might implement using RBAC.
  - Admin -> Manager -> Team Leads -> Employees
- What approach might you take to implement RBAC?
  - Find out all the roles and what permission each role should have

[wiki - RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

- If Authentication is “you are who you say you are,” what is Authorization?
  - Authorization is “based on who you are, what type of access are you authorized to have”.
- Name three primary rules defined for RBAC.
  -  Role based assignment, where a subject can exercise a permission only if the subject has selected or been assigned a role.
  - Role authorization: a subject’s active role must be authorized for the subject.
  - Permission authorization: a subject can exercise a permission only if the permission is authorized for the subject’s active role. In combination of the two roles above, the user can exercise only permissions for which they are aurhorized
- Describe RBAC to a non-technical friend.

### Videos

[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA&ab_channel=Udacity)

- What Are access rights Associated with? The User? or The Role? Explain.
  - In RBAC, access rights are typically associated with the role, rather than the individual user. This means that users are assigned to roles based on their job function or responsibilities, and each role is then given a set of access rights or permissions that define what actions that role is authorized to perform within the system.
- Access Rights, or Authorization, is activated after a user successfully does what?
  - Access Rights or Authorization is activated after a user is successfully authenticated, meaning the system has verified that the user is who they claim to be. Once the user is authenticated, the system can then use the RBAC rules to determine what resources the user is authorized to access and what actions they are authorized to perform within the system.
- Explain how RBAC might benefit a business.
  - RBAC can provide a structured and efficient approach to access control that helps businesses to protect sensitive data, meet compliance requirements, and improve overall security and efficiency.
