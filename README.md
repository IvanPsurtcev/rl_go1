# rl_go1

```
После клонирования репозитория устанавливаем следующие зависимости, если не установлены:
sudo snap install plotjuggler
pip install cbor2

Далее подгружаем сабмодули:
git submodule update --init --recursive

Если хотим запускать в симуляторе, то изменяем в standup.py real = False, если на реальном роботе, то real = True

Запускаем код поднятия робота:
python3 ./src/standup.py

Если выдает ошибку, то попробуйте следующую команду и повторите предыдущую команду:
export LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libstdc++.so.6
```
