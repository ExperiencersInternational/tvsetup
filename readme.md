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
|700|BBC Radio 1|Unknown|
|701|BBC Radio 1Xtra|Unknown|
|702|BBC Radio 2|Unknown|
|703|BBC Radio 3|Unknown|
|704|BBC Radio 4|Unknown|
|705|BBC Radio 5 Live|Unknown|
|706|BBC Radio 5 Sports Extra|Unknown|
|707|BBC Radio 6 Music|Unknown|
|708|BBC Radio 4 Extra|Unknown|
|709|BBC Radio Asian Network|Unknown|
|710|BBC World Service|Unknown|
|718|Smooth Radio|Unknown|
|719-1|BBC Radio Leeds|Unknown|
|720-1|BBC Radio H&W|Unknown|
|720-2|BBC Radio Cymru|Unknown|
|720-3|BBC Radio Devon|Unknown|
|720-4|BBC Radio Foyle|Unknown|
|720-5|BBC Radio Lancashire|Unknown|
|720-6|BBC Radio nan Gàidheal|Unknown|
|720-7|BBC Radio Nottingham|Unknown|
|720-8|BBC Radio Suffolk|Unknown|
|720-9|BBC Radio Sussex|Unknown|
|720-10|BBC Radio York|Unknown|
|720-11|BBC Radio Three Counties|Unknown|
|724|Capital|Unknown|
|726|BBC Radio Stoke|Unknown|
|728|Heart (London)|Unknown|
|731|Classic FM|Unknown|
|732|LBC|Unknown|
|735-1|BBC Radio Gloucestershire|Unknown|
|735-2|BBC Radio Derby|Unknown|

## Parental guidance

This repository **DOES NOT** have any preventions stopping users from accessing content that has a guidance warning on it. Please have regular discussions discussing what they are watching, or make your own specialised guide that only displays specific channels that are safe to watch.
