# AWS Certified Cloud Practitioner Notes
## Section: IAM - Identity and Access Managment

### 📌 Key Concepts
-  **IAM:** Identity and Access Managment (Global Service)
- 
- 

### 🛠️ AWS Services Covered
- 
- 
- 

### 💡 Exam Tips
- 
- 
- 

### 🔍 My Takeaways
- **Users and Groups**
  - *Groups* contain users, not other groups
  - Not all users need to be in a group
  - Groups are used to apply permissions to users within your organization.
  - *Policies* are JSON docs that contain the rules for a group.
  - *Least privilege principle* give users the minimum ammount of permissions needed.
  - *Inline Policy* a policy that is attached directly to a user, not to a group.
- **IAM Policy Structure**
  - *Version* plolicy version, must be included.  current:  "2012-10-17"
  - *id* policy identifier, optional
  - *Statement* individueal statments that form the policy, required
    - *Sid* statement id, optional
    - *Effect* toggles statement access (allow or deny)
    - *Principal* account user or role the policy is applied to
    - *Action* list of actions the policiy allows (or denies)
    - *Resource* list of resources the actions are applied to
    - *Condition* list of conditions for when policy is in effect (optional)
- 

---

*Notes taken from [Udemy AWS CCP Course by Stephane Maarek](https://www.udemy.com/)*