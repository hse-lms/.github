<div align="center">
<img src="https://raw.githubusercontent.com/hse-lms/.github/main/assets/avatar.png" alt="Логотип НИУ ВШЭ" width="112">
<br><br>
<strong>Единая LMS для дисциплины «Программирование»</strong><br>
Задания · Wiki · сдачи · проверки · оценки
</div>

---

Мы объединяем независимо разработанные учебные проекты в один продукт: общую учётную запись, согласованные API и воспроизводимый выпуск системы.

**Сейчас:** проектирование интеграции. Общая LMS ещё не собрана; функции ниже описывают целевую архитектуру.

### Компоненты

| Репозиторий | Назначение |
| --- | --- |
| [core-service](https://github.com/hse-lms/core-service) | Пользователи, роли и авторизация |
| [study-service](https://github.com/hse-lms/study-service) | Курсы, задания, сдачи, оценки и ведомость |
| [wiki-service](https://github.com/hse-lms/wiki-service) | Учебные материалы и поиск |
| [report-validator](https://github.com/hse-lms/report-validator) | Проверка оформления DOCX |
| [code-checker](https://github.com/hse-lms/code-checker) | Интеграция проверки C# |
| [web-client](https://github.com/hse-lms/web-client) | Web-интерфейс LMS |
| [mobile-client](https://github.com/hse-lms/mobile-client) | Мобильный клиент |
| [infra](https://github.com/hse-lms/infra) | Общий запуск, версии и проверка продукта |

Основные репозитории закрыты: их содержимое доступно участникам с соответствующими правами.

### Как части становятся продуктом

**Собственные версии компонентов → согласованные контракты → проверенный состав выпуска → локальная демонстрация.**

В основе — ASP.NET Core, FastAPI, React и Flutter. Для общего окружения планируются Docker Compose и Kafka. Код других авторов сохраняет сведения о происхождении и лицензиях.

<sub>Учебный проект интеграции. Страница не является официальным ресурсом НИУ ВШЭ. Студенческие работы и персональные данные не публикуются.</sub>
