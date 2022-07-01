- - - - - - - - - - - - - - - - - - - - - - - - -
**Timeliner: Simple Timeline Creator with Python MatPlotLib**
- - - - - - - - - - - - - - - - - - - - - - - - -
Create a google sheet online or use with .csv offline with the following schema:

| Event | Date | Priority |
| --- | --- | --- |
| Event 1 | 6.5.22 | 3 |
| Event 2 | 6.14.22 | 1 |

Plot Timelines with MatPlotLib

**To load your live google sheet online (set so anyone with the link can view):**<br/>
Change import_online to True, and replace _your_url_here_ with that part of your url<br/><br/>
**To load your offline .csv:**<br/>
Download your table as .csv (only downloading selected collumns and rows)<br/>
And name the document 'Timeline.csv' and place in the same folder<br/><br/>
**How to Use:**
- Run the script to plot your timelines
- Priority <= 0 is not displayed 
- See the example .csv file (Timeline.csv) attached in this repository
