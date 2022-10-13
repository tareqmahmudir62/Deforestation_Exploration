##  <b> Project Overview </b>  ##

A ficticious NGO called ForestQuery, a non-profit organization, which on a mission to reduce deforestation around the world and which raises awareness about this important environmental topic.

My executive director and her leadership team members are looking to understand which countries and regions around the world seem to have forests that have been shrinking in size, and also which countries and regions have the most significant forest area, both in terms of amount and percent of total area. The hope is that these findings can help inform initiatives, communications, and personnel allocation to achieve the largest impact with the precious few resources that the organization has at its disposal.

I have been able to find tables of data online dealing with forestation as well as total land area and region groupings, and I’ve brought these tables together into a database that I’d like to query to answer some of the most important questions in preparation for a meeting with the ForestQuery executive team coming up in a few days. Ahead of the meeting, I’d like to prepare and disseminate a report for the leadership team that uses complete sentences to help them understand the global deforestation overview between 1990 and 2016. The task is to bring these tables together and query the answers to some of the most important questions in preparation for a meeting with the ForestQuery executive team.

##  <b> Steps Taken to Complete the Task </b>  ##

    1. Create a View called “forestation” by joining all three tables - forest_area, land_area and regions in the editor.
    2. The forest_area and land_area tables join on both country_code AND year.
    3. The regions table joins these based on only country_code.
    4. In the ‘forestation’ View, include the following:
       a.  All of the columns of the origin tables
       b.  A new column that provides the percent of the land area that is designated as forest.
    5. Keep in mind that the column forest_area_sqkm in the forest_area table and the land_area_sqmi in the land_area table are in different units (square kilometers and        square miles, respectively), so an adjustment will need to be made in the calculation written (1 sq mi = 2.59 sq km).
    
##  <b> What I had to Produce? </b>  ##

I was tasked to create a report for the executive team in which I had to explain my findings/results. 

##  <b> Report Section </b>  ##

The report has five sections that I needed to complete:

      1. Global Situation
      2. Regional Outlook
      3. Country-Level Detail
      4. Recommendations
      5. Appendix: SQL queries used
