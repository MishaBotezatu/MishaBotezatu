[bootstrap]
   # list of bootstrap (ip, node id)
    bootstrap_list = [
        ["149.202.86.103:31245", "5GcSNukkKePWpNSjx9STyoEZniJAN4U4EUzdsQyqhuP3WYf6nj"],
        ["149.202.89.125:31245", "5wDwi2GYPniGLzpDfKjXJrmHV3p1rLRmm4bQ9TUWNVkpYmd4Zm"],
        ["158.69.120.215:31245", "5QbsTjSoKzYc8uBbwPCap392CoMQfZ2jviyq492LZPpijctb9c"],
        ["158.69.23.120:31245", "8139kbee951YJdwK99odM7e6V3eW7XShCfX5E2ovG3b9qxqqrq"],
        ["77.204.36.213:31245", "5nW8tSNNz5DhHQiMXYAYuNMyWKanqVkni2M3BEnn5byQtngioA"],
        ["62.35.189.33:31245", "4zrk2uhdM39rK3VASyQNRLsXZS4CqHExiB6T4bNs3Rg1tuyaWg"],
        ["90.8.60.107:31245", "7xqUr16C1YU9LahTotohg7mJS4HXqPpMmGJ43acDw4FhnvbC1E"],
        ["185.213.209.35:31245",  "73TgqG6cbE4FkjGPr2hKwgYE5KuVNu7THseNmoKUwXx5HTzCbD"],
        ["217.160.193.14:31245",  "5pWAtd3L9KJuZ6WRidWthaaXMn9yFqZ98iPEEoQQWynJhQ769y"],
        ["95.217.118.121:31245",  "74CFJ3oF49fsMvLmaRvgf8Ydff6Rfnq96aitQTfoXvzN3pDFNU"],
        ["185.161.122.193:31245",  "7oaYZLAgnmSHjJFeitBJiTMhNu4XzEi8XJKqp6n5pcQcbq2ZJR"],
        ["95.216.27.164:31245",  "5wRuE64kSDj97bhar9fGsky8jMZnGuSiYmkmAT3yCeTHWsgDsu"],
        ["93.10.109.43:31245",  "6Kz4Cc2jjBcNtJtKDaDZFM73KmxHT9cXpw3XeTEoKPoHncQ2CY"],
        ["109.206.131.213:31245",  "5rSBNC5L1ce8nCcWuVFHtncXXxGXUggmEhUbWvMXHGgCJAPdhS"],
        ["82.223.21.200:31245",  "6HuG1zJLbqycQgPUwFaYZddJiyQP6D9QMEhNwPeHKn3XjHQ3Na"],
        ["65.108.59.25:31245",  "8FYpHvFb6x4Z7jUhpUbEmMgDLXULCQVXnE6MkZV23YrhVikWZV"],
        ["194.156.79.23:31245",  "6uscLLig9FnKqL8vHpSJMNLPH3Ud6EAWLs4zvNduP2uwihPHLb"],
        ["95.216.223.62:31245",  "8FmceEnYKfRPiPvXXHCvytmafgJHXGLityRPmf3iFs2VYAq1d7"],
        ["188.166.39.154:31245",  "8DSjrbSuueaAmCtBPae1BwQH7zRM9xUHyigQGLwLKFbaxSbSVp"],
        ["142.132.198.118:31245",  "6wDx3Fk9mNXUbys3TqGBMuPK8NHQRRJgrXpXJU1r8Yxv7MsR1o"],
        ["34.78.72.253:31245",  "5P2KY5ChC8bYv42Fj282yabRhRsP6Us15fkA5y6h3fqyxTm3CG"],
        ["88.198.6.229:31245",  "64t2Reyne4TtcscSLrUnp4iF6bZGR2BHvj5Gpg288eEmF7KTGN"],
        ["139.99.134.252:31245",  "6nY7Uj9AgnsVodfWKTutzbFCiecpc8EXZ8Z4FLHhBRowBQMPeh"],
        ["82.64.216.7:31245", "65Gx8ikMQLAJSrDNDhsWREjf4QjuPFYjGPmGVrjzBVPKi9giE1"],
        ["93.29.134.115:31245", "7hx5EnXjTBWUvqDtVuEzyiQQTdNY6zycDi7GVxr7AqZ19Rzg9o"]
    ]
    # [optionnal] port on which to listen for incoming bootstrap requests
    bind = "[::]:31245"
    # timeout to establish a bootstrap connection
    connect_timeout = 15000
    # delay in milliseconds to wait between consecutive bootstrap attempts
    retry_delay = 5000
    # if ping is too high bootstrap will be inturrupted after max_ping milliseconds
    max_ping = 10000
    # timeout for incoming message readout
    read_timeout = 10000
    # timeout for message sending
    write_timeout = 10000
    # when enabled, apply a correction to the local computer clock to match bootstrap server time
    enable_clock_synchronization = false
    # [server] data is cached for cache duration millis
    cache_duration = 15000
    # max number of simulataneous bootstraps for server
    max_simultaneous_bootstraps = 2
    # max size of recently bootstrapped IP cache
    ip_list_max_size = 10000
    # refuse consecutive bootstrap attempts from a given IP when the interval between them is lower than per_ip_min_interval milliseconds
    per_ip_min_interval = 3600000
