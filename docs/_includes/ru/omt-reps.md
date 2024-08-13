# Работа с повторами

Некоторые сегменты в проекте могут **повторяться**. По умолчанию перевод, введенный в одном из повторяющихся сегментов, **используется автоматически** во всех повторах.

## Определение повторяющихся сегментов

Определить, является ли текущий сегмент повторяющимся, можно по тому, что область **Segment Properties** (Свойства сегмента) будет содержать поле **isDup** со значением `FIRST` для первого сегмента в группе повторов и `NEXT` для всех последующих.

<!-- @todo: in the navigation across panes add segment properties -->
<!-- @todo: update "navigation across panes" > "navigation through panes" -->

![](../_img/repetition-with-labels.png)

<!-- ![](../_img/15_repeated_segment.jpg) -->

<!-- @todo: harmonize font size across all screenshots and gifs -->

Кроме того, маркер текущего сегмента, в котором отображается его номер, также содержит информацию о том, сколько повторов имеется у текущего сегмента.

Второй и все последующие повторы выделяются серым шрифтом, благодаря чему можно определить, что такие сегменты повторяются в проекте.

<!-- @todo: repetitions in black and gray font -->

Если **щелкнуть правой кнопкой мыши** по повторяющемуся сегменту, в контекстом меню будет список всех его повторов. Он дает возможность перейти к другим повторам (для этого нужно выбрать соответствующий пункт контекстного меню). Таким образом вы можете просмотреть контекст, в котором повторяющийся сегмент используется в проекте.

![](../_img/16_repeated_context.jpg)

## Автоматическое использование переводов

При редактировании перевода повторяющегося сегмента следует помнить о том, что как только изменения будут сохранены, они автоматически отобразятся во всех повторах сегмента в проекте.

![](../_img/17_autopropagation.jpg)

## Создание альтернативного перевода

В некоторых случаях перевод повторяющегося сегмента должен быть разным в зависимости от контекста. В такой ситуации возникает необходимость изменить перевод только в одном из повторов, не меняя при этом перевод всех остальных.

Другими словами, вам необходимо создать **вариант перевода** (или альтернативный перевод), который не будет _распространяться автоматически_ на все остальные повторы.

Для создания **альтернативного перевода** выполните следующие действия:

1. _Щелкните правой кнопкой мыши_ по текущему сегменту и выберите пункт контекстного меню **Create Alternative Translation** (Создать вариант перевода).
<!-- ![](../_img/18_create_alternative_translation.jpg) -->
2. Отредактируйте перевод текущего сегмента.
3. Нажмите ++ctrl+s++ для записи альтернативного перевода.
   <!-- ![](../_img/19_alternative_translation_created.jpg) -->
   <!-- @todo: use the example from the slides -->

В области **Multiple Translations** (Варианты перевода) будут показаны варианты перевода текущего текста оригинала.

Вкратце процесс создания альтернативного перевода выглядит так:
![](../_img/create-alternative-translation-in-3-steps.gif)

<!-- @todo for Danina: repeat video, Ctrl+S for every segment! -->

<!-- prettier-ignore -->
!!! danger "Опасность"
    Альтернативные переводы могут оказаться коварными при неправильном применении. Если вам нужно создать альтернативный перевод, точное выполнение трех описанных выше шагов является обязательным.

В следующем видео показано, как создавать альтернативные переводы. Приятного просмотра :octicons-heart-fill-24:{ .heart }.

<div style="padding:60% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/789832289?h=5fd29f998e" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<!-- prettier-ignore -->
!!! warning "Предупреждение"
    Если перевод сегмента уже является альтернативным, то создать альтернативный перевод такого сегмента будет невозможно. В приведенном ниже разделе описано, как определить, является ли перевод текущего сегмента альтернативным.

Если необходимо изменить существующий альтернативный перевод, просто отредактируйте его и сохраните изменения (++ctrl+s++).

## Определение альтернативных переводов

Определить, является ли перевод текущего сегмента альтернативным, можно следующим образом:

Во-первых, если сегмент содержит альтернативный перевод, в области **Segment Properties** (Свойства сегмента) будет содержаться поле **isAlt** со значением `true`. Это поле будет мигать оранжевым при переходе к такому сегменту или при сохранении проекта, если такой сегмент будет в этот момент активным.

![](../_img/omt-alt-prop-flash.png)

Во-вторых, в области **Multiple Translations** (Варианты перевода) будут отображаться варианты перевода и контекст, к которому они привязаны (обычно альтернативные переводы привязаны к имени файла и дополнительным идентификаторам, например ID или ключу сегмента).

![](../_img/omt-alt-multiple-pane.png)

И наконец, наиболее выразительно наличие альтернативного перевода видно по тому, что вы не сможете выбрать пункт **Create Alternative Translation** (Создать вариант перевода) в контекстом меню сегмента или в меню **Edit** (Правка), так как он будет неактивным.

![](../_img/omt-alt-grayed-out.png)

## Восстановление перевода по умолчанию

Если по какой-то причине существующий альтернативный перевод стал ненужным, и вы хотите, чтобы перевод сегмента стал таким же, как в других повторах, проще всего просто удалить текущий вариант перевода. Для этого выполните следующие простые шаги:

- Перейдите к сегменту, в котором вы хотите восстановить перевод по умолчанию
- Нажмите сочетание клавиш ++ctrl+a++, чтобы выбрать весь переведенный текст
- Нажмите клавишу ++del++, чтобы удалить перевод
- Нажмите сочетание клавиш ++ctrl+s++ для сохранения изменений или перейдите к другому сегменту, чтобы восстановить перевод по умолчанию