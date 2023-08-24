# Report: Day2

project name: Mail-server-Backend[SSH:10.1.1.152]
```
Task: Need to add user activity logging to all controllers.
For that, first need to use the "App\Traits\UserActivityLoggable"
trait in each model and define the method "getUserActivityLogName"
which should return a string name like "departments" for the
"Department" model. "designations" for the "Designation" model.
Then in each controller, in "store" and "destroy" methods, you need to
call the function "Department::logUserActivity()" just before the
return method. Examples for the same can be found in
DepartmentController, DesignationController and MailUserController.

```

Done by me: (side by side)
Laravel version 10 installation and new features exploration(Read)
