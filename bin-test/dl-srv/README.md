<p align=center><img width="100px" src="https://cdn.iconscout.com/icon/free/png-256/node-js-1174925.png"></p>

# Dl-SRV

* Um servidor de _downloads_ com NodeJS
* Pode ser ultilzado como servidor _http/https_ normalmente.

<hr>

**Instalação:** [Abrir Docs](/docs/setup)

**Execução:** [Abrir Docs](/docs/execucao)

**Reset:** [Abrir Docs](/docs/reset)

**Api:** [Abrir Docs](/docs/api)

### Instalação :

* 1 - Baixe o instalador:

```sh
wget https://repo.mbcl.ml/dl-srv/latest/installer
```

* 2 - Execute o instalador
```sh
sudo chmod +x installer && ./installer
```

_Todo processo de instalação será feito automaticamente_

<hr> 

### Execução:

* O _arquivo de execução_ se inicia o servidor e se atualizar automaticamente ao ser executado.

```sh
./start```

<hr>

### Reinstalação:

* Para _reinstalar_ o servidor, basta digitar o comando abaixo, isso fará que o servidor se auto reinstalar

```sh
sudo sh bin/reset
```

<hr>

### Api:

`.port` - define a porta do servidor principal _(Ex: 80)_

```json
{
[...]
    "port": 80
[...]
}
```
