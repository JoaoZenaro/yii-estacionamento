<img src="logo-bgdark.jpg" alt="Park Hub Logo" />

# 🐳 Dockerized Yii API + React SPA: Park Hub

Desenvolvimento de aplicação de **gerenciamento de estacionamento** utilizando o Framework definido por sorteio.   
**Programação III: CC 2022 Unoesc.**

## 🎲 Framework Definido
<p align="center">
    <a href="https://www.yiiframework.com/" target="_blank">
        <img src="https://www.yiiframework.com/image/yii_logo_light.svg" width="300" alt="Yii Framework" />
    </a>
</p>

[Yii2 Docs](https://www.yiiframework.com/doc/guide/2.0/en)

## 📚 Tech stack

<div align=center>
  
![Yii](https://img.shields.io/badge/yii-ebf1f2.svg?style=for-the-badge&logo=data:image/png%2bxml;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAACslBMVEUAAADxiiqDyTOEyTOYvTHXmSzyiiyDyDQyrvFXu61As9hmv1ZQtbBAs9nxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiirxiiqDyTODyTODyTODyTODyTPxiirxiiqDyTODyTODyTODyTODyTODyTODyTODyTODyTODyTPxiirxiirxiirxiiqDyTODyTODyTODyTPxiirxiirxiirxiiqDyTODyTODyTODyTODyTPxiirxiirxiirxiiqDyTODyTODyTODyTODyTPxiirxiirxiirxiiqDyTODyTN7zjT2hyrxiirxiiqDyTODyTOAyzPyiSrxiirxiiqDyTODyTODyTOAxzXtiivxiirxiiqDyTOAwDmDtj3ziSrxiirxiiqDyTN8uj3rjCvxiirxiirxiiqDyTODyTN/uTyVsDnziSrxiiqDyTODyTN7uj30iSrxiirxiiqDyTODyTN9uj3ikC3xiirxiirxiiqDyTODyTODyTODyTODyTODyTODyTODyTN+uTyxpDXyiirxiirxiiqDyTODyTODyTODyTOEyTF8x0Rxu19/uTySsTrziSrxiio+stxCs9J/uTuLtDv0iSrxiipAs9hAs9h6uUiJtTj7hinxiipAs9hAs9hZtZt6uUpAs9hAs9hDs9FTtahAs9hAs9hAs9hAs9lAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9hAs9jxiiqDyTODyDSAvDqCxTV/ujyBwTd/uTyAvTqDyTKDxDR/uTt8uUSAuTpRta5rt259uUBAs9g/s9pCs9JatpdAs9n///+bs/oNAAAAz3RSTlMAAAAAAAAAAAAAAAAAACq+nxcow/2pGLkMAoX5aDLm0hwBBQgGAoJjK2eXs724o3xGFQa0pgMZz/ciCL3PEhzd/tgLAaHhIBHN+Z4aZv7kIwOqGyDbG3CpEITCCy3m/Xst45CW5zqV90sqmULwyRNT6+U4t3JX33Nv0B0x7LVC8fhhBzR2rdDk8fvfO9iiCgQSIzZQiPLyR8QkbPr6WKNMNuL9YDMED7P8VGL6+EUKueksI+PCDTPvdDTwzx0o6O1RFtTsZgIGsvvHS4TTdRseJWuXAAAAAWJLR0TlWGULvwAAAAd0SU1FB+UFDQsVOKM1xlcAAAHZSURBVDjLY2DAAhgZ+fgFBBkZGXAARkYh4fMiomI4VTAKip8HAgEJHAoYJaVA8uelZXAYwSgrB1ZwXl4BpoBJUUlZRZWJGeoCNYj8eRF1sBFMqhqaWto6unr6BoaKTEAFRsZQBedNTMEKzMwvQICFub4lExOjlTVMgY0tWIGd/QUYcHDUdGJxdoEpcHUDK3D3uIAAnl7erD6+UAV+/mAFAYEXkIF2UHAIVEFIKFgBUxiKggvhEZFQBVHRYH8yxcSiKIiLT0iEKEiChBRTQDKqESmpaWD59AxGNrACpkxHZPmLl7Kyc0AKcvOgIcnElF+ApODylcKiYqC8bwk8LphUS8sQCq5eu1ZeAVRQWYWIKyamar0amA3Xr12rras/39CIHJnsTE3NLa1t7R2dN27eunatq7vnfG8fWmQzMfVPmDhp8pSpt+9cmzZ9hvxMrKmBg3PW7Lv37s+ZO28+VnkurgULHzx89HjR4iVLsaYmrmXLHzx48OTJipXc2OW5Vq1+AFKxZi0P1tTItW79AzDYsJEXu4JNmyEKtmzlwq5g23aIgh1cOBTs3AWW370HuzwD1959IPn9B7hwKTh4CCh/+MhRHPIMXMeOPzhx8hROeWA4nD5z9hyq+QAq/D4JY4faeAAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMS0wNS0xM1QxMToyMTo1NiswMDowMFdXIWsAAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjEtMDUtMTNUMTE6MjE6NTYrMDA6MDAmCpnXAAAAV3pUWHRSYXcgcHJvZmlsZSB0eXBlIGlwdGMAAHic4/IMCHFWKCjKT8vMSeVSAAMjCy5jCxMjE0uTFAMTIESANMNkAyOzVCDL2NTIxMzEHMQHy4BIoEouAOoXEXTyQjWVAAAAAElFTkSuQmCC&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
</div>

<details>
<summary>

# 🤖 Overview
</summary>
<br>

[What is Yii?](https://www.yiiframework.com/doc/guide/2.0/en/intro-yii)

# Estrutura

|Arquivo/Diretório|Definição|
|-|-|
|.devcontainer/ |Diretório de configurações Docker + Devcontainer|
|.devcontainer/nginx/ |Servidor Proxy para conexão de back e front end em localhost ([NGINX](https://nginx.org/))|
|.devcontainer/www/ |Configuração para container de desenvolvimento PHP + NodeJS (base Alpine)|
|.devcontainer/docker-compose.yml|Configuração central dos containers (Banco de dados, PhpMyAdmin, NGINX, Aplicativos Web)|
|.devcontainer/devcontainer.json |Arquivo de configuração Dev Container. A porta de entrada das demais configurações para desenvolvimento.|
|backend/ |API REST em PHP (Yii2)|
|frontend/ |SPA Vite utilizando React (Typescript)|

## Visão geral

⚠️ ATENÇÃO: O projeto inicialmente não será publicado, portanto somente configurações de desenvolvimento estão presentes, o que pode não funcionar da maneira desejada em produção. ⚠️

O projeto foi visto como uma oportunidade de aplicar praticas modernas de programação, o combo

$$
\begin{array}
    \space SPA\space\textrm{(Single Page Aplication)} & \\
    + & \\
    API\space\textrm{(Application Programming Interface)} \\
    REST\space\textrm{(Representational State Transfer)}
\end{array}
$$

ou seja, websites totalmente divididos e especializados em suas responsabilidades. Aplicativos de "única página" fazem requisições de transferência de estado representacional (*REST*) através de interfaces de programação de aplicativos (*APIs*), isso permite uma grande separação e uma aproximação maior dos princípios *SOLID*, de que cada componente do sistema é focado em uma única responsabilidade, promovendo a independência e a modularidade.

</details>

<details>
<summary>

# 🏗️ Instalação requisitos técnicos
</summary>
<br>

# 🪟 Instalação para Windows

Irei detalhar o ambiente de desenvolvimento em [Dev Containers](https://containers.dev/) utilizando docker para um ambiente totalmente isolado e reproduzível.

Refira-se ao [overview](#overview) do projeto para mais detalhes sobre.

Caso prefira se encorajar a instalar o PHP, Composer, MySQL, Node e NPM, ou mesmo XAMPP na própria máquina, fique a vontade! *Boa sorte!*

> Obs.: O guia a seguir é para executar a instação do [WSL](https://aka.ms/wsl), que recomendo altamente para desenvolvedores em Windows.

## 🐧 Instalar [WSL](https://aka.ms/wsl): Debian

Powershell (Admin):
```console
PS> wsl --install -d debian
```
Após instalado, execute as etapas de instalação e configure seu usuário linux. Então, em sua nova máquina Debian, continue:
> Obs.: Recomendo que utilize um aplicativo de terminal. Ex.: [Windows Terminal](https://apps.microsoft.com/detail/9n0dx20hk701?rtc=1&hl=en-us&gl=US)

## 🐳 Instalar [Docker Engine](https://docs.docker.com/engine/install/)
1. Caso seja **sua primeira vez** instalando o docker, é possível executar o script auxiliar **oficial** para facilitar a instalação:
```console
$ curl https://get.docker.com/ | sh
```
2. Após instalado, talvez seja necessário permitir que o Docker possa executar seus serviços, tradicionalmente através do *systemd*. 
  * [O que é o systemd?](https://learn.microsoft.com/pt-br/windows/wsl/systemd#what-is-systemd-in-linux)
  * [Habilitar systemd](https://learn.microsoft.com/pt-br/windows/wsl/systemd#how-to-enable-systemd)
3. O Docker inicialmente precisa de privilégio de *super usuário*, nesse sentido, siga as instruções da [habilitar acesso ao seu usuario](https://askubuntu.com/a/477554).

```console
$ sudo groupadd docker
$ sudo gpasswd -a $USER docker
$ docker run hello-world # Se esse comando funcionar corretamente sem 'sudo', parabéns! Está tudo devidamente configurado. 
```

## ⚙️ Configuração [VS Code](https://code.visualstudio.com/)

### Extensões
* [VS Code: Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
* [VS Code: Remote Dev Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

</details>

<details>
<summary>

# 🏃‍♂️ Executar o Ambiente de Desenvolvimento
</summary>
<br>

## 1. Setup do projeto
### 🚀 Codespaces
[Faça um fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) do repositorio e então [abra uma instancia "codespace"](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository)

É possível também [abrir um *codespace* localmente](https://docs.github.com/en/codespaces/developing-in-a-codespace/using-github-codespaces-in-visual-studio-code), fazendo um tunel de sua maquina até a instancia remota do GitHub.

### 🐉 VS Code (Certifique-se que os passos de instalação e extensões estão corretos)
Clone o repositório do github
```bash
git clone https://github.com/joaozenaro/park-hub.git
```
Abra o diretório clonado com o vscode
```bash
code park-hub/
```
Abra o container

$Ctrl + Shift + P \longrightarrow \textrm{Dev Containers: Rebuild and Reopen in Container}$

[Docs](https://code.visualstudio.com/remote/advancedcontainers/develop-remote-host#_connect-using-the-remote-ssh-extension)
## 2. Execução do projeto
Executar os comandos dentro do bash WSL. Tanto nos codespaces como localmente.
### Backend
Instalar pacotes
```sh
$ cd backend/
$ composer install
```
Criar a primeira migração no banco, caso não exista
```bash
$ ./yii migrate/up --migrationPath=@yii/rbac/migrations # Work in progress
$ ./yii migrate
```
Executar o servidor
```bash
$ ./yii serve 0.0.0.0
```
### Frontend
Instalar pacotes
```sh
$ cd frontend/
$ npm i
```
Executar o servidor
```bash
$ npm run dev
```

</details>

<details>
<summary>

# 🚩 Regra de Negócio
</summary>
<br>

## Diagrama de classes
```mermaid
classDiagram
    direction TB
    Spot "1" -- "1..*" SpotTicket
    Spot "1" -- "1" SpotType

    class Spot {
        - Id: int Primary Key
        - Code: string -> A1, A2..
        - Floor: string -> "SUB1", "SUB2"..
        - SpotType: int Foreign Key : SpotType
    }

    class SpotType {
        - Id: int Primary Key
        - Name: string -> Carro, Moto, Cadeirante, Eletrico..
        - DefaultPrice: decimal -> Valor padrão do tipo da vaga
    }

    class SpotTicket {
        - Id: int Primary Key
        - ClientLicensePlate: string
        - SpotId: int Foreign Key : Vaga  
        - Price: decimal
        - WasPaid: bool
        - CheckIn: DateTime: DataHora de entrada do veiculo
        - CheckOut: DateTime: DataHora de saida do veiculo
        - WardenUserId: int Foreign Key : User
        + GetFinalPrice() -> Calcula valor a ser pago:\n[`horario de saida > entrada + tolerancia` -> 10 * 1.5/hora]
    }

```
## Requisitos gerais
- [x] Níveis de acesso (Admin / User)
    - Cadastro feito por outro admin:
        - Admin: Edição todos perfis
        - User: Edição próprio perfil

- [x] Login
    1. Admin primeiro cria um usuario basico
    1. Usuario recebe email de convite
    1. Usuario entra na aplicação e completa seu cadastro

- [ ] Planos (pré-pago / pós-pago)
    - A ser definido

- [ ] Vagas
    - Cadastro de novas vagas
    - Utilização de vagas (permanência para cobrança)
    - Consulta de vagas disponíveis no momento
     
- [ ] Fluxo de veículos (entrada / saída)
    - Listagem filtrada para saber:
        - Número de vagas utilizadas por tempo (1 hr, 1 dia, 1 semana, mes...)
        - Utilizadas no momento (Tem data de entrada, mas sem saída)

- [ ] Relatórios sobre movimentação financeira
    - Igual o fluxo de veículo, mas com os valores pagos

[Figma](https://www.figma.com/design/0dlX5PUwTy1rC8o75kMUlf/UNOESC?node-id=11-3&t=kFh40tNdcUobpXaS-0)

</details>

<details>
<summary>

# ⚒️ Documentação (WIP)
</summary>
<br>

## Helper script
Execute o comando abaixo dentro do ambiente de desenvolvimento para agilizar os processos. 
```console
$ run [options]
```

## Endpoints

Serviço|Endpoint
-|-
Frontend|`localhost/`
API|`localhost/api/`
MySQL|`localhost:3306`
PhpMyAdmin|`localhost:9010`
Mailhog|`localhost:8025`

</details>
