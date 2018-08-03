# pureJSCalendar
Simple and clean JS Calendar solution for those who need to get rid of third-party libraries like JQuery. Easily localizable calendar with allowed date spread and with the first day of the week selection.

The calendar can be simply opened by adding a line:
pureJSCalendar.open(dateFormat, x, y, firstDayOfWeek, minDate, maxDate, element, zindex)

Exaple:
pureJSCalendar.open('dd.MM.yyyy', 20, 30, 1, '2018-5-5', '2019-8-20', 'txtTest', 20)

The calendar can be simply closed by adding a line:
pureJSCalendar.close();
