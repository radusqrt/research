
This directory contains pairs of files to be used as source and target tweets for a domain adaptation algorithm. For each language (en and es), files named as "training" have to be used as source datasets, while files containing "Test" represent target datasets. Datasets were produced by applying a language filter to the original disaster datasets from CrisisLexT26, without any further text processing. Namely, disaster tweets contained in each file are:

CrisisLexT26_EarthquakesTraining_ES = {2012_Guatemala_earthquake,2012_Italy_earthquakes,2013_Bohol_earthquake}

CrisisLexT26_EarthquakesTest_ES = {2012_Costa_Rica_earthquake}

CrisisLexT26_FloodsTraining_EN = {2012_Philipinnes_floods,2013_Alberta_floods, 2013_Manila_floods, 2013_Queensland_floods, 2013_Sardinia_floods}

CrisisLexT26_FloodsTest_EN = {2013_Colorado_floods}


**Data Format:** One tweet per line with the following tab-separated fields:
Tweet Text	Information Source

**Labels:**
 - *Information source:* Eyewitness, NotEyewitness    ( = {Government, NGOs, Business, Media, Outsiders} from the original CrisisLexT26 annotation schema).


 




