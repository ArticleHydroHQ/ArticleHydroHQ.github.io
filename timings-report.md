# Server softwares that include timings
- [Pufferfish](https://pufferfish.host/downloads) (V2, disabled by default)
- [Paper](https://papermc.io) (V2)
- [Spigot](https://www.spigotmc.org) (V1)

# Server softwares that *don't* include timings
- [Petal](https://github.com/Bloom-host/Petal) (Includes spark instead, development seems to be dead)
- [Purpur](https://purpurmc.org) (Includes spark instead)
- [Bukkit](https://bukkit.org) (Outdated and insecure, use [Paper](https://papermc.io) instead)
- Any networking software ([Bungeecord](https://www.spigotmc.org/wiki/bungeecord-installation/), [Waterfall](https://papermc.io/downloads#Waterfall), [Velocity](https://papermc.io/downloads#Velocity), etc)

## How to get a timings report
Turn on the server join as an OP then run `/timings on`
then wait or play, about 10-15 minutes then run `/timings paste` and open the link in your browser or share it with the support that has told you to make this

## How to get a spark report
[Spark](https://spark.lucko.me) is a different system than timings, so the commands are different, you can run `/spark profiler start --timeout 60` which will stop after 1 minute.

Alternatively, you can run `/spark profiler start` and wait however long you wait as long as there are no restarts.
When you want it to stop run `/spark profiler stop`

## Should i use timings or spark?
Timings is included with [most server softwares](#server-softwares-that-include-timings), however does constantly drain about 5% of your ticks even if its off (!!!)

[Spark](https://spark.lucko.me) is more powerful and can be used with any server software that supports bukkit plugins, and doesn't drain your server when its not in use.

Ultimately, it's up to you, but [spark](https://spark.lucko.me) is recommended.

# Sources
[Spark](https://spark.lucko.me/docs/Command-Usage#spark-profiler)
