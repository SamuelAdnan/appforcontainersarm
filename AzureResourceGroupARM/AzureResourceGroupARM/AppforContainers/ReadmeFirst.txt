Deployment in this order for deploying the "Container App"

1. First deploy the -> Log Analytic workshop (if you need logs for container envirnoment)
   Get workspaceID 
   Get Secondary share key


2. Now deploy the -> Contanier App envirnoment.
   The appLogsConfiguration section in template.json file
    use the workspaceID as CustomerId, 
    and, SharedKey = above secondary shared key 

3. Now you can deploy the - > Contianer app