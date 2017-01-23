Start git

git config --global user.name "Seu nome"
git config --global user.email seu-email

(caso você queira setar name e email para um projeto específico só retirar o --global)

Editor (opcional)
git config --global core.editor nome-do-editor

Editor de diff
git config --global merge.tool nome-do-editor

Para visualizar as configurações
git config --list

Para visualizar apenas uma configuração
git config user.name  

Para ignorar arquivos ou pastas criar arquivo com nome:
.gitgnore
