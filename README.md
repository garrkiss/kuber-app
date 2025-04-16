# Домашнее задание к занятию "`Запуск приложений в K8S`" - `Бакулев Евгений`

## Задание 1. Создать Deployment и обеспечить доступ к репликам приложения из другого Pod

- [Манифест Deployment](https://github.com/garrkiss/kuber-app/blob/main/manifest/nginx-multitool-deployment.yaml)
- [Манифест Service](https://github.com/garrkiss/kuber-app/blob/main/manifest/pod-multitool.yaml)
- [Манифест Pod](https://github.com/garrkiss/kuber-app/blob/main/manifest/svc-nginx-multitool.yaml)

### Демонстрация количества реплик

![Ссылка](https://github.com/garrkiss/kuber-app/blob/main/img/1.png)

### Проверка доступности из отдельного пода multitool
![Ссылка](https://github.com/garrkiss/kuber-app/blob/main/img/2.png)

## Задание 2. Создать Deployment и обеспечить старт основного контейнера при выполнении условий

[Манифест пода](https://github.com/garrkiss/basekuber/blob/main/manifest/pod-netology-web.yaml)
[Манифест сервиса](https://github.com/garrkiss/basekuber/blob/main/manifest/svc-netology-web.yaml)

![Ссылка](https://github.com/garrkiss/basekuber/blob/main/img/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202025-04-16%2015-02-26.png)

![Ссылка](https://github.com/garrkiss/basekuber/blob/main/img/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202025-04-16%2015-02-54.png)