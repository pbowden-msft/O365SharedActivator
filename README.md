# O365SharedActivator
<b>Microsoft Office 365 Mac Shared Subscription Activator</b>

Purpose: Allows all users on the same computer to share the same Office 365 Subscription</br>
Usage: `O365SharedActivator [--jamf] [--master] [--serialize] [--deactivate] [--user:<username>]`</br>

Example: `O365SharedActivator --master`      (Sets the current users subscription as the master license for this computer)</br>
Example: `O365SharedActivator --serialize`   (Allows the logged-on user to consume the master license)</br>
Example: `O365SharedActivator --deactivate`  (Removes the master license from this computer)</br>

Compatible when running as a login script under Jamf Pro</br>
Copy the script to `/Library/Application Support/Microsoft/`</br>
Use `/Library/Application\ Support/Microsoft/O365SharedActivator --serialize --user:$3` in the login script
