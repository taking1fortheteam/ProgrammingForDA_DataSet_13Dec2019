# ProgrammingForDA_DataSet_13Dec2019
Real World Analysis of real-world phenoemon - synthesis, simulate, research and investigation.

I manage a team of 9 Technical SUport Engineers spread across the globe, 3 in Galway, 2 in Cavite (Philippines) and 5 in Rhode Island (USA). Each have different skills or different products they support and these ar the experts when you or I callSchneider Electric for TEchnical SUpport on any of the APC branded UPS's (Uninterruptible Power Supplies).

Managing this team requires insights to the work they do, as you can imagine, with them being quite remote to me, it is important that I see what work they are completing without me standing over them to ensure the work gets completed. 

We use a platform called Salesforce that is a large corporate CRM application that is spread far and wide but is identical no matter where one might be located in the world. All the information is logged in cases and when cases are escalated to my team this is wher the data becomes vital to me for the successful management of the team ensuring correct resorse allocation, training needs are met, customers needs are met, etc. etc.

WHat I have provided inthis Jupyter Notebook is a sample of what the data from Salesforce may resemble. Essentially there would be 8 key pieces of information when it comes to my team and their case management. 

1. A case reference. THis is what is provided to a csutoemr so they can track the progress of any case and they always have a reference to go back to.
2. The Level 3 Engneer working onthe case.
3. The date the Level 3 engineer is assigned the case.
4. The date the Level 3 Engineer begins working on the case.
5. THe date the Level 3 engineer closes the case.
6. Is the case truly closed? (there are various resons why this might not be the case but Iw ill refrain from goinginto those now)
7. Has the case been resolved? 
8. Has the customer been surveyed?

With all this information I can see any gaps or issues within the team. But to be able to automatically process the data would be a massive improvement than what is currently in place. 
One issues that I have uncovered in the actual applicationwithin my work environment is the fact that the CRM tool does not play nice when reports are being run. I mean if a case is escalated multiple times to my team, the CRM tool only looks at the 1st instance it is escalated and the very last instance it is de-escalated to calculate the time my team has been workingon the case. This is a nonsense. And this is the real reason this is why this project has been selected. 

Unfortunately a lot of time was lost learning, and as such, towards the end I had to skip over a lot of what I really wanted to do. But if time is allocated to me I intend to finish the analytical part of the project, as it is quite unfinished presently. 

But furthermore I would like to take some real data fromthe Salesforce CRM and to apply it to this analysis I have crated to see what I can do to make my life a lot more effecient and ultimately better. Same goes for my teams performance and standing within the company.

TO run the file all you need is to save the notebook to your own machine and run it as you would any Jupyter Notebook. ALl the data is generated automatically as are the plots. Enjoy :)