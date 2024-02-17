# Tautulli_Combined
Combine multiple Tautulli Server statistics into one dashboard for monitoring multiple Plex servers
The below dashboards are available:
1) Total Views by Media Type By Server By Day
2) Total Views by Media Type By Server by Month
3) Most Watched Movies (top 20 - customizable) over the last 60 days (customizable)
4) Most Watched TV Shows (top 20 - customizable) over the last 60 days (customizable)
5) Most active users by play count over the last 60 days ordered by number of plays
6) Server pie chart breakdown by total play count
7) Media type plays pie chart
8) Table with most recent plays
9) Current activity for all servers
![example](https://github.com/jsgiacomi/Tautulli_Combined/blob/main/example.png)

Disclaimer:
I am a self-taught programming enthusiast, and while my code may not be perfect, it does get the job done, which is the primary goal. If you're interested in assisting with code optimization or making it more user-friendly (perhaps executable), your help is appreciated.

How to use:
This takes a little technical know how to use, but if you are already running Plex and Tautulli you should be fine. I will try to make it simple. This is a Jupyter Labs Notebook that outputs dashboards which combine metrics across two tautulli instances. 

1) You need to install Python 3.x. https://www.python.org/downloads/
2) You need to then install all the packages listed in the requirement.txt.
3) Then open the notebook CombinedServerStats.ipynl in Jupyter Labs.
4) Run the first cell and input the requested information.
5) IP address should be entered in xxx.xxx.xxx.xxx:YYYY where YYYY is the port number
6) Tautulli API Key: Settings -> Web Interface -> Enable API Key should be checked and the Key is below that option.
7) Then run the rest of the cells.
8) The dashboard will be output inline but also at: http://127.0.0.1:8050/
