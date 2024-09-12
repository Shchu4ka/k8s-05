# Домашнее задание к занятию «Сетевое взаимодействие в K8S. Часть 2»

## Задание 1. Создать Deployment приложений backend и frontend

- Создаем деплойменты для фронта и бэка
  ![image](https://github.com/user-attachments/assets/f25e8a53-0009-43f6-a3b2-06ce118e3275)
и манифест для сервисов
  ![image](https://github.com/user-attachments/assets/0f03d7ab-daa1-45f8-87da-0d22fea0f35f)

- Применяем все и проверяем, что завелось
  ![image](https://github.com/user-attachments/assets/a8ae2133-4479-48dc-b343-f2f6e1cc30a5)

- Проверяем доступеность между сервисами
  ![image](https://github.com/user-attachments/assets/e5ae832b-6692-4a08-a45b-705b8b99cf5f)

## Задание 2. Создать Ingress и обеспечить доступ к приложениям снаружи кластера

- Включаем Ingress-controller в MicroK8S:
  ![image](https://github.com/user-attachments/assets/68ed306f-7623-4a84-b565-7d25971da924)

- Создаем манифест для ингреса и применяем его
  ![image](https://github.com/user-attachments/assets/56a0a277-43be-4b1f-9c9a-091dd6a7fa86)

- Проверяю доступность до ингреса с локальной машины по ip 
  ![image](https://github.com/user-attachments/assets/ed890ab6-3ce6-44e4-b93d-f2ace523a3a6)
