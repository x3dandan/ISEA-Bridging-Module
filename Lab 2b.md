# Lab 2b
Reflection:

Created New Instance on AWS
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/f969d970-3e4e-4900-8695-bb1b9fdbc6dd" />
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/65a0d995-3ce7-4b7f-9882-cbc5a2bbb53d" />
open Terminal -> proceed to location of saved key file: cd ~/Documents -> ensure key is not publicly viewable using chmod 400 "webserver-key.pem" -> Connect to the instance using its Public DNS
<img width="1718" height="896" alt="image" src="https://github.com/user-attachments/assets/50405093-47a2-4559-acd9-f55d2d755dbd" />
sudo apt update to ensure apt repositories are updated
<img width="1424" height="1488" alt="image" src="https://github.com/user-attachments/assets/80885f6f-6179-4954-b861-7dfedf098f9a" />
installing Nginx Web Server using sudo apt install nginx-full
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/26b5c348-0281-43e7-a6bc-368cccf16857" />
check website is online by opening IP on browser
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/1fdd1cfc-849d-4989-8d04-9ec3c58d5cf5" />
create /var/www/html/index.html with nano /var/www/html/index.html
<img width="2788" height="1544" alt="image" src="https://github.com/user-attachments/assets/c3aaaf20-b2fc-47ca-a221-28223f3778ac" />
Download the sample file into my /home/ubuntu directory. Then  to move it into the /var/www/html directory using sudo. Try:
<img width="2786" height="1052" alt="image" src="https://github.com/user-attachments/assets/f71e879e-954c-48bf-b02e-330bed1a0bae" />
check whether can access the file through the website
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/2561f10c-dd6a-46d8-83ed-14d1ac612d6f" />
Once files have been uploaded, create a link to the file by modifying the HTML in index.html.
Connect and find web root -> find pdf location -> create directory and move file -> Ensure web server can read -> add links to index.html
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/6acb42d9-63bf-4441-b04d-824c452d593e" />
Test link by going to the website and clicking
<img width="3200" height="2000" alt="image" src="https://github.com/user-attachments/assets/a711039b-32d4-4c90-969d-d0913d3d7661" />
