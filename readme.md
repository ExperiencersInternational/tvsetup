# TV Setup

UK IPTV programming guide. All channels currently should work, but depending on your viewer, the last channel may not work, and some others may not work due to geo-restrictions. Radio channels may also cause your app to not function correctly, in that case, I'd recommend forking and removing all radio channels.

33 channels and counting, from TV to Radio.

This guide is based off the Freeview guide, but may include radio stations and extra channels not found on Freeview as well. EPG currently doesn't show info for radio channels, if you can't see any EPG info whatsoever, try using a different app.

Important: CBS Reality seems to use an Irish stream from what I've seen, but all content should still be in English and follow the UK EPG.

Enter experiencersinternational.github.io/tvsetup/config.m3u in your IPTV app to start receiving TV through the internet. You may also have to add the EPG URL listed above.

## Contributors

Here is a few basic things to take note of when contributing:
- DO NOT add any pay channels (e.g. Sky One), else this risks me getting a cease and desist since I'm not operating free to air channels only
- Please order it as close to the Freeview guide as possible, if the free to air channel is not usually in the Freeview guide, always place it at the bottom
- Please only add channels in the highest quality you can find
- For local TV channels excluding radio, please list in the 92x to 99x ranges
- For local radio, use Freeview numbers. If multiple channels use the same numbers, use a - to separate the regions (e.g. 735-1 for Radio Gloucestershire and 735-2 for Radio Derby). If a radio station is not broadcast on Freeview, stick to 740-799 in range
- For channels intended for Wales, stick to a listing in the 90x range, and for channels intended for Scotland, use a channel number in the 91x range

## Compatibility

This service is fully based around the TVirl app for Android TV, it works with all of the features in here perfectly.
You should steer away from the IPTV smarters pro app for mobile (in fact, plain old VLC is probably better), EPG doesn't work as far as I can see with no subscription, channels don't scan properly and some don't play properly.

In order to get correct channel ordering, make sure tvg-chno is used for channel ordering.
