# Creating Windows 10 VM in Azure    

## 1. Login to Azure Portal    
Go to https://portal.azure.com    
Use your Azure Account to login.    

## 2. Search for Windows 10 VM    
In the Azure Portal Search Box, search for "windows 10".

![](./assets/2018-05-10-20-46-27.png)

## 3. Configure VM 
![](./assets/2018-05-10-20-52-01.png)

## 4. Configure Basic Settings and Click OK
![](./assets/2018-05-10-21-00-17.png)

## 5. Select VM Size
![](./assets/2018-05-10-21-06-47.png)

## 6. Set Auto Shutdown Schedule for VM    
This is to prevent unnecessary expenses.
![](./assets/2018-05-10-21-20-51.png)

## 7. Click Create
![](./assets/2018-05-10-21-23-20.png)

## 8. Monitor VM Deployment   
Go back to the Azure Portal Search Box
![](./assets/2018-05-11-00-15-42.png)

![](./assets/2018-05-11-00-22-24.png)
## 9. Ensure that the VM is running
![](./assets/2018-05-11-01-10-01.png)
![](./assets/2018-05-11-01-19-00.png)

## 10. Connect to the VM via Remote Desktop
![](./assets/2018-05-11-01-25-58.png)

From Windows 10, Launch "Remote Desktop Connection".    
Supply the IP address and Port number.
Then, click Connect.
![](./assets/2018-05-11-01-30-14.png)

Supply the VM credentials you created awhile ago.
Then, click OK.
![](./assets/2018-05-11-01-52-08.png)
![](./assets/2018-05-11-01-36-10.png)

References:     
Using Remote Desktop on Windows 7:
https://www.youtube.com/watch?v=RJxgWPV0vi0    
Using Remote Desktop on a Mac:    
https://www.youtube.com/watch?v=nmzXb63kw9Y
 
If you're connected successfully, the Windows Desktop will appear. You can then proceed to use it like a normal Windows machine.    
![](./assets/2018-05-11-01-55-19.png)

Note: If you have issue logging in with the VM credentials, it might be because of the password. Try changing your password and logging in again.

## Starting and Stopping the VM    
In the Azure Portal Search Box, search for your VM.
![](./assets/2018-05-11-02-03-09.png)    
![](./assets/2018-05-11-02-08-33.png)
