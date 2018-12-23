KairosDB - это быстро распределенная масштабируемая база данных временных рядов с открытым исходным кодом, написанная поверх Cassandra. Данные отправляются в базу данных по нескольким протоколам, таким как Telnet[1], Rest[2] и Graphite[3]. Первоначально она была переработана в оригинальном проекте OpenTSDB[4], но он превратился в другую систему, для которой управление данными, обработка данных и визуализация полностью разделены.

Пользователям предоставлен понятный веб-интерфейс, для отправки запросов к базе данных. KairosDB может масштабироваться до более чем 10 миллиардов точек данных за день. KairosDB хранит скалярные значения, на протяжении некоторого времени, часто с дополнительными метаданными (называемые тегами). По сравнению с реляционными базами данных, где строка в таблице обычно представляет собой одно скалярное значение в определенное время, KairosDB обычно объеденяет несколько скалярных значений в одну строку, которая представляет собой период времени.

![KairosDB](webroot/img/logoSmall.png)
[![Build Status](https://travis-ci.org/kairosdb/kairosdb.svg?branch=develop)](https://travis-ci.org/kairosdb/kairosdb)

KairosDB is a fast distributed scalable time series database written on top of Cassandra.

## Documentation

Documentation is found [here](http://kairosdb.github.io/website/).
Chinese Documentation is found [here](http://www.kairosdb.com/).中文文档在这里

[Frequently Asked Questions](https://github.com/kairosdb/kairosdb/wiki/Frequently-Asked-Questions)

## Installing

Download the latest [KairosDB release](https://github.com/kairosdb/kairosdb/releases).

Installation instructions are found [here](http://kairosdb.github.io/docs/build/html/GettingStarted.html)

## Getting Involved

Join the [KairosDB discussion group](https://groups.google.com/forum/#!forum/kairosdb-group).

## Contributing to KairosDB

Contributions to KairosDB are **very welcome**. KairosDB is mainly developed in Java, but there's a lot of tasks for non-Java programmers too, so don't feel shy and join us!

What you can do for KairosDB:

- [KairosDB Core](https://github.com/kairosdb/kairosdb): join the development of core features of KairosDB.
- [Website](https://github.com/kairosdb/kairosdb.github.io): improve the KairosDB website.
- [Documentation](https://github.com/kairosdb/kairosdb/wiki/Contribute:-Documentation): improve our documentation, it's a very important task.

If you have any questions about how to contribute to KairosDB, [join our discussion group](https://groups.google.com/forum/#!forum/kairosdb-group) and tell us your issue.

## License
The license is the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
