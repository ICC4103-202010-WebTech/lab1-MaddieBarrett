3) It begins with the tag "html op="news"", this tag is used to wrap all the code (HTML root element).
Then comes the head, which cointains diffrent tags inside:

 a) meta : this tag provides metadata about the document which is not diplayed, but can be read by the machine. For example here they edited the viewport, which controls the page dimension and scaling.
 
 b) link : this tag specifies de relationship between the actual document and an external source. Here href specifies the URL and rel specifies the relationship of the document with the actual document. Type is used to define de type of content. 
 
 c) title : element to define the title of the document

Then comes the body, where all the data of the web page is enclosed. Here is where all the content is.
Inside the body is the tag "center", used to set the align of test into the center.
Inside the tag "center", comes the tag "table" which defines an HTML table, and inside this tag there are different atributes (the id, the border to specify there are no borders around the table cells, the "cellpadding", "cellspacing", the width of the table, and the color of the background with "bgcolor").
Inside the "table" tag comes the tag "tbody", which is used to group the body content in an HTML table.
Inside the "tbody" there are 3 big "tr" tags, which define a table row.

The first big "tr" tag is for the general website. Then inside of this tag there are "td" tags, each defining a different cell, one for the logo, the other for diffrent options to help the user, and one for the login.
For example the "td" tag for the options cointains "a href" for each options, which indicates the link's destination. 

The second big "tr" tag is for the news. Here there is another "table" tag to organize the news, and in here another "tbody".
Inside this "tbody" tag there is a "tr" tag for each news, so each row is a diffrents news. Also in between each news there are other "tr" tags, these give information about the news above (such as points, comments, etc).
Each of the "tr" tags (for the news) has 3 "td" tags, so 3 cells for each row.
The first "td" tag, is for the number (the news are organized by numbers, so first news, second news, and so on).
The second "td" tag, is used to define an arrow that allows the user to vote.
The third "td" tag, is used for the title of the news. Here there is an "href" so that when the user clicks the title, the user is directed to the source of the news. There is also a "span" tag, where the source of the news is displayed and when clicked it displays (using href) all the news available from that source.
Then, as mentioned before, there are "tr" tags in between each news, these are a row that contain information about the news (points, hide option and comments). These are modelled in the same way the first "tr" tag for the general website is.

The last big "tr" tag is used for the end of the website, which cointains one big cell, so one big "td" tag.
Inside this "td" tag, another table is defined to mark a line diving this section with the news section. Here there is a "tbody" tag, which describes the color of the line for the separation.
Also, inside the "td" tag there are two "center" tags, which center-align text.
The first "center" tag has a "href" to apply to "Y combinator".
The second "center" tag contains "href" for different options of information the user might need, such as guidlines, FAQ, Support, etc.

The main tags are then all closed. Finishing with "/html" tag.

4) hn.js: This file's porpouse is to define the functions of the website. For example, if the user clicks then there is a function that defines what the output should be.
news.css: This file's poprpouse is to define how the web site looks, the asthetic. For example, it gives the font for the lettering, colors, the width ann length for difrent objects, etc.

5) 7 resurces where downloaded.

--> news.ycombinator.com: Type: document, Request Method: GET, Status Code: 200 OK
	
--> news.css?FipHmofufc0acGUN2LQH: Type: stylesheet, Request Method: GET, Status Code: 200 OK
	
--> Y18.gif: Type: gif, Request Method: GET, Status Code: 200 OK (from disk cache)
	
--> s.gif: Type: gif, Request Method: GET, Status Code: 200 OK (from disk cache)
	
--> hn.js?FipHmofufc0acGUN2LQH: Type: script, Request Method: GET, Status Code: 200 OK (from disk cache)
	
--> grayarrow.gif: Type: gif, Request Method: GET, Status Code: 200 OK (from disk cache)
	
--> favicon.ico: Type: x-icon, Request Method: GET, Status Code: 200 OK 



