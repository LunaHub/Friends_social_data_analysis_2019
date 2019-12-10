# Network Analysis: 
## The-one-with-the-main-characters V.1.3
[Go Back](https://lunahub.github.io/Friends_social_data_analysis_2019/)

The 6 main characters in the show Rachel, Joey, Chandler, Ross, Monica and Phoebe have a very dynamic relationship. The diffrent relationships are varying from roommates, friends, partners or even enemies sometimes.

<p align="center">
 <img src="https://media.giphy.com/media/IazUww3PfsXepuuTUu/source.gif" width="400"/>
</p>

By using network analysis we can investergate how the relationship between the characters devolop for each season. 
The network is based on the characters appearance in each scene. So if two main characters appears in the same scene, an edge between them is created. The result of this is a weighted undirected-network for each season, as shown below

<p align="center">
<img src="figures/main_char_network/Network_Main_Char_Season_1.png" width="300"/> <img src="figures/main_char_network/Network_Main_Char_Season_2.png" width="300"/>
</p>
<p align="center">
<img src="figures/main_char_network/Network_Main_Char_Season_3.png" width="250"/> <img src="figures/main_char_network/Network_Main_Char_Season_4.png" width="250"/>
</p>
<p align="center">
<img src="figures/main_char_network/Network_Main_Char_Season_5.png" width="250"/> <img src="figures/main_char_network/Network_Main_Char_Season_6.png" width="250"/>
</p>
<p align="center">
<img src="figures/main_char_network/Network_Main_Char_Season_7.png" width="250"/> <img src="figures/main_char_network/Network_Main_Char_Season_8.png" width="250"/>
</p>
<p align="center">
<img src="figures/main_char_network/Network_Main_Char_Season_9.png" width="250"/> <img src="figures/main_char_network/Network_Main_Char_Season_10.png" width="250"/>
</p>

The following plot shows the weight of each relationship of the 6 main characters. Because the number of scenes is varying the weight is calculated relative to the number of scenes in each season. 

<p align="center">
<img src="figures/main_char_network/All_main_char.png" width="600"/> <img 
</p>
 
The highest relative weight is Joey and Chandler in season 5 at 0.54! This means that Joey and Chandler appears together in 54 % of all the scenes in season 5!

<p align="center">
 <img src="https://media.giphy.com/media/eMIGPdZ77kPgD7nf4j/giphy.gif" width="400"/>
</p>

If you have seen the show you know that the two characters Ross and Rachel have a very complicated relationship through the show. By plotting the weight of the edge we can show how their relationship evolves.

<p align="center">
<img src="figures/main_char_network/ross_rachel.png" width="600"/> <img 
</p>

We can compare this to the number of scenes where Ross and Rachel are the only one present.

<p align="center">
<img src="figures/main_char_network/ross_rach_alone.png" width="600"/> <img 
</p>

The last three seasons their weight is very fluctuating. This makes sense because in season 8 Ross and Rachel gets a baby, in season 9 they are broken up, but in season 10 they end up toghether.

