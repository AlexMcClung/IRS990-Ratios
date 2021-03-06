# IRS 990 Finance Ratios

Instructions and code to download and create financial health metrics with publicly available IRS 990 data

* Primary Reserve Ratio - available resources
* Viability Ratio - debt in relationship to available reserves
* Return on Net Assets Ratio (%) - change in wealth in terms of assets performance
* Net Operating Revenues Ratio (%) - results of operations

These ratios are combined into an index called the Composite Financial Index or CFI.

Each of these indicators has a threshold associated with it that is used to gauge health in that area.

### Source
The CFI was developed by KPMG; Prager, Sealy & Co., LLC.; and BearingPoint, Inc. The Department of Education ratios and composite were developed by KPMG Peat Marwick. 

### Data
IRS Form 990 Extract data files and codebooks can be found here:

https://www.irs.gov/statistics/soi-tax-stats-annual-extract-of-tax-exempt-organization-financial-data

Also needed are some data elements from the IPEDS finance survey (total expenses and net assets) that must be merged with 990 data via EIN number.

If individual schools are missing from the data set or you would like to troubleshoot them individually, you might have some success finding their 990 here:

https://projects.propublica.org/nonprofits/

### Process
Ratios are calculated for comparison over time with other lib arts schools.
