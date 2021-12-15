# Casco Bay Estuary Partnership State of Casco Bay Report Data Repositories

This collection of repositories is an archive of data and data analysis that
support Casco Bay Estuary Partnership (CBEP) "State of Casco Bay" report.

The primary purpose of the archive is to provide transparency with regards to
data and data analyses used to conduct the State of Casco Bay review. A
secondary purpose is to act as an archive of some of the methods used for
analyses of locally available environmental data, to facilitate future projects.

This collection of repositories contains simplified versions of the data
analysis workflow used to produce the State of Casco Bay report.  We have
simplified documentation of data sources; omitted code used to access, clean and
transform source data; and been selective about providing GIS files.  We have
also removed many analyses that were not reflected in the final State of Casco
Bay report, such as models that confirm major findings or helped us select final
models to present.

A more complete archive of the analyses, documenting all data transformations
and analyses, is also available for review [here](http://github.com/CBEP-SoCB-Details).

## Repository Contents
<a name="Contents"></a>
## State of Casco Bay 2020/2021
The 2020/2021 State of Casco Bay Report is structured into multiple Chapters.
Each chapter is based on one to several data sources.  The Github
repositories are built around the data sources (with some variation).
The following section provides a cross-walk from topics to specific
repositories.

### DRIVERS AND STRESSORS; "What's Affecting the Bay?"  
*  A.	Population and Land Use  
    *  Population / Census  
	*  Land Use  
*  B.	Stormwater  
    *  Ten years of water quality monitoring data from Long Creek, 
	  provided by the Long Creek Watershed Management District. .......... 
	    [LCWMD_Monitoring_sum](https://github.com/CBEP-SoCB/LCWMD_Monitoring_sum)
    *  Geospatial data on locations of areas formally included in the
       "Municipal Seperate Storm Sewer System" or MS4 program. .......... 
	   [MS4-Regulated_Areas_sum](https://github.com/CBEP-SoCB/MS4_Regulated_Areas_sum)  
*  C.	Combined Sewer Overflows  
    *  Maine DEP, City of Portland, and Portland Water District data
	    on CSO discharges. .......... 
     [Casco_Bay_CSOs_sum](https://github.com/CBEP-SoCB/Casco_Bay_CSOs_sum)  
*  D. 	Inland Water Quality  
    *  Analyzing DEP Stream Invertebrate biomonitoring data. .......... 
	   [Biomonitoring_sum](https://github.com/CBEP-SoCB/Biomonitoring_sum) 
    *  Maine DEP geospatial information on impaired waters.......... 
	   [Lake_Water_Quality_sum](https://github.com/CBEP-SoCB/Lake_Water_Quality_sum)  
    *  Redrafting graphics based on Portland Water District's Lake 
	   Vulnerability Index. .......... 
	   [PWD_Lake_WQ_Index_sum](https://github.com/CBEP-SoCB/PWD_Lake_WQ_Index_sum)
    *  Water quality data from the Presumpscot Watershed. ..........
	   [Presumpscot_Water_Quality_sum](https://github.com/CBEP-SoCB/Presumpscot_WQ_sum)  
*  E.	Climate Change  
    *  Analysis of eight decades of weather data from the Portland Jetport.
	   Data accessed through NOAA online data APIs.  ..........
	   [CDO-Portland-Jetport_sum](https://github.com/CBEP-SoCB/CDO-Portland-Jetport_sum)  
	*  Analysis of nearly a century of sea levels at the Portland
	   tide gauge and forcasts of future tidal flooding frequencies. .......... 
	   [Portland-SLR_sum](https://github.com/CBEP-SoCB/Portland_SLR_sum)  
*  F.	Invasive Species 
    *  Review of MIMIC data on prevalence of selected invasive
	   marine invertebrates in Casco Bay. .......... 
	   [CB_Invasives_sum](https://github.com/CBEP-SoCB/CB_Invasives_sum)

### CONDITION OF THE BAY; "How is the Bay doing?"	
*  G.	Bay Water Quality  
    * Friends of Casco Bay (FOCB) water quality monitoring data. .......... 
  	[FOCB_Data](https://github.com/CBEP-SoCB/FOCB_WQ_sum)  
	  * Bay Stratification -- Analysis of stratification in several Casco Bay
	  subestuaries. .......... 
	  [Bay_Stratification](https://github.com/CBEP-SoCB/Bay_Stratification_sum)
*  H.	Nutrients  
    *  Friends of Casco Bay (FOCB) nutrient-related data. .......... [FOCB_Nutrients_sum]((https://github.com/CBEP-SoCB/FOCB_Nutrients_sum)
    *  Maine Department of Environmental Protection (DEP) nutrient-related data. .......... [DEP_Nutrients_sum]((https://github.com/CBEP-SoCB/DEP_Nutrients_sum)
    *  Combined FOCB and DEP nutrient data. .......... [Combined_Nutrients_sum]((https://github.com/CBEP-SoCB/Combined_Nutrients_sum)
*  I.	Aquatic Connectivity  
*  J.	Eelgrass  
*  K.	Coastal Acidification  
    * Analysis of data collected by UNH, on behalf of CBEP, measuring
	OA-related parameters at the Southern Maine Community College pier,
	in South Portland.  .......... 
	[CBEP_OA](https://github.com/CBEP-SoCB-Details//CBEP_OA)  
	* Analysis of a four years of Friends of Casco Bay (FOCB) water quality
	data that pertians to ocean acidification.  Data is from data loggers
	deployed off Chebeague Island. .......... 
	[FOCB_OA](https://github.com/CBEP-SoCB-Details//FOCB_OA)  
*  L.	Swimming Beaches and Shellfish Beds  
    *  Maine Department of Marine Resources (DMR) data on bacteria in
	shellfish. .......... 
	[Shellfish_Bacteria](https://github.com/CBEP-SoCB-Details//Shellfish_Bacteria)  
	*  Maine Beaches Program data on bacteria at monitored beaches. ..........  
	[Beaches_Bacteria](https://github.com/CBEP-SoCB-Details//Beaches_Bacteria)  
*  M.	Toxics  
    * CBEP historical data on toxics in Casco Bay Sediments. .......... 
	[CBEP_Sediments](https://github.com/CBEP-SoCB-Details//CBEP_Sediments)  
	* Maine Surface Water Ambient Toxics (SWAT) data on toxic
	contaminants in blue mussels. ..........
	[SWAT_Mussels](https://github.com/CBEP-SoCB-Details//SWAT_Mussels)  
	* Portland Harbor Commission data on toxic contaminants in Portland
	harbor sediments. .......... 
	[PortlandHarborToxics](https://github.com/CBEP-SoCB-Details//PortlandHarborToxics)  
	* Maine Board of Pesticides Control data on pyrethroid pesticides in
	intertidal sediments. .......... 
	[BPC_Pesticides](https://github.com/CBEP-SoCB-Details//BPC_Pesticides)  

### HUMAN CONNECTIONS; "What's Being Done?"	  
*  N.	Conserved Lands  
*  O.	Coastal Habitats  
*  P.	Economics  
    *  Analysis of recent (pre-pandemic) data on number of cruise ships and 
    cruise ship visitors visiting Portland, Maine. .......... 
	[PortlandCruiseShips](https://github.com/CBEP-SoCB-Details//PortlandCruiseShips)  
*  Q.	Education  
*  R.	Stewardship  
*  S.	Climate Preparedness  

# Reuseable Code and Utilities
*  Small package to facilitate use of maximum likelihood estimates of 
   (unobserved) left censored values in left censored data, such as
   observations of concentrations of contaminants or bacteria.
   ..........  [LCensMeans](https://github.com/CBEP-SoCB/LCensMeans)
*  Utility package to facilitate uniformity in graphic design for 
   the 2020-2021 **State of Casco Bay** report.  Defines a default
   graphic style, fonts and six preferred colors.  ..........
   [CBEP_graphics](https://github.com/ccbCBEP-SoCB60/CBEP_graphics)
*  Package to generate several varieties of ggplot style graphics from depth 
   profile data, including interpolated two dimensional depth by time or
   depth by location color plots. [tdggraph](https://github.com/ccbCBEP-SoCB60/tdggraph)

# General Data Sources and Information
*  Watershed Boundary
*  Impervious Cover
*  NHD hydrography
*  Others

## About Casco Bay and Casco Bay Estuary Partnership
Casco Bay Estuary Partnership (CBEP) is one of twenty eight National Estuary
Programs.  Each National Estuary Program is a locally led, non-regulatory,
science-based collaborative organization that works to address challenges facing
Estuaries of National Significance and the communities on their shores.

CBEP works with dozens of partner organizations, including federal, state, and
local government; colleges and universities; non-profits and interest groups;
local businesses and private citizens on behalf of Casco Bay, a coastal
embayment in southern Maine.

You can find more information about CBEP on our 
[web site](https://www.cascobayestuary.org).

Casco Bay is approximately 160 square miles in size, dotted with hundreds of
islands. The roughly 980 square mile watershed is long and narrow, extending as
far as the mountains of Western Maine.  Fourty eight towns and cities touch the
watershed.  Twelve are coastal communities with marine shorelines. Our largest
urban center is Portland, Maine, located on the South West corner of the Bay.
Dozens of lakes dot the watershed including Sebago Lake, Maine's deepest, and
second largest.  The climate is cool-temperate. On the order of a meter of
precipitation falls in most years, spread more or less evenly over twelve
months. Most of that precipitation falls as rain, but snow predominates in the
winter months.

The Casco Bay watershed represents on the order of four and a half  percent of
the land area of Maine, but close to a quarter of the state's population, and a
third of employment and economic activity.  The regional economy is dominated by
the service economy of Portland, but marine-related industries represents about
four percent of jobs and economic activity in the region. That share is
substantially higher for our island and peninsula communities.

Casco Bay supports a robust lobster fishery, substantial clam harvests, a
growing aquaculture industry(principally blue mussels, american oyster, and
sugar kelp). Portland Harbor handles both container ships and oil tankers.
Land-based businesses on the waterfront support Maine's fishing industry, but
also support a burgeoning restaurant scene.  In fact, tourism (including
restuarants, lodging, cruise ships, tour operations, etc. (but omitting property
rentals and real estate) represents close to three quarters of all
marine-related economic activity of the region.

## The Team
The primary author of this archive is Curtis C. Bohlen, Director and lead
scientist of the Casco Bay Estuary Partnership. Other members of the CBEP
staff, including Marti Blair, Victoria Boundy, Matthew Craig, and Thomas
Gilmartin have made additional contributions.

You can find more information about us at the 
[CBEP website](http://cascobayestuary.org).
