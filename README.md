### Проектная работа 5-го спринта

- Логирование происхолит в файл ./rasa.log
- Проект запускается на 5555 порту

Run rasa with CORS
```shell
rasa run --enable-api -p 5555 --cors "*"
```
Run rasa in specific port with logs
```shell
rasa run --enable-api -p 5555 --cors "*" --log-file ./rasa.log --verbose -vv
```
Run rasa in terminal
```shell
rasa shell
```

---

- Дополнительное задание выполнено. 