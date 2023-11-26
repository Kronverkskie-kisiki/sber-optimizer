## Запуск
- `git clone --recurse-submodules `
- `cd sber-assembly`
- `docker-compose build`
- `docker-compose up`

Приложение запустится на [localhost:8080]()

### Дисклеймер:
- Из-за того что мы используем jRPC для коммуникации, приложение скорее всего не запустится на машинах с процессорами arm64, как Linux, так и macOS, так как нет нужных пакетов под данную архитектуру
