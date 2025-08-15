# Conceitos de Git e Github 
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de git e Github

## Configuração inicial
Rode os comandos abaixo no terminal(cmd) do seu computador.
```bash
git config --global user.name "Gabriel Matos Jorge"

git config --global user.email gabriel.jorge01@fatec.sp.gov.br
```

## Comandos do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
IMPORTANTE: Só é executado 1 vez.
```bash
git init
``` 

Para vincular o projeto ao Github, utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lista de comandos que aparece no site.
**IMPORTANTE:** Depois do remote, deve ser executados os outros 2 comandos da página.
```bash
git remote add oringin < URL_repositorio_github >
```


Para verificar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

## Continuação dos comandos do Git
Para salvar seu arquivo, é necessário usar o commit-m "mensagem".
IMPORTANTE: coloque uma mensagem fácil de identificação do arquivo, e sempre use o commit para salvar seus arquivos.
```bash
git commit-m "Continuação da Criação de Arquivo" 
```

Para adicionar algum arquivo, utilize o git add . , o ponto ser para dizer que é para adicionar o arquivo no seu terminal, Pc e etc...
```bash
git add .
```


