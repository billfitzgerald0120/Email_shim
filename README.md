# Email_shim
Shim for pre 5.10 email settings

In the 5.10 release of CFME we are consolidating the email methods into a single method and using instances for configuring the email. The email method is a built in method that gets directly called by the Automation Engine once it has all of the email parameters (to, from, subject, body, signature) defined in the instance. The parameters can be optionally configured using a method before calling the mail method. The default email parameters can be defined in /ManageIQ/Configuration/Email/default instance and used in the different email instances. It allows for a single location to configure default parameters (from, signature, default_recipient).

If you wish to use the pre 5.10 email, you can 


In Server Roles, Enable Git Repositories Owner
Go to Automation, Automate, Import / Export
Under Import Datastore via git, enter Git URL: https://github.com/billfitzgerald0120/Email_shim and enter.
Click Submit, Branch and origin/master is the default

This will create a locked domain.
