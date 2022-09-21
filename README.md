# ggplot2-CollinHOwens
ggplot2-CollinHOwens created by GitHub Classroom

This project is focusing on looking at a specific part of the economy of a video game called lost ark. This will be looking at character leveling materials and analyzing the change of price for 10 items which help you level. This video covers the very basics of leveling your character for those curious about the background of the project. https://youtu.be/lnjMAUlp0-4

The video was made for beginners, this project is aimed towards graphing the market for players who are in the highest level of content. The highest tier of content introduces new items. This image contains the new items we will be looking at and how they are used, while the project will be checking their prices over time.

https://i.imgur.com/nyBvpnN.png

Through game updates and announcements, prices have changed a lot. This project's goal is to visualize how these events have influenced the market for these items.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

The data is originally from this website

https://documenter.getpostman.com/view/20821530/UyxbppKr#ea4a2d4c-07b2-470a-abd7-6386f0191f51

To obtain it I had to scroll to the top right and create an account for Postman, import data, then go to the export market item historical data section, then in query parms I checked the format for CSV, 
and for Path Variables, for Region I copy and pasted "North America West" (dont add the quotations) and for 

itemID I copy and pasted "basic-oreha-fusion-material-2,crystallized-destruction-stone-0,crystallized-guardian-stone-0,great-honor-leapstone-2,honor-shard-pouch-l-3,honor-shard-pouch-m-2,honor-shard-pouch-s-1,solar-blessing-2,solar-grace-1,solar-protection-3" (also do not add the quotations.)

---------------------------------------------------------------------------------------------------------------------------------------------------------------

index.qmd has the final code, the GGPlot 2 graphs folder has the 5 final graphs
