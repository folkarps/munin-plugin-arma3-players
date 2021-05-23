# arma3_players Munin Plugin

This is a quick and dirty [Munin](https://munin-monitoring.org/) plugin to monitor the number of players on Arma 3 servers.

It uses the [Valve A2S Source Server Query](https://developer.valvesoftware.com/wiki/Server_queries) protocol supported by Arma 3 servers.
In theory this plugin can be used on any server that supports A2S queries, the graph name and such would just need to be changed.

## Usage

1. Edit the `target_servers` dict in the arma3_players script to include all the servers to monitor
2. Ensure the Munin node server has Python 3 installed
3. Install the arma3_players plugin script by following [this guide](http://guide.munin-monitoring.org/en/latest/plugin/use.html)
