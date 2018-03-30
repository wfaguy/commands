# WFA Commands
The following WFA commands are currently in the library.

## Enable Full Workflows RBAC
This command will add a "No Category" category (if needed), move all non-assigned workflows to this category and finally enable RBAC restriction on all categories.

Why this command ?  By default everyone can run every workflow.  You can hide them in the admin, but from the rest-api they are still there.  That's dangerous.  This command will restrict ALL workflows at once. Only manually assigned users and groups (and admins) will now have access to the workflows.

