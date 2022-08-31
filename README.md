# Альпако календарь

Собранный календарь и демонстрационная страница находится в `build` директории.   
[Исходники](https://www.figma.com/file/DLwhuW5j2IqVCNcDFaWjno/Untitled?node-id=0%3A1)   
[ТЗ](https://drive.google.com/file/d/18wNojV97xoM8eX0camvLsyFmMGeEpida/view)   

## Кастомизация
В `src/scss/alpako.scss` добавлено несколько переменных, определяющих вид календаря:   
* `$border-radius` - внешнее скругление краев всего календаря;
* `$inner-padding` - внутренний отступ дней календаря;
* `$active-day-outer-inset` - размер внешнего отступа выделения активного дня;
* `$active-day-inner-inset` - размер внутреннего отступа выделения активного дня;

## Сборка
* pug-компиляция: `pug src/pug/index.pug --pretty -o ./build/`
* sass-компиляция: `sass src/scss/alpako.scss build/alpako.css`
