# Explore Insider Risk Management in Microsoft Purview

<h3>Objective</h3>
In this activity, the eDiscovery (Standard) workflow within Microsoft Purview was comprehensively explored. 
The primary objective was to walk through the essential steps for setting up eDiscovery, including configuring role permissions, creating an eDiscovery case, establishing an eDiscovery hold, and executing a search query. 
This activity aimed to provide a foundational understanding of the eDiscovery process and workflow.
</br>
</br>
 
<h2>Task one</h2>
<h3>Setting up Role Permissions for eDiscovery</h3> 

This task aims to assign specific users as members of the eDiscovery Manager role group to ensure access and management of eDiscovery features within Microsoft Purview. </br>

  1. To begin, I opened a web browser and accessed the Microsoft Purview admin portal, which serves as the central hub for managing compliance-related tasks and settings.
  2. Within the admin portal, I navigated to the Compliance section using the options available in the left-hand navigation pane. This section provides access to various compliance-related features and configurations.
  3. Within the Compliance section, I accessed the Roles & Scopes settings, which are essential for defining user roles and permissions within the compliance framework of Microsoft Purview.
  4. Using the search functionality provided, I located the specific role group related to eDiscovery management. Among the available roles, I selected the eDiscovery Manager role, which grants users specific privileges for managing eDiscovery tasks.
  5. After selecting the eDiscovery Manager role, I proceeded to add members to the eDiscovery Administrator subgroup within the role group. This step is crucial for assigning relevant permissions to individuals responsible for eDiscovery activities.
  6. From the list of available users, I selected the individuals designated as MOD Administrator and Megan Bowen to be added to the eDiscovery Administrator subgroup. These users were chosen based on their roles and responsibilities within the organisation.
  7. Finally, I saved the changes made to the role group, confirming the addition of MOD Administrator and Megan Bowen to the eDiscovery Administrator subgroup. This ensured that the designated users have the necessary permissions to perform eDiscovery tasks effectively. </br>

Task 1 involved configuring role permissions for eDiscovery by adding designated users to the eDiscovery Manager role group. 
By assigning specific users as eDiscovery administrators, access and management of eDiscovery features within Microsoft Purview were facilitated, ensuring effective utilisation of the eDiscovery functionality.
</br>
</br>

<p align="center">
<img src="https://i.imgur.com/bRv6mGG.png" width="600" height="400">
<br />
<p align="left"><br />
 </br>


<h2>Task Two</h2>
<h3>Creating an eDiscovery Case</h3>

The objective of this task is to create an eDiscovery case to initiate the use of eDiscovery (Standard) within Microsoft Purview. </br>

  1. Firstly, I accessed the specific section dedicated to eDiscovery (Standard) within the Microsoft Purview compliance portal. This section is where all eDiscovery-related activities are managed.
  2. Within the eDiscovery (Standard) section, I initiated the process of creating a new case by selecting the option marked with a plus sign and labelled "Create a case." This action triggered the case creation workflow.
  3. Following the case creation prompt, I provided a descriptive name for the new case, in this instance, "SC900 Test Case." This name helps identify and distinguish the case from others. After naming the case, I saved the details to proceed.
  4. Once the necessary information was entered and saved, I confirmed the creation of the case. After confirmation, the newly created case should now be visible in the list of cases within the eDiscovery (Standard) section.
  5. With the case successfully created, I commenced working on it, utilising the privileges granted by the eDiscovery Administrator role. These privileges enable efficient management and execution of eDiscovery tasks associated with the case, ensuring compliance and thorough investigation when necessary. </br>

Task 2 focused on the creation of an eDiscovery case, enabling the initiation of eDiscovery (Standard) functionality within Microsoft Purview. 
By creating a case and configuring its settings, the groundwork for conducting eDiscovery processes was established, laying the foundation for subsequent tasks.</br>
</br>

<p align="center">
<img src="https://i.imgur.com/zBYDPJ3.png" width="600" height="400">
<br />
<p align="left"><br />
 </br>

<h2>Task Three</h2>
<h3>Creating an eDiscovery Hold</h3>

Task Description: This task entails creating an eDiscovery hold for the previously created case, specifically targeting the exchange mailbox belonging to Adele Vance. </br>

  1. To begin, I opened the browser and navigated to the eDiscovery (Standard) section, which is a crucial part of our compliance management system.
  2. Within the eDiscovery (Standard) section, I located and selected the case we had previously created, named "SC900 Test Case." This ensured that we were working within the correct context.
  3. Upon selecting the case, I accessed the Hold tab, where we manage holds on specific data to ensure its preservation for legal or compliance purposes. I then proceeded to create a new hold.
  4. During the creation process, I assigned a meaningful name to the hold, opting for "Test hold" to identify it easily. This step is crucial for clarity and organisation within our compliance framework.
  5. Within the hold creation interface, I activated the option to include Exchange mailboxes. This ensures that relevant data from Exchange mailboxes is also subject to the hold we're establishing.
  6. To specify the scope of the hold, I searched for and selected Adele Vance as the user whose data will be encompassed by this hold. This step ensures that data pertinent to Adele Vance is properly preserved.
  7. Before finalising the hold, I carefully reviewed all the settings to ensure they aligned with our compliance requirements. Once satisfied, I submitted the request to create the hold, thereby initiating the process of data preservation as per our compliance protocols.  </br>

Task 3 focused on establishing an eDiscovery hold for the exchange mailbox of Adele Vance within the designated eDiscovery case. By creating the hold and specifying relevant settings, the preservation of content for legal and compliance purposes was ensured, contributing to effective eDiscovery management.
</br>
</br>

<p align="center">
<img src="https://i.imgur.com/CxNqm8n.png" width="600" height="400">
<br />
<p align="left"><br />
 </br>


<h2>Task Four</h2>
<h3>Creating a Search Query</h3>

The goal of this task is to create a search query within the eDiscovery (Standard) case, enabling the identification and retrieval of relevant content for investigation purposes. </br>

  1. Firstly, I accessed our eDiscovery (Standard) platform and located the specific case we've been working on, named SC900 Test Case. This ensured we were focused on the correct case within our compliance management system.
  2. Within the SC900 Test Case, I moved to the Searches section, where we manage search queries to find relevant data within our stored information.
  3. Next, I began the process of creating a new search query, which is essential for identifying specific data that may be pertinent to our compliance investigations or legal requirements.
  4. To maintain clarity and organisation, I assigned a descriptive name to the search query, opting for "Test Hold – Sales Search." This ensured we could easily identify and differentiate this search from others in the future.
  5. Within the search creation interface, I specified the locations where the search should be conducted, ensuring it aligns with the data covered by existing holds. Additionally, I defined specific search criteria to narrow down the results to the most relevant data.
  6. Before finalising the search, I thoroughly reviewed all the settings and criteria to ensure they accurately reflected our requirements. Once confirmed, I submitted the search query, initiating the process of data retrieval based on our specified parameters. </br>

Task 4 involved the creation of a search query within the eDiscovery (Standard) case, facilitating the identification and retrieval of relevant content for investigation purposes. By executing the search query and analysing search statistics, potential insights and actionable information were obtained, supporting effective eDiscovery processes.
</br>
</br>

<p align="center">
<img src="https://i.imgur.com/vG8dQ0O.png" width="600" height="400">
<br />
<p align="left"><br />
 </br>


<h2>Conclusion</h2>

In this activity, the essential steps for setting up eDiscovery (Standard) within Microsoft Purview were comprehensively explored and executed. By configuring role permissions, creating eDiscovery cases, establishing holds, and executing search queries, a foundational understanding of the eDiscovery workflow was attained. Furthermore, through hands-on experience with eDiscovery features and functionalities, valuable insights into legal and compliance management practices were gained, enhancing proficiency in cybersecurity and compliance-related domains.


 </br>
 </br>

