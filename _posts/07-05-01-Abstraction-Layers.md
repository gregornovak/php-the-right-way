---
isChild: true
title:   Plasti abstrakcije
anchor:  databases_abstraction_layers
---

## Plasti abstrakcije {#databases_abstraction_layers_title}

Mnoga ogrodja ponujajo svojo lastno plast abstrakcije, ki lahko ali pa ne sedi na vrhu PDO. Te bodo pogosto posnemale lastnosti za
sistem ene podatkovne baze, ki manjka iz druge z ovitjem poizvedb v PHP metodah, kar vam da dejansko abstrakcijo podatkovne baze namesto samo abstrakcije povezave, ki jo
[PDO][1] ponuja.

To bo seveda dodalo nekaj prekomernosti, vendar če gradite prenosno aplikacijo, ki potrebuje delovati z MySQL, PostgreSQL in
SQLite, potem bo nekaj prekomernosti vredno zaradi čistosti kode.

Nekatere plasti abstrakcije so bile zgrajene z uporabo [PSR-0][psr0] ali [PSR-4][psr4] standardov imenskih prostorov, tako da se jih lahko namesti v katerokoli aplikacijo, ki želite:

* [Aura SQL][6]
* [Doctrine2 DBAL][2]
* [Propel][7]
* [Zend-db][4]


[1]: http://php.net/book.pdo
[2]: http://www.doctrine-project.org/projects/dbal.html
[4]: https://packages.zendframework.com/docs/latest/manual/en/index.html#zendframework/zend-db
[6]: https://github.com/auraphp/Aura.Sql
[7]: http://propelorm.org/
[psr0]: http://www.php-fig.org/psr/psr-0/
[psr4]: http://www.php-fig.org/psr/psr-4/
