# 401 class_08

## 5 steps to RBAC

- What is Role Based Access Control (RBAC) and why do we care?

RBAC is a system that reuses the  same permissions based off of the role the new hire takes on instead of basing permissions on the new hire themself. We care because this saves us time as each permission is reusable based on the role the new hire is assigned.

- Describe a Role/Permission heirarchy that you might implement using RBAC.

First you have the Access Rights you know that a specific Role will need to do their job effectively. Below that you have the Role which you need to connect the User to their Access Rights. At the bottom you have the User who will be assigned a Role to ultimately recieve their Access Rights.

- What approach might you take to implement RBAC?

I would decifer what is the minimum clearance a role would need to effectively do their job. Then I would write the logic to grant access to these permissions. Next, I would write logic that says 'If this a user has this role, allow them these permissions we previously defined. Lastly, I would make some sort of authorization barrier seperating users from roles. If the user is able to pass this barrier to become a user with a role, they now have the ability to use the clearance allotted to the role.

## wiki - RBAC

- If Authentication is “you are who you say you are,” what is Authorization?

Authorization is the process of proving something is valid. 

- Name three primary rules defined for RBAC.

  - Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
  - Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
  - Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

- Describe RBAC to a non-technical friend.

This is a way to allow us to not have to spend extra time assigning permissions to specific people. This way is much more time effective. We specific permissions accesable only to specific roles. As people come in and out of those roles, they gain and forfeit those permissions.

## RBAC tutorial

- What Are access rights Associated with? The User? or The Role? Explain.

Access rights are associated with the role that the user is assigned so that new access rights aren't having to be re-drummed up each time a new user comes onto the scene.

- Access Rights, or Authorization, is activated after a user successfully does what?

Once a user is authorized to be in a certain role their access rights are activated.

- Explain how RBAC might benefit a business.

A good developer writes re-usable code right? This is the same principal here. It allows a business to keep the same re-usable access rights no matter how many new hires they bring in or let go of because the access is reliquished to specific roles instead of people. This way they don't have to make new access standards fitting each hire. Instead they assign a new hire a role and they are ready to go with all the access they need to do their job.
