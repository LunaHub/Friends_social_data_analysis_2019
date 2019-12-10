# The-one-with-all-the-characters
[Go Back](https://lunahub.github.io/Friends_social_data_analysis_2019/)

Your are probably already fimiliar with the 6 main characters of friends (otherwise go [here](https://lunahub.github.io/Friends_social_data_analysis_2019/network_analysis_main_char)). However there are a number of secondary characters that appear quit alot in the show. But how often do they appear? And who are the "main" secondary characters of the show?
This section will explore the features of the network of the complete cast of all seasons along wiht the networks of each season to investigate the evolution over seasons. 

<p align="center"> 
<img src="figures/brand_new_info.gif" width="400">
</p>

The following show the complete network of all charaters in entire show of F.R.I.E.N.D.S. 
Hover on the images below to show network of each season.

<p align="center"> 
	<img src="figures/All_seasons_network_no_labels.png" 
	onmouseover="this.src='figures/All_seasons_network.png';" 
	onmouseout="this.src='figures/All_seasons_network_no_labels.png';"
	width="560" id="main_pic">
</p>

<p align="center"> 
  <img src='figures/S1network.png' 
       onmouseover="main_pic.src='figures/S1network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S2network.png' 
       onmouseover="main_pic.src='figures/S2network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S3network.png' 
       onmouseover="main_pic.src='figures/S3network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S4network.png' 
       onmouseover="main_pic.src='figures/S4network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S5network.png' 
       onmouseover="main_pic.src='figures/S5network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S6network.png' 
       onmouseover="main_pic.src='figures/S6network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S7network.png' 
       onmouseover="main_pic.src='figures/S7network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S8network.png' 
       onmouseover="main_pic.src='figures/S8network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S9network.png' 
       onmouseover="main_pic.src='figures/S9network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
  <img src='figures/S10network.png' 
       onmouseover="main_pic.src='figures/S10network.png';" 
       onmouseout="main_pic.src='figures/All_seasons_network_no_labels.png';" 
       width="112" />
</p>

How are nodes and link made...

As you might notice the network does not give alot of information, so lets dig in the features of the network.

## Network statistics
The complete network of all casted characters of the show includes 285 nodes(charatcers) and 2683 links. The number of characters and links between these over each season is seen in the figures below. The degree distribution is also seen..
<p align="center"> 
	<img src="figures/total_number_of_nodes.png" 
	width="400">
</p>

<p align="center"> 
	<img src="figures/total_number_of_edges.png" 
	width="400">
</p>

<p align="center"> 
	<img src="figures/Degree_dist.png" 
	width="400">
</p>

## Secondary characters

<p align="center"> 
	<img src="figures/main_characters_degree_big_network.png" 
	width="560">
</p>

<p align="center"> 
	<img src="figures/bi_characters_degree_big_network.png" 
	width="560">
</p>

<p align="center"> 
	<img src="figures/Number_of_char_appearing_in_each_season.png" 
	width="560">
</p>

### Networks of secondary characters
This is the network of the most frequenct appearing characters

<p align="center"> 
	{% include All_seasons_frequent_char_network_interactive.html %} 
</p>
{% include Interactive_network.html %} 

## Communitites
<p align="center"> 
	<img src="figures/All_seasons_network_communities.png" 
	width="560">
</p>
Some text...
<p align="center"> 
	<img src="figures/Number_of_char_in_communities.png" 
	width="400">
</p>

## Friendship paradox
<p align="center"> 
	<img src="figures/Friendship_paradox.png" 
	width="600">
</p>


[Go Back](https://lunahub.github.io/Friends_social_data_analysis_2019/)
