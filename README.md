# Auto switch profitability miner

Single point miner proxy that switches between most profitable. 
Can deal with multiple CPU, GPU and ASICs with one running instance, good for dedicated mining motherboards.

# What it does?

* Downloads the necessary official miners from the supported coins
* Benchmarks how your current rig perform to the active coins
* Picks a pool from the available ones that you provide
* Launches the according miner software to that coin
* Currently takes data from https://whattomine.com to determine what is best to mine at the moment

# Future

* Use AI (machine learning) to try and make market predictions (and mine those coins instead of the immediate profitable coins)
* Adjustable median from historical data to decide whether or not stay with constant profitability coins
* Graphical interface added through electron alongside the console interface
* Pluggable interface for market sources other than whattomine

# Full Disclosure

Not afiliated in any way with WhatToMine, they are just the public endpoint of data

# License

MIT

# Development

* BTC: `16QDbqa6UMFtMCdDcJJ5N2bqryH4Q56BVU`
* BCH: `1E6gKfkyxsjr2rSbcHbnfsQumKxkGKwRYc`
* ETH: `0xfF9087E7112d3b7D7B5bDD6C9ffb0970ACC162E7`
* MIOTA: `NNIH9VGEQFZAJIITBO9FEDSYUDYXHMAINGSKWIU9ADUHYYNTIYGJADZITOCVMWEFTKJGCNCJN9ZRFUZKCPSUOMDAKD`
* NXT: `NXT-7TJT-8NS2-8QBS-5Y89X`
* BTG: `GY2RWXUKYDmYDaroMmucgUdF7dLqaHDKWu`
* XEM: `NBC772-Q3SL4X-AGVNMP-JAWGJE-U6BCSB-Q7WNAX-YU5V`
* DASH: `XaqxcT3BDmSLGB4M6ozrET1qJPBA4RJpng`
