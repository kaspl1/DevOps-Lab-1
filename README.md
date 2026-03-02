# DevOps-Lab-1
Отчет лабораторной работы номер 1
<img width="1762" height="498" alt="image" src="https://github.com/user-attachments/assets/17584f6a-5c6d-4c00-8430-fb12ee55697c" />
<img width="1583" height="315" alt="image" src="https://github.com/user-attachments/assets/c304aaed-c995-4daa-a695-3a3871da1f4e" />
В ходе лабораторной работы были проделанны следующие шаги:
Собран базовый образ для python приложения.
При первом запуске вывод о неудачном подключении к бд.
Написал docker-compose, при первом запуске указал неверные credentials для бд.
Повторный запуск с новыми кредами не удался — причина: старые данные в вольюмах блокировали инициализацию с новыми параметрами.
Исправил: почистил тома (docker compose down -v) и поднял заново.
