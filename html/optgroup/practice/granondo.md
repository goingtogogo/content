🛠 У тега `<optgroup>` не очень много вариантов стилизации, мы можем изменить фон и параметры текста. В зависимости от браузера и операционной системы стили работают по-разному. Или не работают вообще 😕

✅ — меняется, ⛔ — не меняется:

**Windows**

| Браузер        | Текст | Фон |
| -------------- | ----- | --- |
| Chrome         | ✅     | ✅   |
| Safari         | ✅     | ✅   |
| Opera          | ✅     | ✅   |
| Edge           | ✅     | ✅   |
| Firefox        | ✅     | ✅   |
| Yandex Browser | ✅     | ✅   |

В Safari и Firefox выделяется только заголовок, к остальному списку стили не применяются.

**macOS**

| Браузер        | Текст | Фон |
| -------------- | ----- | --- |
| Chrome         | ⛔     | ⛔   |
| Safari         | ⛔     | ⛔   |
| Opera          | ⛔     | ⛔   |
| Edge           | ✅     | ✅   |
| Firefox        | ✅     | ⛔   |
| Yandex Browser | ⛔     | ⛔   |

При этом, пока мы не выберем список, во всех браузерах и операционных системах он идёт стандартного серого цвета, для изменения стиля списка вам потребуется стилизовать тег [`<select>`](/html/select/).

Демо ниже поможет понять, поддерживаются ли стили в вашем браузере и операционной системе. Если текст заголовка группы не оранжевого цвета, а фон у него не чёрный, то поддержки нет.

<iframe title="Стилизация <optgroup>" src="../demos/styles/" height="350"></iframe>
