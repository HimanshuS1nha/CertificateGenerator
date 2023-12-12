Steps :

1. Create a mongo db database instance. Copy its URI and paste in in main.py at line number 175 inplace of "MONGODB URI"
2. Go into verify folder, create a .env file and add an entry like this MONGO_URI=the mongodb uri you copied
3. Create a app password for an email from which the certificates will be emailed to the participants and put the email and the app password in main.py at line number 164 inplace of "EMAILID" and "APP PASSWORD". Also, add the email in line number 131 of main.py inplace of "EMAILID"
4. The format for the excel file to be uploaded is given in Book.xlsx
5. If you want to host this, host the verify folder (as a nextjs project) and the other parts (as a Python Flask project) separately and update line number 52 with the url of the website where you hosted the verify folder