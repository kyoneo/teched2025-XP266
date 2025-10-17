# Verify all Release Steps

In this exercise, we will verify the pipeline job status covering the different stages. Especially the release stage for the handover to SAP Cloud Transport Management and the result are of interest.

## Exercise 5.0 - Check the Pipeline Job Status

1. In your SAP BTP subaccount named with **XP266_CENTRAL**, go to **Services -> Instances and Subscription** and choose **Continuous Integration & Delivery**.

    <br> ![](images/CI_D_service.png)
2. In the Jobs area click on your pipeline job.

    <br> ![](images/CI_D_Job.png)
3. Check whether the pipeline job finished successfully and click on the finished result to check the execution log.

    <br>![alt text](images/job_successful.png)
4. Browse through the different stages and click on the Release stage.

    <br>![alt text](images/release_stage.png)
5. In the log file search for "createdTransportRequestId".

    <br>![alt text](images/transport_id_log.png)
6. This transport will be available in your SAP Cloud Transport Management tenant.

## Exercise 5.1 - Verify Transports created in SAP Cloud Transport Management

1. Open SAP Cloud Transport Management and go to Transport Nodes.

    <br>![alt text](images/transport_nodes.png)
2. Select the node QA and navigate to the import queue by clicking on the line item.

    <br>![alt text](images/nav_to_import_queue.png)
3. Look for your transport IDs. The transports will appear in status "Initial".

    <br>![alt text](images/import_queue.png)

## Summary

Well done! You've now verified the pipeline and release steps. Furthermore, you know the transports are available in SAP Cloud Transport Management for your delivery to Quality Assurance and Production.

Continue with [Manage your Feature in Cloud ALM & Deployment](../ex6/README.md)
