## Class 08


(https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)
What is Role Based Access Control (RBAC) and why do we care?
RBAC is the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment. With tight adherence to access requirements established for each role, access management becomes much easier.

The question therefore is why, with an achievable and time-honored approach, we can’t seem to get a handle on access control. We are certainly being pushed in that direction of RBAC, with all of the major standards, including PCI DSS, HIPAA and Gramm-Leach-Bliley all requiring some form of it.
<br>

Describe a Role/Permission heirarchy that you might implement using RBAC.
Supervisor getting more admin control, vs a cashier within a companies software.
<br>

What approach might you take to implement RBAC?
Create a hairarchy of who gets what permissions, and then give empoloyees the appropriate roles in order to get it to function.
<br>

(https://en.wikipedia.org/wiki/Role-based_access_control)

If Authentication is “you are who you say you are,” what is Authorization?
Are you able to acess this despite who you are? Do you have permission?
<br>

Name three primary rules defined for RBAC.
Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.
<br>

Describe RBAC to a non-technical friend.
RBAC is the way a comapny allows its employees to do certain things with software based upon their level within a company, and within the scope of their job.
<br>


(https://www.youtube.com/watch?v=C4NP8Eon3cA)
What Are access rights Associated with? The User? or The Role? Explain.
Rights are associate with file access amd associated with the role not the user. It's because certain roles like accounting may need accounting data where as security does not need access to the accounting data for their day to day.
<br>

Access Rights, or Authorization, is activated after a user successfully does what?
Authenticated.
<br>

Explain how RBAC might benefit a business.
It will keep certain files, and actions associated with a persons role at a company within scope, and only allow users authorized to do / see certain things with the appropriate files / actions.
<br>
