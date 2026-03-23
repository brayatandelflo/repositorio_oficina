
# repositorio_oficina

## Nota sobre reescritura de historial

Se reescribieron mensajes de varios commits en la rama `main` para unificar el estilo de los mensajes. Esto cambió los hashes de esos commits y se realizó un push forzado seguro (`--force-with-lease`) al remoto.



```powershell
git fetch origin
git checkout main
git reset --hard origin/main
```



```powershell
git branch backup-local-work
git checkout backup-local-work
```

comandos utilizados para la actualizacion de nombres.

