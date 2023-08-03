# Top-Earning-Musical-Tours-2-in-The-Past-Four-Years 
## By Alex Ducca 
### Data Analysis Process
* Download the [file]( "Top Earning Tours in The Past Four Years"

_5 Questions with Step by Step Answers on the following Data Sheet_ 

**Question 1: Based on the provided Datasheet, which Artists/Record Agency are in the Top 5 grossing musical tours in the past four years? Which Artists/Record Agency are in the lowest 5 grossing musical tours? Include a screenshot of a pivot table.** 

**Step by Step Answer** 

1. First highlight the data from A1 to I41.
2. Click on the _Insert_ columnn located on the top left corner of the google sheets document and click on the 6th option _Pivot Table_ and create table in new sheet.
3. After, click on the _Pivot Table_ tab located in the bottom left corner of Google Sheets to bring you to the _Pivot Table_.
4. Once that is open, look at the right side of the screen where it says _Pivot Table Editor_ and add **Gross/Millions** to the _Values_ tab and the _Filters_ tab.
5. On the _Filters_ tab for **Gross/Millions** click on "showing all items" and "filter by value"; all values here will be shown from lowest to greatest; checkmark the values **$86,700,000--$87,100,000--$115,500,000--$160,400,000--$177,800,000--$201,800,000--$212,000,000--$215,200,000--$358,500,000**.
6.  After that, add **Artists** to the _Rows_ tab
7.  Add **Agency** to the _Columns_ tab. 

* The Pivot Table should look like this.
 ![Pivot table 1 for queestion 1](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/cd8dbf34-f4ab-449b-ae0f-a05185bca4bc)


 * **As shown from the Pivot Table- the top earners in the past 4 years were Elton John(Howard Rose/Rocket Music Ent.), Bad Bunny(United Talent Agency), The Rolling Stones(Concerts West), Harry Styles(Creative Artist Agency), and P!ink(Marshall Arts).**  

8. To find the 5 lowest grossing musical tours based on the provided data; go to _Pivot Table Editor_ and click on the _Filters_ tab for **Gross/Millions**. Click on _Filter by Values_, and check the values __$25,500,000--$40,300,000--$44,400,000--$44,600,000--$46,000,000__ 

* The Pivot Table should look like this

![Capture](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/ea55a3e3-101e-463b-8f18-ee93d9c70473)



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

![Question 2 Pivot table](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/69b3092f-42b4-4a48-a2ec-b1efebdaf0c3) 

* **As shown in the Pivot Table, the top five agencies that grossed the most money in the past 4 years is _United Talent Agency_($358,500,000)--_Marshall Arts_(215,200,000)--_Howard Rose/Rocket Music Ent. Grp._(212,000,000)--_Creative Artists Agency_(211,700,000)-and-_The Howard Rose Agency_(201,800,000).**

**Question 3: Which two genres of music are most consistent in the top 10 muscial tours of the past 4 years.**

  **Step By Step Answer**

  1. Repeat steps on how to create a Pivot Table
  2. Add **Genre of Music** to the _Row_ tab.
  3. Add **Genre of Music** to the _Value_ tab.
  4. On the _Value_ tab click on "Summarize by COUNTA".

* The Pivot Table should look like this.
![Question 3 Pivot Table](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/736b7f0c-da42-44eb-9cf6-942db6f7fcea)

* **As shown in the Pivot Table, the top 2 genres of music in the top 10 musical tours of the past 4 years are _Rock_(21) and _Pop_(11)**

**Question 4: Which musical tour/artist has the highest average ticket price in the last 4 years?** 

**Step By Step Answer** 

1. Create a Pivot Table.
2. Add **Artist** to the *Rows* tab.
3. Add **Average Ticket Price** to the _Values_ tab.
4. On the _Values_ tab click on "Summarize by AVERAGE"

* The Pivot Table should look like this.

![Question 4 Pivot Table](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/e815f5d6-695b-4bc6-bda3-d97f87f70455) 

* **As show in the Pivot Table, the highest _Average Ticket Price_ for an artist goes to _Dead & Company_ with an average of $256.63 per ticket.**

**Question 5: Which Artist and Agency had the highest average tickets sold in the past 4 years?** 

1. Create a Pivot Table
2. Add **Artist** to the _Rows_ tab.
3. Add **Average Tickets Sold** to the _Values_ tab.
4. On the _Values_ tab click on "Summarize By Average".

* The Pivot Table should look like this.

![Question 5a Pivot Table](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/0c5a6c90-85ad-4bf6-9bc0-abb1dea79eae) 

* **As shown in the Pivot Table, the artist with the highest average tickets sold in the past 4 years is Ed Sheeran with an average of 48,151 tickets sold.**
* Finding the Agency with Highest average tickets sold.

1. Create Pivot Table
2. Add **Agency** to the _Rows_ tab.
3. Add **Average Tickets Sold** to the _Values_ tab.
4. On the _Values_ tab click on "Summarize by Average".

* The Pivot Table should look like this.

![Question 5b Pivot Table](https://github.com/axducca438/Top-Earning-Musical-Tours-2-in-The-Past-Four-Years/assets/140102446/835d66df-8b2f-4b63-ad48-4b95bf219e92) 

* **As shown in the Pivot Table, the Agency with the highest average tickets sold in the past 4 years is Conerts West with 46,047 average tickets sold.** 



