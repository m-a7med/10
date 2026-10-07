:for i from=2 to=254 do={
  /queue simple add name=("pc" . ($i-1)) target=("192.168.80." . $i) max-limit=1M/4M
}

https://api.telegram.org/bot/getUpdates


# 10
