# Основное
Данная модификация является пре-бета версией игры "Dangerous Dave in the Haunted Mansion: Modification Edition". Код переписан с нуля, ресурсы взяты оригинальные.

Фактически данная игра является конструктором аркад, который даёт множество новых возможностей. На данный момент можно оценить только два уровня из оригинальной игры в связи с отсутствием написанного интеллекта для монстров, которые появляются с 3-го уровня.

# Нюансы
В версии pre-beta 0.4 с версии pre-beta 0.3 было внесено много изменений, в том числе все скрипты интеллекта монстров до 0.3 pre-beta перестали работать, при этом версия pre-beta 0.4 ещё не выпущена. Отсюда при попытке создать модпак для версии 0.3 всё получится, но с версии 0.4 он может не работать. Данная модификация выложена именно в версии pre-beta 0.3.

# Подробности
В данной модификации практически все параметры, а так же все ресурсы вынесены во внешние файлы. Это называется "модпак". Для стандартного Дейва используется модпак "StandartDave" (с версии pre-beta 0.4 опечатка исправлена, и он называется StandardDave). Редактора модпаков, к сожалению, я пока не написал. Таким образом, любые модпаки пока что можно создавать только вручную, для карт же используя сторонний редактор и конвертер в формат модификации. Написать можно практически любой платформер в данном стиле. Например, Марио. К сожалению, пока нельзя выйти за рамки возможностей Dangerous Dave 2 в рамках управления игроком, так как поведение игрока не вынесено во внешние файлы, а "зашито" внутрь бинарника. Интеллект монстров пишется на lua, возможны использования любых ресурсов. Данная программа пока работает только на платформе Windows, но переписыванием библиотеки отрисовки (чем я сейчас потихоньку и занимаюсь) можно достигнуть совместимости с любой платформой, в том числе Android и iOS.

Информацию по тому, что доступно и планируется, можно прочитать в Changes.txt и readme.txt
