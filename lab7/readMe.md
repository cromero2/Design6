## Lab 7

<p>For the first part of this lab, I signed up for thingspeak, and created a channel with a cpu usage and available memory fields. 
  After saving the channel I copied the API key, and upon running the code, was able to view the published details: </p>

  ![image](https://github.com/cromero2/Design6/assets/98184880/0f4bd96e-40b4-441e-84a0-5aa252086c40)

  ![image](https://github.com/cromero2/Design6/assets/98184880/cb98e73d-17ff-4039-ad14-f5fd4c2620a5)


<p>For the second part of the lab, I created a project in google IAM, and enabled the Google Drive and Google Sheets APIs by creating a service account, and generating an account key which I could pass into the python code. After then creating a google sheet, and sharing it with the service account, I was able to run the python file and it automatically filled in the sheet with my cpu data:</p>

![image](https://github.com/cromero2/Design6/assets/98184880/6881cbc9-89e8-47d0-8607-1cc86e404d7a)

<p>I changed /opt/vc/bin/vcgencmd to /usr/bin/vcgencmd in system_info.py, and then ran the code: </p>

![image](https://github.com/cromero2/Design6/assets/98184880/bdd4a4b7-069a-4579-a7f3-e5039556532d)
