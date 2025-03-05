# fetch-dysentery

Neofetch meets the Oregon Trail

![dysentery2(1)](https://github.com/user-attachments/assets/bbaa18a4-7cab-4e87-bcf1-9ec83e29c29f)

If you trust me:

```
curl -Ls https://raw.githubusercontent.com/wong-justin/fetch-dysentery/refs/heads/main/fetch-dysentery | bash
```

You can override the messages by using these options:

```
--user-at-host
--date
--weather
--battery
--packages
--ram
--cores
--disk-space-used
--disk-space-remaining
```

Example: `curl -Ls https://raw.githubusercontent.com/wong-justin/fetch-dysentery/refs/heads/main/fetch-dysentery | bash -s -- --date "$(date +%Y-%m-%d)"`

This is especially useful if one of the specs fails to display on your machine.
