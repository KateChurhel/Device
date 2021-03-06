# Личный проект: Девайс

* Студент: [Екатерина](https://up.htmlacademy.ru/htmlcss/21/user/11431).
* Наставник: [Наталья Майстренко](https://htmlacademy.ru/profile/natalie).

---

## Техническое задание: Девайс

* Название сайта: Девайс
* Домен: пока нет

---

### 1. Общие технические требования
* 1.1. Стандарты вёрстки: HTML5, CSS3, прогрессивное улучшение.
* 1.2. Сетка: определена в макете.
* 1.3. Адаптивность вёрстки: нет.
* 1.4. Используемые фреймворки: нет.
* 1.5. Кроссбраузерность: IE11+, Edge, Chrome, Firefox, Opera, Safari.
* 1.6. Типографика: частично определена в макете (прочее — на усмотрение разработчика).
* 1.7. Используемые шрифты: Gilroy, Open Sans (есть в папке с макетом и на WebFont.ru).
* 1.8. С макетом предоставлен styleguide.psd, содержащий прорисовку состояний элементов интерфейса. При любых расхождениях с макетами он должен иметь наивысший приоритет.

### 2. Пояснения для учащихся
* 2.1. В макетах есть скрытые слои с всплывающими окнами. Такие слои в блоке слоёв фотошопа выделены синим цветом.
* 2.2. Макеты верстаются постепенно, не нужно сразу выполнять все требования.
* 2.3. Ниже в разделе «Обязательные требования» описано поведение блоков, которое должно быть реализовано для получения допуска. Требования из раздела «Дополнительные требования» можно реализовать по желанию для выполнения дополнительных критериев.

### 3. Обязательные требования
* Все макеты:
  * 3.1. Контентная область центрируется и не может быть уже макетной ширины.
  * 3.2. Авторизованному и неавторизованному посетителю показывается разный вид блока авторизации (смотрите device-catalog.psd и device-index.psd).
  * 3.3. В блоке авторизованного посетителя имя и иконка пользователя являются ссылкой на профайл.
  * 3.4. Логотип Академии в подвале ведёт на лендинг интенсива «Профессиональный HTML и CSS, уровень 1».
* device-index.psd:
  * 3.5. Блоки с названиями разделов («виртуальная реальность», «моноподы для селфи», ...) являются ссылками на разделы каталога.
  * 3.6. Промо-слайдер: слайдер. Вёрстка всех слайдов обязательна. Оживление слайдера необязательно, принцип оживления описан в 4 разделе.
  * 3.7. Блок «Сервисы» («доставка», «гарантии», «кредит»): слайдер. Вёрстка всех слайдов обязательна. Оживление слайдера необязательно, принцип оживления описан в 4 разделе.
  * 3.8. Блок карты — достаточная реализация — обычное изображение, клик по ней приводит к переходу на сервис карт.
  * 3.9. Вёрстка модального окна обязательна (смотрите папку слоёв «write us»).
* device-catalog.psd:
  * 3.10. Логотип — это ссылка на главную страницу.
  * 3.11. Фильтр: верстать с помощью формы, кнопка «Показать» отвечает за отправку формы.
  * 3.12. Блок «Стоимость» — при наведении на любой из маркеров появляется указатель cursor: pointer, делать маркеры подвижными не обязательно, цена меняться не должна.
  * 3.13. При наведении на карточку товара появляются кнопки «В корзину» и «Добавить к сравнению» (смотрите styleguide.psd). Ссылкой на отдельную страницу товара является только название товара (отдельную страницу верстать не нужно).
  * 3.14. Количество товаров в правом блоке может быть любым, добавление товаров не должно ломать страницу.
  * 3.15. У любого товара может быть метка «new».

### 4. Дополнительные требования
* device-index.psd:
  * 4.1. Промо-слайдер: оживление слайдера. Смена слайдов в слайдере должна происходить мгновенно, без промежуточных состояний и анимации (некоторые слайды скрыты - смотрите слои выделенные красным цветом).
  * 4.2. Блок «Сервисы» («доставка», «гарантии», «кредит»): оживление слайдера. Слайдер с табами работает аналогично промо-слайдеру: по клику на таб меняется слайд мгновенно.
  * 4.3. Блок карты — реализация по желанию — часть интерактивной карты, клик на неё приводит к появлению полного размера интерактивной карты (смотрите папку слоёв «map hover»), окно позиционируется относительно вьюпорта, а не страницы.
  * 4.4. При клике по кнопке «Напишите нам?..» возникает модальное окно (смотрите папку слоёв «write us»), окно позиционируется относительно вьюпорта, а не страницы.
* device-catalog.psd:
  * 4.5. Фильтр: по нажатию кнопки «Показать» осуществляется отправка формы.

---

## Критерии оценивания

---

### Базовые критерии

#### Разметка
* Б1. Выполнена HTML-разметка всех страниц и всех элементов на страницах.
* Б2. К страницам подключён один стилевой файл (с учётом normalize.css к каждой странице могут быть подключены два стилевых файла).
* Б3. Стилевой файл подключён внутри <head>.
* Б4. Грубые ошибки в разметке отсутствуют.
* Б5. Документ проходит проверку на валидность http://validator.w3.org/nu/.

#### Стилизация
* Б6. Вся собственная стилизация выполнена в одном стилевом файле.
* Б7. Раскладка блоков на странице сделана с помощью флексбоксов.
* Б8. В CSS отсутствует !important.
* Б9. Подключены правильные шрифты, их размеры, высота строк, цвет и толщина равны соответствующим параметрам в макетах и техническом задании.
* Б10. Указаны альтернативные варианты шрифта и тип семейства в конце перечисления font-family.
* Б11. При наполнении контентом (как в макете) элементы каждой страницы соответствуют макету.

#### Тестирование
* Б12. Вёрстка идентично отображается в последних версиях браузеров Chrome, Opera, Firefox, Safari, Edge, а также в Internet Explorer 11+.
* Б13. Сайт нормально смотрится на минимальной для макета ширине.

#### Разное
* Б14. В корне проекта имеются папки css, img, js или аналогичные. Главная страница имеет название index.html. В названиях и расширениях файлов нет заглавных букв и пробелов, использованы только латинские символы.
* Б15. Единообразное написание и форматирование кода в HTML, CSS и JavaScript.
* Б16. Выбран подходящий формат изображений.
* Б17. Проект соответствует техническому заданию

### Дополнительные критерии

#### Разметка
* Д1. У всех изображений в теге <img> прописан размер.
* Д2. Использовано минимально возможное количество HTML-элементов (нет лишних элементов).
* Д3. Все скрипты подключены непосредственно перед </body>.
* Д4. Названия полей форм привязаны к своим полям с помощью <label>.

#### Стилизация
* Д5. Использован normalize.css.
* Д6. Для стилизации не использованы #id.
* Д7. Нет вложенности селекторов больше двух.
* Д8. При использовании блочно-строчных элементов явно указывайте вертикальное выравнивание
* Д9. Для CSS-свойств с префиксом указан его вариант без префикса, и это указание идёт последним.
* Д10. Для блока, у которого есть фоновое изображение, прописан фоновый цвет, который соответствует преобладающему цвету изображения (пока изображение не загружено, страница выглядит похоже на макет).
* Д11. Все состояния элементов (смотрите styleguide.psd) прописаны в стилевом файле.
* Д12. Стилизация нестандартных элементов форм.
* Д13. Файл стилей представлен в двух вариантах: с форматированием и минимизированный, к странице подключён минимизированный.
* Д25. Нет глобальных стилей тегов.

#### JavaScript
* Д14. Собственные скрипты собраны в отдельном JavaScript-файле, который подключён в HTML перед закрывающим тегом body.
* Д15. JavaScript-файл представлен в двух вариантах: с форматированием и минимизированный, к странице подключён минимизированный.
* Д16. С помощью JavaScript реализовано открытие/закрытие окна с формой (без вспомогательных библиотек).
* Д17. С помощью JavaScript добавлена анимация формы (без вспомогательных библиотек).
* Д18. Добавлена интерактивная карта (допускается подключение с помощью iframe).

#### Тестирование
* Д19. Вёрстка проходит тест на переполнение контентом.

#### Доступность
* Д26. У интерактивных элементов при нажатии или фокусе с клавиатуры есть активное состояние.
* Д27. Все интерактивные элементы имеют текстовое описание.

#### Разное
* Д20. Критическая функциональность сайта работоспособна без JavaScript (использовано прогрессивное улучшение).
* Д21. Отсутствует транслит в названиях классов, атрибутах, названиях файлов и так далее.
* Д22. При взаимодействии с элементами (наведение, нажатие) ни сам элемент, ни окружающие его блоки не меняют своего положения (если иное не прописано в техническом задании или styleguide.psd).
* Д23. Проведена базовая оптимизация: минифицированы стили и скрипты (при наличии).
* Д24. Страницы должны ссылаться друг на друга из главного меню.
