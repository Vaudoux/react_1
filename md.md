# 1
const now = new Date().toLocaleTimeString();

Создать функциональный компонент CurrentTime, который будет отображать текущее время, форматированное в удобочитаемом виде (например, "Текущее время: 14:35").
Использовать объект Date для получения текущего времени и метод toLocaleTimeString() для его форматирования.
Импортировать компонент CurrentTime в App.js и использовать его внутри компонента App, чтобы отобразить текущее время на странице.
Добавить минимальную стилизацию для компонента CurrentTime, чтобы выделить отображаемое время (например, использовать <h2> для заголовка и немного CSS для улучшения внешнего вида).

# 2
Создать функциональный компонент EventCard, который будет отображать информацию о событии: название, дату и место проведения. Компонент должен принимать эти данные через пропсы.
В компоненте App, использовать компонент EventCard несколько раз с различными данными о событиях, переданными через пропсы, чтобы показать список предстоящих событий.
Добавить минимальную стилизацию для компонента EventCard, используя CSS классы, чтобы визуально выделить информацию о каждом событии.

# 3
if (hour < 12) {
greeting = 'Доброе утро';
new Date().getHours()