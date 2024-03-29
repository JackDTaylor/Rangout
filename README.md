# Rangout

## ОБЩЕЕ
* Угол по отношению к ветру определяет максимальную скорость корабля
* В зависимости от стоящих на корабле типов парусов определяется лучший угол хода
* Ветер сильнее определенного значения - шторм

## БЛОК "КОРАБЛЬ" И РЕСУРСЫ
* Блок "Корабль" имеет три слота инвентаря для парусов, снастей и досок
* Блок "Корабль" определяет необходимое для корабля количество досок, снастей и парусины
  * Необходимое количество парусины определяется по количеству блоков "Парус"
  * Необходимое количество снастей определяется по количеству блоков "Мачта" и "Парус"
  * Необходимое количество досок определяется по общему количеству блоков корабля
* При плавании в шторм парусина, снасти и доски из инвентаря корабля расходуются в зависимости от силы ветра
* При недостаточном количестве парусины скорость корабля пропорционально уменьшается
  * Если парусины меньше 20% от необходимого - корабль стоит
* При недостаточном количестве снастей ускорение и скорость поворота корабля пропорционально уменьшаются
  * Если снастей меньше 20% от необходимого - корабль стоит
* При недостаточном количестве досок, количество досок и снастей постепенно уменьшается и без шторма
  * Если досок меньше 50% от необходимого - корабль разбирается обратно в блоки
  * (Удалять случайные блоки корабля при нехватке досок?)

## БЛОК "ПАРУС"
* По сути - только реи, для крафта не нужна парусина, только дерево
* Несколько типов парусов: прямой, косой и кливер
* Наличие самого паруса определяется от наличия парусины в инвентаре корабля
* Постараться сделать рендер парусов в зависимости от их состояния (количества парусины в инвентаре корабля)
* Постараться сделать управление парусами более реалистичным - поднятие/спуск парусов, наполненость в зависимости от ветра

## БЛОК "МАЧТА"
* Несколько диаметров
* Мачты становятся только тоньше к верху и не больше двух одинаковых блоков мачт подряд
  * Мачта большего диаметра не может ставиться на мачту меньшего
  * Мачта такого же диаметра может ставиться на аналогичную только если та стоит на мачте большего диаметра
* По мачте можно подниматься как по лестнице

## ДЕКОРАТИВНЫЕ БЛОКИ
* "Воронье гнездо" (из v1)
* Ванты (из v1)
* Лестница из веревок (из v1)
