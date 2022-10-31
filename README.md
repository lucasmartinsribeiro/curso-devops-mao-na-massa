## Projeto realizado durante o curso DevOps Mão na Massa


### ✅ Requisitos
 
- Instalar o Vagrant
- Instalar o VirtualBox
---

### ⚙ Instruções para Utilização

- Primeiro é necessário realizar a cópia do projeto, faça o download do arquivo .zip ou o git clone:

```bash
curso-devops-mao-na-massa.zip or git clone https://github.com/lucasmartinsribeiro/curso-devops-mao-na-massa.git
```

- Feito a cópia do projeto, o próximo passo é acessar a pasta com o projeto que você quer rodar  e instalar as dependências

```bash
Ex: cd curso-devops-ma0-na-massa && cd lab-docker
```

- Instalando .vagrant

```bash
vagrant up
```

- Entrar na aplicação

```bash
vagrant ssh
```

- Caso você for criar um Vagrantfile do zero, será necessário:

```bash
vagrant init
```

- Fazer upload de uma pasta para dentro da sua máquina virtual

```bash
vagrant upload nome-da-pasta
```

- Quando você realizar uma mudança no provision, e quer subir essa mudança

```bash
vagrant provision
```