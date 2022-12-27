# TV Setup

UK IPTV programming guide. All channels currently should work, but depending on your viewer, the last channel may not work, and some others may not work due to geo-restrictions. Radio channels may also cause your app to not function correctly, in that case, I'd recommend forking and removing all radio channels.

33 channels and counting, from TV to Radio.

This guide is based off the Freeview guide, but may include radio stations and extra channels not found on Freeview as well. EPG currently won't work on this by the way, I have no idea how to fix this at the moment.

Edit: If you're using TVirl on a Android TV device, you should be able to add the EPG from IPTV-org and everything should work except radio (link https://iptv-org.github.io/epg/guides/UK.xml).

Enter experiencersinternational.github.io/tvsetup/config.m3u in your IPTV app to start receiving TV through the internet. You may also have to add the EPG URL listed above.

## Contributors

Here is a few basic things to take note of when contributing:
- DO NOT add any pay channels (e.g. Sky One), else this risks me getting a cease and desist since I'm not operating free to air channels only
- Please order it as close to the Freeview guide as possible, if the free to air channel is not usually in the Freeview guide, always place it at the bottom
- Please only add channels in the highest quality you can find
- If you're adding a regional specific channel, stick to some number post-800. For radio, you should instead use something like 735-1 (BBC Radio Gloucestershire), since it helps separate the different regions

## Compatibility

This service is fully based around the TVirl app for Android TV, it works with all of the features in here perfectly.
You should steer away from the IPTV smarters pro app for mobile (in fact, plain old VLC is probably better), EPG doesn't work as far as I can see with no subscription, channels don't scan properly and some don't play properly.

In order to get correct channel ordering, make sure tvg-chno is used for channel ordering.
