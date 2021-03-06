# NeuroStartUp

![логотип](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)

*NeuroStartUp* — динамически развивающийся стартап, специализирующийся на поиске с использованием новейших технологий искусственного интеллекта.

Наши преимущества:
* Высокая точность поиска
* Высокая скорость поиска
* Низкая цена

## Начало работы
* Установить GIT на ПК
* Настроить GIT
    * задать username
    * задать useremail
* Зарегестрироваться в GITHub

### Prerequisites (что нужно установить на ПК для использования):
* Операционную систему
* Браузер
* GIT 
* Редактор кода (например, VS Code)

Пошаговый процесс установки:
1. Пройдите по [ссылке](https://git-scm.com/download/win)
1. Скачайте установочный файл
1. Запустите установку
1. Выберите путь установки
1. Дождитесь завершения установки 

После установки необходимо запустить GIT:
1. Кликните правой кнопкой мыши на любую папку Windows 
1. Выберете опцию GIT Bash Here 

Должно открыться окно:
![пример](https://github.com/netology-code/guides/raw/master/git/img/15.png)

Вы можете встроить NeuroStartUp в ваши приложения с помощью следующих сниппетов (кусочков) кода.

```
JavaScript:
```

```
<script src="https://localhost/neuro.sdk.min.js"></script>
Java (Maven):
```

```
<dependency>
  <groupId>neuro</groupId>
  <artifactId>sdk</artifactId>
  <version>1.0.0</version>
</dependency>
iOS (добавьте код в ваш Podfile):
```

```
platform :ios, '8.0'
pod "neuro-ios-sdk"
```