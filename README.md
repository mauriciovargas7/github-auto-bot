# 🔄 Git Sync Bot

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow) ![Python](https://img.shields.io/badge/python-3.11-blue) ![Git](https://img.shields.io/badge/git-automation-red)

Bot desenvolvido em Python para automatizar operações com GitHub, como **clone, commit e sincronização de múltiplos repositórios** de forma simples e prática.

---

## 🧠 Visão Geral

Este projeto foi criado para facilitar o gerenciamento de vários repositórios ao mesmo tempo, eliminando tarefas repetitivas como:

- Clonar vários repositórios manualmente  
- Atualizar repositórios locais (`git pull`)  
- Enviar alterações (`git push`)  

Tudo isso é feito automaticamente através de scripts.

---

## 🚀 Funcionalidades

✔ Clona todos os repositórios de um usuário do GitHub  
✔ Atualiza repositórios já existentes (`git pull`)  
✔ Envia alterações locais automaticamente (`git add`, `commit`, `push`)  
✔ Ignora repositórios que não são Git  
✔ Estrutura simples e fácil de adaptar  

---

## ⚙️ Tecnologias Utilizadas

- Python  
- Git CLI  
- GitHub API  
- Requests  

---

## 🏗️ Funcionamento

O bot executa três etapas principais:

1. 🔍 Busca os repositórios do usuário via API do GitHub  
2. 📥 Clona os repositórios que ainda não existem localmente  
3. 📤 Atualiza ou envia alterações para os repositórios existentes  

---

## 📁 Estrutura esperada
