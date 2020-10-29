## Термины, используемые в сообществе

// коллективное авторство?

* `Препинак` &mdash; знак препинания.
* **Названия пальцев.** Проблема оригинальный названий в том, что некоторые из них являются прилагательными, и поэтому к ним необходимо добавлять слово `палец`. Наши же названия стремятся избавиться от этого.

  Мы создали три разные системы. Про последнюю есть [статья](https://bouncepaw.github.io/fingers), но эта система не рекомендуется. Так же все пальцы кроме тамба называются общим словом `фингер` (или `фингерец` по системе Вольки).
  
  |Русское название|Сокращённое|По Вольке|По Баунспо|
  |----------------|-----------|---------|----------|
  |Большой         |Тамб       |Тамбец, толстец|Тамб|
  |Указательный    |Указ       |Указец   |Индике    | 
  |Средний         |Сред       |Среднец  |Медиус    | 
  |Безымянный      |Безым      |Безымянец|Ануляр    | 
  |Мизинец         |Миз        |Мизинец  |Мизинец   |

* **Названия рук.** Аналогично пальцам. 

  |Русское название |optozorax|bouncepaw|
  |-----------------|---------|---------|
  |Левая рука       |Лу́ка     |Шуйца    |
  |Правая рука      |Пру́ка    |Десница  | 
  
  У обоих систем логичные обоснования. Система optozorax'а основана на сокращениях (*л*евая р*ука*, *пр*авая р*ука*), а система bouncepaw'а использует слова, которые в языке существуют давно ([десница](https://ru.wiktionary.org/wiki/десница) и [шуйца](https://ru.wiktionary.org/wiki/шуйца)). Система bouncepaw'а используется в чате гораздо дольше, но optozorax предлагает провести естественный отбор. Проводим.

* `Кластер` — набор клавиш, нажимаемых одним пальцем одной руки. Синоним: `зона`. У каждого кластера есть названия: `тамбкластер`, `указкластер`, `средкластер`, `безымкластер`, `мизкластер`. Слово `тамбкластер` — самое старшее из всех.
* `ЙМК` (`ЯМК`) &mdash; QMK.
* `Сканкод` &mdash; код клавиши, который отправляет клавиатура.
* `Кикод` &mdash; 
  1. код клавиши, используемый ОС (может не совпадать со сканкодом),
  2. код клавиши, используемый ЙМК (совпадает со сканкодом, но можно создать свой, несовпадающий кикод).
* `Кл` &mdash; Кладенец.
* `Ак` &mdash; Аккордеонум.
* `Ваки` &mdash; Вакидзаси.
* `Криворядый` — обзывательство для человека, использующего стандартную клавиатуру со смещёнными рядами. Клавиатуры с адекватным смещением для левой руки не считаются.
* `Стаггер` — смещение рядов на клавиатуре. Англицизм от `staggered keys`, [пример использования.](https://ux.stackexchange.com/questions/40390/why-are-keyboard-keys-staggered)
* `Глаз'ОК` — метод создания раскладки, когда не используются никакие сложные математические вычисления, а клавиши просто расставляются на глазок. Активно используется большинством раскладкоделов в нашем чате. Вариант написания: 👁️👌.
* `Мод`, `модификатор` — клавиша-модификатор.
  * `Shift`/`Шифт`
  * `Alt`/`Альт`, `Meta`/`Мета`
  * `Ctrl`/`Ктрл`, `Control`/`Контрол`
  * `Win`/`Вин`, `Cmd`/`Кмд`, `Super`/`Супер`
  * `Hyper`/`Гипер`
* `Quasi` (`Квази`) — модификатор, заменяющий все остальные модификаторы и слои. Реализована в Кладенце. [Статья](http://ibnteo.klava.org/keyboard/quasi).
* `Астра` — слоефикатор, снимающий функцию символьных слоёв с Квази и забирающий её на себя. Способен вводить символы, находящиеся в другой ораске. Реализован в [Секире](https://github.com/bouncepaw/sequira/blob/master/litsrc/keymap.c.md#keymap).
* `Квазимоды` &mdash; модификаторы, удерживаемые в нажатом состоянии одной кнопкой Quasi
* `Слоефикатор` — клавиша переключения слоя (не различает переключения TG и MO).
  * TG включение слоя — когда нажал кнопку один раз и слой остается включенным всё время. При нажатии этой кнопки снова слой выключается. Аналогично действию Caps Lock.
  * MO включение слоя — когда слой включён только когда клавиша зажата. Аналогично действию Shift. Оба названия взяты из QMK.
* `СК` — Стандартная Клавиатура.
* `Шайзеклава` — СК, образовано от немецкого слова "шайзе" - дерьмо.

  Критерии шайзеклавы от optozorax'а:
    * Имеет смещение рядов вида `\\` (или `//` в особо запущенных случаях)
    * Не знает о слоях сложнее `FN+F1 = Volume Up` (вследствие чего появляются блоки стрелок, нумпад, блок F-клавиш)
    * Не имеет как минимум `3` кнопки на каждый тамб
      * Клавишу Alt с обоих сторон на СК с натягом можно назвать тамбовой клавишей, а вот клавиши Win, Menu не считаются принадлежащими тамбу, потому что они находятся слишком далеко от домашней позиции.
 
  Если выполнено пунктов из этого списка:
    * 0 - хорошая клава
    * 1 - сложный случай, надо думать отдельно
    * 2 - шайзе
    * 3 - абсолютное шайзе
* `Монотайп` — аккордовая клавиатура, которая за один аккорд пишет только один символ. Пример: вакидзаси.
* `Политайп` — аккордовая клавиатура, которая за один аккорд может написать несколько символов. Пример: кладенец.
* `Стенотайп` — очень сложные аккордовые клавиатуры, позволяющие писать со скоростью речи. Требуют многие годы для освоения. Мы их не очень любим.
* также нужен термин для клавиатур, которые монотайпы, но не аккордовые.
* `Дискорд` — сочетание клавиш на дискордовой клавиатуре. Дискорд = простая клавиша + любое количество иефикаторов. 
* `Дискордовая клавиатура` — клавиатура, целиком построенная на использовании дискордов. К ним относятся все СК и большинство эрго. 
* `Полуаккордовая клавиатура` — дискордовая клавиатура, но есть ряд часто используемых монотайповых аккордов. 
* `Фирмварная раскладка`, `фираска`, `прокладка` — раскладка со стороны клавиатуры.
* `Операционная раскладка`, `ораска` — раскладка со стороны ОС.
* `Залипающий шифт` — такой шифт, после единичного нажатия которого, он применяется к следующей клавише. Может использоваться для увеличения удобства обычного набора, или для набора больших букв на клавиатурах, где не получается одновременно зажать шифт и клавишу (например, на клавиатуре телефона).
* `Кнопка Leap` — кнопка инкрементального поиска в заданном направлении. В Canon Cat было две таких кнопки под пробелом: `←Leap` и `Leap→`, ищущие текст назад и вперёд по документу.
* `Монотайпность` — свойство аккордовой клавуатуры уметь набирать только один кикод за один акорд. См. `монотайп`. Если некоторые аккорды на клавиатуре запрограмированы на ввод нескольких символов (макрос), то это ещё не делает клавиатуру политайповой. См. Вакидзаси. 
* `Политайпность`, `полисимвольность` — свойство аккордовой клавиатуры уметь набирать несколько кикодов за один аккорд. См. `политайп`. 
* `Полиаккордовость` — свойство аккордовой клавиатуры уметь вводить сразу несколько аккордов за раз. Классический пример: оригинальный кладенец с двумя идентичными зонами аккордов. Если каждая зона монотайповая, то полиаккордовость позволяет вводить несколько символов за раз (посредством такого слитного аккорда), делая клавиатуру полисимвольной.