# 📄 config.yml

```YAML
#--------------------------------#
#          HeckersHomes          #
#--------------------------------#
# The default amount of homes a player gets (
  # the amount of homes a player gets is:
  # the default amount (everyone gets this) (manage in default-max-homes)
  # + the amount of extra homes they get from their rank (only players with that rank get those added to their max homes count) (manage in vault-groups)
  # + the amount of extra homes they get from the store (only this player gets those added to their max homes count) (manage in {plugin-folder}/HeckersHomes/player-data/{uuid}.yml/extra-homes))
default-max-homes: 2
vault-groups:
  enabled: true
  default:
    extra-homes: 0
  # other examples
  #vip:
    #extra-homes: 2
  #vipplus:
    #extra-homes: 4

# Add your store link here
store-link: "https://store.exmple.net/change-in-config.yml"

# version, DO NOT CHANGE!
version: 1.0
```
