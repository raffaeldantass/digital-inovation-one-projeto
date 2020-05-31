### Projeto - Réplica da Home do Github
Bem vindo! Aqui você encontra as instruções nencessárias para preparar seu ambiente de desenvolvimento e baixar os arquivos deste projeto. Vamos fazer juntos através das aulas deste mini curso! 

#### Instalação dos arquivos necessários
Se você não tem o Node instalado na sua máquina, por favor, instale, siga este [link aqui](https://nodejs.org/en/download/), veja qual é o seu sistema operacional e baixe o respectivo instalador, caso queira saber mais sobre o que é o NodeJS, você pode checar neste [tutorial](https://nodejs.org/en/about/). 

Será importante também instalar o Git na sua máquina para baixarmos os arquivos do projeto, caso não tenha ainda na sua máquina, você pode fazer o download por [aqui](https://git-scm.com/downloads).

Usaremos o VSCode como editor neste projeto, caso não tenha, você pode fazer o download [aqui](https://code.visualstudio.com/download), não é obrigatório, você pode usar o editor de sua preferência, mas recomendamos utilizar o VSCode pela facilidade. 

---

#### Preparação do ambiente
Primeiramente, no seu computador, recomendamos criar uma pasta para colocar todos os seus projetos, caso já tenha, pode seguir adiante. 

Agora vamos fazer o clone do repositório deste projeto na sua máquina, para isso, abra seu terminal, navegue até a pasta onde deseja deixar o projeto e em seguida, copie e cole o código abaixo no seu terminal: <br/>
`git clone https://github.com/raffaeldantass/digital-inovation-one-projeto.git && cd digital-inovation-one-projeto`
Se preferir basta fazer o Download do Projeto e deixar no local de sua preferência. 

Agora, como você tem o NodeJS instalado na sua máquina, vamos instalar um pacote para criar nosso servidor local, ele é bem simples e não tem nada de especial, mas vai nos dar algumas possibilidades extras. 
Copie o código abaixo e cole no seu terminal: <br />
`npm install --global http-server`

---

#### Rodando o projeto
Agora que temos tudo instalado e pronto, vamos rodar e começar a estruturar nosso projeto. 
No seu editor, você vai encontrar o projeto estruturado da seguinte forma: 

```
src
  index.html
  assets
  scripts
  style
.gitignore
LICENSE
README.md
```

Para que o nosso servidor local encontra o arquivo inicial que, neste caso, é o `index.html`, vamos rodar no nosso terminal o seguinte comando: 
`http-server ./src`

Mas **atenção**, é necessário rodar esse comando no seu terminal diretamente do local onde você deixo o seu projeto, então, se for dentro da pasta *Projetos*, será algo como mostrado abaixo: 
`~/projetos/home-github http-server ./src`
Ou se for no Windows: 
`C:\user\projetos\home-github> http-server ./src`

E é isso, agora que temos o projeto rodando, vamos começar! 
