# задание weather.app

1. `https://get.geojs.io/v1/ip/geo.json`
киньте fetch по адресу и получите данные по широте, долготе и городу (latitude, longitude, city)

2. сделайте fetch запрос по адресу:
`https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&current_weather=true` -  вам нужно заменить координаты в строке на данные выше (вместо 52.52 и 13.41 должны приходить данные из первой API). Получите данные погоды: температуру, скорость ветра и.т.д
также заберите weathercode - он вам понадобится

3. напишите функцию расшифровщик для кода погоды
информацию возьмите в документации `[api.open-meteo.com](https://open-meteo.com/en/docs)`
выведите данные на странице, используйте current_weather_units
для расшифровки можно использовать синтаксис if / else или switch / case `https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch`

4. используйте лоадер из классной работы или любой другой
поставьте setTimeout на 1.5 сек, чтобы лоадер подольше крутился.

5. добавьте стили по вкусу

6. задеплойте на git pages в отдельном репозитории и пришлите мне ссылку на него
