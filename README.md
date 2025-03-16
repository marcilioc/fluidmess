# Sistema de Monitoramento e Controle de Fluidos por Medidas Mássicas
Repositório para registro dos documentos do TCC e gerenciamento das atividades relacionadas do projeto.

## Organização do diretório
``` md
@ TCC_template
|
|`---artigo------------|
|                      |`---img|
|                       `---artigo.md
|
|`---trabalho_academico|
|                      |`---img|
|                      |`---notas_referencias.md
|                       `---notas_permanentes.md
|
|`---gestao------------|
|                       `---ferrementas_de_gestao|
|                       `---gestao_do_projeto.md
|
 `---prog--------------|
                       |`---esp32-|
                       |           `--- . . .
                       |`---db----|
                       |           `--- . . .
                        `---server|
                                   `--- . . .
 
```

## Tutorial: Como fazer alterações em arquivos no GitHub
Como utilizar os comandos básicos de terminal do git para fazer atualizações no repositório

### 1. Verifique se o seu usuários está configurado no VS Code
```
$ git config --global user.name "Nome de Usuário"
$ git config --global user.email "email@exemplo.com"
```

### 2. Adicionar arquivos editados
Após fazer edições na sua IDE, será necessáirio informar quais arquivos editados serão adicionados ao repositório.
```
Para adicionar todas as edições:
$ git add .

Para adicionar arquivos específicos:
$ git add ./caminho/nome_do_arquivo
```

### 3. Criar um commit
O GitHub atualiza os arquivos por commits, que são pequenos pacotes rastreáveis de alterações no repositório. Com os arquivos informados, deve-se criar um commit para que os arquivos sejam alterados com rastreamento de mudanças e de quem mudou.

O commit deve ter uma mensagem informando o que foi feito obrigatoriamente. o recomendado é que a mensagem seja direta e explique claramente o que foi feito.
```
$ git commit -m "Exemplo de mensagem de commit"
```

### 4. Realizar o push
Após o commit, suas mudanças já estarão registradas e terão sua rastreabilidade. Porém, para realmente editar o repositório, é necessário enviar as alterações completamente. Para isso, deve-se utilizar o comando push.
```
$ git push
```

Pronto! Após realizar estes passos, suas alterações estarão na página do repositório no GitHub, indicadas com a mensagem do commit escrita anteriormente.