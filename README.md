

# FINDING STORIES WITH DATA

On this page you will find files and exercises which accompany [CIJ course](https://tcij.org/scheduled-training) Finding Stories with Data.

**Module 1**

-   After session 1, it will help you to consolidate what you learned by downloading [this file](https://github.com/Stonepeople/FSiD/blob/main/donations2019_2020_Exercise.xlsx) and trying the exercises which are contained within it. NB - the data is similar to what we used in class, but it's older, so the results will not be the same as they were during the session. 

-   [This](https://github.com/Stonepeople/FSiD/blob/main/Interviewing_data.pdf) is the short presentation

-   -   If you just want to read about pivot tables [this pdf](https://github.com/Stonepeople/FSiD/blob/main/PIVOT%20TABLES.pdf) is all you need.
    -   If you have had enough of political donations for now, try downloading a dataset about something you're interested in - [this gov.uk site](https://www.gov.uk/government/statistical-data-sets) is a great place to start. We will of course be covering how to find data in more detail in session 2. 



**Module 2**

-    Finding data quickly and efficiently is a skill that's worth practicing; the best sites and tricks will depend on the beat you're working on, and we can't cover everything in a single session. So you will probably find it helpful to download the fuller list of advanced operators the [Cheatsheet](https://github.com/Stonepeople/FSiD/blob/main/GoogleguideCheatSheet.pdf) from [googleduide.com](http://www.googleguide.com/print/adv_op_ref.pdf).
-    You may also want to read  this excellent [Guide to Google Dorking (another name for advanced searching)](https://exposingtheinvisible.org/guides/google-dorking/) to get a deeper insight into what we did, and how it can help your investigation. It also covers some important security issues.
-    If it helps - you can download the [presentation on finding data](https://github.com/Stonepeople/FSiD/blob/main/FindingData.pdf) which we went through in class.

-  If money is your beat, this set of links will help to get you started [Follow the Money](https://github.com/Stonepeople/FSiD/blob/main/FollowTheMoney.pdf). 
-  
-   This link will take you to a list of links used in the the [Finding data presentation](https://github.com/Stonepeople/FSiD/blob/main/Links%20from%20FindingData.pdf)

The [Awesome Public Datasets repo](https://github.com/awesomedata/awesome-public-datasets) as the name suggests - is awesome!

-  And this set of generally [useful links](https://github.com/Stonepeople/FSiD/blob/main/USEFUL%20LINKS%20TO%20DATA.pdf) may also help get you started.

These [tabs](https://www.one-tab.com/page/JkfVibrkRyuw8EeOIscRag) will take you to the information and sites in the main presentation



**Module 3**
Module 3 is entirely remote - you do the work in your own time, preferably between module 2 and module 4 in order to bring any questions or issues you encounter to discussion at the beginning of Module 4.

-  Rather than spending a whole live session being bombarded with new information, you can come prepared, possibly having had a chance to try some of the techniques for yourself, or ready to ask questions and solve them in the session. 
-   [ImportHTML](https://youtu.be/h3Nyld3wNzY) - shows a simple way to scrape (convert a table from a web page to a spreadsheet) using a formula built into Googlesheets. This formula will get you a long way without needing to learn code. 
-   NB - The importhtml formula works for many a site, but since making this video it has become impossible to scrape the parliament.uk data as shown. That data is now available as a [download](https://www.parliament.uk/mps-lords-and-offices/standards-and-financial-interests/parliamentary-commissioner-for-standards/registers-of-interests/register-of-interests-of-members-staff/) 
  
   - names, especially company names, can be rendered in a dataset in so many different ways, so it's worth learning how to use a tool which can identify these slight differences and correct them so that the computer can pull together all the data relating to the same entity. This video shows you the core function of openrefine [cleaning data](https://youtu.be/oJ3WqlwzeeE)
 
     - Openrefine, crucially, doesn't edit the dataset you give it to clean - it works on it, within a browser window, and when you have done the cleaning, you need to "export" the data back to an xls or csv file. This video shows you how to [export your OpenRefine project](https://youtu.be/UWJIu0Ss4eU) To follow along using the same data you will need the source table from this [Wikipedia page](https://en.wikipedia.org/wiki/List_of_MPs_elected_in_the_2019_United_Kingdom_general_election). 

-   Matching names in a column in OpenRefine with company names on OpenCorporates.com.To see how it's done, watch [this video](https://youtu.be/3CV6rEn0stM) 

-   NB – to make use of the OpenCorporates reconciliation service you will need to add this address to the reconciliation menu in OpenRefine https://opencorporates.com/reconcile (see 1.18” in the video).

-   See [here](https://api.opencorporates.com/documentation/Reconciliation_API_documentation_v0.1.pdf) for documentation.

-   NB In order to make this work with your copy of OpenRefine, you will also need to create an OpenCorporates account, and apply for a (free) API key. OpenCorporates will then add your IP address to their list of users whose computers are allowed to use the reconcile function.

-   When we first wrote this guide, we recommended [Tabula](https://tabula.technology/) as a free tool to extract tables from pdf files and save them as csv files. [This video](https://youtu.be/xZ_sPdJtOLo)walks you through the process.

-   However - in the last 12 months or so, AI tools have begun to do the same job more quickly, and sometimes more accurately than Tabula and other pdf to csv conversion tools. You can ask various llm's to do the job, specifying the columns you want, and columns it can ignore. We have been getting excellent results with AI within a coding environment - so the AI not only does the job, it leaves you with a script you can use to do the same job when the pdf you need is next updated. 

- 	One of the best ways to get ahead of competitors who have the same data as you is to combine your dataset with another in order to answer more questions, or dig out more detail. Before AI, everyone had to learn the VLOOKUP formula, which we demonstrate in [this video](https://youtu.be/NCBP8Z1x_RY).
- 	In this example, where we wanted to add to the data showing donations to Members of Parliament, we also needed to clean the names - one dataset had honorifics (Mr, Mrs, Dr, The Rt Hon etc) which stopped us joining it to the other dataset which just included MPs names - so we demonstrate how to [clean names](https://youtu.be/tCET1qWOb3U) with OpenRefine. This process also creates a reproducible script which you can keep to save time when you do the same job in the future.
  
-   We also demonstrate [Power Query](https://youtu.be/9P6iyjPguok) This is an Excel feature which allows you to merge data without learning VLOOKUP. It also keeps a record of what you have done, so you can check or reproduce your work – eg when you use a later edition of the same data. In the age of AI, this may not be necessary - you can ask a Microsoft AI tool such as Co-Pilot to do all this for you. But it's worth knowing what it's going to do. 

Practice material accompanying the videos

•	To practice “VLookup” you need to download a copy of [this worksheet](https://github.com/Stonepeople/FSiD/blob/main/MPs_donations_vlookup_exercise.xlsx) containing the two datasets.

•	If you want to practise cleaning the MPs names (removing titles etc) using OpenRefine as in the video "Cleaning names with OpenRefine", you will need to download a copy of [this dataset](https://github.com/Stonepeople/FSiD/blob/main/Donations_to_MPs.csv)

•	To get a copy of the company donation data demonstrated in the cleaning and reconciling videos (2nd and 4th on the list), open [this link](http://search.electoralcommission.org.uk/?currentPage=1&rows=10&sort=AcceptedDate&order=desc&tab=1&open=filter&et=pp&et=ppm&et=tp&et=perpar&et=rd&isIrishSourceYes=true&isIrishSourceNo=true&date=Reported&from&to&quarters=2021Q1234&quarters=2020Q1234&prePoll=false&postPoll=true&donorStatus=company&register=gb&register=ni&register=none&optCols=Register&optCols=CampaigningName&optCols=AccountingUnitsAsCentralParty&optCols=IsSponsorship&optCols=IsIrishSource&optCols=RegulatedDoneeType&optCols=CompanyRegistrationNumber&optCols=Postcode&optCols=NatureOfDonation&optCols=PurposeOfVisit&optCols=DonationAction&optCols=ReportedDate&optCols=IsReportedPrePoll&optCols=ReportingPeriodName&optCols=IsBequest&optCols=IsAggregation) in a new tab, and download a copy of the resulting file - using the [Export results] button.

•	To practice the Power Query demo with the data used in the [video](https://youtu.be/9P6iyjPguok) you will need to download copies of these two datasets:
– [donations to MPs](https://github.com/Stonepeople/FSiD/blob/main/Donations_to_MPs.csv) 
and
[list of MPs elected in 2019](https://github.com/Stonepeople/FSiD/blob/main/ListofMPs2019election.csv)

-   OpenRefine itself is well-documented, and the startup screen contains links to useful instructional videos. You may also find [this pdf](https://github.com/Stonepeople/FSiD/blob/main/OPEN%20REFINE%20STARTER%20NOTES_JS.pdf) a useful written guide to get you started

-   Reconciling lists using OpenRefine is covered in [this pdf](https://github.com/Stonepeople/FSiD/blob/main/Reconciling%20in%20OpenRefine.pdf)
-
-   In September 2024 we added to the Finding Stories course an optional presentation on webscraping, which also introduces APIs, and why you need to know about them. The summary of the presentation is in [this pdf](https://1drv.ms/b/s!AkCB08o5241CjMMBLfL69qBakjHa0Q?e=qOUpCd) Meanwhile [Scraping the web](https://github.com/Stonepeople/FSiD/blob/main/scraping%20the%20web.pdf) is an excellent tipsheet from [IRE](https://www.ire.org/) (it's well worth joining IRE. At around $70 a year it's worth  joining just for the library of tipsheets!)

When you're ready to do some more practice, read on:

Challenge part 1 (optional) – pdf to spreadsheet. [This link](https://github.com/Stonepeople/FSwD/blob/main/Gifts_visits_short.pdf) takes you so a relatively small list (37 names) of House of Commons staff who have declared receipt of Gifts or Hospitality. As in the real world, you may receive such data as a pdf file. 
Although you can ask the publisher to send it to you as csv/xls, you may want to convert it to those formats yourself. We recommend Tabula, but other methods are available, including CometDocs, see this [review page](https://pdf.wondershare.com/top-pdf-software/best-pdf-to-excel-converter.html) 

If you prefer, you can start here - 
Challenge part 2 – the pdf conversion should give you [this file](https://github.com/Stonepeople/FSwD/blob/main/Gifts_visits.xlsx) which has five columns and 37 rows. (NB – some of the entries in column 5 are so long they make the dataset very wide: in order to simplify the conversion process, we restricted the width of this column, so you will see that your conversion isn’t quite the same as this file – Gifts_visits.xlsx  This makes no difference to the exercises)
Column A contains the staff members’ family names in upper case, and column B their first names. Can you create a new column combining the names, all in one case (ie all upper, or with a capital first letter for each part), with “Firstname Surname”. 
	Hint – spreadsheet programs can do this using formulas such as UPPER, PROPER, and CONCATENATE. You may also want to try it in OpenRefine and see which you prefer. 
If you want more practice, try combining the MPs’ names into another new column, in one case, “SURNAME, FIRSTNAME” – ie, with a comma and space after the surname.  


**Module 4**


-   [Why visualise](https://github.com/Stonepeople/FSiD/blob/main/Why%20visualise%20CIJ.pdf) is the presentation used in module 4. 
-   There's a quick introduction to making graphics from spreadsheets in two parts [Part 1](https://youtu.be/CPG3tj2vZYg) takes you raw data to a graph, and introduces you to [Datawrapper](https://www.datawrapper.de/). [Part 2](https://youtu.be/n3cFrf4pQsc) takes a look at creating a graph from a pivot table. 
-   [This video](https://youtu.be/Qv-g9XhpOf0) looks at how to do the same thing with Googlesheets
-   There's a more detailed step-by-step guide to making a visualisation from an Excel pivot table [here](https://youtu.be/Pakq8_hauwI) and from googlesheets [here](https://youtu.be/q4TxXLBpxa8)
-   [This video](https://youtu.be/Fw0YXqenFoo) looks at choosing the kind of chart most appropriate to the needs of your story
-   For handouts on choosing the right chart we recommend this interactive page produced by the Financial Times - [Visual Vocabulary](https://ft-interactive.github.io/visual-vocabulary/)
-   For those who like a pdf to refer to, this [Choosing a Chart](https://github.com/Stonepeople/FSwD/blob/main/choosing-a-good-chart-09.pdf) is the one referred to during the course. 
