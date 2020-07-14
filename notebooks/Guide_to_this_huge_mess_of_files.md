<h2>
I need to make this guide because for the life of me, I can not remember which file does what.<br>
Commenting and Documentation are really important, lads. Keep that in mind.

<hr>
<h3> BASE1 Anime_Image_Scraper_Trial1.ipynb <h3>
  Takes a file with row separated URLS as input.<br>
  Tries to download images based on the URLS given in the file.<br>
  Shows a ton of errors now.<br>
<hr>
  
<h3> BASE2 Anime_Image_Scraper_Trial2.ipynb <h3>
  Has a pop-up to enable/disable Ad-Block when scraping (prolly caused issues).<br>
  Uses Selenium, Chromedriver and some JavaScript magic to download URLS to a text file.<br>
  Seems to work.<br>
<hr>
  
<h3> BASE3 Anime_Image_Scraper.ipynb <h3>
  This script uses the old script with a few modifications (to get URLs).<br>
  The primary purpose of this script is to make a dataset (albeit inefficiently - no threading - slow - boring). It takes a list     as input. This is a list of Anime names. 100 top Anime from IMDB it seems like. (All that effort to clean MAL data for   nothing?). Anyway the script downloads 100 images for each of these anime.<br>
  Seems to work.  <br>
  100x100 images = 6-7 hours to download<br>
<hr>  
  
<h3> BASE4 Anime_Image_Scraper.ipynb <h3>
  Glaringly small file. Suspicious.<br>
  I seem to have downloaded some Images based off of MAL (around 40 images). Seems like a script to test if stuff works.<br>
  Seems to work.<br>
  39 images = 63.99 seconds to download<br>
<hr>
  
<h3> BASE5 Anime_Data Collection.ipynb <h3>
  This script is same as the one before this but with a heavier load.<br>
  Seems like we found a file with a lot of Image links from MAL / Kaggle.<br>
  Seems to work.<br>
  14377 images = 12107.61 seconds to download<br>
  
  
<h3> BASE6 Non_Anime_Data_Collection.ipynb <h3>
  This script does some fun stuff to get an anime related dataset from Kaggle and unzips it to a folder. I somehow feel like this   took a lot of time. Excruciating.<br>
  It also gets cifar-10 data from kaggle.<br>
  
<hr>
  
<h3> BASE7 getting CIFAR-10.ipynb <h3>
  Gets cifar-10 data from FAST AI. I think this was our hack to acquire the cifar-10 data faster.<br>
<hr>

<h3> BASE8 moving stuff around.ipynb <h3>
  Eh, there's but a single rm and mv command in this script. Sad.<br>
<hr>
  
<h3> BASE9 Anime_Image_Scraper.ipynb <h3>

<h3> BASE10 Anime_Image_Scraper.ipynb <h3>

<h3> BASE11 Anime_Image_Scraper DNU.ipynb <h3>

<h3> BASE12 Anime_Image_Scraper.ipynb <h3>

<h3> BASE13 Anime_Character_Name_scraper.ipynb <h3>

<h3> BASE14 Anime_Image_Scraper only Pool no thread.ipynb <h3>

<h3> BASE15 Anime_Image_Scraper with mlcrate.ipynb <h3>

<h3> BASE16 Anime_Image_Scraper only Pool no thread-datav3.ipynb <h3>

<h3> BASE17 Anime_Image_Scraper only Pool no thread with max retry fix.ipynb <h3>

<h3> BASE18 Anime_Image_Scraper.ipynb <h3>

<h3> BASE19 Anime_Image_Scraper Works.ipynb <h3>

<h3> MODEL1 Anime or Not Anime (data).ipynb <h3>
<h3> MODEL2 Anime or Not Anime (data_v2)-Copy1.ipynb <h3>
<h3> MODEL3 Which Anime (data_v3_old).ipynb <h3>
<h3> MODEL3 Which Anime (data_v4).ipynb <h3>
<h3> MODEL4 Which Anime (data_v3) with Proper Docs.ipynb <h3>
<h3> MODEL4 Which Anime (data_v4) Grayscale Trial.ipynb <h3>
<h3> MODEL4 Which Anime (data_v4) some Model Trials.ipynb <h3>
<h3> MODEL4 Which Anime (data_v4) Transform Trials.ipynb <h3>
<h3> MODEL4 Which Anime (data_v4) with Proper Docs.ipynb <h3>
<h3> MODEL5 Which Anime (data_v3_new).ipynb <h3>
<h3> MODEL4 Anime_Image_Scraper Works.ipynb <h3>

