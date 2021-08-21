# Manage Moodle User Context Roles

Requirements:

- A web service with access to the following functions
  - core_user_get_users_by_field
  - core_role_assign_roles
  - core_role_unassign_roles
- A role with the following capabilities
  - moodle/role:assign
  - moodle/user:viewdetails
  - moodle/user:viewhiddendetails
  - moodle/course:useremail
  - moodle/user:update
  - moodle/webservice:createtoken
- A user
  - assigned as an authorized user of the web service mentioned above
  - assigned the role mentioned above at the system level
  - allowed to assign specific roles in question