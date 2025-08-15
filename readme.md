# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de Git e Github

## Configuração inicial 
Rode os comandos abaixo no terminal(cmd) do seu computador
```bash 
git config --global user.name "Caio Vinicius Alves"
git config --global user.email caio.alves17@fatec.sp.gov.br
```

## Comandos do Git
Para iniciar o GIT em uma pasta do computador, utilizamos o init.
**IMPORTANTE:** Só é executado 1x.
```bash
git init
```

PAra vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lista de comandos que aparece no site.
**IMPORTANTE:** Depois do remote deve ser executados os outros 2 comandos da página.
```bash
git remote add origin < url_repositorio_github >
```



Para verificar a situação do repositório (pasta), usamos o status a qualquer momento.
```bash
git status
```

Ele prepara o arquivo para ser commitado. Todos os arquivos que o status aparecer como vermelho, deve ser usado esse comando.
```bash
git add . (o ponto serve para adicionar todas as pendências)
```

Para salvar e atualizar as novas adições, usamos
**IMPORANTE:** Realizar sempre no final de algum trabalho ou caso estiver trabalhando com algo sensível, salvar sempre.
```bash
git commit -m "mensagem para lembrar do que fez"
```

Para baixar as alterações que estão apenas no Github utilizamos o pull.
**IMPORTANTE:** Sempre deve baixar a ultima versão da nuvem antes de enviar a atual do computador
```bash
git pull
```

Para enviar os commits do pc para o Github utilizamos o push.
```bash
git push
```

Para baixar o repositório do Github em um novo computador utilizamos o clone
```bash
git clone < url do repositório do github > 
```
