# Top-Earning-Musical-Tours-2-in-The-Past-Four-Years 
## By Alex Ducca 
### Data Analysis Process
* Download the [Top 10 Musical Tours of the Past 4 Years](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/blob/d40c1eedbebe700ad19cf75a5d4c9dda6bb3c1fa/Top%2010%20Musical%20Tours%20(2019-2022).xlsx) as an excel file and then open the file in google sheets. 

_5 Questions with Step by Step Answers on the following Data Sheet_ 

**Question 1: Based on the provided Datasheet, which Artists/Record Agency are in the Top 5 grossing musical tours of the past four years? Which Artists/Record Agency are in the lowest 5 grossing musical tours? Include a screenshot of a pivot table.** 

**Step by Step Answer** 

1. First highlight the data from A1 to I41.
2. Click on the _Insert_ columnn located on the top left corner of the google sheets document and click on the 6th option _Pivot Table_ and create table in new sheet.
3. After, click on the _Pivot Table_ tab located in the bottom left corner of Google Sheets to bring you to the _Pivot Table_.
4. Once that is open, look at the right side of the screen where it says _Pivot Table Editor_ and add **Gross/Millions** to the _Values_ tab and the _Filters_ tab.
5. On the _Filters_ tab for **Gross/Millions** click on "showing all items" and "filter by value"; all values here will be shown from lowest to greatest; checkmark the values **$86,700,000--$87,100,000--$115,500,000--$160,400,000--$177,800,000--$201,800,000--$212,000,000--$215,200,000--$358,500,000**.
6.  After that, add **Artists** to the _Rows_ tab
7.  Add **Agency** to the _Columns_ tab. 

* The Pivot Table should look like this.
 ![Pivot table 1 for queestion 1](/Question1PivotTable.png) 


 * **As shown from the Pivot Table- the top earners in the past 4 years were Elton John(Howard Rose/Rocket Music Ent.), Bad Bunny(United Talent Agency), The Rolling Stones(Concerts West), Harry Styles(Creative Artist Agency), and P!ink(Marshall Arts).**  

8. To find the 5 lowest grossing musical tours based on the provided data; go to _Pivot Table Editor_ and click on the _Filters_ tab for **Gross/Millions**. Click on _Filter by Values_, and check the values __$25,500,000--$40,300,000--$44,400,000--$44,600,000--$46,000,000__ 

* The Pivot Table should look like this

![Capture](/Question1APivotTable.png) 



* **As shown from the Pivot Table- The lowest earners were Andrea Bocelli(Klassics Music Management Limited), Post Malone(United Talent Agency), Phish(Wassernan Music), Queen + Adam Lambert(Creative Artists Agency), and Dave Matthews Band(Wasserman Music).**

**Question 2: Which five agencies in the top 10 musical tours grossed the most money in the past four years?** 

**Step By Step Answer** 

1. Repeat steps from question 1 explanation on how to create a pivot table.
2. Add **Agency** to the _Rows_
3. Add **Gross/Millions** to the _Values_ tab.
4. Add **Gross/Millions** to the _Filters_ tab.
5. In the _Filters_ tab click on "showing all items" and click on "Filter by Value"
6. Checkmark the top 5 greatest values --**$358,500,000--$215,200,000--$212,000,000--$211,700,000--$201,800,000** 
* The Pivot Table should look like this.

![Question 2 Pivot table](/Question2PivotTable.png) 

* **As shown in the Pivot Table, the top five agencies that grossed the most money in the past 4 years is _United Talent Agency_($358,500,000)--_Marshall Arts_(215,200,000)--_Howard Rose/Rocket Music Ent. Grp._(212,000,000)--_Creative Artists Agency_(211,700,000)-and-_The Howard Rose Agency_(201,800,000).**

**Question 3: Which two genres of music are most consistent in the top 10 muscial tours of the past 4 years.**

  **Step By Step Answer**

  1. Repeat steps on how to create a Pivot Table
  2. Add **Genre of Music** to the _Row_ tab.
  3. Add **Genre of Music** to the _Value_ tab.
  4. On the _Value_ tab click on "Summarize by COUNTA".

* The Pivot Table should look like this.
![Question 3 Pivot Table](/Question3PivotTable.png) 

* **As shown in the Pivot Table, the top 2 genres of music in the top 10 musical tours of the past 4 years are _Rock_(21) and _Pop_(11)**

**Question 4: Which musical tour/artist has the highest average ticket price in the last 4 years?** 

**Step By Step Answer** 

1. Create a Pivot Table.
2. Add **Artist** to the *Rows* tab.
3. Add **Average Ticket Price** to the _Values_ tab.
4. On the _Values_ tab click on "Summarize by AVERAGE"

* The Pivot Table should look like this.

![Question 4 Pivot Table](/Question4PivotTable.png) 

* **As show in the Pivot Table, the highest _Average Ticket Price_ for an artist goes to _Dead & Company_ with an average of $256.63 per ticket.**

**Question 5: Which 5 Artists and Agency had the highest average tickets sold in the past 4 years?** 

1. Create a Pivot Table
2. Add **Artist** to the _Rows_ tab.
3. Add **Average Tickets Sold** to the _Values_ tab.
4. On the _Values_ tab click on "Summarize By Average".

* The Pivot Table should look like this. 

![Question 5a Pivot Table](/Question5PivotTable.png)

* **As shown in the Pivot Table, the artists with the highest average tickets sold in the past 4 years are Ed Sheeran(48,151)--The Weekend(47,404)-- Garth Brooks(46,865)--The Rolling Stones(46,047)-and-Bon Jovi(42,286)** 
* Finding the 5 Agencies with Highest average tickets sold.

1. Create Pivot Table
2. Add **Agency** to the _Rows_ tab.
3. Add **Average Tickets Sold** to the _Values_ tab.
4. On the _Values_ tab click on "Summarize by Average".

* The Pivot Table should look like this.

![Question 5b Pivot Table](/Question5aPivotTable.png) 

* **As shown in the Pivot Table, the 5 Agencies with the highest average tickets sold in the past 4 years are Big Hit Entertainment(40,434)--MNS2(39,705)--Live Nation Global Touring(40,434)-and-Creative Artists Agency(27,010)**

**Question 6: Which genre has made the most money in the past 4 years?** 

1. Create a Pivot Table
2. Add **Gross/Millions** to the _Values_ tab.
3. Add **Genre of Music** to the _Rows_ tab.

* The Pivot Table should look like this.

![Question6](/Question6PivotTable.png) 

* **As showin in the Pivot Table, the genre of music that has made the most money in the past 4 years is Rock with $2,095,900,000.** 


### Story Summary and Sourcing 

The goal with this data is  to illustrate that the genre of Rock is not “dead” despite articles by well-known music magazines/organizations saying it is. Based off the data from the trade publication Pollstar the genre of Rock is still represented in the top 10 grossing musical tours of all time in the past four years. Moreover, the genre of Rock is the most prevalent in the highest average tickets sold , average ticket price, and  in the genre of the artist. 

The Article [_Rock ‘N’ Roll Is Dead. No, Really This Time_ by _Forbes_](https://www.forbes.com/sites/dannyross1/2017/03/20/rock-n-roll-is-dead-no-really-this-time/?sh=3fb4ac564ded) magazine presents data that shows that the genre of Rock is dead, based on the genre’s relevance in modern day streaming sales. Although this article presents valid data and opinions on the state of Rock as a genre, Forbes is neglecting to acknowledge that the genre of Rock is still outperforming other genres such as Pop and Hip Hop/Rap. Additionally, Rock and Rock artists have been consistently in the top 10 and top 5 highest grossing musical tours in the past four years. For this story I will be interviewing Danny Ross (Twitter @dannyrossmusic) from Forbes Music to get his opinion on the data from the last 4 years and whether they still agree with the notion that ‘Rock is Dead’  while being presented the data from Pollstar. 

Moreover, in the article [_Is Rock ‘n’ Roll Dead, or Just Old?_ by Bill Flanagan](https://www.nytimes.com/2016/11/20/opinion/sunday/is-rock-n-roll-dead-or-just-old.html), Flanagan takes a similar approach to the Forbes article stating that the Rock genre is dying in terms of growing record sales and radio play. He claims that Rock is coming to an end because the new generation are taking over the sound waves in terms of streaming, radio, and record sales. I would like to interview Bill Flanagan (Twitter @BillFlanagan) because I believe he would provide good insight when given the data that shows that the genre of Rock still dominating the musical tour spectrum of the business. 

### Data Visualizations 

_The Following is a bar chart that illustrates how much money the genres, found in the Top 10 musical tours, have made in the past 4 years._ 

![DataViz](/DataVizUpdate.png) 





