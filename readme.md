# TV Setup

## About

UK IPTV programming guide. All channels currently should work, but depending on your viewer, the last channel may not work, and some others may not work due to geo-restrictions. Radio channels may also cause your app to not function correctly, in that case, I'd recommend forking and removing all radio channels.

100 channels and counting, from TV to Radio.

This guide is based off the Freeview guide, but may include radio stations and extra channels not found on Freeview as well. EPG currently doesn't show info for radio channels, if you can't see any EPG info whatsoever, try using a different app.

Enter experiencersinternational.github.io/tvsetup/config.m3u in your IPTV app to start receiving TV through the internet. You may also have to add the EPG URL listed above.

### Copyright 

Despite it being my best intentions not to host any copyrighted content, due to only focusing on free to air content, there may be a few things that slip through the cracks, and in those cases, please submit a copyright removal request to me, and I will remove the affected content on the list. Please don't just go and file a request to GitHub and take down the entire thing.

Please also note that I don't host any of the content apart from the Information channel which is a looping video.

## Contributors

Here is a few basic things to take note of when contributing:
- **DO NOT** add any pay to view channels (e.g. Sky Max), else this risks me getting a cease and desist since I'm not operating free to air channels only
- Please order it as close to the Freeview guide as possible, if the free to air channel is not usually in the Freeview guide, always place it at the bottom
- Please only add channels in the highest quality you can find
- For local TV channels excluding radio, please list in the 92x to 99x ranges
- For local radio stations, use Freeview numbers. If multiple channels use the same numbers, use a - to separate the regions (e.g. 735-1 for Radio Gloucestershire and 735-2 for Radio Derby). If a radio station is not broadcast on Freeview, stick to 740-798 in range
- For channels intended for Wales, stick to a listing in the 90x range, and for channels intended for Scotland, use a channel number in the 91x range

## Compatibility

This service is fully based around the TVirl app for Android TV, it works with all of the features in here perfectly.
You should steer away from the IPTV smarters pro app for mobile (in fact, plain old VLC is probably better), EPG doesn't work as far as I can see with no subscription, channels don't scan properly and some don't play properly.

In order to get correct channel ordering, make sure tvg-chno is used for channel ordering.

## Channels

Not bothering to write down everything, but this allows easy access to most popular channels.

### TV

|Channel number|Channel name|Quality|Region Area|
|-|-|-|-|
|1|BBC One|720p|England|
|2|BBC Two|720p|England|
|3|ITV1|1080p|West Country (South)|
|4|Channel 4|1320x1080 (1080p)|N/A|
|5|Channel 5|1080p|N/A|
|6|ITV2|1080p|N/A|
|7|BBC Three|720p|England|
|9|BBC Four|720p|England|
|10|ITV3|880x720 (720p)|N/A|
|13|E4|576p|N/A|
|35|ITV1 +1|576p|Granada|
|801|4Music|576p|N/A|
|807|RT UK*|1080p|UK|
|910|STV|1080p|Scotland|
|911|STV+1|1080p|Scotland|

`* Opinions shared do not represent my own opinions and users should be warned that this channel hosts Russian state-affiliated media.`

### Radio

This list only displays channels which only display audio. For other channels which show music, refer to the TV list (if the specified channel has been added to the list that is).

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

## Parental guidance

This repository **DOES NOT** have any preventions stopping users from accessing content that has a guidance warning on it. Please have regular discussions discussing what they are watching, or make your own specialised guide that only displays specific channels that are safe to watch.
