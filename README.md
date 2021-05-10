Вариантов как отобразить таблицу в мобильной версии может быть несколько. Самое простое оставить как есть, тогда у пользователя появится горизонтальный скролл. Ваариант простой, но не удобный. Можно подумать над тем что бы сделать таблицу интерактивной, но как по мне, для простой таблицы получается довольно трудозатратно. Я предлагаю вариант при котором каждая строка отображается друг под другом и соорентированна колонкой. Пользователю не придется далеко листать (при условии что таблица не будет сильно разрастаться). Реализуется достаточно просто благодаря Flexbox.
С читаемостью текста я вижу несколько проблем. Во первых он разного размера, во вторых ориентирован по разному (где то по центру а где то по правому краю) и третье, текст липнет к краям контейнера. Соответственно я предлагаю следующее: во первых задать ячейке не фиксированную высоту а минимальную, тем самым весь текст поместится, а благодаряя флексам ячейки будут выровнены. Далее мы можем установить единый размер шрифта. И третье это выровнять весь текст например по центру.
Таблица сверстана и представлена с учетом трбования улучшить читаемость текста. Есть закоментированный код который изначально отвечает за отображение таблицы в исходном виде.
