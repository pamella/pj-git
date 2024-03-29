# :star: pj-git
Repositório auxiliar ao treinamento de Git para a PJ. (Dez, 2019)


## Slides
- [Slides](http://bit.ly/pj-git)


## Fork esse repositório
Fork  esse repositório clicando no botão de fork  na parte superior desta página.
Isso criará uma cópia deste repositório em sua conta.

<img width="300" src="https://i.imgur.com/bQ4GWBK.png" alt="Fork esse repositório" />


## Clone o repositório
Agora clone este repositório para a sua máquina. Clique no botão "Clone or download" e, em seguida, clique no ícone "Copy to clipboard" para copiar a URL.

<img width="300" src="https://i.imgur.com/psXtajj.png" alt="Clone o repositório" />
<img width="300" src="https://i.imgur.com/6lcwvN4.png" alt="copiar URL" />

Abra seu terminal e execute o seguinte comando do git:
```
git clone <url que copiou>
```
onde "url que copiou" (sem as aspas) é a URL deste repositório. Consulte as etapas anteriores para obter a URL.

Por exemplo:
```
git clone https://github.com/seu-usuario/pj-git.git
```
onde "seu-usuário" é o seu usuário do GitHub. Aqui você está copiando o conteúdo do repositório pj-git para o seu computador.


## Crie uma branch

Vá para o diretório do repositório no seu computador (caso você não esteja lá):
```
cd pj-git
```

Agora crie uma branch usando o comando `git checkout`:
```
git checkout -b <add-seu-nome>
```

Por exemplo:
```
git checkout -b add-larissa-silva
```
Obs.: O nome da branch não precisa ter a sigla "add", mas nesse caso é recomendável, porque a finalidade desta branch é a de adicionar o seu nome a uma lista.


## Efetue as alterações necessárias e faça um Commit
Agora abra o arquivo `Contributors.md` em seu editor de código, adicione o seu nome a ele e salve o arquivo. 

Se você for para o diretório do projeto e executar o comando `git status`, verá que há alterações. Adicione essas alterações na branch que você acabou de criar utilizando o comando `git add`:
```
git add Contributors.md
```
Agora faça um Commit dessas alterações utilizando o comando `git commit`:
```
git commit -m "Add <seu-nome> to Contributors list"
```
preenchendo `<seu-nome>` com o seu nome.


## Faça um Push das alterações para o GitHub
Faça um Push utilizando o comando `git push`:
```
git push origin <add-seu-nome>
```
substituindo `<add-seu-nome>` pelo nome da branch que você criou anteriormente.


## Envie suas alterações para serem revisadas
Se você for para o seu repositório no GitHub, verá um botão `Compare & pull request`. Clique nesse botão.

<img src="https://i.imgur.com/S9e5SKa.png" alt="Crie um Pull Request" />

Agora envie um Pull Request.

<img src="https://i.imgur.com/Yznycm4.png" alt="Envie o Pull Request" />

Assim, poderei mergear as suas mudanças na branch principal (master) deste projeto. Você receberá um e-mail de notificação quando as alterações forem mergeadas.


## Referências
| Tópico | Referência |
| --- | --- |
| Pull request template |[Vinta django-react-boilerplate](https://github.com/vintasoftware/django-react-boilerplate/blob/master/.github/PULL_REQUEST_TEMPLATE.md)|
| Ideia do tipo de contribuição| [First Contributions](https://github.com/firstcontributions/first-contributions)|
| PR Checklist | [Pull Requests Checklist](https://devchecklists.com/pull-requests-checklist/) |
