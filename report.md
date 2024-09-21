## Лабораторная работа 1

Отчёт по моей лабе

1. Создаю новый файл с именем `script.bash`

```bash
touch script.bash
```

2. Открываю созданный файл `script.bash` для редактирования.

```bash  
gedit script.bash
```

3. Вписываю шебанг

```bash
#!/bin/bash
```

4. Вписывыю главную часть скрипта

```bash
echo "Welcome to ITMO University"
```
  
5. Запускаю скрипт в терминале
```bash
bash script.bash
```

6. Скрипт работает!

 ![Screenshot From 2024-09-21 21-27-22](https://github.com/user-attachments/assets/589bd042-182c-4cee-b3df-ce3390fe9631)

  ![Screenshot From 2024-09-21 21-35-33](https://github.com/user-attachments/assets/73f4e526-89d7-413b-82a9-e84de445fa75)

Теперь приступлю к задаче.

### Задача

1. Создаю новый файл с именем `script.bash`

```bash
touch script.bash
```

2. Открываю созданный файл `script.bash` для редактирования.

```bash  
gedit script.bash
```

3. Вписываю шебанг

```bash
#!/bin/bash
```

4. Вписываю главную часть скрипта

```bash
echo "Welcome, $*"
```
  Здесь `$` отвечает за ввод переменных, а `*` в сочетании с `$` позволяет выдать все переданные переменные в виде строки
  
5. Запускаю скрипт в терминале как в примерах:
```bash
bash script.bash Vasya Pupkin
```

```bash
bash script.bash Benedict Timothy Carlton Cumberbatch
```

6. Скрипт работает!

   ![Screenshot From 2024-09-21 21-40-50](https://github.com/user-attachments/assets/db70dc19-a9d5-463d-bb1d-70a92441dd07)

   ![Screenshot From 2024-09-21 21-22-50](https://github.com/user-attachments/assets/8e689824-483d-4fd3-8a2a-49aa8de1f433)
   
   ![Screenshot From 2024-09-21 21-36-35](https://github.com/user-attachments/assets/c9731e8a-8550-424b-a651-f0f6eb0a3b57)


### Вывод

Выполнив лабораторную работу, я получила новые знания, поработала с терминалом в очередной раз.
