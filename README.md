# 🛠️ **Atividade: Gestão de Código Fonte com GitHub e VS Code**  

> 📌 **Atenção!** Para esta atividade, você precisará de pelo menos um outro colaborador.  
> 🔥 **IMPORTANTE:** **TODOS** os colaboradores devem responder esta tarefa, apresentando as evidências da execução das etapas.

---

## 🎯 **Objetivo**  
Esta atividade tem como objetivo praticar os conceitos de **gestão de código fonte** utilizando **Git**, **GitHub** e **Visual Studio Code (VS Code)**, simulando um fluxo básico de colaboração entre desenvolvedores.

---

## 📌 **Etapas da Atividade**  

### 🔹 **1. Criar uma conta no GitHub**  
Caso ainda não tenha uma conta, crie a sua em: [GitHub](https://github.com/).

### 🔹 **2. Instalar o Git**  
Baixe e instale a versão mais recente do Git em seu computador:  
🔗 [Download Git](https://git-scm.com/)

### 🔹 **3. Instalar o Visual Studio Code (VS Code)**  
Baixe e instale o **VS Code**:  
🔗 [Download VS Code](https://code.visualstudio.com/)

### 🔹 **4. Criar um repositório no GitHub**  
- No **GitHub**, crie um **repositório público** chamado `scm`.

### 🔹 **5. Clonar o repositório no seu computador**  
Abra o terminal e execute o comando:  

```sh
git clone https://github.com/SEU-USUARIO/scm.git
```

### 🔹 **6. Criar e editar um arquivo `index.html`**  
- No **VS Code**, crie um arquivo chamado `index.html` e insira um conteúdo válido (por exemplo, um código HTML básico).

### 🔹 **7. Fazer commit e enviar alterações para o repositório remoto**  
Execute os seguintes comandos no terminal:

```sh
git add .
git commit -m "Adicionando o arquivo index.html"
git push
```

### 🔹 **8. Adicionar um colaborador ao repositório**  
- No GitHub, vá até a aba "Settings" > "Collaborators", e convide seu par para acessar o repositório.
- Seu par deve aceitar o convite e então clonar o repositório em seu computador

### 🔹 **9. O colaborador clona o repositório e faz alterações**  
O colaborador deve executar:

```sh
git clone https://github.com/SEU-USUARIO/scm.git
```

- Depois, abrir o arquivo `index.html`, fazer uma alteração e seguir o fluxo:

```sh
git add .
git commit -m "Alteração no index.html"
git push
```

### 🔹 **10. Atualizar o repositório local e verificar mudanças**  
Agora, retorne ao seu terminal e execute:

```sh
git pull
```

- Verifique se as alterações feitas pelo seu colaborador foram incorporadas.

---

## 📄 **Evidências a serem entregues**  
Cada integrante deve gerar um documento (**.docx** ou **.pdf**) contendo:  

✅ **1. O endereço (URL) do repositório criado.**  
✅ **2. Captura de tela dos commits feitos por você e pelo seu colaborador.**

---

## 💡 **Dicas e comandos úteis**  

🔹 Configurar o Git com seu nome e e-mail (obrigatório para commits)

```sh
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

| Comando | Descrição |
|---------|------------|
| `git clone URL_DO_REPOSITORIO` | Clona o repositório para seu computador |
| `git add .` | Adiciona todas as mudanças para o próximo commit |
| `git commit -m "mensagem"` | Cria um commit com uma mensagem descritiva |
| `git push` | Envia as alterações locais para o repositório remoto |
| `git pull` | Atualiza seu repositório local com as alterações remotas |

---

🛠️ **Parabéns!** Você acabou de simular um fluxo básico de versionamento de código em equipe. 🎉🚀
