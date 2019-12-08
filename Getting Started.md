# SQL Server
You will need access to a SQL Server instance for this course.  There are two options for this:
1. Install SQL Server on your machine (this option is only supported on Windows)
2. Sign up for a free Azure account and host the database there.

Option 1 takes a bit more work, but it is recommended because you will be able to access your SQL server at anytime.  With option 2, you will need internet access to use your server.

## Install SQL Server on your machine (Recommended)
1. Download SQL Server Developer from https://go.microsoft.com/fwlink/?linkid=853016
2. Run the installer and choose the custom option

![install step 1](images/install-1.png)
3. Select a folder in which to save the installation files and click install

![install step 2](images/install-2.png)
4. Wait for the installation files to download

![install step 3](images/install-3.png)
5. Once this is complete, the SQL Server Installation center will open.  If not, you can run the Setup.exe program under the Developer_ENU folder located in the installation path

![install step 4](images/install-4.png)
6. Choose the Installation option on the left side, then click 'New SQL Server standalone-installation or add features to an existing installation'

![install step 5](images/install-5.png)
7. This will launch the setup wizard.  Click next

![install step 6](images/install-6.png)
8. Accept the license terms and click next

![install step 7](images/install-7.png)
9. The wizard should go through the next steps automatically.  Under Install Rules, you may see a warning about Windows Firewall, which you can disregard.

![install step 8](images/install-8.png)

10. In the next step, you will choose the features to install.  At this point, you only need to choose 'Database Engine Services'

![install step 9](images/install-9.png)

11. Accept the defaults in the Instance Configuration screen

![install step 10](images/install-10.png)
12. Accept the defaults in the Server Configuration screen

![install step 11](images/install-11.png)
13. In the Database Engine Configuration, choose Windows Authentication, and be sure to use the Add Current User option to specify SQL Server administrators

![install step 12](images/install-12.png)
14. In the Ready to Install screen, click Install

![install step 13](images/install-13.png)

15. Wait for the installation to complete, then click close

![install step 11](images/install-14.png)

# Install SQL Server tools
## Sql Server Management Studio
Sql Server Management Studio(SSMS) is a standard tool used to develop and administer Microsoft SQL Server databases.  Install and configure SSMS as follows:

1. Download SSMS from https://aka.ms/ssmsfullsetup
2. Run the installer and go through the steps
3. Launch SSMS.  When you launch, you will be presented with a dialog to connect to your database.  Type 'localhost' into the Server name box and click connect.

![ssms](images/ssms-1.png)



### Azure Data Studio
Azure Data Studio is a lightweight, cross-platform alternative to SSMS that is focused on SQL development.  Install and configure Azure Data Studio as follows:

1. Download Azure Data Studio from https://docs.microsoft.com/en-us/sql/azure-data-studio/download?view=sql-server-ver15
2. Run the installer and go through the steps
3. Launch Azure Data Studio.  On the right pane, you will connect to your database.  Choose Micrsoft SQL Server for the connection type, and type 'localhost' into the Server field, and Windows Authentication for Authentication type.  Then click connect.

![azure data studio](images/ads-1.png)

# Setup the Sample Databases