# Data-Engineering-and-visualization

## Introduction
Data engineering is a fundamental part of every analysis. The term refers to the planning, preparation, and processing of data to make it moreuseful for analysis. It can include simple tasks like identifying and correcting imperfections in your data and calculating new fields. It can alsoinclude more complex tasks like reducing the dimensions of a multivariate dataset.
Data engineering also involves the process of geoenriching your data. Geoenrichment can include various tasks:
· Adding a spatial location to your data, referred to as geocoding
· Using other data sources to extract information and add, or enrich, these values to your dataset
· Calculating new fields that represent spatial characteristics, like the distance from a particular feature in a landscape

## Scenario
Because voting is voluntary in the United States, the level of voter participation (referred to as "voter turnout") has a significant impact on theelection results and resulting public policy.
Modeling voter turnout, and understanding where low turnout is prevalent, can inform outreach efforts to increase voter participation. With the ultimate goal of predicting voter turnout, in this project, the focus is on performing various data engineering tasks to prepare election result data for predictive analysis.
The data for this section is obtained from the Harvard Dataverse and the United States Census Bureau
. The voter turnout dataset from Harvard Dataverse has vote totals from each U.S. county for U.S. presidential elections from 2000 to 2020.

## Tools
- ArcGIS Pro 3.2.0
- Python: ArcGIS Notebook
In this exercise, ArcGIS Notebooks and the Data Engineering view in ArcGIS Pro was used to perform data engineering tasks. These tasks will use the built-in tools that are available with these products as well as tools that are available by integrating open-source libraries. Using ArcGISNotebooks allows for the documentation and sharing of steps taken to prepare the data for analysis, ensuring transparent and reproducible research or analysis.

## Description
Data files for this project was derived from MIT Election Data and Science Lab (Massachusetts Institute of Technology) and can be found on the [Havard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ). The voter turnout dataset has vote totals for each US Presidential election from 2000 - 2020, for each county in the US. The data and related materials can be found on Esri's (https://www.esri.com) and are intended for educational purposes only (see Terms of Use).

## Terms of Use
None, Harvard Dataverse data is licensed as public domain under CC0 Public Domain Dedication.
Use of this Data is restricted to training, demonstration, and educational purposes only. This Data cannot be sold or used for marketing without the express written consent of Environmental Systems Research Institute Inc. THE DATA AND RELATED MATERIALS MAY CONTAIN SOME NONCONFORMITIES, DEFECTS, OR ERRORS. ESRI DOES NOT WARRANT THAT THE DATA WILL MEET USER'S NEEDS OR EXPECTATIONS; THAT THE USE OF THE DATA WILL BE UNINTERRUPTED; OR THAT ALL NONCONFORMITIES, DEFECTS, OR ERRORS CAN OR WILL BE CORRECTED. ESRI IS NOT INVITING RELIANCE ON THIS DATA, AND THE USER SHOULD ALWAYS VERIFY ACTUAL DATA.THE DATA AND RELATED MATERIALS ARE PROVIDED "AS-IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.IN NO EVENT SHALL ESRI AND/OR ITS LICENSOR(S) BE LIABLE FOR COSTS OF PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOST PROFITS, LOST SALES, OR BUSINESS EXPENDITURES, INVESTMENTS, OR COMMITMENTS IN CONNECTION WITH ANY BUSINESS; LOSS OF ANY GOODWILL; OR FOR ANY INDIRECT, SPECIAL, INCIDENTAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES ARISING OUT OF THIS AGREEMENT OR USE OF THE DATA AND RELATED MATERIALS, HOWEVER CAUSED, ON ANY THEORY OF LIABILITY, AND WHETHER OR NOT ESRI OR ITS LICENSOR(S) HAVE BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. THESE LIMITATIONS SHALL APPLY NOTWITHSTANDING ANY FAILURE OF ESSENTIAL PURPOSE OF ANY EXCLUSIVE REMEDY.In the event that the data vendor(s) has (have) granted the end user permission to redistribute the Geodata, please use proper proprietary or copyright attribution for the various data vendor(s), and provide the associated metadata file(s) with the Geodata.

## Credits (Attribution)
MIT Election Data and Science Lab (Massachusetts Institute of Technology), Esri Training Services - for educational purposes only

