# Meu primeiro arquivo de programacao

Resumos de comandos mais usados.

## 😍  Perfis sociais
- [GITHUB](https://github.com/leopoldosilvajr)
- [LINKEDIN](https://br.linkedin.com/in/leopoldosilvajunior)

## 🎀 Básico de Git
| AULA 1 - Configurando Git| Comando | Extras | 
| ------------- | ------------- | ------------ |
| Fazer configurações gerais no seu local de trabalho   | ````git config````  |  |
| Criar pastas | ````mkdir NOME DA PASTA````  |  |
| Criar pastas | ````touch NOMEDOARQUIVO.EXTENSAO````  | Pode fazer só um comando e dar espaço para criar diversos arquivos |


| AULA 2 - Repositórios  | Comando | Extras | 
| ------------- | ------------- | ------------ |
| Adicionar repositório remoto em seu local de dev  | ````git clone http ou SSH do repositório````  | http usa token gerado pela plataforma do github |
| Abrir o git  | ````git init````  | ideal abrir o diretório pelo explorador de arquivos e usar a opção git bash here no botão direito do mouse |
| Adicionar repositório remoto em seu local de dev  | ````git remote````  | exemplo ````git remote add origin https://github.com/username/nome-do-repositorio.git```` |
| Verificar se há alguma alteração pendente de realizar  | ````git status````  |  |
| Quando não quer adicionar algo no commit para ir para o git  | ````echo NOME DA PASTA OU ARQUIVO/ > .gitignore````  |  |
| Adicionar arquivo ou pasta para ser enviada para o repositório do git  | ````git add NOMEDOARQUIVO.EXTENSAO````  | usar add . para adicionar todas alterações no commit |
| Passar documentos do seu local para o repositório no Git  | ````git commit````  | Adicionar ````git commit -m"TEXTO"```` para adicionar um comentário neste commit |
| Verificar histórico de commits e comentários  | ````git log````  | |
| Verificar histórico detalhado de commits e comentários  | ````git reflog````  | Mostra histórico completo de alterações |
 

| AULA 3 - Desfazer alterações de repositórios  | Comando | Extras | 
| ------------- | ------------- | ------------ |
| Quando você inicia o git em uma pasta errada  | ````rm -rf .git````  | O .git pode ser trocado por outro nome de diretório |
| Para restaurar alterações indesejadas para a última versão que foi commitada | ````git restore NOMEDOARQUIVO.EXTENSAO````  |  |
| Retornar para commit anterior | ````git reset --OPCAO HASHCOMMIT````  | soft / mixed / hard |
| Para alterar descrição de um commit | ````git commit --amend -m"NOVO TEXTO"````  |  |

## 🔍 Referências

[CONTEÚDO GIT](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)