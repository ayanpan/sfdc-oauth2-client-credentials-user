# Setup OAuth 2.0 Client-Credentials User in Salesforce
**Step-1:** Create a "Connected App" in Salesforce, using an user with sufficient privileges, preferably Admin rights. Reference Article - https://help.salesforce.com/s/articleView?id=sf.cg_task_admin_connected_apps.htm&type=5 

**Step-2:** Select "Enable Client Credentials Flow" only, leaving other options unchecked.
![image](https://github.com/user-attachments/assets/4bfe9761-e225-4b54-98ca-f383339a26ee)

**Step-3:** In the Client Credentials Flow, select "Manage" and set the "Run As" value to an Admin user. Then Save the Connected App.
![image](https://github.com/user-attachments/assets/5f8b5567-c8e7-43c2-84cd-72bc4d0c3453)
