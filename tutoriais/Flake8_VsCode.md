# :computer: Flake8 no Vscode :computer:

O objetivo deste tutorial, é mostrar como configurar o [linter](https://en.wikipedia.org/wiki/Lint_(software)) [flake8](https://pypi.org/project/flake8/)
para executar pelo atalho Ctrl + Shift + S na IDE VsCode.

## :memo: :heavy_check_mark: Pré- requisito:

:green_circle: Extensão Pylance

![Pylint](https://user-images.githubusercontent.com/104836457/172157386-627032e3-9885-4be4-955e-9791114d2bf4.png)

## :ballot_box_with_check: Configuração no VsCode

:large_blue_circle: Passo 1 :

No terminal, no ambiente virtual criado para o projeto, instale o flake8:

```bash

pip install flake8

```

:bulb: Dúvidas sobre como criar um ambiente virtual? [clique aqui](https://realpython.com/python-virtual-environments-a-primer/)


:large_blue_circle: Passo 2 :
Digite Ctrl + Shift + P , selecione a opção 'Python: Enable/Disable Linting', depois selecione 'Enable'

![step3](https://user-images.githubusercontent.com/104836457/172173705-be8e805d-8f07-42f4-a0a0-6ad97c51c675.png)

![step3_1](https://user-images.githubusercontent.com/104836457/172174166-4ba679be-ebe5-452c-8212-33ec79272344.png)


:large_blue_circle: Passo 3: 

No menu superior do VsCode, selecione ' File > Preferences > Keyboard Shortcuts'. No campo de busca digite 'Python: Run Linting' e será mostrada a opção:

![step4](https://user-images.githubusercontent.com/104836457/172177097-808cb5ad-deb1-4c57-a529-623cbc48e62a.png)

Clique nela e aparecerá uma janela para a inserção do atalho, digite Ctrl Shift S, e pressione Enter.

![step4_1](https://user-images.githubusercontent.com/104836457/172178350-ebada56e-ab1f-4991-9d53-ba8b47d4e201.png)


![step4_2](https://user-images.githubusercontent.com/104836457/172178553-fbe0489e-8423-4d09-8d0a-e52740965b94.png)


:large_blue_circle: Passo 4 : 

Digite Ctrl + Shift + P , selecione a opção 'Select linter' 

![step1](https://user-images.githubusercontent.com/104836457/172160810-aac7cfd8-5dfc-443e-a263-f3170ac6eeae.png)

Selecione 'Flake8'

![step4_3](https://user-images.githubusercontent.com/104836457/172179637-b0446467-6384-4dc8-ae20-d329a2accfe4.png)

## :thumbsup: Agora é possível acionar o linter flake8 através de Ctrl + Shift + S





