34. Напиши наступні SQL команди (Не користуйся MySQL):
    a) Є уявна таблиця Workers (id. name, hireDate(дата найму), profession). Дістати всіх Тестувальників з таблиці Workers, відсортувати за датою найму
    b)Дістати 5 останніх найнятих Тестувальників з таблиці Workers

Розв'язання:
a) SELECT \* FROM Workers WHERE profession = "Тестувальник" ORDER BY hireDate ASC;
b) SELECT \* FROM Workers WHERE profession = "Тестувальник" ORDER BY hireDate DESC LIMIT 5;
