# Covid-19 cases per region in Greece
This repostory contains files for the page : [Covid-19 cases per region Greece](https://kostasthanos.github.io/svg_map_cases/regions_index.html).

## [Covid-19 cases per region Greece](https://kostasthanos.github.io/svg_map_cases/regions_index.html)
This page is showing the destribution of covid-19 cases per region in Greece. In this page you can find all the necessary details.

The map on the left side of the page is divided by region while the color of each region becomes darker and darker as the number of cases in it increases.

Next to the map there are the greek regions classified in descending order by the number of cases. The data comes from page iMEdD and specifically from the GitHub repository [iMEdD-Lab](https://github.com/iMEdD-Lab/open-data).

On the right side of the page are the data about the days that the virus is active in the country, the total number of cases, the daily increase and the date of last update. Finally, there are some sources and the GitHub repository where the data about the progression of the pandemic in the country are presented in detail and with plots.

You can hover over the regions in the map with your mouse to see an info box about the cases in each region.

The correspondence between the names of regions in greek and egnlish is the following :

<center>
|    Greek (Ελληνικά)   |     English (Αγγλικά)   |   
|          ---          |           ---           | 
|      Άγιον Όρος       |     	Mount Athos       |
| Αν. Μακεδονία & Θράκη | East Macedonia & Thrace |
|        Αττική         | 	      Attica          | 
|     Βόρειο Αιγαίο     |  	    North Aegean      |
|     Δυτική Ελλάδα     |  	   Western Greece     |
|    Δυτική Μακεδονία   |  	  Western Macedonia   |
|        Ήπειρος        |  	      Epirus          |
|        Θεσσαλία       |  	     Thessaly         |
|      Ιόνια Νησιά      |  	   Ionian Islands     |
|  Κεντρική Μακεδονία   |  	 Central Macedonia    |
|         Κρήτη         |  	      Crete           |
|      Νότιο Αιγαίο     |  	   South Aegean       |
|      Πελοπόννησος     |      Peloponnese        |
|      Στερεά Ελλάδα    |     Central Greece      |
|     Υπό διερεύνηση    |  Under investigation    |
| Χωρίς μόνιμη κατικοία |  	 Of no fix abode      |
</center>

## Source of data : 
The data which have been used in the file [*cases_per_region_Greece.ipynb*](https://github.com/kostasthanos/Covid-19-Regions-Greece/blob/master/cases_per_region_Greece.ipynb) are located in [iMedD-Lab](https://raw.githubusercontent.com/iMEdD-Lab/open-data/master/COVID-19/regions_greece.csv) repository in **csv** format and are converted into **json** file inside the notebook.

You can check also the full repository of iMedD-Lab about the data collection from here : [iMedD-Lab/open-data](https://github.com/iMEdD-Lab/open-data)

## Author
* **Konstantinos Thanos**
