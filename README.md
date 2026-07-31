# Custom_US_IPTV_No_Sportz
Custom IPTV playlist mapped with 4 built in guides
_Custom Tim (Manual edit from Github us_all.m3u combined with Select channels from KLOWD and LIVENOW all sports, BET, foreign, and kids programming removed)
M3U: _Custom Tim V2.0
EPG: https://epg.pw/xmltv/epg_US.xml
EPG: https://raw.githubusercontent.com/mikekaprielian/rtnaodhor93n398/refs/heads/main/en/videoall.xml
EPG: https://raw.githubusercontent.com/matthuisman/i.mjh.nz/refs/heads/master/PlutoTV/us.xml
EPG: https://i.mjh.nz/PBS/all.xml.gz



_Buddy Chew Chew
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

_Fire TV
https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_firetv.m3u

_Roku
M3U: https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us_roku.m3u  
EPG: https://raw.githubusercontent.com/matthuisman/i.mjh.nz/refs/heads/master/Roku/all.xml



_All Combined (Buddy Chew Chew)
https://raw.githubusercontent.com/BuddyChewChew/combine-remote-playlists/refs/heads/main/combined_playlist.m3u
https://iptv-org.github.io/iptv/index.m3u



EPG Guide-XML:
https://epg.pw/xmltv/epg_US.xml     (this EPG uses tvg-id="465000" numbers as its key matching field.) 
https://raw.githubusercontent.com/mikekaprielian/rtnaodhor93n398/refs/heads/main/en/videoall.xml     (This EPG uses tvg-id="Channel Name" as its key matching field. It is also alphabetic so easier to manually match)
https://epgshare01.online/epgshare01/epg_ripper_ALL_SOURCES1.xml.gz

Custom: https://www.open-epg.com/generate/pMeRnsFumZ.xml  (custom from Open-EPG, updates once per day at noon, only goes out one day)
 

***FOX***

* WORKING (as of 7/31/2026)

#EXTINF:-1 group-title="News" tvg-id="Fox.News.Channel.HD.us2" tvg-logo="http://schedulesdirect-api20141201-logos.s3.dualstack.us-east-1.amazonaws.com/stationLogos/s16374_dark_360w_270h.png",FOX News
http://kstv.us:8080/live/Kh2fHxR0c8/3333726709/22530.ts

#EXTINF:-1 tvg-chno="62" tvg-id="Fox.News.Channel.HD.us2" tvg-name="Fox News" tvg-logo="http://schedulesdirect-api20141201-logos.s3.dualstack.us-east-1.amazonaws.com/stationLogos/s16374_dark_360w_270h.png" group-title="TV",Fox News
http://206.212.244.63/67/index.m3u8

#EXTINF:-1 tvg-chno="60" tvg-id="Fox.Business.HD.us2" tvg-name="Fox Business" tvg-logo="http://schedulesdirect-api20141201-logos.s3.dualstack.us-east-1.amazonaws.com/stationLogos/s58649_dark_360w_270h.png" group-title="TV",Fox Business
http://206.212.244.63/66/index.m3u8

REBEL IPTV has free working Fox News but unable to generate source url Sometimes it flips to Fox Live.

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
