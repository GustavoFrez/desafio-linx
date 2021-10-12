# Desafio Linx - Tarefas a fazer


## Sobre

Página responsiva de um gerenciador de tarefas desenvolvido em Sass.

![npm](https://img.shields.io/badge/npm-6.1.13-orange)
![node](https://img.shields.io/badge/NodeJS-14.17.0-brightgreen)
![Sass](https://img.shields.io/badge/Sass-2.14.2-pink)

## Link da página pronta

  https://gustavofrez.github.io/desafio-linx/

## Passo a passo 

Primeiramente você deve ter instalado em sua máquina o Node.js, caso você não possua o Node.js você pode estar efetuando download através desse link https://nodejs.org/en/download/ de acordo com o seu sistema operacional.

Após a instalação do Node.js você pode testar se ele está devidamente instalado abrindo o terminal do seu sistema operacional e digitando na sua linha de comando > node -v e aparecerá a versão do Node.js instalada em sua máquina.
<br><br>
Exemplo Node.js :
<br><br>
![Node](https://i.ibb.co/w43WqSq/prompt-comando.png)

Nosso próximo passo será clonar este repositório e você precisará ter instalado em sua máquina o GIT, caso não tenha também, basta efetuar o download através desse link https://git-scm.com/downloads e instalar.
<br><br>
Exemplo de como clonar o repositório:
<br><br>

![GITClone](https://i.ibb.co/Zm0bxkb/git-clone-linx.png)
<br><br>

Crie uma pasta em local de preferência, abra essa pasta e clique dentro com o botão direito dou mouse e selecione a opção GIT BASH HERE.

Dentro do GIT BASH, digite na sua linha de comando:

```sh
  $ git clone https://github.com/GustavoFrez/desafio-linx
```

Abra a pasta que clonou dentro de uma IDE, optamos por usar o VScode neste exemplo, caso você não tenha o VScode instalado em sua máquina você pode efetuar o download por aqui --> https://code.visualstudio.com/download

Agora vamos instalar o Sass através do terminal do VScode, você pode instalar
através do terminal de sua preferência.

![Sass](https://i.ibb.co/fk2xgBc/npm-sass.png)
<br><br>

Bastar copiar o comando abaixo:

```sh
  $ npm install -g sass
```

Para saber se o Sass está funcionando em sua máquina digite no terminal

```sh
  $ sass --version
```

![Sass](https://i.ibb.co/LkR5g02/sass-version.png)
<br><br>

Caso aconteça de aparecer o erro de script desabilitado basta seguir o passo a passo desse tutorial aqui https://paulosantanna.com/2012/10/14/habilitando-a-execucao-de-scripts-powershell/


Por fim basta você buildar do projeto digitando o seguinte comando:

![BuildSass](https://i.ibb.co/Pwxh6fn/build-sass-certo.png)
<br><br>

```sh
  $ sass --watch sass/app.sass:css/app.css
```
<br>
E pronto agora você já pode desenvolver!
<br><br>

Desenvolvido com :heart: por Gustavo Frez

Observações do desafio:

- Foi a primeira vez que desenvolvi algo com o Sass vi várias vantagens mas confesso que apanhei um pouco com relação a identação do código.

- Obrigado pela oportunidade além de um desafio foi um grande aprendizado para mim.


