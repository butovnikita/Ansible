# Установка VictoriaMetrics

### victoriametrics
Хранилище данных  
http://puv-dev-monitoring.otr.ru:8428/vmui  

### vmagent
Сбор данных  
http://puv-dev-monitoring.otr.ru:8429  

Обзор таргетов  
http://puv-dev-monitoring.otr.ru:8429/targets  

Посмотреть текущий конфиг  
http://puv-dev-monitoring.otr.ru:8429/config  

Конфиг  
https://dpr-gitlab.otr.ru/admins/infra-puv/victoriametrics/-/blob/master/victoria/files/config/prometheus.yml  

Релоад конфига  
http://puv-dev-monitoring.otr.ru:8429/-/reload  

### grafana
http://puv-dev-monitoring.otr.ru:3000  
admin:admin  
grafana:Oracle33 (read only)  

Дашборды в json  
https://dpr-gitlab.otr.ru/admins/infra-puv/victoriametrics/-/tree/master/victoria/files/dashboards  

Конфиги grafana  
https://dpr-gitlab.otr.ru/admins/infra-puv/victoriametrics/-/tree/master/victoria/files/provisioning  

### vmalert alertmanager alertmanager-telegram
Алерты и включение silences  
http://puv-dev-monitoring.otr.ru:9093/#/alerts  

Конфиги vmalert  
https://dpr-gitlab.otr.ru/admins/infra-puv/victoriametrics/-/tree/master/victoria/files/config/vmalert  

Релоад конфига vmalert  
http://puv-dev-monitoring.otr.ru:8880/-/reload  

Конфиг alertmanager  
https://dpr-gitlab.otr.ru/admins/infra-puv/victoriametrics/-/blob/master/victoria/files/config/alertmanager.yml  

#### blackbox-exporter  
Экспортер для веб проверок  

Конфиг  
https://dpr-gitlab.otr.ru/admins/infra-puv/victoriametrics/-/blob/master/victoria/files/config/blackbox-exporter.yml  

#### роль для установки экспортеров
https://dpr-gitlab.otr.ru/admins/infra-puv/node_exporter  
