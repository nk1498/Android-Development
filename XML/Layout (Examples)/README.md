__THIS IS THE TYPE OF LOGIN PAGE WHICH HAS BEEN CREATED USING XML CODE <br>__
https://3.bp.blogspot.com/-QbmDZqar-d0/UtpS_M_X7rI/AAAAAAAAA8o/-xsM2wbmr_U/s1600/AA+Login+Page.png

##  Changes to make


> * String values<br>
While entering string value in any attribute directly a yellow high lighted bulb appear which says<br>
__"Hardcoded string, should use @string more..."__<br>
To replace the hardcoded string in windows:
__Press Alt+Enter and choose Extract string resource and once the dialouge box opens give it a proper name__<br>
Another way to do so: <br>
__Go to res directory, then to values inside it and open strings.xml file there you will see resources parent tag which consists of string tags used in xml code.__<br>
__Now create the string tags and name them and give them the value which you want to display.__<br>
__To use the strings.xml file in your code, simply refer "@string/the_name_you_gave_to_the_string"__<br>
In the xml code see lines <br>
28<br>
42<br>
54<br>
65<br> 
Where hardcoded string has been used, change them with above mentioned steps.

> * Colors values<br>
Instead of giving hex codes for color now we will use the same process as we did for string value.<br>
__Go to res directory, then to values inside it and open colors.xml file there you will see resources parent tag which consists of color tags used in the xml code and the application.__<br>
__Simply add the color name and use the hex codes__<br>
__To use colors.xml file in your code, simply refer "@color/the_name_you_gave_to_the_color"__<br>



## Inserting Image in xml code<br>
__The image used in this section for facebook can be downloaded from this site given below __<br>
https://factwish.com/wp-content/images/2018/06/A55_Featured.png  <br>
__Once downloaded copy and paste the image in drawable section of android studio, from there we can refer the image when we need it in our code.<br>__
__To refer the image simply use "@drawaable/downloaded_image"__<br>
See line 12 of the xml code for more clarity. 
