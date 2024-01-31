# Part One

<h2>Task One - Setting up Microsoft 365 audit log</h2>
In this task I successfully set up the Audit log capability in Microsoft 365.
Despite documentation suggesting that the audit log is enabled by default, it was necessary to manually enable it for most users. 
This is crucial as Microsoft 365 utilizes audit logs for user insights, policy enforcement, and analytics.

<h3>Enabling the Audit log</h3>

To initiate the setup, I opened Microsoft Edge and navigated to admin.microsoft.com, where I signed in using my admin credentials. 
After accessing the Microsoft 365 admin center, I selected "Show all" from the left navigation pane and proceeded to the Compliance admin center. 
From there, I accessed the Audit functionality within the Microsoft Purview compliance portal.

Upon verifying the selection of the "New Search" tab, I waited for 2-3 minutes on the Audit page. 
If auditing was not enabled, a blue bar appeared at the top, prompting me to start recording user and admin activity. 
I followed this prompt, confirming updates to organization settings if necessary. Once auditing was enabled, the blue bar disappeared.

To confirm the successful setup, I returned to the home page of the Microsoft Purview compliance portal and signed out of Microsoft 365. 
This setup ensures that the audit log capability is activated, allowing for the tracking of user and admin activities for insights and compliance purposes.

<br/>
<br/>
