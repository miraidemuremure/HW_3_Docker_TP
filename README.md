# Домашнее задание 3 — Docker

## Как запустить

### 1. Генератор данных
```bash
./run.sh build_generator
./run.sh run_generator
```
Создаст файл `data/data.csv`

### 2. Отчёт
```bash
./run.sh build_reporter
./run.sh run_reporter
```
Создаст файл `data/report.html`

### 3. Открыть отчёт в браузере

1. Запусти: `./run.sh report_server`
2. Открой вкладку **Ports** внизу в VS Code
3. Нажми на глобус рядом с портом **8080**
4. В адресе добавь `/report.html`

Это работает так: nginx запускается внутри контейнера на порту 80, Codespaces пробрасывает его на порт 8080 хоста, а дальше Codespaces даёт публичную ссылку — и отчёт открывается в браузере.
