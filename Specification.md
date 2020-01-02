# Техническое задание
## [Проект - Fitness](Readme.md)
### Общие технические требования
1. Стандарты вёрстки: HTML5, CSS3, прогрессивное улучшение.
2. Сетка: определена в макете.
3. Раскладка блоков на странице делается с помощью флексбоксов.
4. Адаптивность сетки: мобильная, планшетная и десктопная версии. **Desktop First.** На всех промежуточных разрешениях используется резиновая вёрстка. 
5. Используемая методология: БЭМ.
6. Используемые фреймворки: нет.
7. Используемый препроцессор:  Sass (SCSS).
8. Используемый инструмент автоматизации: Gulp. [https://github.com/tsergeytovarov/gulp-template](https://github.com/tsergeytovarov/gulp-template)
9. Кроссбраузерность: Chrome, Firefox, Safari, Edge, Internet Explorer 11.
10. Графика не предоставляется и её необходимо вырезать самостоятельно.  Правила работы с Figmа тут — [https://htmlacademy.ru/blog/useful/figma](https://htmlacademy.ru/blog/useful/figma)
11. Нестандартные шрифты подключены локально. Скачать можно с Google Fonts — [https://fonts.google.com/](https://fonts.google.com/)
12. JavaScript по желанию (Минимальная реализация, модальные окна, переключения и так далее)

### Пояснения по макету
1. Необходимо выполнить верстку одной страницы с адаптивностью. Десктопная, планшетная и мобильная версии.
2. Брейкпоинты : 
  - мобильная версия — 320px - 767px;
  - планшетная версия — 768px - 1199px;
  - десктопная версия — от 1200px и выше
3. При клике на "Купить абонемент" скролл страницы до раздела Абонементы. Реализация через JavaScript по желанию. 
  ![https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fccd96a69-c6b6-44cf-839c-c200de83d6e5%2F1._Header.png?table=block&id=c258a40c-86ee-4e65-9f1c-619a0c565a5e&width=1680&cache=v2](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fccd96a69-c6b6-44cf-839c-c200de83d6e5%2F1._Header.png?table=block&id=c258a40c-86ee-4e65-9f1c-619a0c565a5e&width=1680&cache=v2)

4. В разделе "Абонементы" блоки при наведении меняют свои размеры и оформление. Кнопка "Купить абонемент" ведет на потенциальную страницу, которой нет в макете.
  ![https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fd5cdf464-a571-4a4b-8430-8abcfcb08cc3%2F2._abonement.png?table=block&id=888fbf02-6d3f-4899-bb12-153645d66eae&width=1600&cache=v2](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fd5cdf464-a571-4a4b-8430-8abcfcb08cc3%2F2._abonement.png?table=block&id=888fbf02-6d3f-4899-bb12-153645d66eae&width=1600&cache=v2)

5. Кнопка "Заполнить заявку" ведет на потенциальную страницу, которой нет в макете.
  ![https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F21626d33-7a30-4cd7-891d-eb605d580b91%2Fpromo.png?table=block&id=aeba6ed8-55b9-4516-9f80-60d259d125ef&width=1590&cache=v2](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F21626d33-7a30-4cd7-891d-eb605d580b91%2Fpromo.png?table=block&id=aeba6ed8-55b9-4516-9f80-60d259d125ef&width=1590&cache=v2)

6. Блок "Тренеры" - это слайдер, который меняет сразу по четыре тренера. При наведении на преподавателя появляется информация о нем. В планшетной версии слайдер меняет по  два тренера, в мобильной — по одному. Вёрстка минимум восьми слайдов - обязательна. Слайды можно сделать одинаковыми. Реализация слайдера через JavaScript по желанию. 
  ![https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa1da1950-c5a1-44ef-8766-38ee5b0cee79%2Fslider1.png?table=block&id=aef737c4-8cae-445b-a73f-f561f83ff577&width=1710&cache=v2](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa1da1950-c5a1-44ef-8766-38ee5b0cee79%2Fslider1.png?table=block&id=aef737c4-8cae-445b-a73f-f561f83ff577&width=1710&cache=v2)

7. Блок "Отзывы" — это слайдер. Вёрстка минимум двух слайдов - обязательна. Слайды можно сделать одинаковыми. Реализация слайдера через JavaScript по желанию.
8. Интерактивное расписание - выполняется отдельной страницей.  Реализация через JavaScript. ***Вёрстка и реализация интерактивного расписания по желанию исполнителя.***
    - При наведении на занятие подсвечивается соответствующий день и время.
    - В планшетной версии предусмотрена полоса прокрутки влево-вправо по дням недели.
    - В мобильной версии день выбирается из выпадающего списка.
