# Домашнее задание 3 — Docker

## Как запустить

### 1. Генератор данных
```bash
./run.sh build_generator
./run.sh run_generator
```
Создаст файл data/data.csv

### 2. Отчёт
```bash
./run.sh build_reporter
./run.sh run_reporter
```
Создаст файл data/report.html

### 3. Открыть отчёт в браузере

1. Запусти ./run.sh report_server
2. Внизу в VS Code открой вкладку Ports
3. Рядом с портом 8080 нажми на иконку глобуса
4. В адресной строке в конце добавь /report.html


