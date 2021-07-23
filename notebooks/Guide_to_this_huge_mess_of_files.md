<h2>
I need to make this guide because for the life of me, I can not remember which file does what.<br>
Commenting and Documentation are really important, lads. Keep that in mind.
</h2>

<hr>
<h3> BASE1 Anime_Image_Scraper_Trial1.ipynb </h3>
  Takes a file with row separated URLS as input.<br>
  Tries to download images based on the URLS given in the file.<br>
  Shows a ton of errors now.<br>
<hr>
  
<h3> BASE2 Anime_Image_Scraper_Trial2.ipynb </h3>
  Has a pop-up to enable/disable Ad-Block when scraping (prolly caused issues).<br>
  Uses Selenium, Chromedriver and some JavaScript magic to download URLS to a text file.<br>
  Seems to work.<br>
<hr>
  
<h3> BASE3 Anime_Image_Scraper.ipynb </h3>
  This script uses the old script with a few modifications (to get URLs).<br>
  The primary purpose of this script is to make a dataset (albeit inefficiently - no threading - slow - boring). It takes a list     as input. This is a list of Anime names. 100 top Anime from IMDB it seems like. (All that effort to clean MAL data for   nothing?). Anyway the script downloads 100 images for each of these anime.<br>
  Seems to work.  <br>
  100x100 images = 6-7 hours to download<br>
  THIS IS USABLE<br>
<hr>  
  
<h3> BASE4 Anime_Image_Scraper.ipynb </h3>
  Glaringly small file. Suspicious.<br>
  I seem to have downloaded some Images based off of MAL (around 40 images). Seems like a script to test if stuff works.<br>
  Seems to work.<br>
  39 images = 63.99 seconds to download<br>
<hr>
  
<h3> BASE5 Anime_Data Collection.ipynb </h3>
  This script is same as the one before this but with a heavier load.<br>
  Seems like we found a file with a lot of Image links from MAL / Kaggle.<br>
  Seems to work.<br>
  14377 images = 12107.61 seconds to download<br>
  
  
<h3> BASE6 Non_Anime_Data_Collection.ipynb </h3>
  This script does some fun stuff to get an anime related dataset from Kaggle and unzips it to a folder. I somehow feel like this   took a lot of time. Excruciating.<br>
  It also gets cifar-10 data from kaggle.<br>
  
<hr>
  
<h3> BASE7 getting CIFAR-10.ipynb </h3>
  Gets cifar-10 data from FAST AI. I think this was our hack to acquire the cifar-10 data faster.<br>
<hr>

<h3> BASE8 moving stuff around.ipynb </h3>
  Eh, there's but a single rm and mv command in this script. Sad.<br>
<hr>
  
<h3> BASE9 Anime_Image_Scraper.ipynb </h3>
  This is script which explores multi-threaded image downloads.
<hr>

<h3> BASE10 Anime_Image_Scraper.ipynb </h3>
  We further refine the threaded scrapring in this script.
  100 imgges = 73.51s without threading
  100 images = 47.45s with threading
<hr>

<h3> BASE11 Anime_Image_Scraper DNU.ipynb </h3>
  Ignore. DO NOT USE. Runs into a race condition.
<hr>

<h3> BASE12 Anime_Image_Scraper.ipynb </h3>
  We try to download the 100x100 images, I think this is where the wrong images went into the wrong folders. Hopefully not. But I'm not sure. We'll see. <br>
  I'm not sure if it worked, there are a lot of warnings.
  Download statistics are hard to find.
<hr>

<h3> BASE13 Anime_Character_Name_scraper.ipynb </h3>
  IMPORTANT.
  Scraping top 10 characters for 192 different anime it seems like.
  We get the names based on the anime-id.
  Takes around 21 minutes to get these 1920 names.
<hr>

<h3> BASE14 Anime_Image_Scraper only Pool no thread.ipynb </h3>
  This is a multiprocessed trial script to download anime faces.
  No stats.
  
<hr>
<h3> BASE15 Anime_Image_Scraper with mlcrate.ipynb </h3>
   This is a trial script, attempting to use the mlcrate library.
   DO NOT USE.
   It does not work.

<hr>
<h3> BASE16 Anime_Image_Scraper only Pool no thread-datav3.ipynb </h3>
  This is a script to download the faces using pooling. 
  Seems like it works.
<hr>

<h3> BASE17 Anime_Image_Scraper only Pool no thread with max retry fix.ipynb </h3>
  I think we deal with some issues in the character names in this script which could affect scraping.
  Otherwise it's the same as the old script.
  We run into a max retry error because we send too many requests at once. Apologies, server-chan. I will treat you better.
<hr>

<h3> BASE18 Anime_Image_Scraper.ipynb </h3>
  This is an attempt to scale the threaded scraper.
  I think we tried putting a lock on the thread here.
  I dont really know if it worked.
<hr>

<h3> BASE19 Anime_Image_Scraper Works.ipynb </h3>
  I am not sure, but the trial for 5 anime seems to have worked here the comments mention that we took care of the exception.
  It seems to have worked.
<hr>

<h3> MODEL1 Anime or Not Anime (data).ipynb </h3>
<h3> MODEL2 Anime or Not Anime (data_v2)-Copy1.ipynb </h3>
<h3> MODEL3 Which Anime (data_v3_old).ipynb </h3>
<h3> MODEL3 Which Anime (data_v4).ipynb </h3>
<h3> MODEL4 Which Anime (data_v3) with Proper Docs.ipynb </h3>
<h3> MODEL4 Which Anime (data_v4) Grayscale Trial.ipynb </h3>
<h3> MODEL4 Which Anime (data_v4) some Model Trials.ipynb </h3>
<h3> MODEL4 Which Anime (data_v4) Transform Trials.ipynb </h3>
<h3> MODEL4 Which Anime (data_v4) with Proper Docs.ipynb </h3>
<h3> MODEL5 Which Anime (data_v3_new).ipynb </h3>
<h3> MODEL4 Anime_Image_Scraper Works.ipynb </h3>

