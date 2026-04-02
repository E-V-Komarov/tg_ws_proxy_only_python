# tg_ws_proxy_only_python

## Установка
**Iphone**
Скачайте из маркета [приложение `iSH`](https://apps.apple.com/ru/app/ish-shell/id1436902243)
Важно! Установка пакетов в iSH не работает без vpn ;(
```bash
apk update &&
apk add python3 py3-pip py3-cryptography curl &&
echo "cat /dev/location > /dev/null &\npython3 tg_ws_proxy_cli.py" >> ~/.profile &&
curl -L -o tg_ws_proxy_cli.py "https://github.com/E-V-Komarov/tg_ws_proxy_only_python/releases/download/0.0.1/tg_ws_proxy_cli.py"
```
