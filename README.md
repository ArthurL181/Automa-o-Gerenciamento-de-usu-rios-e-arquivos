# Automa-o-Gerenciamento-de-usu-rios-e-arquivos

-Objetivo
Automatizar:
1. O gerenciamento de permissões de diretórios de projetos.
2. A geração de relatórios diários com arquivos modificados em `/shared`.

---

-1. Script `manage_permissions.sh`

-Função
Cria grupos e diretórios de projeto, configurando permissões e adicionando usuários.

-Uso
```bash
sudo ./manage_permissions.sh <nome_projeto> <usuario1> <usuario2> ...
