# Домашнее задание к лекции «Docker»

```bash
docker run -d -v ${PWD}/html:/usr/share/nginx/html -p 7777:80 nginx
```
# Проверка работоспособности

```bash
curl localhost:7777
```
