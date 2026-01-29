# Set Up an App Dev Environment on Google Cloud  
  
## Task:  
1. Create a bucket for storing the photographs.  
2. Create a Pub/Sub topic that will be used by a Cloud Run Function you create.  
3. Create a Cloud Run Function.  
4. Remove the previous cloud engineer’s access from the memories project.  
  
## Notes:  
* Some standards you should follow:  
    * Create all resources in the REGION region and ZONE zone, unless otherwise directed.  
    * Use the project VPCs.  
    * Allocate cost effective resource sizes.  
    * Use e2-micro for small Linux VMs and e2-medium for Windows or other applications such as Kubernetes nodes.