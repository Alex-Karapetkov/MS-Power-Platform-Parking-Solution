# Microsoft Power Platform Parking Solution
As part of Microsoft’s Power Up Challenge, I developed a comprehensive parking management solution for Contoso High School using Power Platform. The project features a Dataverse data model, a model-driven app for submitting parking requests, a tablet-friendly canvas app for logging inspections, a Power Automate flow to confirm requests via email, and a Power BI report to analyze parking trends and identify unauthorized usage. The solution demonstrates my expertise in app development, automation, and data visualization within the Power Platform ecosystem. The project specification is included in this repository as a separate pdf file. I also included the resources used in the project including the Excel files used for data.
Watch the full video walkthrough here: https://youtu.be/x3H_bk6jDF8

# Quick Note:
The Power BI report is included as separate .pbix file in repo that can be run in Power BI Desktop app.

# Prerequisites
Before importing and running this solution, ensure you have the following:

- A Microsoft Power Platform environment with appropriate permissions to import solutions, create apps, and run flows.

- Access to the Microsoft Power Apps portal.

- Power BI Desktop installed to open the included .pbix report file.

Required managed solutions pre-installed in the target environment:

- App Framework Infra Extensions (msdyn_AppFrameworkInfraExtensions), version 1.0.0.15 or higher.

- App Module Assets (AppModuleWebResources), version 2.5 or higher.


# Importing the Solution
- Download the unmanaged solution ZIP file from this repository.

- Log into the Power Apps portal at https://make.powerapps.com.

- Navigate to Solutions and select Import solution.

- Upload the downloaded solution ZIP file.

- If the environment does not already have the required managed dependencies (App Framework Infra Extensions and App Module Assets), the import will fail. Please ensure these are installed before proceeding.

- Complete the import process.


# How to Use the Solution
Model-Driven App (Parking Requests): Users submit and manage parking requests via a user-friendly interface.

Canvas App (Parking Inspections): Designed for tablet use, this app allows authorized personnel to log parking inspections on the go.

Power Automate Flow: Automatically sends email confirmations upon parking request submissions.

Power BI Report: Analyze parking trends and identify unauthorized usage. Open the .pbix report file using Power BI Desktop, connect to the environment’s Dataverse data, and publish to Power BI service if needed.


# Dependencies and Notes
The solution depends on the following managed solutions to function correctly:

- App Framework Infra Extensions (msdyn_AppFrameworkInfraExtensions) - provides essential framework components.

- App Module Assets (AppModuleWebResources) - supplies necessary web resources and assets.

Failure to have these managed solutions installed prior to import will cause the solution import to fail.

The Power BI report is not included inside the solution package but is provided separately as a .pbix file in the repo for manual use.

