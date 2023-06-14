FileUpload is a 2 step process:
  (i)  Uploading the files from the local(from our laptops) to the Server
  (ii) Uploading the files from the Server to the Cloud

-> Upload() method with the FileUpload middleware will be used to Upload the files from the local to the Server(from the local to the temporary location in the Server)

-> Upload() method with the Cloudinary dependency will be used to Upload the files from the Server to the Cloud and delete the files from the Server(i.e., from the temporary location)

-> In case of fileupload first we have to upload the file to the cloud(cloudinary) and create an entry for that file in the DB pointing that particular file in the cloud



                    Steps to be followed to get API keys for cloudinary
                    --------------------------------------------------
CLOUD_NAME:
-----------
Dashboard -> Copy "Cloud Name"

API_KEY & API_SECRET:
---------------------
settings -> Access Keys -> Copy "API Key" and "API Secret"

MONGODB_URL:
------------
-> Copy MongoDB url from MongoDB Atlas



                    Steps to be followed to get API keys for Nodemailer
                    ---------------------------------------------------
MAIL_PASS:
----------
Go to Gmail -> Manage Google Account -> Security -> 2 Step Verification ->  Provide Mobile Number   -> After entering OTP, Click on "turn on" button

-> 2 Factor Authentication will be enabled by doing above step

-> Come back and again click on 2 Step Verification and scroll to down

-> Click on App Passwords

-> Click on dropdown and select 'other' option

-> It will show us the list of apps(applications)

-> Click on Generate Password