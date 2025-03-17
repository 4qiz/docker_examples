## **Доступ к сервисам**

- **Grafana**: [http://host:3000](http://host:3000)
  - **Логин**: `admin`
  - **Пароль**: `admin`

## **Настройка Grafana**

1. Откройте **Grafana**: [http://host:3000](http://host:3000).
2. Перейдите в **Connections → Data Sources**.
3. Добавьте источник **Prometheus**:
   - **URL**: `http://prometheus:9090`
   - Нажмите **Save & Test**.
4. Импортируйте **Node Exporter Full Dashboard**:
   - Перейдите в **Dashboards → Import**.
   - Введите **Dashboard ID: 1860**.
   - Нажмите **Load** и выберите источник **Prometheus**.
