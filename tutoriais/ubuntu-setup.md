# :computer: Realizando o setup local de em um novo computador

:large_blue_circle: Passo 1: certifique-se que o Git está instalado e que você  já tenha
permissão de acesso aos repositórios da 4Intelligence (projeto clonado em seu diretório local)


:large_blue_circle: Passo 2: certifique-se que o VSCode está instalado na versão 1.74

Caso não tenha, baixar deste link: ![VSCode 1.74](https://code.visualstudio.com/updates/v1_74)

A motivação para utilização desta versão dá-se devido a este problema relatado no ![Stackoverflow](https://stackoverflow.com/questions/75439217/error-debugging-python-in-vs-code-pythonpath-is-not-valid-if-python-is-spec)


:large_blue_circle: Passo 3: instale o docker no Ubuntu:
![docker](https://docs.docker.com/engine/install/ubuntu/)


Checar se o docker-compose está instalado
``` bash
sudo docker–compose --version
```

Se não estiver instalado, instalar o mesmo:
```bash
sudo apt install docker-compose
```


:large_blue_circle: Passo 4: realizar as configurações pós instalação do docker
![pós instalação docker](https://docs.docker.com/engine/install/linux-postinstall/)


:large_blue_circle: Passo 5: instalar Google Cloud CLI na sua máquina
![google CLI](https://cloud.google.com/sdk/docs/install)


:large_blue_circle: Passo 6: Realizar a configuração do Google Cloud CLI para docker
![Configurar google CLI para docker](https://cloud.google.com/container-registry/docs/advanced-authentication?hl=pt-br#gcloud-helper)


:large_blue_circle: Passo 7: certificar-se que você tem acesso aos projetos no GCP 



## Feito tudo isso, seu ambiente deverá estar disponível para um build normal de uma imagem.





