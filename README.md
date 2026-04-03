# Custom_US_IPTV_No_Sportz
Custom IPTV playlist mapped with 3 built in guides
_Custom Tim (Manual edit from Github us_all.m3u combined with Select channels from KLOWD and LIVENOW all sports, BET, foreign, and kids programming removed)
M3U: C:\Users\timsc\Downloads\MEmu Download\IPTV\_Custom Tim.m3u
EPG: https://epg.pw/xmltv/epg_US.xml
EPG: https://raw.githubusercontent.com/mikekaprielian/rtnaodhor93n398/refs/heads/main/en/videoall.xml
EPG: https://raw.githubusercontent.com/matthuisman/i.mjh.nz/refs/heads/master/PlutoTV/us.xml


_Buddy Chew Chew TV PASS
M3U: https://raw.githubusercontent.com/BuddyChewChew/My-Streams/refs/heads/main/tv.m3u (has built in EPG which seems to fill well)
EPG: https://raw.githubusercontent.com/doms9/iptv/refs/heads/default/M3U8/TV.xml

M3U: https://raw.githubusercontent.com/BuddyChewChew/buddylive/refs/heads/main/buddylive_v1.m3u
M3U: https://github.com/BuddyChewChew/My-Streams/blob/main/tv.m3u
M3U: https://raw.githubusercontent.com/BuddyChewChew/My-Streams/refs/heads/main/Backup.m3u
includes EPG:#EXTM3U url-tvg="https://raw.githubusercontent.com/BuddyChewChew/My-Streams/refs/heads/main/epgs/Backup-epg.xml.gz" (but EPG in the M3u only works in IPTV, Not Emby Live TV, and this EPG doesn't seem to match anything. 

_Klowd (Github IPTV) (has OANN)
M3U: https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_klowdtv.m3u
No EPG, but use Mike Prarielian EPG below.

_LocalNow
M3U: https://www.apsattv.com/localnow.m3u (has ch 3, 13, 17 local stations)
EPG: https://raw.githubusercontent.com/BuddyChewChew/localnow-playlist-generator/refs/heads/main/epg.xml

_LG Channels US (updated 16/09/25)
https://www.apsattv.com/uslg.m3u

_Samsung (Buddy Chew Chew)
M3U: https://raw.githubusercontent.com/BuddyChewChew/app-m3u-generator/refs/heads/main/playlists/samsungtvplus_us.m3u
EPG: 

_Plex (US) (Buddy Chew Chew)
https://raw.githubusercontent.com/BuddyChewChew/app-m3u-generator/refs/heads/main/playlists/plex_us.m3u
EPG: 

_Pluto (US) (Buddy Chew Chew)
https://raw.githubusercontent.com/BuddyChewChew/app-m3u-generator/refs/heads/main/playlists/plutotv_us.m3u
EPG: https://raw.githubusercontent.com/matthuisman/i.mjh.nz/refs/heads/master/PlutoTV/us.xml 

_Tubi (All) (Buddy Chew Chew)
https://raw.githubusercontent.com/BuddyChewChew/app-m3u-generator/refs/heads/main/playlists/tubi_all.m3u
EPG: 

_Xumo (Buddy Chew Chew)
https://raw.githubusercontent.com/BuddyChewChew/xumo-playlist-generator/refs/heads/main/playlists/xumo_playlist.m3u
EPG: 

_TV PASS (Github IPTV)
https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_tvpass.m3u
EPG: 

_TV APP
M3U: https://tvpass.org/playlist/m3u
EPG: https://raw.githubusercontent.com/BuddyChewChew/My-Streams/refs/heads/main/TheTVApp.m3u8
  
_The TVapp.to without a high volume warning (Buddy Chew Chew Live)
M3U: https://raw.githubusercontent.com/BuddyChewChew/buddylive/refs/heads/main/en/videoall.m3u
EPG: https://tvpass.org/epg.xml (comprehensive but has only 1 day of guide data)



_Fire TV
https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_firetv.m3u

_Roku
M3U: https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_roku.m3u  
EPG: https://raw.githubusercontent.com/matthuisman/i.mjh.nz/refs/heads/master/Roku/all.xml



_All Combined (Buddy Chew Chew)
https://raw.githubusercontent.com/BuddyChewChew/combine-remote-playlists/refs/heads/main/combined_playlist.m3u
https://iptv-org.github.io/iptv/index.m3u


Dead:
 _Move On Joy (no longer working)
M3U: https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_moveonjoy.m3u
M3U: https://us_moveonjoy.m3u
EPG: 

_STIRR (All) (Buddy Chew Chew) NO LONGER WORKING OFFLINE DEAD
https://raw.githubusercontent.com/BuddyChewChew/app-m3u-generator/refs/heads/main/playlists/stirr_all.m3u
EPG:

_PPV 
M3UL StreamEast https://raw.githubusercontent.com/BuddyChewChew/My-Streams/refs/heads/main/PPVLand.m3u8

 
EPG Guide-XML:
https://epg.pw/xmltv/epg_US.xml     (this EPG uses tvg-id="465000" numbers as its key matching field.) 
https://raw.githubusercontent.com/mikekaprielian/rtnaodhor93n398/refs/heads/main/en/videoall.xml     (This EPG uses tvg-id="Channel Name" as its key matching field. It is also alphabetic so easier to manually match)
https://epgshare01.online/epgshare01/epg_ripper_ALL_SOURCES1.xml.gz

Custom: https://www.open-epg.com/generate/pMeRnsFumZ.xml  (custom from Open-EPG, updates once per day at noon, only goes out one day)
 

Dispatcharr:
1. load m3u(s)
2. enable groups in the edit settings
3. go to channels tab; on left side are the channels you will add to or delete for the new playlist. On the right are the playlist streams which may not populate as a channel,
so you may have to click the plus sign and add the stream as a channel.
4. add playlist EPG
5. go back to channels tab and click the three dots on the channel side and click "auto match EPG"
6. click edit to add or change icon, or to try and automatch EPG again.

***FOX***

* WORKING

1 #EXTINF:-1 group-title="News" tvg-chno="67" tvg-id="FOX News Channel" tvg-name="Fox News" tvg-logo="http://schedulesdirect-api20141201-logos.s3.dualstack.us-east-1.amazonaws.com/stationLogos/s16374_dark_360w_270h.png" group-title="TV",Fox News
https://starshare.st/live/P4B9TB9xR8/humongous2tonight/51.ts

2 #EXTINF:-1 group-title="USA TV" tvg-ID="FOX News Channel" tvg-name="FOX News Channel" tvg-logo="https://cdn.tvpassport.com/image/station/240x135/v2/s16374_h15_ab.png", FOX News Channel
https://v4.thetvapp.to/hls/FoxNewsChannel/tracks-v1a1/mono.m3u8?token=7I-XU5wzlgwEEBOHnsgbqg&expires=1774800512&user_id=eDcyRHNEcDZnMFIzNUpERllLWXJlQndkZWM2UDhGZXR6UGJJTFFhRA==




5 #EXTINF:-1 tvg-id="FOX News Channel" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Fox_News_Channel_logo.svg/960px-Fox_News_Channel_logo.svg.png" group-title="News",Fox News Channel (720p) [Not 24/7]
https://tvpass.org/live/FoxNewsChannel/hd

6 #EXTINF:-1 tvg-id="FOX News Channel" tvg-name="Fox News SD" group-title="Live",Fox News SD
https://tvpass.org/live/FoxNewsChannel/sd



* NOT WORKING
3 #EXTINF:-1  tvg-name="FOX News Channel SD" tvg-id="FOX News Channel" tvg-logo="https://github.com/tv-logo/tv-logos/blob/main/countries/united-states/fox-news-us.png?raw=true" group-title="TheTVApp",FOX News Channel SD
https://e1.thetvapp.to/hls/FoxNewsChannel/tracks-v1a1/mono.m3u8?token=w-7q_4u1yOxA3tDFUio97Q&expires=1774806073&user_id=RzAxak5McG1lb01LOTlFa3hHVEpzZlowWHdsQjdOQUVpNUhpa1g5Yg==

4 #EXTINF:-1  tvg-name="FOX News Channel HD" tvg-id="fox-news" tvg-logo="https://github.com/tv-logo/tv-logos/blob/main/countries/united-states/fox-news-us.png?raw=true" group-title="TheTVApp",FOX News Channel HD
https://v8.thetvapp.to/hls/FoxNewsChannel/tracks-v1a1/mono.m3u8?token=lLxKtzGM7k1eFTUmrYWplA&expires=1774806082&user_id=RzAxak5McG1lb01LOTlFa3hHVEpzZlowWHdsQjdOQUVpNUhpa1g5Yg==

8 #EXTINF:-1 group-title="MoveOnJoy+" tvg-id="Fox.News.Channel.HD.us2" tvg-logo="http://schedulesdirect-api20141201-logos.s3.dualstack.us-east-1.amazonaws.com/stationLogos/s16374_dark_360w_270h.png" tvg-name="FOX News Channel", FOX NEWS CHANNEL
https://fl1.moveonjoy.com/FOX_NEWS_CHANNEL/mpegts

9 #EXTINF:-1 tvg-id="FoxNewsChannel.us" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Fox_News_Channel_logo.svg/512px-Fox_News_Channel_logo.svg.png" group-title="News" http-referrer="https://www.newslive.com/" http-user-agent="Mozilla/5.0 (iPhone; CPU iPhone OS 17_7 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1",Fox News Channel (720p)
#EXTVLCOPT:http-referrer=https://www.newslive.com/
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (iPhone; CPU iPhone OS 17_7 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1
https://stream.livenewsplay.com:9443/hls/foxnews/foxsd.m3u8



#EXTINF:-1 tvg-id="plex.tv.FOX.Weather.plex" tvg-logo="https://provider-static.plex.tv/epg/cms/production/5822536e-f8a5-44ea-a82f-a73be1b983e8/fox_weather_horizontal.png" group-title="News Other", FOX WEATHER
https://jmp2.uk/plex-5e20b730f2f8d5003d739db7-6351b29cb940534786b2ec17.m3u8

#EXTINF:-1 tvg-id="LiveNOWfromFOX.us@SD" tvg-logo="https://i.imgur.com/1JnyzHv.png" group-title="News",LiveNOW from FOX (1080p) [Geo-blocked]
https://pb-k5p02dtnr2162.akamaized.net/LiveNOW_from_FOX.m3u8

***KNOWN WORKING EPG's***
https://epg.pw/xmltv/epg_US.xml
https://raw.githubusercontent.com/mikekaprielian/rtnaodhor93n398/refs/heads/main/en/videoall.xml

***NEWSMAX***
#EXTINF:-1 tvg-id="NewsmaxTV.us@SD",Newsmax TV (720p)
https://amg00217-newsmax-amg00217c2-zeasn-us-2412.playouts.now.amagi.tv/playlist/amg00217-newsmaxmediafast-newsmaxn1-zeasnus/playlist.m3u8

#EXTINF:-1 tvg-id="NewsmaxTV.us@SD",Newsmax TV (1080p)
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/145.0.0.0 Safari/537.36 Edg/145.0.0.0
https://d35j504z0x2vu2.cloudfront.net/v1/master/0bc8e8376bd8417a1b6761138aa41c26c7309312/newsmax-tv/index.m3u8?ads.vf=Td2nCUXB4ha

#EXTINF:-1 tvg-id="Newsmax TV" group-title="News" tvg-name="Newsmax" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Newsmax_logo.svg/512px-Newsmax_logo.svg.png", Newsmax TV (720p)
https://nmx1ota.akamaized.net/hls/live/2107010/Live_1/index.m3u8
#EXTINF:-1 group-title="News" tvg-id="Newsmax TV" tvg-name="Newsmax" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Newsmax_logo.svg/512px-Newsmax_logo.svg.png", NewsMax TV HD (TVPass)
https://tvpass.org/live/NewsmaxTV/hd
#EXTINF:-1 group-title="News" tvg-id="Newsmax TV" tvg-name="Newsmax" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Newsmax_logo.svg/512px-Newsmax_logo.svg.png", NewsMax TV SD (TVPass)
https://tvpass.org/live/NewsmaxTV/sd
#EXTINF:-1 group-title="News" tvg-id="NewsNet.us" tvg-name="Newsnet" tvg-logo="https://upload.wikimedia.org/wikipedia/commons/9/98/NewsNetLogo2022.png", NewsNet (720p)
https://2-fss-2.streamhoster.com/pl_138/amlst:201950-1311088/playlist.m3u8

# OANN from Klowdtv

#EXTINF:-1 tvg-id="465382" group-title="News" tvg-name="OANN" tvg-logo="https://upload.wikimedia.org/wikipedia/en/thumb/8/84/One_America_News_Network_logo.svg/512px-One_America_News_Network_logo.svg.png", OAN (720p)
https://a-cdn.klowdtv.com/live1/oan_720p/playlist.m3u8
#EXTINF:-1 tvg-id="465382" group-title="News" tvg-name="OANN" tvg-logo="https://logos.fandom.com/wiki/One_America_News_Network?file=One_America_News_Network.svg", OAN
https://cdn.klowdtv.net/803B48A/oan_aws/OAN.m3u8
#EXTINF:-1 tvg-id="OANEncore.us" tvg-name="OAN Encore" group-title="News" tvg-logo="https://i.imgur.com/9S4ZbPL.jpg", OAN Encore (720p) [Geo-blocked]
https://a-cdn.herringnetwork.com/affiliate/oane/playlist.m3u8
#EXTINF:-1 group-title="News" tvg-id="5e7cf6c7b156d500078c5f44" tvg-name="" tvg-logo="https://i.imgur.com/0xW69iu.png", OANPlus (1080p)
https://oan-plus-tcl.amagi.tv/playlist.m3u8
#EXTINF:-1 tvg-id="5e7cf6c7b156d500078c5f44" group-title="News" tvg-name="OAN+", OAN Plus
https://67bf68ca230b4e82bd5ac42d46449483.mediatailor.us-west-2.amazonaws.com/v1/master/d138761b0916ee5f222129c594a33677627df5e3/KlowdTV_OAN_Plus/fast/OAN_Encore/playlist.m3u8
