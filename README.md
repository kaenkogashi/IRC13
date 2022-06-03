# IRC13
We introduce the Interpersonal Relation Classification Web-Based Still Images Dataset (IRC-WebImages) which contains 13 types of social relationships.
***This note is under construction.***

This ReadMe explains IRC-WebImages dataset's CSV headers (IRC.csv). 

URL: Image download URL.

p1x1,	p1y1,	p1x2 ,p1y2: IRC's person1 bounding box upper left and lower right's x,y coordinate. Please note that all coordinates are after the original images have been scaled to 640 pixels in height or width.

p2x1,	p2y1,	p2x2 ,p2y2: IRC's person2 bounding box upper left and lower right's x,y coordinate. Please note that all coordinates are after the original images have been scaled to 640 pixels in height or width.

IRC_Id_1,	IRC_Id_2,	IRC_Id_3: IRC's social relationship ID.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
IRC_Ids are numbers from 0 to 51.
0:none
1:Child-parent
2:Child-other family elder
3:Siblings
4:Spouse
5:Lovers
6:Courtship
7:Friends
8:Neighbors
9:Roommates
10:Workplace superior-subordinate
11:Colleague/partners
12:Opponents
13:Professional contact
