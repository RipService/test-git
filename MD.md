**Регистрация  пользователя на сайте**

**Цель**: Успешная регистрация пользователя <https://skillfactoryca.atlassian.net/browse/SP-6> 

***Основной сценарий:***

1. *Пользователь* нажимает регистрация 
1. Система открывает страницу регистрации и отражает выбор клиенту логин пароль или вход по одноразовому паролю
1. Пользователь выбирает одноразовый пароль и вводит ИИН 
1. Система производит поиск и находит клиента , система отражает окно ввода номера телефона <https://skillfactoryca.atlassian.net/jira/software/projects/SP/boards/1?selectedIssue=SP-8> 
1. Пользователь вводит номер телефона и нажимает подтвердить 
1. Система обрабатывает данные и отправляет смс об подтверждение и отражает окно для ввода смс кода <https://skillfactoryca.atlassian.net/jira/software/projects/SP/boards/1?selectedIssue=SP-7> 
1. Клиент вводит код подтверждения 
1. Система регистрирует клиента 
1. Сценарий завершен 

***Альтернативный сценарий :***

1. **Пользователь** нажимает регистрация 
1. Система открывает страницу регистрации и отражает выбор клиенту логин пароль или вход по одноразовому паролю
1. Пользователь выбирает логин пароль
1. Система отражает поле для ввода ИИН 
1. Пользователь вводит ИИН 
1. Система производит поиск и находит клиента <https://skillfactoryca.atlassian.net/jira/software/projects/SP/boards/1?selectedIssue=SP-8> , система отражает поле для ввода создания логина пароля 
1. **Пользователь** вводит логи пароль нажимает подтвердить 
1. Система обрабатывает данные и отправляет смс об подтверждение и отражает окно для ввода смс кода <https://skillfactoryca.atlassian.net/jira/software/projects/SP/boards/1?selectedIssue=SP-7> 
1. Клиент вводит код подтверждения 
1. Система регистрирует клиента 
1. Сценарий завершен 

***Сценарий Исключения :***

1. **Пользователь** нажимает регистрация 
1. Система открывает страницу регистрации и отражает выбор клиенту логин пароль или вход по одноразовому паролю
1. Пользователь выбирает логин пароль
1. Система отражает поле для ввода ИИН 
1. ***Пользователь:*** вводит ИИН 
1. Система производит поиск клиент не найдет <https://skillfactoryca.atlassian.net/jira/software/projects/SP/boards/1?selectedIssue=SP-8> 
1. Сценарий завершен 

