# virt-homeworks-05-virt-02-iaac
Карпов Андрей DEVOPS-21

## Задача 1

- Опишите своими словами основные преимущества применения на практике IaaC паттернов.
- Какой из принципов IaaC является основополагающим?

## Задача 2

- Чем Ansible выгодно отличается от других систем управление конфигурациями?
- Какой, на ваш взгляд, метод работы систем конфигурации более надёжный push или pull?

### Ответ:
1.Ansible написан на python, не требует наличия агента на клиенте
2.push надёжней, т.к. централизованно управляет конфигурацией и исключает ситуации, когда прямое изменеие на сервере не отразится в репозитории, что может привести к непредсказуемым ситуациям.

## Задача 3

Установить на личный компьютер:

- VirtualBox
- Vagrant
- Ansible

*Приложить вывод команд установленных версий каждой из программ, оформленный в markdown.*

### Ответ:
VirtualBox<br>
```
c:\Program Files\Oracle\VirtualBox>vboxmanage --version
6.1.36r152435
```
Vagrant
```
d:\HashiCorp\Vagrant\bin>vagrant --version
Vagrant 2.2.20.dev
```
