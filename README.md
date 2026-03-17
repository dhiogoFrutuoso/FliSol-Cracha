<div align="center">

# 🎴 FliSol Crachá Customizer

### Crie seu crachá geek e leve uma lembrança do festival para casa.

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![FliSol](https://img.shields.io/badge/FliSol-2026-blueviolet?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<br/>

> **Apresentado no FliSol (Festival Latino-Americano de Instalação de Software Livre)**  
> Uma aplicação web para criação de crachás personalizados — com fundos temáticos do universo geek.

</div>

---

## ✨ Sobre o Projeto

O **FliSol Crachá Customizer** nasceu de uma ideia simples e poderosa: transformar o crachá de evento em um objeto de identidade pessoal.

Durante o FliSol, os participantes podem acessar a aplicação, montar seu próprio crachá com nome, título, ícone e tema visual de sua preferência — e **baixar a imagem na hora**, para imprimir e usar como lembrança do festival.

O diferencial está nos temas disponíveis: além de paletas de cores elegantes, o sistema oferece **fundos temáticos do mundo geek** — animes, jogos, séries, filmes e sci-fi clássico. O objetivo é conectar a cultura do software livre com a cultura pop e criar um ponto de atração genuíno para o público jovem.

---

## 🖼️ Funcionalidades

- **Personalização de conteúdo** — nome, título, subtítulo, ícone/emoji e instituição/empresa
- **Fundos com cores** — mais de 40 paletas organizadas em categorias:
  - 🎨 Clássicas
  - 🎌 Animes (Naruto, Dragon Ball, Demon Slayer, One Piece...)
  - 🎮 Jogos (Zelda, Cyberpunk, Dark Souls, Minecraft...)
  - 🎬 Séries & Filmes (Marvel, Star Wars, Harry Potter, Batman...)
  - 👾 Clássicos Geek (Matrix, Tron, Blade Runner, Dune...)
- **Fundos com imagens** — categorias de Natureza, Cidade, Espaço, Abstrato e **Mundo Geek** (imagens locais configuráveis)
- **Controle de escurecimento** — slider para ajustar a opacidade do overlay nas imagens
- **Seleção de fonte** — 12 fontes do Google Fonts com preview ao vivo
- **Proporções de card** — Wide, Square e Tall
- **Download como PNG** — gerado via `html2canvas` em alta resolução (escala 3×)
- **Preview em tempo real** — tudo atualiza instantaneamente no card

---

## 🖥️ Compatibilidade

> ⚠️ **Esta aplicação foi desenvolvida exclusivamente para uso em desktop.**

O projeto foi criado com foco na apresentação presencial no FliSol, onde os participantes interagem com o sistema em notebooks ou computadores do estande. **Não há responsividade para dispositivos móveis ou tablets**, pois não se trata de um produto de uso público — e sim de uma ferramenta de demonstração e experiência para o evento.

---

## 🚀 Como Usar

### 1. Clone o repositório

```bash
git clone https://github.com/dhiogoFrutuoso/FliSol-Cracha.git
cd FliSol-Cracha
```

### 2. Adicione suas imagens geek (opcional)

Coloque suas imagens na pasta `assets/img/` e registre-as no array `GEEK_IMAGES` dentro do `index.html`:

```javascript
const GEEK_IMAGES = [
  {
    id:       "gk01",
    name:     "One Piece",
    url:      "./assets/img/one-piece.png",
    thumbUrl: "./assets/img/one-piece.png",
  },
  // adicione mais imagens aqui...
];
```

### 3. Abra no navegador

Não é necessário servidor. Basta abrir o `index.html` diretamente no navegador:

```
Abrir com: Google Chrome / Firefox / Edge
```

> Para imagens locais (pasta `assets/img/`), o `html2canvas` captura sem restrições de CORS por se tratar de arquivos do próprio sistema.

---

## 📁 Estrutura do Projeto

```
FliSol-Cracha/
│
├── index.html          # Aplicação principal (HTML + JS)
├── css/
│   └── styles.css      # Estilos da interface
├── assets/
│   └── img/            # Imagens de fundo geek (locais)
└── LICENSE
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da aplicação |
| CSS3 | Layout, animações e responsividade de tela |
| JavaScript (Vanilla) | Lógica de personalização e renderização |
| [html2canvas](https://html2canvas.hertzen.com/) | Captura e exportação do card como PNG |
| [Google Fonts](https://fonts.google.com/) | Tipografias variadas para o card |

---

## 🎯 Contexto — FliSol

O **Festival Latino-Americano de Instalação de Software Livre (FliSol)** é o maior evento de promoção do software livre na América Latina. Realizado anualmente de forma descentralizada, reúne comunidades técnicas, estudantes e entusiastas da tecnologia.

Este projeto integra a programação do evento como uma **atividade interativa**, com o objetivo de:

- Atrair jovens para o estande do IFCE
- Aproximar a cultura geek da cultura do software livre
- Oferecer uma lembrança física e personalizada do festival
- Demonstrar, na prática, o que é possível construir com tecnologias abertas e gratuitas

---

## 👨‍💻 Desenvolvido por

**Dhiago Frutuoso**  
Estudante do IFCE · Participante do FliSol 2026

---

<div align="center">

Feito com 💜 para o **FliSol 2026**

*Software livre, cultura livre, criatividade livre.*

</div>