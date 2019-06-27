# true()

Функция **`true`** возвращает тождественную "истину".

## Синтаксис

### XPath 1.0

```
boolean true()
```

## Описание и примеры

В XPath нет констант и, тем более, логических констант, определяющих "истину" и "ложь", как в других языках. Функции `true` и [`false`](/xpath/false/) восполняют эту нехватку.

### Пример

```
true() or $var ? true
```

Это выражение всегда будет истинным вне зависимости от значения переменной `var`, поскольку дизъюнкция (логическая операция "или") с тождественной "истиной" всегда будет "истиной".

## Ссылки

- [true()](https://developer.mozilla.org/en-US/docs/Web/XPath/Functions/true) на MDN