---
isChild: true
title:   Razširitev MySQL
anchor:  mysql_extension
---

## Razširitev MySQL {#mysql_extension_title}

Razširitev [mysql] za PHP ni več v aktivnem razvoju in je [uradno opuščena od PHP 5.5.0][mysql_deprecated],
kar pomeni, da bo odstranjena znotraj nekaj naslednjih izdaj. Če uporabljate katerekoli funkcije, ki
se začnejo z `mysql_*`, kot sta `mysql_connect()` in `mysql_query()` v vaših aplikacijah, potem le te enostavno ne
bodo na voljo v kasnejših verzijah PHP. To pomeni, da se boste v srečali s prepisovanjem, torej
je najboljša opcija zamenjava mysql uporabe z [mysqli] ali [PDO] v vaših aplikacijah znotraj vašega razvojnega časovnega
načrta, tako da se vam ne bo mudilo kasneje.

**Če pričenjate od začetka potem vsekakor ne
uporabite [mysql] razširitve: uporabite [MySQLi razširitev][mysqli], ali uporabite [PDO].**

* [PHP: Izbira API-ja za MySQL][mysql_api]
* [PDO Tutorial for MySQL Developers][pdo4mysql_devs]

[mysql]: http://php.net/mysql
[mysql_deprecated]: http://php.net/migration55.deprecated
[mysqli]: http://php.net/mysqli
[PDO]: http://php.net/pdo
[mysql_api]: http://php.net/mysqlinfo.api.choosing
[pdo4mysql_devs]: http://wiki.hashphp.org/PDO_Tutorial_for_MySQL_Developers