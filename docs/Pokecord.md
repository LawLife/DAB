# Pokecord.yaml

Configurations options for farming Pokecord related things. Currently supports autocatching and releasing.

## Config Options:

### Booleans (True/False)

| Bool        | Description                                                         |
|:-----------:|:-------------------------------------------------------------------:|
| firsttime   | Used for commandline configuration, disable to configure manually   |
| enabled     | Whether or not all Pokecord related farming is enabled              |
| autocatch   | Whether or not automatic Pokemon catching is enabled                |
| autorelease | Whether or not automatic releasing of configured Pokemon is enabled |

### Integers

| Integer          | Description                                                                  |
|:----------------:|:----------------------------------------------------------------------------:|
| autocatchdelay   | Delay, in seconds, before Pokemon are automatically caught                   |
| minimumiv        | Minimum IV required for pokemon not to be discarded by autorelease           |
### Lists

| List     | Description                                          |
|:--------:|:----------------------------------------------------:|
| channels | List of channel ids to do Pokecord related things in |

### Dictionaries (Key: Value)

| Dictionary | Description                                                       |
|:----------:|:------------------------------------------------------------------|
| prefixes   | Pokecord prefixes (values) corresponding with the channels (keys) |

Additional notes [here](Additional.md)
