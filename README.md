# homeWorkItK01-08
Doing homework from the IT-KAMASUTRA 'js с нуля, ваще с нуля' 01-08

Задачи:
$1-вывести в консоль значения атрибута class для найденного  firstNameEl

$2-добавьте в разметку HTML ещё 2 инпута для lastName (фамилия) и адреса

$3-заполните value в самом HTML своими данными для этих инпутов.

$4-попросите выведите в консоль эти value с помощью JS

$5-добавьте в html тег select, в качестве опций (option) которого сделайте список городов: moscow, minsk, kiev

$6-для option со значением 'minsk' добавьте атрибут selected (минск будет сразу выбран\селектнут в этом списке)

$7-найдите этот select с помощью JS и выведите в консоль его value 
(обратите внимание, что атрибута value у самого тега select внутри html не существует, но у его "души", найденной через js, такое свойство есть, и оно будет равно тому value той option, которая будет выбрана в момент считывания этого значения)

$8-Обратите внимание, что у вложенных в select тегов option могут быть, а могут и не быть атрибуты value
Если он есть, то значением выбранной опции будет считаться значение этого атрибута. Ниже значением будет ‘m’

<option value='m'> Minsk </option>

Если его нет - значением будет innerHTML данной опции (текст между открывающимся и закрывающимся тегами:

           <option> вот я есть значение </option>

Поиграйтесь так со списком городов

$9-Добавьте на страницу textarea, заполните его внутренность (в самом html файле, то, что между открывающим и закрывающим тегом textarea) (оно же innerHTML) коротким предложением, перечислив свои хобби.

$10-Найдите c помощью JS этот textarea на странице и выведите в консоль его value с помощью (обратите внимание, что атрибута value у тэга textarea не существует, но у его "души"-объекта, найденной через js, такое свойство есть и оно равняется тексту, введённому между тегами

$11-Выведите в консоль innerHTML найденного раннее textarea.

Делаем вывод, что:
textarea.innerHTML === textarea.value

innerHTML - это содержимое между открывающим и закрывающимся тегом

$12-Добавьте на страницу div, внутри него картинку, атрибут src которого равен ссылки на вашу аватарку в ВК (можно в ВК кликнуть правой кнопкой по элементу и выбрать inspect element). Результат: мы видим картинку =)

$13-Найдите этот div с помощью JS и в консоль выведите его значение value. Что видим? undefined? Делаем вывод: ни у тега div в разметке, ни у его "души"-объекта в JS нет свойства value

$14-Запомните!!! value есть только у элементов, с помощью которых пользователь может вводить какие-то данные (впечатывать, выбирать) с UI: input, select, textarea

$15-выведите в консоль сво-во innerHTML у найденного дива (что-то типа someElement.innerHTML, по аналогии someElement.value)

Вообще что такое “сво-во”? то что пишется после точки у найденного элемента. Как правило название свойства соответствует названию атрибута, то есть
у элемента мы можем прочитать:

el.id
el.value
el.style
el.name
el.selected (для option)
el.checked (для input c type=checkbox)
el.src и так далее...

$16-отобразите в консоли innerHTML найденного ранее тега select.
Видим, что содержимое выводится как текст (внутри - теги, но мы видим их как текст)

найдите добавленную ранее img и выведите в консоль её св-во src  и alt (добавьте атрибут alt для картинки)
