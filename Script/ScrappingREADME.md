To scrap the data, you will have to install beautiful soup, and selenium. Also, to use selenium, you will have to download a webdriver, I suggest you the chrome one,
available at this link: https://chromedriver.chromium.org/downloads (the windows version for 32 bits Windows works also for 64 bits). Once this webdriver
downloaded, you will have to unzip it and place it in the same folder than the script. (you can also when you call the driver define the location of the application, but 
this way was the easiest way for me to do it with jupyter notebook on my local).

Once you downloaded every package, you can start running the code from **RUN HERE** till **SCRAP ALL DATAS**. (don't run for seasons 2010, 2011 part) 

I think we can split the scrapping like this: 
  I will scrap 2010, 2011, 2012 and 2013 seasons, Anuj will scrap 2014, 2015, and 2016 seasons and Anupam will scrap 2017, 2018 and 2020 ones.
  

BEFORE RUNNING BE SURE YOU SCRAP THE GOOD SEASONS. 

2014, 2015 and 2016 seasons means that you will RUN THE CELL FOR S_watch[2:5] !!!!! not S_watch only

2017, 2018 and 2020 means that you will RUN FOR S_watch[5:] !!!! 

OK SORRY! I forgot to tell this but you have to get the current player list in a pd.DataFrame named df_player before started SCRAPPING. 
To do this, you can run the code in *retrieve current Nba players* or you can download the csv in dataset folder and read the csv as df_player pandas DataFrame.

After that you can run cells  just under **FOR OTHER SEASONS**. Change the name of your file accordingly to the season you scrapped and upload it here. 

Note: If you want you can reduce the sleep in the code.
      
  I think that the scrapping will failed at least one time, to don't have to scrap the datas from the beginning, you can get the date of the last element
      in the scores dataframe you create in the cell below, find this url in the s10 or s11 or, ... etc (I do it with several try), begin again 
      your scraping for this season from this indexing. 
      
  BE CAREFUL WITH IDS! 
      
  If any question ask me for sure!
