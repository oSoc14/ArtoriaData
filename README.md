ArtoriaData
===========

Data used by the Artoria Belfort app found at https://github.com/oSoc14/Artoria.

Usage by app
===========
The application fetches the information in poi.json the first time it's started and after that every time the application is used and data in the application is older than 12 hours.

Editing data
===========
When you spot typos or would like to update some description click poi.json above, click edit in the top right corner and you can edit the data directly in the webbrowser. After you've finished don't forget to press save!

Adding data
===========
Adding a building to the list is easy. Click poi.json in the list above, click edit in the top right corner  and paste this template under the last entry, before the last ], and fill in the data between <>s [Remove the hooks too!].

    ,
     {
    "id":<NEXT NUMBER>,
    "NL_name":"<DUTCH NAME>",
    "ENG_name":<<ENGLISH NAME>",
    "FR_name":"<FRENCH NAME>",
    "lat":<Latitude>,
    "lon":<Longtitude>,
    "height":<HEIGHT>,
    "NL_description":"<DUTCH DESCRIPTION HERE>",
    "ENG_description":"<ENGLISH DESCRIPTION HERE>",
    "FR_description":"<FRENCH DESCRIPTION HERE> ", 
    "image_link":"<Top image here with http://, Bigger images are better! they should be atleast 400p >"
    }

Validating data
============
After you've added data you should validate the .json file, this can be done by pasting the link https://raw.githubusercontent.com/oSoc14/ArtoriaData/master/poi.json in http://jsonlint.com/
The result should be "Valid JSON"

Additional help
============
If you encounted any more trouble you can always contact me at Laurens.DeGraeve \<at> outlook \<dot> com.
