# Iptv-free-direct

edited : extra addon as optional but if you want dailymotion and youtube link to work you will need them

addon video.iptv.free  will load your m3u list or xml and your have a search tool built in it but for now it handle only 1 list per selection  .. online or local  m3u / xml  .. please note for pastebin link .. your need the raw paste link to work

also you can put dailymotion link and youtube as well 

exemple of link you might wanna use in your list:

##Dailymotion##

/plugins supported / live or video link /

#EXTINF:-1 tvg-id="New EPG" tvg-logo="https://i.ibb.co/Njj2M62/dailymotion.png" tvg-name="DailyMotion"  group-title="New Group",DM TEST link plugins
plugin://plugin.video.dailymotion_com/?url=xxtuy6&mode=playLiveVideo

/direct link is working / live or video link /

#EXTINF:-1 tvg-id="New EPG" tvg-logo="https://i.ibb.co/Njj2M62/dailymotion.png" tvg-name="DailyMotion"  group-title="New Group",DM TEST link 
https://www.dailymotion.com/video/xxtuy6


##Youtube##

/plugins supported / live or video link /

#EXTINF:-1 tvg-id="New EPG" tvg-logo="https://i.ibb.co/SXyQzHG/26c89d70.png" tvg-name="Youtube" group-title="New Group",YT TEST link plugins
plugin://plugin.video.youtube/play/?video_id=wwNZKfBLAsc

/direct link is working / live or video link /

#EXTINF:-1 tvg-id="New EPG" tvg-logo="https://i.ibb.co/SXyQzHG/26c89d70.png" tvg-name="Youtube" group-title="New Group",YT TEST channel direct
https://www.youtube.com/watch?v=wwNZKfBLAsc

/you will get all video in list from the channel/

#EXTINF:-1 tvg-id="New EPG" tvg-logo="https://i.ibb.co/SXyQzHG/26c89d70.png" tvg-name="Youtube" group-title="New Group",YT TEST user
https://www.youtube.com/user/franceinfo


rtmp ts m3u8 aac mp3 mp4 and so on will work .. tv and radio link as well

https://github.com/Sphinxroot/plugin.video.iptv.free/raw/master/plugin.video.iptv.free.1.0.0.zip


some tool that i use https://github.com/Sphinxroot/iptv-tool 


in the future .. dailymotion video listing of a channel user  and multilisting 
