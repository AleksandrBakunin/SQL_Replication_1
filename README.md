# Домашнее задание к занятию "`12.6. «Репликация и масштабирование. Часть 1»`" - `Александр Бакунин`

---

### Задание 1

Основными различиями, отличающими master-slave (m-s) и master-master (m-m) репликации, являются:
1) В случае m-s репликации данные изначально записываются в master сервер, там же происходят все операции с данными. Slave является вспомогательным сервером, который копирует данные с master'а, однако мы не можем записываться туда напрямую, оттуда мы можем только списать данные. 
2)В случае m-m данные записываются напрямую в оба master'a и могут быть записаны/считаны оттуда в равной степени, то есть это по сути тот же m-s, только каждый сервер является и мастером, и слейвом одновременно.

---

### Задание 2



---
