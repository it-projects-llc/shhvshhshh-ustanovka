# Как установить Щвщщ через Doodba

Мы рекомендуем устанавливать Щвщщ через инструмент [doodba](https://github.com/Tecnativa/doodba). Для этого используйте следующие настройки.

## [repos.yaml](https://github.com/Tecnativa/doodba#optodoocustomsrcreposyaml) 


```yaml

odoo:
  defaults:
    depth: $DEPTH_MERGE
  remotes:
    shhvshhshhshh: https://github.com/it-projects-llc/shhvshhshhshh.git
  target: origin $ODOO_VERSION
  merges:
    - origin $ODOO_VERSION
```
## [addons.yaml](https://github.com/Tecnativa/doodba/blob/master/README.md#optodoocustomsrcaddonsyaml)

```yaml

ENV:
  DEFAULT_REPO_PATTERN: https://github.com/it-projects-llc/{}.git

misc-addons:
  - web_debranding

l10n-addons:
  - shhvshhshhshh
```

# Другие способы установки

Основные способы установки перечисленные здесь: [руководство-разработчика.щвщщ.рф/setup/install.html](https://xn----8sbaaecap4amnj6bbcfvicnvkf8i.xn--b1a9bba.xn--p1ai/setup/install.html)

При этом вам нужно будет добавлять следующие репозитории в [addons_path](https://xn--v1aaa.xn--b1a9bba.xn--p1ai/ru/latest/admin/addons_path.html):

* https://github.com/it-projects-llc/misc-addons
* https://github.com/it-projects-llc/l10n-addons

