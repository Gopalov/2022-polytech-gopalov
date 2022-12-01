Какой процесс имеет наименьший идентификатор?
```
$ ps -Ao pid,comm --sort=pid | head -n 2
PID COMMAND
1 init
```
Какой идетификтор у вашего текущего shell-процесса?
PID TTY           TIME CMD
9pts/0         00:00:01 bash
```
$ ps -p $$
```
Сколько всего запущено процессов?
```
$ ps -A | wc -l
8
```
