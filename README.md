# Предпринятые действия

Я установил три виртуальные машины в VirtualBox и выставил тип подключения - Сетевой мост у них всех.
![image](https://github.com/cs-itmo-2023/lab-3-kr4nder/assets/99131850/6a24da29-ca03-42b8-8ac2-7a8b0c36f96a)

После этого в виртуальной машине "В" я заблокировал IP виртуальной машины "Б" с помощью iptables.
![image](https://github.com/cs-itmo-2023/lab-3-kr4nder/assets/99131850/d644b5f9-e303-418c-bc5a-f40c52d69473)

# Скрины итогов
## Доступ виртуальной машины А в Интернет
![Access of VM A to Internet](https://i.imgur.com/dymunCu.jpg)

## Сетевой доступ от машины А к машине Б
![Access of VM A to VM bb](https://i.imgur.com/vB0Pygi.jpg)

## Сетевой доступ от машины А к машине В
![Access of VM A to B](https://i.imgur.com/qkKndry.jpg)

## Запрет доступа от машины Б к машине В
![No Access of VM bb to B](https://i.imgur.com/SCzAGIe.jpg)

## Терминалы всех трёх машин
![All VM](https://i.imgur.com/vFh2ji9.jpg)
