33. Напиши наступні SQL команди (Не користуйся MySQL):
    a) Витягнути номер телефону та адресу користувача Muzik.
    b)Дістати всіх користувачів, в кого ім’я закінчується на А
    c)Витягнути дані про користувачів, які мають суму замовлення понад 2000 грн.
    d) Підрахувати кількість замовлень у таблиці
    e)Підрахувати загальну суму зроблених замовлень.
    Картинка: https://drive.google.com/file/d/11-sIJRM8mwS9KCoNzk5SKBdZiB74Z7lY/view

Розвя'язання:
a) SELECT phone, address FROM USER WHERE name = "Muzik";
b) SELECT \* FROM USER WHERE name LIKE "%А";
c) SELECT \* FROM USER JOIN ORDER ON Id = user_id WHERE sum > 2000;
d) SELECT COUNT(Id) FROM ORDER;
e) SELECT SUM(sum) FROM ORDER;
