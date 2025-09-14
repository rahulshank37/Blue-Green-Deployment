# Blue-Green Deployment with Azure App Service

## Project Overview

This project demonstrates a **Blue-Green deployment** strategy using **Azure App Service**. A static HTML website is deployed to a **production slot (Blue)** and a **staging slot (Green)**. Updates are first deployed to the staging slot, verified, and then swapped into production, ensuring **zero downtime** and a **safe deployment process**.

## Features

* Deploy a static HTML website to Azure App Service.
* Create a **staging deployment slot** for testing updates.
* Modify and deploy updates safely to the staging slot.
* Swap slots to promote changes to production.
* Verify updates in staging before making them live.

## Tools & Services Used

* **Azure App Service**: Hosts the web application.
* **Deployment Slots**: Manage Blue (production) and Green (staging) environments.
* **Azure CLI / Cloud Shell**: Automates deployment and slot management.
* **Application Insights (Optional)**: Monitors app performance and errors.
* **GitHub (Optional)**: Stores application code and deployment scripts.

## Benefits of Blue-Green Deployment

* **Safe Deployments**: Test updates without affecting production.
* **Zero Downtime**: Users experience uninterrupted service.
* **Easy Rollback**: Previous version remains available in staging.
* **Reduced Risk**: Minimizes deployment errors and operational impact.

## Steps

1. Clone the sample HTML app from GitHub.
2. Set deployment variables for the resource group and App Service name.
3. Deploy the initial app to the **production slot (Blue)**.
4. Create a **staging slot (Green)** for updates.
5. Update the code in staging and deploy.
6. Verify the staging slot is working correctly.
7. Swap staging and production slots to promote changes.
8. Verify the production slot reflects the updates.

## Conclusion

This project demonstrates a **safe, reliable, and efficient deployment strategy** using Azure App Service. Blue-Green deployment minimizes downtime, allows thorough testing, and provides instant rollback options, making it ideal for modern DevOps practices.
