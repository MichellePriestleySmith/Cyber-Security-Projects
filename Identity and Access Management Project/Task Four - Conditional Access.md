# Task Four

<h2>Microsoft Entra Conditional Access</h2>
<h2>Objective</h2>
 
This series of tasks focused on a thorough exploration of Microsoft Entra, specifically delving into the access management features of Microsoft Entra ID with a concentrated emphasis on Conditional Access. The scenario involved experiencing Conditional Access Multi-Factor Authentication (MFA) from both an administrative and a user perspective.
</br> 
</br>
 
<h2>Part one</h2>
<h3> Password Reset for User 'Debra Berger'</h3>
 
In this task, I facilitated a password reset for the user 'Debra Berger' to enable her initial sign-in for subsequent activities.</br> 

As the administrator, I utilised Microsoft Edge to navigate to https://entra.microsoft.com, where I signed in using administrative credentials. Following this, I reset Debra Berger's password, documenting the new password for future reference. This step ensured a seamless transition to subsequent tasks by providing access to the specified user account, thus facilitating the administrator's ability to configure Conditional Access policies.</br> 

This task served as the foundation for further exploration, granting access to the user account and allowing the administrator to proceed with the configuration of Conditional Access policies.
</br> 
</br>

<h2>Part Two</h2>
<h3>Creation of Conditional Access Policy for Multi-Factor Authentication</h3>

The objective of this task was to craft a Conditional Access policy in Azure AD, with a specific focus on Multi-Factor Authentication.</br>

Continuing as the administrator, I navigated to the Microsoft Entra admin center and formulated a new Conditional Access policy named "MFA Test Policy." This policy targeted the user Debra Berger and was designed for Microsoft Admin Portals, specifically Azure. It was configured to grant access only after completing Multi-Factor Authentication (MFA). The process involved selecting users, defining target resources, conditions, and access controls, with the final step being the activation of the policy. </br>

This task provided insights into the creation and implementation of a Conditional Access policy, showcasing the administrator's ability to configure robust security measures, particularly the requirement of MFA for accessing designated Microsoft Admin Portals.
</br>
</br>

<h2>Part Three</h2>
<h3>User Experience of Conditional Access Policy</h3>

In this task, I assumed the role of the user, Debra Berger, to understand the impact of the Conditional Access policy. </br> 

Acting as the user, I signed in to the Microsoft 365 portal without encountering MFA, as it wasn't part of the policy. However, when attempting to access the Azure portal, MFA was triggered, initiating the registration process. I selected a preferred method for MFA, completed the registration, and successfully accessed the Azure portal, adhering to the Conditional Access policy. The task concluded with a sign-out.</br> 

This task offered a valuable perspective from the user's standpoint, highlighting the impact of the Conditional Access policy on MFA requirements for accessing Microsoft Admin Portals.
</br>
</br>

<h2>Conclusion</h2>

This task constituted an in-depth exploration of Microsoft Entra ID, highlighting its seamless integration with Microsoft 365. It underscored the flexibility of accessing Microsoft Entra ID features through both the Microsoft 365 admin portal and the Azure portal. The user walkthrough included creating a new user, configuring settings, exploring role options, and managing licences. This hands-on experience solidified my understanding of Microsoft Entra ID capabilities, particularly in user and licence management.
</br>
</br>


