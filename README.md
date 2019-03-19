
# Always Responsive-pages
**Web Page Display and Printing For Any Computer and Internet Device**

There are many devices and browsers on the Internet. Backwards compatibility must be considered. Creating webpages that display on any device and any browser without concern regarding bandwidth is problematic. Another consideration is with a new version of a browser, the webpage may crumble and the code needs to be rewritten. Flexbox cannot be trusted for all browsers.

When using this code

    Legacy browsers are not an issue.

    Difficult browsers are not an issue.

    Backwards compatibility is not an issue.

    Users can print any webpage straight from the net.

**Blockquote Version**

        Place the code/content for every webpage between an opening blockquote and a closing blockquote.

        Place blockquote after the body tag.

        body>

        blockquote>

        Insert webpage content

        Close the tags at the foot of the webpage 

        /blockquote 

        /body 

        /html

    Using this version web pages will print allowing margins for pages to be placed in three-ring binders double sided. Again, device and/or printer is not a consideration.

**Table Version**

        Alternate to the blockquote option.

        Enclose the webpage in one large table

        Always use percentages to size the table

        Always use the center option for the table.
        
        Centered and percentage table options keeps the text tidy, when users enlarge the text within. Designers may want to drop back to Html 4.01.


        Example:

        table width=”90%” align=”center”

        This will produce a 5% margin on each side of the table.

        Avoid the table description option. Browsers may display the description option in plain text on the webpage.

        Insert webpage content into the table using rows and cells.

        Be aware, browsers may display the lines between table cells and rows.

        Close the tags at the foot of the webpage

        /table>

        /body>

        /html>

Both options will work on all versions of HTML. With these coding options webpages will resize and adjust. No need to write different code for different devices and browsers. Both versions will allow - any user, any device, any bandwidth, to print pages straight from the browser.

**Accessibility**

Users with visibility and/or accessibility issues may need to enlarge the text to a preferred size while reading on the browser. The option of increasing or decreasing the size of the font relative to the default size, as in <font size="+1(num)"> or <font size="-1(num)"> , where "num" is a number. This allows the fonts to resize according to the page.

Users can choose any font size (unless constrained by CSS or text boxes), and the page will adjust.

The apache 2.0  was filed May 2000.
First added to github June 15, 2018, updated March 19, 2019 by Alexandra Andrews 
