## Installing Sql Server
You can follow along with the steps listed below or you can also follow along with the video I created on [YouTube](https://youtu.be/9nh5SMXOzxY).
1. Open your favorite browser
1. Visit https://www.microsoft.com/en-us/sql-server/sql-server-downloads
1. Scroll down the page until you see "Or, download a free specialized edition"
1. Under Developer Edition click on [Download now](https://go.microsoft.com/fwlink/?linkid=853016)
1. Once the download is completed click on the executable to install
1. Select Basic
1. Accept User License, folder and click on "Install"

## Installing SQL Server Management Studio (SSMS)
The second half of the video on the link above continues on how to install SSMS
1. Once SQL Server Database completes installing there is a selection of options on the lower part of the window
1. Click on "Install SSMS"
1. Accept the license agreement, select the appropriate folder and click install

## Enable the SQL Server SA Account
1. Login using your Windows Credentials
   ![Windows Credentials](/windows/sqlserver_windowscredentials.png)
1. Under "Object Explorer", expand "Security" and expand "Login"
1. Towards the bottom of the node, right-click on the sa user and select "properties"
1. Provide a password that you can remember and confirm it
1. Under "Object Explorer", select "Status"
1. on the right pane, under "Login", select "Enabled"
1. Click "Ok"

## Test the newly enabled SA Account
1. Under "Object Explorer", right-click on (SQL Server 14.0.1000.169) and select "Disconnect"
1. Under "Object Explorer", click on "Connect", select "Database Engine"
1. Provide the following:
Server Name: (local)
Authentication: SQL Server Authentication
Login: sa
Password: (*Provide you password*)
1. Click "Connect"
