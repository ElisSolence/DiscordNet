# DiscordNet
the discord network info and a basic discord.py bot

## Address structure
`255.255.255.255:65535`

#### Host
The first 4 numbers should consist of an integer from 0 to 255.
These numbers are refered to as the `Host`
Each member in the program gets a unique `Host` code.

#### Port
The last 5th number should consist of an integer from 0 to 65535.
This number is refered to as the `Port`
A select `Port` numbers are reserved for special utilities.

| Port    | Purpose                     |
| ------- | --------------------------- |
| `0    ` | host main port              |
| `1    ` | remote terminal             |
| `2    ` | return bot owner id         |
