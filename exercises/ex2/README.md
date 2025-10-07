# Exercise 2 - Maintain your Feature in Cloud ALM

In this exercise, we will check whether the integration between SAP Cloud ALM and SAP Cloud Transport Management service has been established properly. This will enable the usage of Features in SAP Cloud ALM to transport changes throughout your landscape. The creation of the Feature will be part of the exercise.

## Exercise 2.0 - Check your Cloud ALM and cTMS integration

1. Go to the BTP Cockpit of your [SAP Cloud ALM subaccount](https://emea.cockpit.btp.cloud.sap/cockpit/?idp=tdct3ched1.accounts.ondemand.com#/globalaccount/4c772782-0751-42ee-93c3-897452fdcb63/subaccount/98874a1a-2203-4250-9655-a517c06586b6/subaccountoverview) and login with your user and password.
2. Open the **Destinations** view (to be found in the Connectivity area in the navigation pane).

    <br>![alt text](images/btp_cockpit_destination.png)
3. Search for destination **CALM_FTR_CTMS_XP266-0XX** (use your hands-on session user e.g. XP266-001) and open it by clicking on the line item.

    <br>![alt text](images/calm_ctms_destination.png)
4. Click **"Check Connection"**. 

    <br>![alt text](images/check_connection.png)
5. The result in the dialog shall be "HTTP request (without authentication) to CALM_FTR_CTMS_XP266-0XX destination succeeded".

    <br>![alt text](images/check_dialog.png)
 
## Exercise 2.1 - Create a new Feature

1. Open [SAP Cloud ALM](https://xp266-calm-lf1zy9xc.eu10-004.alm.cloud.sap/launchpad#Shell-home) and login with your user and password.
2. Go to the **Features** application.

    <br>![alt text](images/feature_tile.png)
3. Check whether your project SAP TechEd Hands-On XP266-0XX (use your hands-on session user e.g. XP266-001) is selected. If that is not the case please select the correct project.

    <br>![alt text](images/project_selection.png)
4. Click **"Create"** on the top right of the Features list.

    <br>![](images/create_feature.png)
5. Add a **meaningful title** to your Feature and a description.

    <br>![alt text](images/title_and_description.png)
6. In the **Additional Information** section change the priority to "High" and select your user as Responsible.

    <br>![alt text](images/priority_responsible.png)
7. Click on **"Save and Close"**.

    <br>![alt text](images/save_and_close.png)
8. Click the button **"Start Implementation"** to switch the Feature to status "In Implementation".

    <br>![alt text](images/start_implementation.png)
9. Your Feature in status "In Implementation" shows up in the Features Overview list on the left-hand side.

    <br>![alt text](images/feature_in_overview.png)

Congratulations, you have created your Feature!

## Summary

In this exercise you've verified that the integration between SAP Cloud ALM and SAP Cloud Transport Management has been established through SAP BTP destination properly. The Feature for later usage in the deployment process is available in status "In Implementation".

Continue to - [Develop your pro-code application](../ex3/README.md)
