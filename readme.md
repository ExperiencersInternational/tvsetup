# TVsetup

## About

A list of free-to-air, mostly available on Freeview, channels in the UK. Contains over 140 channels (currently about 110 due to withdrawing some broken channels) from TV to Radio.

Get started by adding the playlist link in your application:

```
https://experiencersinternational.github.io/tvsetup/config.m3u
```

If your application doesn't automatically add an EPG, add this 48-hour EPG run by @dp247:

```
https://raw.githubusercontent.com/dp247/Freeview-EPG/master/epg.xml
```

Most channels are ordered in the Freeview style, so you'll feel right at home. A few exceptions do apply though.

For update information, follow me over on the fediverse `@experiencersinternational@mstdn.social`.

If you want to contribute, read the [contributing guide](docs/contributing_guide.md) first.

### Copyright 

Despite it being my best intentions not to host any copyrighted content, due to only focusing on free to air content, there may be a few things that slip through the cracks, and in those cases, please submit a copyright removal request to me, and I will remove the affected content on the list. Please don't just go and file a request to GitHub and take down the entire thing.

Please also note that I don't host any of the content apart from the Information channel which is a looping video.

## Compatibility

**I need to rewrite this all eventually, I'll probably be putting some guides on the wiki out for compatibility eventually.**

This service is fully based around the TVirl app for Android TV, it works with all of the features in here perfectly.
You should steer away from the IPTV smarters pro app for mobile (in fact, plain old VLC is probably better), EPG doesn't work as far as I can see with no subscription, channels don't scan properly and some don't play properly.

In order to get correct channel ordering, make sure tvg-chno is used for channel ordering.

## Channels

Not bothering to write down everything, but this allows easy access to most popular channels. Most TV channels broadcast in 25fps apart from Ideal World.

**EDIT: Some of these channels may have been removed, and I haven't gone and removed them from the list below. STV has replaced ITV1, same with the +1 stream.**

### TV

|Channel number|Channel name|Quality|Region Area|
|-|-|-|-|
|1|BBC One|720p|England|
|2|BBC Two|720p|England|
|3|STV|1080p|West Scotland|
|4|Channel 4|1320x1080 (1080p)|Scotland|
|5|Channel 5**|1080p|N/A|
|7|BBC Three|720p|England|
|9|BBC Four|720p|England|
|13|E4|576p|N/A|
|14|Film4|576p|N/A|
|15|Channel 4+1|576p|N/A|
|16|QVC|540p|UK|
|17|Really|576p|N/A|
|18|More4|576p|N/A|
|19|Dave|576p|N/A|
|20|Drama|576p|N/A|
|21|5USA|576p|N/A|
|27|Yesterday|576p|N/A|
|28|ITVBe|576p|N/A|
|32|5STAR**|576p|N/A|
|33|5ACTION**|576p|N/A|
|35|STV +1|1080p|West Scotland|
|37|QVC Beauty|540p|UK|
|38|QVC Style|540p|UK|
|84|PBS America|720p|N/A|
|85|Create & Craft|720p|N/A|
|201|CBBC|720p|N/A|
|202|CBeebies|720p|N/A|
|232|BBC Parliament|540p|N/A|
|235|Al Jazeera|1080p|N/A|
|237|TalkTV|1080p|N/A|
|801|4Music|576p|N/A|
|805|Now 80s|720p|N/A|
|807|RT UK*|1080p|UK|

`* Opinions shared do not represent my own opinions and users should be warned that this channel hosts Russian state-affiliated media. ** Subtitles available.`

### Radio

This list only displays channels which only display audio. For other channels which show music, refer to the TV list (if the specified channel has been added to the list that is). TV guides are currently unavailable for most regional stations, will be trying to fix it soon.

|Channel number|Channel name|Quality|
|-|-|-|
|700|BBC Radio 1|320k|
|701|BBC Radio 1Xtra|320k|
|702|BBC Radio 2|320k|
|703|BBC Radio 3|320k|
|704|BBC Radio 4|320k|
|705|BBC Radio 5 Live|320k|
|706|BBC Radio 5 Sports Extra|320k|
|707|BBC Radio 6 Music|320k|
|708|BBC Radio 4 Extra|320k|
|709|BBC Radio Asian Network|320k|
|710|BBC World Service|96k|
|718|Smooth Radio|128k|
|719-1|BBC Radio Leeds|320k|
|719-2|BBC Radio Jersey|320k|
|719-3|BBC Radio Bristol|320k|
|719-4|BBC Radio Berkshire|320k|
|719-5|BBC Radio CWR|320k|
|719-6|BBC Radio Kent|320k|
|719-7|BBC Radio Manchester|320k|
|719-8|BBC Radio Newcastle|320k|
|719-9|BBC Radio Norfolk|320k|
|719-10|BBC Radio Scotland|320k|
|719-11|BBC Radio Ulster|320k|
|719-12|BBC Radio Wales|320k|
|720-1|BBC Radio H&W|320k|
|720-2|BBC Radio Cymru|320k|
|720-3|BBC Radio Devon|320k|
|720-4|BBC Radio Foyle|320k|
|720-5|BBC Radio Lancashire|320k|
|720-6|BBC Radio nan Gàidheal|320k|
|720-7|BBC Radio Nottingham|320k|
|720-8|BBC Radio Suffolk|320k|
|720-9|BBC Radio Sussex|320k|
|720-10|BBC Radio York|320k|
|720-11|BBC Radio Three Counties|320k|
|721-1|BBC Radio Cornwall|320k|
|721-2|BBC Radio Cumbria|320k|
|721-3|BBC Radio Cymru 2|320k|
|721-4|BBC Radio Guernsey|320k|
|721-5|BBC Radio Humberside|320k|
|721-6|BBC Radio Leicester|320k|
|721-7|BBC Radio London|320k|
|721-8|BBC Radio Shropshire|320k|
|721-9|BBC Radio Wiltshire|320k|
|722-1|BBC Radio Cambridgeshire|320k|
|722-2|BBC Radio Lincolnshire|320k|
|722-3|BBC Radio Merseyside|320k|
|722-4|BBC Radio Oxford|320k|
|722-5|BBC Radio Solent|320k|
|722-6|BBC Radio Somerset|320k|
|722-7|BBC Radio Surrey|320k|
|722-8|BBC Radio Tees|320k|
|722-9|BBC Radio WM|320k|
|724|Capital|128k|
|726|BBC Radio Stoke|320k|
|728|Heart (London)|128k|
|731|Classic FM|128k|
|732|LBC|48k|
|733|TransWorldRadio|128k|
|734-1|BBC Essex|320k|
|734-2|BBC Radio Northampton|320k|
|734-3|BBC Radio Sheffield|320k|
|735-1|BBC Radio Gloucestershire|320k|
|735-2|BBC Radio Derby|320k|
|740|BBC Radio Orkney|320k|
|741|BBC Radio Shetland|320k|
|742|BBC Radio 1 Dance|320k|
|743|BBC Radio 1 Relax|320k|
|744|CBeebies Radio|320k|

## Parental guidance

This repository **DOES NOT** have any preventions stopping users from accessing content that has a guidance warning on it. Please have regular discussions discussing what they are watching, or make your own specialised guide that only displays specific channels that are safe to watch.
