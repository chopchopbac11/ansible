player_limit: -1
ip_forward: false
permissions:
  default:
  - bungeecord.command.server
  - bungeecord.command.list
  admin:
  - bungeecord.command.alert
  - bungeecord.command.end
  - bungeecord.command.ip
  - bungeecord.command.reload
timeout: 30000
log_commands: false
online_mode: false
servers:
  Hub-MG:
    motd: '&1Just another BungeeCord - Forced Host'
    address: 64.237.49.154:25596
    restricted: false
  Prison:    
    motd: '&1Just another BungeeCord - Forced Host'
    address: 206.221.190.26:25581
    restricted: false
listeners:
- query_port: 25577
  motd: '&1Another Bungee server'
  priorities:
  - lobby
  bind_local_address: true
  tab_list: GLOBAL_PING
  query_enabled: false
  host: 0.0.0.0:25577
  forced_hosts:
    64.237.49.154:25596: Hub-MG
  max_players: 1
  tab_size: 60
  ping_passthrough: false
  force_default_server: true
disabled_commands:
- disabledcommandhere
network_compression_threshold: 256
groups:
  md_5:
  - admin
connection_throttle: 4000
stats: 550e0c05-98ae-42d6-8a79-64e08596d2ad
