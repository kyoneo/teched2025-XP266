# Exercise 2 - Maintain your Feature in Cloud ALM

In this exercise, we will check whether the connection between SAP Cloud ALM and SAP Cloud Transport Managemeent service has been established properly. This will enable the usage of Features in SAP Cloud ALM to transport changes throghout your landscape. The Creation of the Feature will be part of the exercise.

## Exercise 2.0 - Check your Cloud ALM and cTMS configuration

1. Go to the BTP Cockpit of your [SAP Cloud ALM subaccount](https://emea.cockpit.btp.cloud.sap/cockpit/?idp=tdct3ched1.accounts.ondemand.com#/globalaccount/4c772782-0751-42ee-93c3-897452fdcb63/subaccount/98874a1a-2203-4250-9655-a517c06586b6/subaccountoverview) and login with your usr and password.
2. Open the Destinations view (to be found in the Connectivity area in the navigation pane).
![alt text](image-1.png)
3. Search for destination CALM_FTR_CTMS_XP266-0XX (use your hands-on session user e.g. XP266-001) and open it by clicking on the line item.
![alt text](image-2.png)
4. Click Check Connection. 
![alt text](image-3.png)
5. The result shall be "HTTP request to destination succeeded".
![alt text](image-4.png)
 
## Exercise 2.1 - Create a new Feature

1. Open [SAP Cloud ALM](https://xp266-calm-lf1zy9xc.authentication.eu10.hana.ondemand.com/login) and login with your user and password.
2. Go to the Features application.
![alt text](image-5.png)
3. Check whether your project SAP TechEd Hands-On XP266-0XX is selected. If that is not the case please select the correct project.
![alt text](image-11.png)
4. Click "Create" on the top right of the Features list.
![alt text](image-12.png)
5. Add a meaningful name to your Feature and a Description.
![alt text](image-13.png)
6. In the Additional Information section change the priority to "High" and select yourself as Responsible.
![alt text](image-14.png)
7. Click on "Save and Close".
![alt text](image-15.png)
8. Click the button "Start Implementation" to switch the Feature to status "In Implementation".
![alt text](image-17.png)
9. Your Feature in status "In Implementation" shows up in the Features Overview list on the left hand side.
![alt text](image-18.png)

## Summary

You've now created the Feature for later usage in the deployment process.

Continue to - [Develop your pro-code application](../ex3/README.md)
