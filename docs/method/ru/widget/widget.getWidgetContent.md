widget.getWidgetContent

$description
Метод возвращает содержимое одного виджета как обычный HTTP-ответ.

$params#wid
Идентификатор виджета

$params#style
Стиль виджета

$additional
См. [мобильные виджеты](/dev/sdk/js-ext/widgets)

Содержимое и параметры виджета могут зависеть от состояния сессии.

Для возвращения нескольких методов сразу см. {% replace_method widget.getWidgets %}.

Виджет возвращается, закодированный в формате Base64. Пример обработки:

{% format_code OKSDK.Util.decodeUtf8(atob(widget) %}