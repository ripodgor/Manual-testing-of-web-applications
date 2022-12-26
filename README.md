# Manual-testing-of-web-applications

### [Курсовой проект к модулю "Введение в тестирование"](https://docs.google.com/spreadsheets/d/1pS3h7qK2O5W0-_5njZeLxMBU9UOrDqckcHcgPZPb2cA/edit#gid=0)

#### [Задание](https://github.com/netology-code/iqa-diplom/blob/main/README.md)
#### Задание 1 [```решение```](https://docs.google.com/spreadsheets/d/1-xiAhfRif44yxPjiJaPwo90WscMuJilfVIVAqBwZIr8/edit?usp=sharing)
Написать чек-лист для функциональной проверки [личного кабинета](https://henderson.ru/cabinet/) зарегистированного авторизованного пользователя (включая функционал разделов) на сайте https://henderson.ru/.

Требования к выполнению:

Чек-лист должен представлять собой структурированный (многоуровневый) список, который содержит набор функциональных позитивных и негативных проверок клиентской стороны компонентов объекта тестирования.
При составлении списка проверок должны учитываться различные варианты состояний страниц. Например, при проверке функционала "Мои отзывы" мы проверяем не только состояние без отзывов, но и с ними.
Мы ожидаем от вас список проверок функционала личного кабинета без учета хедера и футера страницы, то есть то, что есть в этой [области](https://drive.google.com/file/d/1rn6z04Erx7QjUmmTm4-R5MNNBgXpRSP2/view).
#### Задание 2
##### 2.1.[```решение```](https://docs.google.com/spreadsheets/d/17Vpalr_lZ9Qw_nAZGss83wr5yfUaP_Oo7aV5RK3SLsM/edit?usp=sharing) 
Необходимо написать набор тест-кейсов на проверку функционала восстановления пароля.

Ваша задача - написать минимум 20 тест-кейсов, которые должны покрывать все, что описано в требованиях по [ссылке](https://docs.google.com/document/d/12deDbATIy0Xps8MiWvumNqHISfAlFc4etY8F4lPcqJ4/edit), и учитывать позитивные и негативные кейсы и включать в себя полные циклы восстановления пароля. Помните, что мы проверяем не только и не столько саму форму, но процесс восстановления с применением техник тест-дизайна. Обратите внимание, что основа для написания тестов - информация в требованиях, а не на реальном сайте + не все требования могут быть реализованы в реальном сайте на данный момент.

##### 2.2.* [```решение```](https://docs.google.com/document/d/1Hjz0sgfptkFCElMjOt4CaQidLIuzYfYKtNk532fQmIk/edit?usp=sharing)
Напишите свои вопросы по данным требованиям - они могут касаться не описанных, но важных сценариев, граничных значений и подобных проблем, по аналогии с ДЗ.

#### Задание 3 
##### 3.1. [```решение```](https://docs.google.com/spreadsheets/d/1Td3OHN_U5_Sx2GCicbpvf1OMcogOm7LdnYgJVbUDEEk/edit?usp=sharing)
На основе [скриншота](https://drive.google.com/file/d/1ucv3JFqEGY7ijVtP0Qn0BrdV2ipqYu37/view) создать не менее трех баг репортов. Обратите внимание, что в данном случае, в окружении мы можем описать тот браузер, с которого проводилась бы проверка, т.е ваш актуальный браузер.

##### 3.2* [```решение```](https://docs.google.com/spreadsheets/d/1AOXj6cVucjn_T1-eI9MLo8zpT-ARn5PmyRH19CV89X0/edit?usp=sharing)(необязательное задание).
Найти баг в функционале "Написать отзыв" в карточке товара и составить на него баг-репорт. Если найдете несколько - замечательно!

#### Задание 4 [```решение```](https://docs.google.com/document/d/113XKT4KvSqjsNDEUUb2E2Ljl8-iBLmkc-VWWJ5nIsCw/edit?usp=sharing)
Вы тестируете страницу карточки товара. Из ТЗ вы знаете, что товар может стоить от 1 рубля до 10 000 000 рублей. К сожалению, на сайте в данный момент товаров с такой ценой нет, а разработчик бекенда в отпуске, поэтому вам нужно протестировать верстку страницы карточки товара с максимальной и минимальной ценой самостоятельно. Ваша задача - самостоятельно определить, как проще это реализовать, и предоставить решение в виде скриншотов страницы (чтобы было видно, с помощью чего вы изменили эту цену) карточки товара с минимальной и максимальной ценой товара.

#### Задание 5 [```решение```](https://docs.google.com/document/d/1CrV44RxIznK7DXvKCbszZQsbAT3aZ8GDQC9G755jb8E/edit?usp=sharing)
Бекенд разработчик говорит, что мы отправляем данные с сайта в неправильном формате и просит вас помочь найти нужный запрос. Фронтенд разработчик ушел в отпуск в поход без связи, а документация пропала.

Известно, что проблема в данных, которые уходят в post запросе по адресу api.mindbox.ru/v3/js/operations/, и происходит это скорее всего при работе с личными данными пользователя (например авторизация, личный кабинет, просмотр корзины).

Ваша задача - изучить ответы и запросы при работе с сайтом; найти, как же выглядят параметры deviceUUID, requestId и status, и приложить скриншот искомого превью в таблицу с решениями.
