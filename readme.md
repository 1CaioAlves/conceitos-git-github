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

