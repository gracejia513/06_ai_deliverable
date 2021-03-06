# GEOGRAPHY 595 B: Humanistic GIS 06_ai deliverable

- **Name:** Grace Jia
- **Email:** gracejia@uw.edu

### Part 1: Rerunning 010-062 using gay_seattle data
Every coding exercise were executed again to replicate the gay_seattle pratical exercies. Most of the codes can be replicated smoothly, however I identified some minor issues that might be due to personal PC's configuration. Here are some screenshots and notes for future reference.
<details>
  <summary><b>Troubleshoot</b></summary>

1. [package installation](https://github.com/gracejia513/06_ai_deliverable/blob/main/Troubleshoot01.png?raw=true) The extra package spacy can be downloaded using !python -m spacy download en_core_web_sm

2. [drive mount](https://github.com/gracejia513/06_ai_deliverable/blob/main/Troubleshoot02.png?raw=true) It is better to mount to personal Google drive than that of using UW's email

3. [missing font](https://github.com/gracejia513/06_ai_deliverable/blob/main/Troubleshoot03.png?raw=true) verdana.ttf was missing in the asset. 

</details>
<br/>

### Part 2: Rerunning 010-040 using native_seattle data
Exercise 010 to 040 were execuded with downloaded native-seattle data. Additionaly, social network analyysis was performed using the generated data.
The social network looks like this.
![](https://github.com/gracejia513/06_ai_deliverable/blob/main/native_seattle_gephi.png)


### Part 3: Comparison summary
The book, *Native Seattle*, illustrates a place-based story that connects the early and the contemporary native community in Seattle. Native people and places played a vital part in the founding of Seattle and in what the city is today, just as urban changes transformed what it meant to be native. Thrush looked into the ways in which different populations inhabited and enriched the place of Seattle. Judging from *Native Seattle* word cloud, the word indigenous closely resides and with town, duwamish, river, and other "place" related words. This positioning and connection mirrors the key message of the book, looking at how people and place evolve as an ecosystem. 
![](https://github.com/gracejia513/06_ai_deliverable/blob/main/img/native-seattle.png)
However, it was observed that the algorithm did not rule out the single letters in the word cloud. But this issue was later resolved in constructing the social network. It was observed that *Native Seattle*'s social network has a slightly lower modularity than that of the *Gay Seattle*. Modularity reflects how words are densely connected to other words within the same cluster but sparsely connected to words in different clusters. In this sense, the structure of *Gay Seattle* might be more clustered and clearly delineated.  

![](https://github.com/gracejia513/06_ai_deliverable/blob/main/img/gay-seattle-Grace.png)
Taking a different perspective, *Gay Seattle*'s word cloud reflected the author's main effort to discribe how the gay and lesbian communities have struggled, evolved, and created "a sense of belonging in Seattle." The word cloud has multiple entities, service groups and knitted toghther. The connection between people is also present in the clusters in its social network.
![](https://github.com/gracejia513/06_ai_deliverable/blob/main/gay_seattle_gephi.png)
It was also observed that, for *Gay Seattle* the social network nodes settled faster than that of *Native Seattle*. And checking the "stronger grravity" box in the layout->tuning parameters section makes the nodes move even longer in both case. 

Overall, I really enjoyed creating the word cloud as it delivers the key information using color and font size. It grabs the reader's attention to the most dominant topic with large and bold font, and naturally links to other topics by position and color. The cloud itself can be thought of as a road map that deciphers the book's intent. It leads the readers in and yet leaves many mysteries to be solved.


## Reference
- [Resource 1:](https://github.com/jakobzhao/geog595/tree/master/06_ai)
- [Resource 2:](https://www.goodreads.com/book/show/562626.Native_Seattle)
- [Resource 3:](https://www.goodreads.com/en/book/show/1252504.Gay_Seattle)
