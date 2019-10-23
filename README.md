# Problem3 Soultion Java edition
## Name: Peng Xu Email pxu105@syr.edu
### compile Environment IDEA

### STEP
step 1: put the foods.txt(sorce text) and stopWordsList.txt in the right directory D:\Problem3\... 

step 2: run the code `D:\Problem3\src\main\com\wordCount.java`, the console will print the top 500 frequent words and the document `most500FreWords.txt` and `reviewVextor.txt` will be created at D:\Problem3\..., the reviewVextor records all the reviews' vector data in readable format for weka, over 1Gb, you may not need to open it.  

step 3: import weka.jar to the project, run the code `D:\Problem3\src\main\com\KmeansByWeka.java`, wait for around the 20 minutes, the console will print the final 10 clusters by K-means method by weka, the `clusterResult.txt` will be created then.  

step 4: copy the data in `clusterResult.txt` to an excel, the you can get top 5 words of each cluster by selecting

### REMIND
  The result text has already been created under directory D:\Problem3\result  
      Top500 frequent words in :  `Problem3\result\most500FreWords.txt`  
      10 clusters by weka k-means: `Problem3\result\clusterResult.txt`  
      Top5 5 words of each clusters: `Problem3\result\top5words.txt`  
