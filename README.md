# esx_policejob

## Description

This a small rewrite-of/addition-to [ZAD4YTV's esx_policejob](https://github.com/ZAD4YTV/esx_policejob) with editionof code from [Schwim](https://forum.cfx.re/u/schwim/summary)

This allows the Player Police to "assist" the AI Police. The AI police will now no longer attack Player's with a 'police job'. Players with a police job cannot obtain a wanted level. After a desired number of player police are online the 

#### Possible To-Do List
- Disable AI after configurable set number of Player Police are Online
- Allow AI police to target Player Police who trigger wanted level events.

### Download & Instalation

#### Using GIT

```sh
cd resources
git clone https://github.com//DetanShi/esx_policejob_ai [esx]/esx_policejob
```

#### Manualy

- Download <https://github.com/DetanShi/esx_policejob_ai/archive/refs/heads/main.zip>

### Instalation
- rename folder to `esx_policejob`
- Place in the `esx` or `esx_addons` repository
- Add `start esx_policejob` to your server.cfg
- Add the `esx_policejob.sql` to your database

### Configuration
- inside `config.lua`
```
Config.DisableWantedLevel	  = false
Config.EnoughCopsOnline		  = 3
```

- Disable wanted level turns off wanted level
- `Config.EnoughCopsOnline` can be changed to reflect your desired number to disable the AI if enought players are on.
- Default `Config.EnoughCopsOnline` is 3, once three player 'police' are online AI will disable.

## Legal

### License

- GNU License GPL V3.0
- Read the license in this url <https://github.com/ZAD4YTV/esx_policejob/blob/main/LICENSE>
