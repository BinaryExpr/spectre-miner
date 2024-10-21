# A miner for the [Spectre Network](https://github.com/spectre-project/rusty-spectre)

This miner was optimized to run much faster than the official miner.

The miner uses the [Spectre Stratum Bridge](https://github.com/spectre-project/spectre-stratum-bridge) to mine.

Dev fee: 2.5%

### Options ###
```
   -d <daemon_address>   # ip address or hostname of a bridge/pool (for example, 127.0.0.1:5555)
   -w <wallet_address>
   -t <threads>
   --watchdog            # restarts the miner if hashrate was 0 for longer than 20 seconds
```
