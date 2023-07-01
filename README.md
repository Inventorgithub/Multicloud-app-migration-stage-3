###Stag-3
##- Connect to Google Cloud Shell
- Download the dump
cd ~
mkdir mission3_en
cd mission3_en
wget https://tcb-public-events.s3.amazonaws.com/icp/mission3.zip
unzip mission3.zip

###Connect to Cloud SQL MySQL database instance

mysql --host=<public_ip_address> --port=3306 -u app -p

###Import the dump on Cloud SQL

use dbcovidtesting;
source ~/mission3_en/mission3/en/db/db_dump.sql

###Check if the data got imported correctly

select * from records;
exit;

###Amazon Web Services - PDF Files Migration steps

###- Connect to the AWS Cloud Shell
- Download the PDF files

mkdir mission3_en
cd mission3_en
wget https://tcb-public-events.s3.amazonaws.com/icp/mission3.zip
unzip mission3.zip

###Sync PDF Files with your AWS S3 used for COVID-19 Testing Status System.

cd mission3/en/pdf_files
aws s3 sync . s3://luxxy-covid-testing-system-pdf-en-xxxx

###- Test the application. 
