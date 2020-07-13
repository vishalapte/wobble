# Services

## photoanalysisd

*Disable*

``` bash
launchctl disable gui/$UID/com.apple.photoanalysisd && launchctl kill -TERM gui/$UID/com.apple.photoanalysisd
launchctl disable user/$UID/com.apple.photoanalysisd && launchctl kill -TERM user/$UID/com.apple.photoanalysisd
```

*Enable*

``` bash
launchctl enable gui/$UID/com.apple.photoanalysisd && launchctl kill -TERM gui/$UID/com.apple.photoanalysisd
launchctl enable user/$UID/com.apple.photoanalysisd && launchctl kill -TERM user/$UID/com.apple.photoanalysisd
```
