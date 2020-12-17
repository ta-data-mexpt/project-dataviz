![League_of_legends_logo](https://www.google.com/search?q=league+of+legends+png&sxsrf=ALeKk007yOwYU2xzvOvdEGVbBlTLBLq6Zw:1608231044228&source=lnms&tbm=isch&sa=X&ved=2ahUKEwiW-e3A19XtAhWUGM0KHVM3AFEQ_AUoAXoECBAQAw&biw=1440&bih=764#imgrc=JxK_v-W135qjgM.png)

# Project: Visualizing Real World Data

## Overview: Have you ever wanted to own a team? 

The goal of this project is to show an investor interested in forming his e-sports team, how much it would cost to have 5 professional players of the game league of legends

The following variables are analyzed:
- Number of players per level in each region (8 regions and 3 levels are considered)
- The performance of players through two indicators summed up: League points and ratio of games won
- The average salary they could earn according to the region in which they are

---

## Files in the folder project_files:

- crear_csv_LoL.ipynb: First code created, it is the guide and the complement of the file Project_Lol_modulo_2.ipynb
- Project_Lol_modulo_2.ipynb: code to obtain the necessary data from the riot games API, this file creates 2 csv: summoners_8_regions.csv and champs_summoners.csv
- apiKey.txt: file where you should paste the api key that comes from the riot games API. This key is personal and has a time limit, the person who wants to run the file: Project_Lol_modulo_2.ipynb, must create his own api key and paste it here
- summoners_8_regions.csv: first csv created. It contains all the summoners from the 8 regions and the 3 tiers
- champs_summoners.csv: second csv created. It contains the champions used by the summoners
- esports - lol - proyecto 2.pdf: File to present to investors that has the summary of all the information and the final conclusions
- Stats_LoL.twbx: file in tableu public with the graphs that summaries all the info
- Sueldos_gamers.xlsx: excel file that has the average salary for each profesional summoner of each region and for each tier
- summoners_8_regions_tableu_edited.csv: csv file containing the modified file of summoners_8_regions

## Details to be considered:

regions:
na1 = Norteamérica (consideran EUA y Canada)
eun1 = europa nordica y este
kr1 = Corea del sur
br1 = Brasil
la1 = latinoamérica norte (incluido méxico)
la2 = latinoamérica sur
euw1 = europa oeste
jp1 = japon

tiers:
Grandmaster
master
Challenger

- **apiKey.txt** You need to creat your apiKey in the next link: https://developer.riotgames.com
- **Project_Lol_modulo_2.ipynb** when you run the code to obtain the champs_summoners.csv, it will take around 9 hours, so be patient

## Hope you enjoy the project! :) 
