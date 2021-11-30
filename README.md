#### Задача:
  Спроектувати сервіс, який по заданому шляху побудує дерево до заданого файлу/папки.
  Структура файлів/папок зберігається в заданому сховищі.
#### *
  - Дотримуватись правил фоматування (`eslint`)
  - Написати тести
  - Написати `Dockerfile`
#### **
  - Спроектувати з перспективою редагування структури дерева
#### ***
  - Спроектувати з можливістю міграції на інший тип сховища
#### Вхідні дані:
  Рядок, який містить шлях до файла/папки, наприклад:
  `/usr/bin/applications/myStuff.cfg`

  Інтерфейс роботи з вхідними даними довільний.
#### Вихідні дані:
  - якщо вказані файл/папка існують:
    - Дерево вигляду
      ```
      -usr
      |
      --bin
        |
        --applications
          |
          --myStuff.cfg
      ```
    - Вкладеність повинно бути видно
    - Потрібно розрізняти файл і папку
  - якщо такого файлу/папки немає:
    Повертати помилку.

  Спосіб відображення результату роботи довільний.
#### Технології:
  - MySql для зберігання
  - Бінарні дерева
  - Рекурсія

#### Планування:
  Після оцінки завдання прохання оцінити, скільки часу знадобиться на його виконання
