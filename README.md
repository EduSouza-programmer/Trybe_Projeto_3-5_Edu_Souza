<h1 align="center">
    <img alt="Image Trybe" src="https://i.ibb.co/d4W2x4g/trybe.png" width="400px" />
</h1>

<h3 align="center">
  Exercício 3-5: HTML & CSS - Projeto - HTML & CSS - Concluído o/ o/ o/
</h3>

<blockquote align="center">“Quanto mais você estuda, mais aprende e se aproxima de realizar seu sonhos!”</blockquote>

<h1></h1>

<p align="center">

  <a href="https://www.linkedin.com/in/eduardosouzaprogrammer/">
    <img alt="Made by Eduardo Souza" src="https://img.shields.io/badge/made%20by-Edu%20Souza-%23F8952D">
  </a>&nbsp;

 <a href="https://edusouza-programmer.github.io/">
<img alt="Github page Edu Souza " src="https://img.shields.io/badge/Github%20page-Edu_Souza-orange">
</a>&nbsp;

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

<p align="center">
  <a href="#rocket-Sobre-o-Exercício">Sobre o Exercício</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Entrega">Entrega</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Licença">Licença</a>
</p>

# :rocket: Sobre o Exercício

Essa é a hora de pôr em prática tudo o que você aprendeu durante a semana e mostrar para seus amigos o quanto você evoluiu.
Você utilizará as principais tags HTML para compor a estrutura de uma página e irá estilizar e alterar o posicionamento dos componentes através de CSS.
Nesta seção, você vai criar uma página, do zero, utilizando HTML e CSS. O objetivo é consolidar todo o conhecimento adquirido com a produção completa de um site.

- Entender como funciona a estrutura (HTML) de uma página;

- Entender como o estilo (CSS) é aplicado à página;

- Construir páginas utilizando HTML e CSS;

- Realizar manutenções em páginas já existentes;

- Aplicar Layout e Box Model na prática;

## Requisitos Obrigatórios:

Você deve criar um site que com uma série de informações a respeito do que você aprendeu nos últimos três blocos, estilizado de forma apropriada.

**Em outras palavras, uma página de `Lessons Learned`**;

**Lembre-se de verificar sua página no [achecker](https://achecker.ca/checker/index.php).**

# Sumário

### Requisitos do projeto

#### 1 - O corpo da página deve possuir uma cor de fundo específica

- Possuir cor de fundo: rgb(253, 251, 251)

#### 2 - Seu site deve possuir uma barra superior com um título

- A barra deve possuir o ID "cabecalho"

- O elemento com o id `cabecalho` deve ser fixo no topo da página, com a propriedade top tendo `0px`

- O título deve estar dentro da barra e possuir o ID "titulo", além de ser uma tag `h1`

#### 3 - A página deve possuir uma foto sua

- A foto deve ser inserida utilizando uma tag `img` com o ID "minha_foto"

#### 4 - A página deve possuir uma lista de lições aprendidas

- A lista deve ser numerada e possuir o ID "licoes_aprendidas"

- A lista deve possuir 10 itens

#### 5 - A página deve possuir uma lista de lições que ainda deseja aprender

- A lista **não** deve ser numerada e deve possuir o ID "licoes_a_aprender"

- A lista deve possuir 10 itens

#### 6 - A página deve possuir um rodapé

- O rodapé deve utilizar a tag `footer` e possuir o ID "rodape"

#### 7 - A página deve possuir pelo menos um link externo

- A configuração desse link deve ser feita para abrir em uma nova aba do navegador

#### 8 - Crie um artigo sobre seu aprendizado

- A `tag` `article` devem ser utilizadas

- O artigo deve ter mais de 300 letras e menos de 600

#### 9 - Crie uma seção que conta uma passagem sobre seu aprendizado

- A `tag` `aside` deve ser utilizada

- A seção deve ter mais que 100 letras e menos que 300

#### 10 - Torne o seu site mais acessível e melhore seu ranqueamento em mecanismos de busca na Web aplicando os elementos HTML de acordo com o sentido e propósito de cada um deles

- A página deve possuir um elemento `article`

- A página deve possuir um elemento `header`

- A página deve possuir um elemento `nav`

- A página deve possuir um elemento `section`

- A página deve possuir um elemento `aside`

- A página deve possuir um elemento `footer`

#### 11 - Seu site deve passar sem problemas na verificação de semântica do site achecker

### Requisitos Bônus:

#### 12 - Adicione uma tabela à página

- A página deve possuir uma tabela

#### 13 - Brinque com o Box model!

- Altere `margin`, `padding` e `border` dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes

#### 14 - Altere atributos relacionados as fontes

- Altere o tamanho da letra

- Altere a cor da letra

- Altere o espaçamento entre as linhas

- Altere o `font-family`

#### 15 - Faça com que seu artigo e seção sobre aprendizados fiquem um ao lado do outro

- Utilizar a classe 'lado-esquerdo'

- Utilizar a classe 'lado-direito'

- Verificar se os elementos com as classes lado-direito e lado-esquerdo estão posicionados corretamente

#

# Entrega

Essa página vai ser desenvolvida do zero, utilizando os arquivos index.html e style.css para o HTML e CSS, respectivamente. Leia o arquivo README.md do projeto com atenção para uma explicação detalhada de como desenvolver e entregar seu projeto.
Lembre-se de verificar sua página no achecker. Seu site deve passar sem problemas na verificação de semântica.

## Projeto [Meus códigos]

Você deverá criar um site utilizando as principais tags HTML para compor a estrutura de uma página e irá estilizar e alterar o posicionamento dos componentes através de CSS.

#### Resposta:

<details>
 <summary>Código HTML</summary>

```html
<!DOCTYPE html>
<html lang="pt">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://fonts.googleapis.com/css2?family=Caudex&family=Chelsea+Market&family=Lobster&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
    <title>Project-HTML&CSS</title>
  </head>

  <body>
    <header id="cabecalho">
      <h1 id="titulo">Projeto<br />HTML & CSS</h1>
    </header>
    <main>
      <div>
        <div class="nav-conteiner">
          <nav>
            <lu>
              <li><a href="#">Home</a></li>
              <li><a href="#sobre">Sobre</a></li>
              <li><a href="#rodape">Contatos</a></li>
            </lu>
          </nav>
        </div>
        <div class="main-conteiner conteiner">
          <div class="itens">
            <a
              href="https://www.linkedin.com/in/eduardosouzaprogrammer/"
              target="_blank"
            >
              <img
                id="minha_foto"
                src="https://i.ibb.co/NNvbkXY/117194973-1970721483063027-331802382092093166-n.jpg"
                alt="Foto de um cara muito legal e estudioso chamado Edu Souza"
              />
            </a>
          </div>
          <div class="itens">
            <article class="main-article">
              <h1>Eduardo Souza</h1>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat,
                incidunt earum. Quisquam totam in accusamus magnam. officia
                sapiente dicta adipisci modi consectetur saepe laborum.
                consectetur saepe laborum.
              </p>
            </article>
          </div>
        </div>
      </div>
    </main>
    <section id="sobre" class="experiencias">
      <div class="quotes-svg">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
          <path
            d="M228 119c5.523 0 10-4.478 10-10V77c0-27.57-22.43-50-50-50H50C22.43 27 0 49.43 0 77v119.988c0 27.57 22.43 50 50 50h64.692c-2.276 74.706-30.621 113.542-86.459 118.622a10 10 0 00-9.094 9.959V475a10 10 0 0010.561 9.984c68.908-3.876 121.511-27.591 156.349-70.487C220.521 372.051 238 310.029 238 230.152v-35.819c0-5.522-4.477-10-10-10s-10 4.478-10 10v35.819c0 146.644-58.535 223.331-178.86 234.097v-79.836c30.411-4.73 53.934-18.886 70.007-42.161 17.049-24.691 25.694-60.106 25.694-105.264 0-5.522-4.477-10-10-10H50c-16.542 0-30-13.458-30-30V77c0-16.542 13.458-30 30-30h138c16.542 0 30 13.458 30 30v32c0 5.522 4.477 10 10 10zM462 27H324c-27.57 0-50 22.43-50 50v119.988c0 27.57 22.43 50 50 50h64.692c-2.276 74.706-30.621 113.542-86.459 118.622a10 10 0 00-9.094 9.959V475a10 10 0 0010.561 9.984c68.908-3.876 121.511-27.591 156.349-70.487C494.521 372.052 512 310.029 512 230.152V77c0-27.57-22.43-50-50-50zm30 203.152c0 146.644-58.535 223.331-178.861 234.097v-79.836c30.412-4.73 53.935-18.886 70.007-42.161 17.049-24.69 25.694-60.105 25.694-105.264 0-5.522-4.477-10-10-10H324c-16.542 0-30-13.458-30-30V77c0-16.542 13.458-30 30-30h120v74.034c0 5.522 4.477 10 10 10s10-4.478 10-10v-73.96c15.612 1.034 28 14.057 28 29.926v153.152z"
          />
          <path
            d="M454 145.751c-5.523 0-10 4.527-10 10.049 0 5.522 4.477 10 10 10 5.522 0 10-4.478 10-10v-.099c0-5.522-4.477-9.95-10-9.95zM228 141.666c-5.523 0-10 4.478-10 10v.209c0 5.522 4.477 10 10 10s10-4.478 10-10v-.209c0-5.522-4.477-10-10-10z"
          />
        </svg>
      </div>

      <aside>
        <h1>Experiência com a <em>Trybe</em></h1>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Distinctio
          expedita iure iste quae incidunt alias necessitatibus, dolorem,
          cupiditate voluptates fugit earum facilis voluptates fugit earum.
        </p>
      </aside>
      <div class="rocket-svg">
        <svg viewBox="0 0 512.004 512.004" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M130.239 138.268l-44.358 3.427c-12.343.954-23.336 7.423-30.162 17.748L4.562 236.815c-5.177 7.83-6 17.629-2.203 26.213 3.798 8.584 11.603 14.566 20.878 16.003l40.615 6.29c9.501-50.42 32.245-100.716 66.387-147.053zM226.682 448.151l6.291 40.615c1.437 9.275 7.419 17.08 16.002 20.877a27.434 27.434 0 0011.112 2.36 27.34 27.34 0 0015.102-4.563l77.374-51.156c10.325-6.827 16.794-17.821 17.746-30.162l3.427-44.358c-46.338 34.143-96.633 56.887-147.054 66.387zM211.407 420c1.41 0 2.828-.116 4.243-.352 21.124-3.532 41.484-9.482 60.906-17.27l-166.93-166.93c-7.788 19.421-13.738 39.781-17.27 60.906-1.392 8.327 1.401 16.81 7.37 22.78l93.144 93.144c4.956 4.955 11.645 7.722 18.537 7.722zM471.178 227.003c40.849-78.974 42.362-162.43 40.227-201.57C510.674 12.022 499.982 1.33 486.57.599A412.7 412.7 0 00464.131 0C420.365 0 351.114 6.629 285 40.826c-52.542 27.177-121.439 87.018-162.087 165.66.48.375.949.773 1.391 1.215l180 180c.442.442.839.91 1.214 1.39 78.642-40.649 138.483-109.546 165.66-162.088zM297.698 108.24c29.241-29.241 76.822-29.244 106.065 0 14.166 14.165 21.967 33 21.967 53.033s-7.801 38.868-21.967 53.033c-14.619 14.619-33.829 21.93-53.032 21.932-19.209.001-38.41-7.309-53.033-21.932-14.166-14.165-21.968-33-21.968-53.033s7.802-38.868 21.968-53.033z"
          />
          <path
            d="M318.911 193.092c17.545 17.545 46.095 17.546 63.64 0 8.499-8.5 13.18-19.8 13.18-31.82s-4.681-23.32-13.18-31.819c-8.772-8.773-20.296-13.159-31.82-13.159-11.523 0-23.047 4.386-31.819 13.159-8.499 8.499-13.181 19.799-13.181 31.819s4.681 23.321 13.18 31.82zM15.305 421.938c3.839 0 7.678-1.464 10.606-4.394l48.973-48.973c5.858-5.858 5.858-15.355 0-21.213-5.857-5.858-15.355-5.858-21.213 0L4.698 396.331c-5.858 5.858-5.858 15.355 0 21.213a14.954 14.954 0 0010.607 4.394zM119.765 392.239c-5.857-5.858-15.355-5.858-21.213 0L4.397 486.394c-5.858 5.858-5.858 15.355 0 21.213C7.326 510.536 11.165 512 15.004 512s7.678-1.464 10.606-4.394l94.154-94.154c5.859-5.858 5.859-15.355.001-21.213zM143.432 437.12L94.46 486.093c-5.858 5.858-5.858 15.355 0 21.213 2.929 2.929 6.768 4.394 10.606 4.394s7.678-1.464 10.606-4.394l48.973-48.973c5.858-5.858 5.858-15.355 0-21.213-5.857-5.858-15.355-5.858-21.213 0z"
          />
        </svg>
      </div>
    </section>
    <section>
      <div class="licoes-conteiner conteiner">
        <div class="lado-esquerdo">
          <h1>Lições Aprendidas</h1>
          <ol id="licoes_aprendidas">
            <li>Unix</li>
            <li>Git & GitHub</li>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>VScode</li>
            <li>Unit Tests</li>
            <li>DOM</li>
            <li>Slack</li>
            <li>Semantic HTML</li>
          </ol>
        </div>
        <div class="lado-direito">
          <h1>Desejo aprender</h1>
          <ul id="licoes_a_aprender">
            <li>React</li>
            <li>React-Native</li>
            <li>NodeJs</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>VScode</li>
            <li>Unit Tests</li>
            <li>DOM</li>
            <li>Slack</li>
            <li>Semantic HTML</li>
          </ul>
        </div>
      </div>
    </section>
    <div class="table">
      <table>
        <thead>
          <tr>
            <th>
              100% Concluído
              <svg
                height="512pt"
                viewBox="0 -13 512.00014 512"
                width="512pt"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="m511.074219 401.507812c-2.402344-11.5625-9.199219-21.441406-19.140625-27.820312-9.941406-6.375-21.75-8.433594-33.265625-5.800781l-53.367188 12.21875v-21.816407c10.703125-10.082031 21.847657-23.246093 29.773438-35.277343 13.898437-21.097657 23.734375-44.265625 29.234375-68.847657 6.539062-29.246093 6.679687-60.207031.402344-89.546874-1.15625-5.398438-6.472657-8.84375-11.871094-7.683594-5.402344 1.152344-8.839844 6.46875-7.6875 11.871094 5.679687 26.535156 5.554687 54.542968-.363282 80.992187-4.96875 22.210937-13.859374 43.144531-26.417968 62.210937-3.722656 5.652344-8.238282 11.582032-13.070313 17.246094v-110.84375c0-5.523437-4.476562-10-10-10h-79.105469v-106.789062c0-5.507813-4.457031-9.980469-9.964843-10l-89.105469-.300782c-.011719 0-.019531 0-.03125 0-2.648438 0-5.1875 1.046876-7.058594 2.917969-1.882812 1.875-2.941406 4.421875-2.941406 7.082031v55.550782h-79.117188c-5.519531 0-10 4.476562-10 10v99.027344h-22.28125v-13.582032c0-5.519531-4.476562-9.996094-10-9.996094h-10.257812c-1.746094-9.613281-2.757812-19.378906-2.996094-29.128906-.585937-23.707031 3.171875-46.902344 11.164063-68.949218 1.863281-5.140626 3.980469-10.265626 6.289062-15.226563 2.332031-5.007813.160157-10.957031-4.84375-13.289063-5.007812-2.324218-10.957031-.160156-13.285156 4.847657-2.558594 5.492187-4.902344 11.164062-6.960937 16.851562-8.84375 24.394531-13 50.054688-12.359376 76.257813.238282 9.578125 1.152344 19.164062 2.703126 28.636718h-45.148438c-5.523438 0-10 4.476563-10 10v175.773438c0 5.523438 4.476562 10 10 10h75.695312c5.523438 0 10-4.476562 10-10v-9.507812h37.617188l152.378906 59.765624c14.226563 5.582032 29.128906 8.390626 44.109375 8.390626 9.988281 0 20.019531-1.25 29.898438-3.761719l119.433593-30.355469c22.671876-5.761719 36.699219-28.214844 31.941407-51.117188zm-125.769531-173.097656v156.273438l-26.734376 6.121094c-2.875.65625-5.78125 1.175781-8.703124 1.582031-11.140626 1.535156-22.507813 1.210937-33.53125-.972657-.046876-.011718-.09375-.019531-.140626-.03125v-15.164062c7.625-11.375 10.152344-25.796875 6.15625-38.960938-1.113281-3.671874-2.695312-7.214843-4.707031-10.484374-.457031-.742188-.933593-1.46875-1.429687-2.179688-.003906-.011719-.011719-.019531-.019532-.03125v-96.15625h69.109376zm-158.210938-117.054687 69.105469.230469v197.09375l-38.621094-15.984376-30.484375-12.621093zm-89.117188 65.515625h69.105469v94.917968l-12.402343-5.132812c-1.214844-.503906-2.515626-.761719-3.824219-.761719h-52.878907zm-62.28125 241.222656h-55.695312v-155.777344h47.179688c.019531 0 .042968.003906.066406.003906.019531 0 .035156-.003906.054687-.003906h8.394531zm398.511719 15.148438-119.433593 30.355468c-20.617188 5.238282-41.980469 3.898438-61.78125-3.863281l-154.136719-60.457031c-1.164063-.457032-2.402344-.6875-3.652344-.6875h-39.507813v-112.691406h93.167969l64.703125 26.78125 35.40625 14.65625c12.527344 5.195312 18.523438 19.890624 13.386719 32.402343-1.03125 2.511719-2.308594 4.898438-4.003906 7.027344-6.261719 7.902344-16.570313 11.386719-26.210938 9.042969-.078125-.019532-.15625-.039063-.234375-.058594-.578125-.144531-1.152344-.3125-1.722656-.5l-67.285156-25.867188c-.546875-.210937-.835938-.320312-.835938-.320312-5.152344-1.984375-10.9375.589844-12.921875 5.746094-1.980469 5.152344.589844 10.941406 5.746094 12.921875 0 0 37.9375 14.585937 66.867187 25.742187.582032.226563 1.160157.4375 1.742188.632813l22.214844 8.542969c6.714844 2.582031 13.398437 5.152343 20.386718 6.9375 11.867188 3.03125 24.183594 4.25 36.417969 3.582031 6.898438-.375 13.785157-1.328125 20.519531-2.867188l34.496094-7.894531c.035156-.007812.070313-.023438.105469-.03125l65.492187-14.992188c6.230469-1.425781 12.625-.3125 18 3.136719 5.382813 3.453125 9.058594 8.800781 10.359376 15.058594 2.578124 12.394531-5.015626 24.546875-17.285157 27.664063zm0 0"
                />
                <path
                  d="m127.878906 71.125c2.390625 0 4.789063-.851562 6.699219-2.578125 17.84375-16.117187 39.152344-28.972656 61.632813-37.179687 24.355468-8.890626 51.054687-12.683594 77.214843-10.964844 18.722657 1.230468 37.066407 5.226562 54.519531 11.875 5.15625 1.964844 10.9375-.621094 12.902344-5.785156 1.96875-5.160157-.621094-10.9375-5.785156-12.902344-19.3125-7.359375-39.609375-11.78125-60.324219-13.144532-28.914062-1.898437-58.441406 2.296876-85.386719 12.136719-24.871093 9.078125-48.445312 23.300781-68.175781 41.121094-4.101562 3.703125-4.421875 10.027344-.71875 14.125 1.972657 2.1875 4.691407 3.296875 7.421875 3.296875zm0 0"
                />
                <path
                  d="m354.886719 142.492188c1.894531 1.644531 4.230469 2.449218 6.554687 2.449218 2.792969 0 5.574219-1.164062 7.554688-3.4375l82.273437-94.707031c3.625-4.167969 3.179688-10.484375-.988281-14.105469-4.171875-3.621094-10.484375-3.179687-14.105469.988282l-82.277343 94.707031c-3.625 4.167969-3.179688 10.484375.988281 14.105469zm0 0"
                />
                <path
                  d="m428.617188 99.738281c-13.84375 0-25.105469 11.261719-25.105469 25.105469s11.261719 25.105469 25.105469 25.105469 25.105468-11.265625 25.105468-25.105469c0-13.84375-11.261718-25.105469-25.105468-25.105469zm0 30.210938c-2.816407 0-5.105469-2.289063-5.105469-5.105469 0-2.8125 2.289062-5.105469 5.105469-5.105469 2.8125 0 5.105468 2.292969 5.105468 5.105469 0 2.816406-2.292968 5.105469-5.105468 5.105469zm0 0"
                />
                <path
                  d="m373.085938 77.476562c13.84375 0 25.105468-11.261718 25.105468-25.105468s-11.261718-25.105469-25.105468-25.105469-25.105469 11.261719-25.105469 25.105469 11.261719 25.105468 25.105469 25.105468zm0-30.214843c2.816406 0 5.105468 2.292969 5.105468 5.109375 0 2.8125-2.289062 5.105468-5.105468 5.105468-2.816407 0-5.105469-2.292968-5.105469-5.105468 0-2.816406 2.289062-5.109375 5.105469-5.109375zm0 0"
                />
                <path
                  d="m92.328125 94.625c1.601563 3.84375 5.542969 6.382812 9.71875 6.164062 4.128906-.214843 7.746094-3.007812 9.023437-6.929687 1.289063-3.957031-.117187-8.464844-3.425781-10.992187-3.371093-2.570313-8.105469-2.730469-11.636719-.382813-3.917968 2.605469-5.488281 7.800781-3.679687 12.140625zm0 0"
                />
              </svg>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>
              Quanto mais você estuda, mais aprende e se aproxima de realizar
              seu sonhos!
            </td>
          </tr>
        </tbody>
      </table>
    </div>

    <footer id="rodape">
      <div>
        <p>
          Feito com &hearts; por
          <em
            ><a
              href="https://github.com/EduSouza-programmer/EduSouza-programmer.github.io"
              target="_blank"
              >Edu Souza : estudante -- turma 7</a
            ></em
          >
        </p>
      </div>
    </footer>
  </body>
</html>
```

</details>

<details>
 <summary>Código CSS</summary>

```CSS
* {
  margin: 0;
  padding: 0;
  border: 0;
}

.conteiner::after,
.conteiner::before {
  content: "";
  display: table;
  clear: both;
}

body {
  background-color: rgb(253, 251, 251);
  font-family: 'Chelsea Market', cursive;


}

#cabecalho {
  position: fixed;
  top: 0;
  width: 100%;
  /* background-color: rgb(131, 226, 43); */
  background-image: url("https://i.ibb.co/LpqJBpX/cool-background-main.png");
  background-size: cover;
  border-bottom: 3px solid rgba(165, 42, 42, 0.281);
  margin: 0 auto;
  text-align: center;
  padding: 10px;
  font-size: 10px;
  z-index: 10;



}

/* hero */

main {
  background-image: url("https://i.ibb.co/LpqJBpX/cool-background-main.png");
  background-size: cover;
  border-bottom: 2px solid rgba(165, 42, 42, 0.281);


}

.nav-conteiner {
  width: 700px;
  background-color: rgba(165, 42, 42, 0.247);
  padding: 10px;
  margin-top: 70px;
  border-radius: 0 0 10px 10px;
  border-top: 2px solid rgba(165, 42, 42, 0.281);

}

.nav-conteiner li {
  display: inline-block;
  margin: 0 30px;
  line-height: 25px;



}

.nav-conteiner a {

  text-decoration: none;
  font-size: 18px;
  color: whitesmoke;

}

.nav-conteiner a:hover {
  border-bottom: 3px dashed rgba(240, 240, 240, 0.658);
  font-weight: bold;

}



main div {

  /* background-color: aqua; */
  max-width: 1170px;
  margin: 0 auto;
  text-align: center;
  padding-bottom: 30px;
  line-height: 25px;


}

.itens {

  width: 540px;
  margin: 30px 20px;
  float: left;

}


.itens img {

  margin-top: 40px;
  width: 345px;
  border-radius: 20% 5px 20% 5px;
  border: 3px solid rgba(165, 42, 42, 0.24);



}

.itens article {
  margin-top: 90px;
}

.itens h1 {
  padding: 30px 0;
  font-size: 40px;
  color: antiquewhite;

}

/* seção experiencias */

.experiencias {
  max-width: 1170px;
  margin: 0 auto;
  text-align: center;
  padding: 60px 0 30px 0;
  /* background-color: brown; */
}

.experiencias em {
  color: rgb(39, 190, 39);
  text-decoration: underline;
  font-size: 32px;
}

.experiencias h1 {

  font-size: 24px;
}




.experiencias p {
  width: 700px;
  padding: 60px 0 30px;
  margin: 0 auto;
  /* background-color: blue; */
  line-height: 25px;

}


.quotes-svg {
  width: 70px;
  height: 70px;
  margin: 0 auto 0px 200px;



}

.rocket-svg {
  width: 70px;
  height: 70px;
  margin: 30px auto;

}

.licoes-conteiner {
  max-width: 1170px;
  margin: 0px auto;
  /* background-color: yellow; */
  text-align: center;
  padding-top: 15px;
  padding-bottom: 60px;


}

.licoes-conteiner div {
  width: 450px;
  float: left;
  margin: 0 65px;
  /* background-color: blueviolet; */
  padding: 0 0 15px;
}

.licoes-conteiner h1 {
  font-size: 24px;
}

#licoes_aprendidas {
  text-align: left;
  margin-left: 100px;
  padding: 30px 0;

}

#licoes_a_aprender {
  text-align: left;
  margin-left: 100px;
  padding: 30px 0;
}

.table {
  max-width: 1170px;
  margin: 0 auto;

  text-align: center;

}

.table table {
  display: inline;
}

.table svg {
  width: 30px;
  height: 30px;
}



#rodape {
  text-align: center;
  padding: 20px 0;
  background-image: url("https://i.ibb.co/LpqJBpX/cool-background-main.png");
  background-size: cover;
  border-top: 2px solid rgba(165, 42, 42, 0.281);
}

#rodape div {
  max-width: 1170px;
  margin: 0 auto;
}

#rodape a {
  color: whitesmoke;
  text-decoration: none;
  font-size: 18px;
}

#rodape a:hover {
  border-bottom: 3px dashed rgba(240, 240, 240, 0.658);
  font-weight: bold;
}
```

</details>

<p align="right">
    <a href="https://edusouza-programmer.github.io/Trybe_Projeto_3-5_Edu_Souza/index.html">
    <img alt="Go index.html" src="https://img.shields.io/badge/Go-index.html-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

## Licença

Este projeto está licenciado sob a Licença MIT - consulte [LICENSE](https://opensource.org/licenses/MIT) para maiores detalhes.
