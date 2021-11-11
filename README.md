# esx_policejob

## Description

This a small re-write of [ZAD4YTV's esx_policejob](https://github.com/ZAD4YTV/esx_policejob) and the code for having the AI Police not attack Player Police [Schwim](https://forum.cfx.re/u/schwim/summary)

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
