# SafetyMeter

Proposal Presentation: https://docs.google.com/presentation/d/1evwgpaSo2TNE3quI4UhSxzL611lQ-aenufIu8Lzjrk0/edit#slide=id.p

Map:
- When you build the app and map function isn’t working, please go to Features > Location > Custom Location.. and set your simulator location to be 38.64801 and -90.24142 since simulator doesn’t detect the current location.
- When you build the app and map function isn’t working, please  go to Features > Location > Custom Location..  and set your simulator location to be 38.64801 and  -90.24142 since simulator doesn’t detect the current location.

- The map only works in St. Louis area.
- In the map search bar, please search avenue names to find locations (e.g. delmar loop, 6000 waterman), which pinpoint the location. Then press ctrl + option + click the map to zoom.
- Safety scores (danger score) are shown in gray button from scale of 0 to 100. 0 means the area is totally safe and 100 means the area is extremely dangerous.
- Live update updates user’s current location but it’s not used in the map.


News Feed:
- This is an unnecessary error, but to prevent boringssl_metrics_log_metric_block_invoke error, type in terminal ‘xcrun simctl spawn booted log config --subsystem com.apple.network --category boringssl --mode "level:off’ to ignore warnings. It’s a negligible error that happens because we’re using a simulator instead of a real phone.
- News feed shows latest crime news in St. Louis. It doesn't show crime news outside St. Louis. 


Password Reset:
- Tapping reset button send reset password instruction to your email (especially if you're using a Gmail Account) If you can’t find reset password email in your inbox, check your spam inbox.

GitHub Repo (may be private): https://github.com/HowardWHW/CSE438-SafetyMeter

