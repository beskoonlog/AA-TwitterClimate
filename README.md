# AA-TwitterClimate
Logan Beskoon

This repository contains two jupyter notebooks.The purpose was to pull Twitter descriptions of followers of prominent figures within the Climate community, but extremely polar ideology. From there, I wanted to do a group comparison of a sub-topic for both of the group of followers. This subgrouping is established by using a lexicon expansion of relatively high frequency words of a sub-group within a body of followers. A final group comparison happens between the related (hopefully) subgroups.

Background on the two Twitter accounts whose followers I pulled:
I pulled the Twitter followers of two well-known individuals in regard to climate action views. The account CFiguerers is I Christiana Figueres. She is an internationally recognized leader on climate change and typically calls for strong action. The second account, EcoSenseNow, belongs to Patrick Moore. He considers himself a sensible environmentalist. He is strongly against taking drastic action in the name of climate change. And he is also the director of C02Coalition (https://co2coalition.org/) which advocates “ to engage in an informed and dispassionate discussion of climate change, humans’ role in the climate system, the limitations of climate models, and the consequences of mandated reductions in CO2 emissions”. Looking at the users’ descriptions that follow each figure, I would hypothesis that we could create an interesting comparing in word usage.

CFigueres has 160055 followers and EcoSenseNow has 10330 followers. This data does include emojis (encoded). For CFigueres, she is from Costa Rica. So I would suspect a decent amount of followers are Spanish speaking, and would require using Spanish stop words and taking into account that you may miss some words in cleaning data. There are some weird issues in the EcoSenseNow_followers.txt file as some rows seem to have too many columns.
For ‘CFigueres_followers.txt’ there are:
-	1,356,792 tokens
-	Average token length is 6.6 
-	Lexical diversity 0.19
For ‘EcoSenseNow_followers.txt’ there are:
-	679345 tokens
-	 Average Token Length 6.33
-	 Lexical Diversity 0.221

Files in the repo:
'Beskoon Twitter Climate Figures Lexicon Expansion.ipynb' contains code and a write which compares the two groups of twitter followers. Specific for my write up, I chose to compare sub groups of education as a final groups comparison. These sub groups were created by expanding a lexicon based on the first word containing something related to education. From there, I chose words accordingly trying to focus on education the best I could. With a lexicon established for for groups of Twitter followers, I created a subgroup for each group. And then I did comparison of both education-based subgroups. The final group compario

'Beskoon Twitter Data pull based on Climate view figures.ipynb' contains code for which pulled Twitter followers' description and other account info and stores that info in two txt.files respective for each Climate Figure's followers. 