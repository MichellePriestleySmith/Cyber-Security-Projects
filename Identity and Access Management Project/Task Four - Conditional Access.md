# Task Four

<h2>Microsoft Entra Conditional Access</h2>

This set of tasks focuses on exploring the capabilities of Microsoft Entra, specifically diving into the access management features of Microsoft Entra ID with a focus on Conditional Access. 
The task scenario involved experiencing Conditional Access Multi-Factor Authentication (MFA) from both an administrator and a user perspective. </br>
As the admin, the primary task was to create a policy requiring users to undergo MFA when accessing Microsoft Admin portals.  </br>
The user perspective involved understanding the impact of the Conditional Access policy, including the registration process for MFA. </br>
</br>

<h2>Part one</h2>

In this task I reset the password for the user 'Debra Berger' to allow initial sign-in for subsequent tasks.
</br>

Acting as the administrator, I opened Microsoft Edge, navigated to https://entra.microsoft.com, and signed in using admin credentials. </br>
Following this, I reset Debra Berger's password, as her initial password was unknown. </br>
The new password was noted for future use. </br>
This task ensured a seamless transition to subsequent tasks by providing access as the specified user. </br>
</br>

This task successfully set the groundwork for further exploration by enabling access to the user account, 
facilitating the admin's ability to configure Conditional Access policies.
</br>
</br>

<h2>Part Two</h2>

The purpose of this task was to create a Conditional Access policy in Azure AD, focusing on Multi-Factor Authentication.
</br>

Still acting as the administrator, I navigated to the Microsoft Entra admin center and created a new Conditional Access policy named "MFA Test Policy." </br>
This policy targeted the specific user, Debra Berger, again, and applied to Microsoft Admin Portals, specifically Azure. </br>
The policy was configured to grant access only after completing Multi-Factor Authentication (MFA). </br>
The final part of the process involved selecting users, defining target resources, conditions, and access controls. Finally, the policy was enabled. </br>
</br>

From this task I gained insights into the creation and implementation of a Conditional Access policy, 
demonstrating the admin's ability to configure security measures, specifically requiring MFA for accessing designated Microsoft Admin Portals.
</br>
</br>

<h2>Part Three</h2>

In this task I experienced the impact of the Conditional Access policy as the user, Debra Berger.
</br>

Now acting as the user, Debra Berger, I signed in to the Microsoft 365 portal without encountering MFA since it wasn't part of the policy. </br>
However, when attempting to access the Azure portal, MFA was triggered, leading to the registration process. </br>
I selected a different method for MFA, completed the registration, and successfully accessed the Azure portal, adhering to the Conditional Access policy. </br>
The task concluded with signing out.
</br>

This task showcased the user's perspective, highlighting the impact of the Conditional Access policy on MFA requirements for accessing Microsoft Admin Portals.
</br>
</br>

<h2>Conclusion</h2>

This set of tasks provided a comprehensive understanding of setting up a Conditional Access policy that mandates MFA for accessing Microsoft Admin portals. 
It covered the administrative configuration process and the user's experience during MFA registration, emphasizing the policy's impact on accessing the Azure portal. 
The hands-on tasks enhanced knowledge of Microsoft Entra's security features, specifically Conditional Access, 
contributing valuable skills to enhance cybersecurity proficiency.
</br>
</br>



