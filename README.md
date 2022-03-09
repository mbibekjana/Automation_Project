# Automation_Project
1.  This script will install apache2 if not installed
2.  Will ensure apache2 is running
3.  Will ensure apache2 is enabled
4.  Will create a tar archive of apache2 logs to /temp directory
5.  Next log tar file will copy to S3 by AWS CLI.
6.  Will create a inventory.html to /var/www/html/. Column of the html file is Log Type         Date Created         Type        Size
7.  This bash file will set to cron which every min store the apache log file to s3 and will update inventory.html file