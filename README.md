# DataEngineering-Azure-Spencer
Azure base Data Engineering Solution

## Financial Dashboards
- Azure functions to process financial reports on 2nd day of every month
- Azure SQLServer to store the data
- Following are the 4 reports that run on a monthly basis on azure functions and populate the respective SQLServer tables
        1.CompletedWoByRoute
        2.CompletedWoTotalByPrimaryEmployeeByService
        3.CustomerGrowthLossByProgramCategoryByAccount
        4.PaidInvoicesByRoute

## Technician Dashboards
- Azure function to calculate technician reports run on a weekly basis on every Wednesday
- Weekly Technician reports consumes 4 files as input from AzureDataLakeStorage and calculate the technician reports

## Zyltus Call Dashboard
- Azure function to showcase near realtime results
- Zyltus provides an API to fetch the live data of people at work in the call center
- Azure function fetches the data every 5Minutes and populates the same in Azure SQLServer
