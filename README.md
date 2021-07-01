# axiectl


# Helper

- Deploy service: 
    +   `axiectl {{ Service name }} {{ env }} {{ mount file }} {{ docker image }}` .
    +   docker image will be add by Jenkins. ( JTE cmd_release ) .
- cmd_release examples : 
    +   `axiectl auction_trackers dev Settings.toml` .
        - Deploy new container `auction_trackers` to `Dev` server with setting mount file `Settings.toml`
    +   `axiectl axie_trackers dev ''`
        - Deploy new container `axie_trackers` to `Dev` server without docker mount volume.