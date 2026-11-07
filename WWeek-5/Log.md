This week looked at using R in Google Colab which I have also used in my geography classes in the past. I also looked at  the three Harris matrix exercises, which I found pretty fun. There were definitely a lot of ups and downs and learning curves working with all this new stuff, especially the Harris matrices, which really confused me at the start. I think it was because of my lack of an archaeology background. 

**Archaeological statistics in R**
Initial thoughts and things 
- the R notebook took around 11 minutes to start running and fully execute, loading all of the data, which really confused me because I had never had it execute for that long unless an error was happening.
- The first things I looked at were working with the Dartpoints dataset and using functions like mean(), summary() and numsummary(), which was a good refresher since I have used R in over a year.
- Trying to include columns 1-4 in numsummary() gave me an error, I think because the columns were not made of numerical data, so you can summarize them like that.

  Trial Turns #1 and #2
  - I used the BACups data set that had 60 bronze age cups and different measurements that went with them
  - I used read() and summary() to look at the data and also created a bar graph with the data
  - Another issue I had, which confused me for a little while, was when I disconnected from wifi while going home and I started working on it again, and nothing was loaded. I got an error saying datasets not loaded. I was rushing at this point to try and finish a bit of the work before going somewhere, so when I realized I would have to load all the datasets again, I didn't have enough time.
  - <img width="641" height="493" alt="image" src="https://github.com/user-attachments/assets/5970ec00-29a7-49bc-9b7d-21e34e765ff3" />
  
Chi-squared test #3
- For this test, I used the EndScrapers dataset, comparing scraper widths and two archaeological sites
- I got a p-value of 0.0006, which would mean there could be an association between scraper widths and the sites they are found at.
- It is cool to think about how useful this could be and how it can speed up looking through data
-  <img width="379" height="701" alt="image" src="https://github.com/user-attachments/assets/b2a698c5-e9b4-4b9f-a65d-db572299bbb1" />

Graveyard Data #4 
- i loaded the graveyard data and ran some code to find out that it had 339 rows and 55 columns
- i created a bar graph to show the different conditions of gravestone inscriptions
- Messing around with it, I was also able to look at which cemeteries had the most recorded gravestones. Beechwood Cemetery had 20, and Billings Estate had 15. 
- One thing I noticed was that my graph looked kind of ugly because the names for the conditions of inscription were long and overlapped with other wording on the graph and i could not figure out how to make it look nicer.
- This was a good refresher because I remember having a lab a year ago where we really dove into creating graphs with R and Google Colab
- <img width="917" height="644" alt="image" src="https://github.com/user-attachments/assets/f8c1ae0a-4fb6-4b3f-a9a8-459b4cb2723c" />
<img width="604" height="362" alt="image" src="https://github.com/user-attachments/assets/66c1d689-82db-45ac-bc12-61de35d10af3" />

**Harris Matrix Exercises**
Exercise 1: 
This was really confusing for me at first, and again I think it might be because I don't have any archaeology background, but it was somewhat similar to soil properties in geography. Figuring out what cut actually meant was a huge help, and after the first exercise I picked it up pretty quickly. 
- I took a couple of attempts on this practice because I just kept confusing contexts and entering wrong layers
- After a couple of attempts, understanding it became easier
- I did make two versions of the matrix that I will include. One matrix I made had a context that was a cut connect and cut through more bottom layers, but I found it looked messy and was not sure if it was necessary to show it cutting through all those layers. I am still a bit confused on this part, but I understand it better after the later exercises, I think
- A lot of relationships between contexts looked cluttered, but I thought they were important
<img width="501" height="822" alt="image" src="https://github.com/user-attachments/assets/99ab2b2d-da7b-4382-9d26-6f455c4fa9c8" />
<img width="744" height="782" alt="image" src="https://github.com/user-attachments/assets/ffd68a2b-e38f-439b-b572-99e3e34b4bb4" />

Exercise 2:
- I think I started understanding how these matrices work here
- Cuts were still kind of confusing me, and how the layering works. i think its hard and confusing on how we are supposed to represent how deep a cut goes, since the matrix just shows the order of things.
- I was also very confused about context 19

Exercise 3: 
This exercise was actually pretty fun and reminded me a lot about doing soil work
- I marked out 25 contexts on the drawing
- I somewhat got confused with the thin layers, as well as the thin layers that to me, kind of looked like a riverbed to the right of one of the big cuts.
- After numbering the drawing i used the same numbers to create contexts for the Harris matrix, and it went pretty well, and I think I worked out most of the confusion that I was having earlier.
<img width="778" height="737" alt="image" src="https://github.com/user-attachments/assets/dddfc18d-525b-4863-8058-7692c07c688d" />
<img width="764" height="852" alt="image" src="https://github.com/user-attachments/assets/0ae5daea-9448-4a16-8cc4-e130653c0247" />


**Challenges**
I think the biggest challenges I had this week were just learning and relearning new things. I found the Harris matrix confusing just because of the terminology and it being a bit overwhelming. I equally found R confusing because it's a lot of data and new things all in one place. It definitely helped to have whole classes centred around R in the past. Overall, I thought most of the challenges I had were very easily overcome and made this week's work interesting to learn about. 
