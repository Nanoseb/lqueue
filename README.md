# lqueue
Lightweight local queue management compatible with slurm jobfiles

### Usage:
- First run the deamon:
```
lqueue deamon
```

- Then generate an empty jobfile (a slurm jobfile can be used too)
```
lqueue gen-jobfile
```

- Add a jobfile to the queue:
```
lqueue add jobfile
```

- Visualise the status of the queue
```
lqueue status
```

- For more detail a manpage is accessible via 
```
lqueue help
```
