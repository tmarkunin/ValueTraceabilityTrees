Google Cloud resources are organized hierarchically. This hierarchy allows you to map your enterprise's operational structure to Google Cloud, and to manage access control and permissions for groups of related resources. 

It's recommended to create separate GCP project for each environment and define access access rights and available quotas on the project level. 

The following diagram shows an example hierarchy. 




##### Capping usage 
You might want to limit usage of a particular resource by setting your own quota limits. For example, to prevent getting billed for usage beyond the free courtesy usage limits, you can set requests per day caps. The simplest way to cap quota is to edit the limits on the API-specific quota page. 

Go to the quota page in the Cloud Console for the API whose usage you want to cap. 
On the quota line you want to change, click the edit icon ( edit), then enter your preferred total quota, up to the limit specified by Google. 
Click Save to save your changes. 