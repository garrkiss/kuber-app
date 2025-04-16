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

- [Манифест Deployment](https://github.com/garrkiss/kuber-app/blob/main/manifest/nginx-deployment.yaml)
- [Манифест Service](https://github.com/garrkiss/kuber-app/blob/main/manifest/svc-nginx.yaml)

![Ссылка](https://github.com/garrkiss/kuber-app/blob/main/img/3.png)