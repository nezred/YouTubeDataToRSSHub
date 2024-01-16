# YoutubeDataToRSSHub

This fork converts your subscriptions to RSSHub links.

---------------

# YouTubeDataToRSS
Converts youtube subscription data from "your data" into opml for import into rss feed program or website.\
There is two file format possiblities - JSON and CSV.\
There is scripts for both file formats.\
This script needs python3 or newer.\
\
How to use: \
python jsontoopml.py (input json file) (output opml file)\
or\
python csvtoopml.py (input csv file) (output opml file)\
\
If there is error "TypeError: 'encoding' is an invalid keyword argument for this function", then you will need to change python in command above to python3.\
\
\
How to get JSON or CSV file with only all youtube subscriptions:\
1: be at youtube homepage, logged in.\
2: click your account icon at top right.\
3: click "Your data in YouTube"\
4: click "More" below "Your YouTube Dashboard"\
5: click "Download YouTube Data"\
6: in "Select data to include", click "All YouTube data included"\
7: click "deselect all" then select "subscriptions", then click "OK"\
8: click "Next Step"\
9: Make sure "Export once" is selected, your preferred archive file format, then click "Create export"\
10: wait for it to show download link, or wait for email with download link.\
11: download and extract subscriptions.json or subscriptions.csv file.
