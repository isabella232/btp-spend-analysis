## Deploying DWC Business Content

Now that the HANA Cloud tables (Input Layer) have been successfully created, we can deploy the Data Warehouse Cloud views (Harmonization Layer and Reporting Layer).

Navigate to the Repository Explorer and Select the SAP & Partner Content Space

 
![DWC Deploy](../images/DWCLane_DeployContent1.png) 

If you’ve downloaded other business content packages into this space, you can narrow down the list of views to be deployed by selecting the ‘Not Deployed’ filter in the search pane.

![DWC Deploy](../images/DWCLane_DeployContent2.png) 

To Deploy a view, you will click on the View Name which will launch you into the Data Builder screen for the View.  Inside of the Data Builder, you will click on the Deploy button for the view*

![DWC Deploy](../images/DWCLane_DeployContent3.png)
 

*Avoid navigating back and forth from the list of views to the data builder when deploying these views by Right Clicking on the view name in the list and ‘open in new tab’.  After you deploy the view, you can close that tab.

 
It’s best to deploy the Input Layer views first, followed by Harmonization Layer views and finally the Reporting Layer Views.

Deploy the following:

### Input Layer Views – technical names
- SAP_PROC_SA_IL_AccountDim
- SAP_PROC_SA_IL_SupplierDim
- SAP_PROC_SA_IL_PartDim
- SAP_PROC_SA_IL_CompanySiteDim
- SAP_PROC_SA_IL_UNSPSCDim
- SAP_PROC_SA_IL_ContractDim
- SAP_PROC_SA_IL_SourceSystemDim
- SAP_PROC_SA_IL_CostCenterDim
- SAP_PROC_SA_IL_POLineItemFact
- SAP_PROC_SA_IL_InvoiceLineItemFact
### Harmonization Layer Views – technical names
- SAP_PROC_SA_HL_PPA_Variance
- SAP_PROC_SA_HL_PPV_Variance
- SAP_PROC_SA_HL_SOC_Variance
- SAP_PROC_SA_HL_SupplierDim
### Reporting Layer Views – technical names
- SAP_PROC_SA_RL_PART_OPTIMIZATI
- SAP_PROC_SA_RL_SPEND_ANALYSIS
### Entity Relationship diagram – technical name
- SAP_PROC_SA_ER_DEPLOY
 
