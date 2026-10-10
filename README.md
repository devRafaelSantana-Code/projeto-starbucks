# ☕ Starbucks Happy Hour — Showcase Interface

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/CSS%20Grid-6C63FF?style=for-the-badge" alt="CSS Grid">
  <img src="https://img.shields.io/badge/Flexbox-0A7EA4?style=for-the-badge" alt="Flexbox">
  <img src="https://img.shields.io/badge/Responsive%20Design-2E8B57?style=for-the-badge" alt="Responsive Design">
</p>

## 📌 Sobre o Projeto

Este projeto consiste numa **recriação front-end de uma interface promocional inspirada na campanha Starbucks® Happy Hour**.

Desenvolvido a partir de desafios práticos propostos pela plataforma **B7Web**, o projeto reproduz uma landing page composta por secções promocionais, imagens de produtos, conteúdos institucionais e elementos de navegação.

O principal objetivo é consolidar conhecimentos de **HTML5 e CSS3**, com destaque para a construção de layouts responsivos, a utilização combinada de CSS Grid e Flexbox, a organização de recursos visuais e a aplicação de tipografia para estabelecer hierarquia e identidade visual.

A interface procura reproduzir a composição visual de uma página promocional, explorando a distribuição dos conteúdos, o posicionamento das imagens e a adaptação dos elementos a diferentes dimensões de ecrã.

> **Nota:** Projeto desenvolvido para fins educacionais, sem afiliação oficial, patrocínio ou aprovação da Starbucks®.

---

## 🌐 Demonstração Online

A aplicação está disponível para visualização através da Vercel.

<p align="center">
  <a href="https://projeto-starbucks-nu.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/VER%20PROJETO%20ONLINE-006341?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver projeto online na Vercel">
  </a>
</p>

🔗 **Link direto:** [https://projeto-starbucks-nu.vercel.app/](https://projeto-starbucks-nu.vercel.app/)

Explora a interface promocional e a adaptação do layout a diferentes dimensões de ecrã.

---

## 🛠️ Detalhes Técnicos

### 🧩 Layout com CSS Grid e Flexbox

A construção da interface utiliza diferentes técnicas de layout, escolhidas de acordo com as necessidades de cada secção.

O **Flexbox** permite organizar elementos ao longo de um eixo principal e alinhar os seus conteúdos, sendo adequado para barras de navegação, agrupamentos de elementos e componentes flexíveis.

O **CSS Grid** permite estruturar as principais áreas promocionais através de linhas e colunas, facilitando a distribuição dos blocos de conteúdo e a criação de composições visuais.

Exemplo de configuração:

```css
grid-template-columns: repeat(2, 1fr);
```

A função `repeat()` simplifica a definição das colunas, enquanto a unidade `fr` distribui o espaço disponível entre as colunas da grelha.

### 📐 Posicionamento dos Elementos na Grid

As propriedades `grid-column` e `grid-row` permitem definir a posição dos elementos e controlar a extensão que ocupam dentro da grelha.

Exemplo:

```css
grid-column: 1 / 3;
grid-row: 1 / 2;
```

Neste exemplo, o elemento ocupa duas colunas, delimitadas pelas linhas de grelha 1 e 3, e posiciona-se na primeira linha.

Esta técnica permite criar composições assimétricas e distribuir os conteúdos de forma flexível, sendo particularmente útil em layouts promocionais e editoriais.

### 🔤 Tipografia com Google Fonts

O projeto utiliza fontes externas disponibilizadas pelo **Google Fonts** para estabelecer diferentes níveis de hierarquia tipográfica.

- **Oswald:** utilizada nos títulos e nas chamadas promocionais de maior destaque.
- **Open Sans:** utilizada nos textos descritivos e nos restantes conteúdos da interface.

A combinação destas famílias tipográficas contribui para diferenciar títulos e textos corridos, reforçando a organização visual da página.

### 🖼️ Imagens e Banner

A interface utiliza imagens de produtos e recursos visuais para reproduzir a identidade da campanha promocional.

Na área de destaque, as propriedades CSS de fundo permitem adaptar a imagem à dimensão do elemento:

```css
background-size: cover;
background-position: center;
```

A propriedade `background-size: cover` dimensiona a imagem para preencher a área disponível, preservando as proporções. Quando necessário, partes da imagem podem ficar fora da área visível.

Já `background-position: center` define o centro da imagem como referência para o seu posicionamento.

As imagens dos produtos e os elementos gráficos complementares contribuem para a composição visual e para a consistência estética da interface.

---

## 📱 Responsividade

O projeto utiliza **Media Queries** para adaptar a apresentação dos conteúdos a diferentes dimensões de ecrã.

Esta abordagem permite aplicar regras CSS específicas de acordo com a largura do viewport e outras características da área de visualização.

Entre os principais aspetos da adaptação responsiva, destacam-se:

- Ajuste dos tamanhos de fonte;
- Redimensionamento das imagens;
- Reorganização das áreas definidas com CSS Grid;
- Adaptação dos espaçamentos internos e externos;
- Alteração da disposição de determinados elementos;
- Melhoria da legibilidade em ecrãs de menores dimensões.

O objetivo é preservar a hierarquia visual e proporcionar uma experiência de utilização consistente em computadores, tablets e dispositivos móveis.

---

## 🎨 Estrutura Visual e Identidade

A composição visual utiliza uma paleta de cores inspirada na identidade gráfica associada à campanha representada.

### 🎨 Cores Principais

| Cor       | Utilização                                |
| --------- | ----------------------------------------- |
| `#006341` | Destaques visuais e títulos secundários   |
| `#117050` | Elementos de destaque e detalhes gráficos |

A utilização consistente destas cores ajuda a estabelecer continuidade visual entre as diferentes secções da página.

### 📏 Largura do Conteúdo

O projeto utiliza unidades relativas ao viewport e limites de largura para controlar a dimensão de determinadas áreas.

Exemplo:

```css
max-width: 80vw;
```

A unidade `vw` corresponde a 1% da largura do viewport. Assim, `80vw` representa 80% da largura da área de visualização.

A utilização de `max-width` define um limite máximo para a largura do elemento, permitindo uma composição mais controlada em ecrãs maiores.

---

## 💻 Como Executar o Projeto Localmente

Por se tratar de uma aplicação web estática desenvolvida com HTML5 e CSS3, não é necessária a instalação de dependências ou a utilização de ferramentas de compilação.

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/projeto-starbucks.git
```

> Substitui `SEU-USUARIO` pelo teu nome de utilizador do GitHub e confirma o endereço do repositório.

### 2. Aceder ao diretório

```bash
cd projeto-starbucks
```

### 3. Abrir a aplicação

Abre o ficheiro `index.html` diretamente num navegador moderno.

Em alternativa, podes utilizar a extensão **Live Server** no Visual Studio Code para executar o projeto num servidor local e visualizar as alterações durante o desenvolvimento.

---

## 📁 Estrutura do Projeto

```text
projeto-starbucks/
│
├── assets/
│   ├── css/
│   │   └── style.css          # Estilos e layouts da interface
│   │
│   ├── fonts/
│   │   └── fonte.css          # Declarações e configurações tipográficas
│   │
│   └── images/                # Imagens e recursos visuais da página
│
├── index.html                 # Estrutura principal da página
└── README.md                  # Documentação do projeto
```

---

## 👨‍💻 Autor

**Rafael Santana** 🚀

> Estudante de Engenharia da Computação, com foco no desenvolvimento Full-Stack, na criação de interfaces responsivas e na construção de aplicações web modernas.

---

## 📚 Tecnologias e Conceitos Praticados

- **HTML5** — estruturação semântica de páginas web;
- **CSS3** — estilização e apresentação dos conteúdos;
- **CSS Grid** — organização de layouts em linhas e colunas;
- **Flexbox** — construção de layouts flexíveis;
- **Media Queries** — adaptação da interface a diferentes ecrãs;
- **Responsive Design** — desenvolvimento de interfaces responsivas;
- **Google Fonts** — integração de fontes tipográficas externas;
- **CSS Backgrounds** — configuração e posicionamento de imagens de fundo;
- **Hierarquia tipográfica** — organização visual dos conteúdos;
- **Organização de recursos estáticos** — estruturação de ficheiros CSS, fontes e imagens.

---

<p align="center">
  Projeto desenvolvido para fins educacionais e para consolidação de conhecimentos em HTML5, CSS3, CSS Grid, Flexbox e desenvolvimento de interfaces responsivas.
</p>
