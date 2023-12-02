NAME|PROMPT|DESCRIPTION|EXAMPLE
|--|--|--|--|
|CronJob|`kubectl ai "Завдання по розкладу"`|Створення завдання, яке виконується за розкладом|[app-cronjob.yaml](yaml/app-cronjob.yaml)|
|Job|`kubectl ai "Одноразове завдання"`|Запуск одноразового завдання|[app-job.yaml](yaml/app-job.yaml)|
|Liveness Probe|`kubectl ai "Перевірка чи працює контейнер"`|Перевірка, чи працює контейнер|[app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)|
|Багатоконтейнерний Pod|`kubectl ai "Pod з кількома контейнерами"`|Створення Pod, що містить кілька контейнерів|[app-multicontainer.yaml](yaml/app-multicontainer.yaml)|
|Readiness Probe|`kubectl ai "Перевірку готовності контейнера"`|Перевірка готовності контейнера обробляти трафік|[app-readinessProbe.yaml](yaml/app-readinessProbe.yaml)|
|Обмеження ресурсів|`kubectl ai "Обмеження ресурсів для контейнера"`|Встановлення обмежень ресурсів для контейнера|[app-resources.yaml](yaml/app-resources.yaml)|
|Секрети як змінні оточення|`kubectl ai "Передача конфіденційних даних через змінні оточення"`|Передача конфіденційних даних у контейнер через змінні оточення|[app-secret-env.yaml](yaml/app-secret-env.yaml)|
|Volume Mounts|`kubectl ai "Підключення тома до контейнера для зберігання даних"`|Підключення тома до контейнера для зберігання даних|[app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)|
Базовий Pod|`kubectl ai "Базовий маніфест Pod"`|Простий маніфест Pod для базового розгортання додатка|[yaml/app.yaml](yaml/app.yaml)|

