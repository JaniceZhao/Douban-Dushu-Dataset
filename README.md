# Dateset Description

DouBan DuShu is a Chinese website where users can share their reviews about various kinds of books.  Most of the users in this website are unprofessional book reviewers. Therefore, the comments are usually spoken Chinese or even Internet slang.

In addition to the comments, users can mark the books from one star to 5 stars according to the quality of the books. We have collected more than 37 million short comments from about 18 thousand books with 1 million users. The great number of users provide diversity of the language styles, from moderate formal to informal. An example of the data item is shown in the following table.


| Key       	| Description                                      	| Value Example    	|
|-----------	|--------------------------------------------------	|------------------	|
| Book Name 	| The name of the book                             	| 理想国           	|
| User Name 	| Who gives the comment                            	| 399              	|
| Tag       	| The tag the book belongs to                      	| 思想             	|
| Comment   	| Content of the comment                           	| 我是国师的脑残粉 	|
| Star      	| Stars given to the book (from 1 star to 5 stars) 	| 5 stars          	|
| Date      	| When the comment posted                          	| 2018-08-21       	|
| Like      	| Count of "like" on the comment                 	| 0                	|


# Data Preprocessing
1. convert full width symbols to half width symbols
2. remove some special symbols 
3. convert traditional Chinese to simplified Chinese



# Terms of Use:

1. Respect the privacy of personal information of the original source
2. The original copyright of all the data belongs to writers of the reviews and DouBan
3. The dataset is **only** for study and research purposes. Without permission, it may not be used for any commercial purposes
4. Redistribution is **NOT** allowed
4. Some items must be deleted if the copyright owners claim
5. If you want to use the dataset for depth study, please cite this paper: TBD

# Date Download

If you want to acquire the corpus. Please fill the [application form](https://github.com/JaniceZhao/Douban-Dushu-Dataset/blob/master/application%20form.pdf) and send to Jianyu Zhao: zhaojianyuqd@163.com

Due to the large size of the corpus, we divide the whole dataset to 4 CSV files.