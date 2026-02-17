<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=120&section=header"/>

<h1 align="center">🪢 Jogo da Forca</h1>

<p align="center">
  Jogo da forca clássico no navegador — com teclado virtual, categorias, modo manual e modo automático.
</p>

<div align="center">

  [![Demo](https://img.shields.io/badge/🌐%20Jogar%20Agora-2482FF?style=for-the-badge)](https://https-shini.github.io/Jogo-Forca/)
  [![Código](https://img.shields.io/badge/Ver%20Código-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/https-shini/Jogo-Forca)

</div>

---

## 📌 O que é este projeto?

Uma versão web do clássico **Jogo da Forca**. O jogador tenta adivinhar uma palavra secreta escolhendo letras pelo teclado virtual. A cada erro, uma parte do boneco é desenhada na forca. O jogador tem **6 tentativas** antes de perder.

O jogo possui dois modos de uso: **automático**, com uma lista de palavras já incluída, e **manual**, onde o jogador pode adicionar suas próprias palavras e categorias.

---

## 🎮 Como jogar

1. Acesse o jogo pelo link abaixo
2. Uma palavra secreta e sua categoria aparecem na tela
3. Clique nas letras do teclado virtual para adivinhar
4. Letras corretas aparecem na palavra — erradas desenham o boneco
5. Adivinhe a palavra antes de usar as 6 tentativas!

> 💡 Clique no botão 🔄 para sortear uma nova palavra sem precisar recarregar a página.

---

## ✨ Funcionalidades

- **6 tentativas** com imagens progressivas da forca (7 estados no total)
- **Teclado virtual** com todas as letras do alfabeto
- Letras corretas ficam **verdes**, erradas ficam **roxas**
- Exibe a **categoria** da palavra (Lugares, Animais, Transporte, etc.)
- **Modal de resultado** — mostra "Parabéns!" ao vencer ou revela a palavra ao perder
- Botão 🔄 para **sortear nova palavra** sem recarregar
- **Modo Automático** — palavras sorteadas da lista embutida no jogo
- **Modo Manual** — jogador adiciona sua própria palavra e categoria via formulário
- Alternância entre os modos com o botão ⏸️/▶️

---

## 📚 Categorias disponíveis (modo automático)

| Categoria | Exemplos |
|---|---|
| **Lugares** | Irlanda, Groelândia, Uzbequistão... |
| **Transporte** | Bicicleta, Funicular, Aeronave... |
| **Objetos** | Esparadrapo, Tamborete, Bocal... |
| **Alimentos** | Amendoim, Esfirra, Desjejum... |
| **Animais** | Dromedário, Sagui, Hipopótamo... |
| **TV e Cinema** | Stranger Things, Bob Esponja, Mulher Maravilha... |

---

## 🌐 Experimente agora

Você pode jogar sem precisar baixar nada:

👉 **[https://https-shini.github.io/Jogo-Forca/](https://https-shini.github.io/Jogo-Forca/)**

Basta abrir o link no navegador e começar a jogar!

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura da página e teclado virtual
- **CSS3** — layout responsivo e animações do modal
- **JavaScript** — lógica do jogo, modos automático/manual e controle de estado
- **Bootstrap 4** — modal de resultado (vitória/derrota)
- **Boxicons** — ícones dos botões de ação
- **Google Fonts (Ubuntu)** — tipografia da interface

---

## 🗂️ Estrutura de arquivos

```
Jogo-Forca/
│
├── index.html        → Estrutura da página, teclado e modais
│
├── css/
│   └── style.css     → Estilo, responsividade e animações
│
├── js/
│   └── script.js     → Lógica do jogo, modos e interações
│
└── img/
    ├── forca.png       → Estado inicial (forca vazia)
    ├── forca01.png     → 1 erro
    ├── forca02.png     → 2 erros
    ├── forca03.png     → 3 erros
    ├── forca04.png     → 4 erros
    ├── forca05.png     → 5 erros
    ├── forca06.png     → 6 erros (game over)
    └── jogarNovamente.gif
```

---

## 🔄 Modos de jogo

| Modo | Como funciona |
|---|---|
| **Automático** ⏸️ | Palavra sorteada aleatoriamente da lista embutida. Clicar em 🔄 recarrega o jogo com nova palavra. |
| **Manual** ▶️ | Jogador digita uma palavra e uma categoria no formulário. Clicando em 🔄 sorteia entre as palavras já adicionadas, sem recarregar. |

---

## 🚀 Como rodar localmente

**1. Clone o repositório**
```bash
git clone https://github.com/https-shini/Jogo-Forca.git
cd Jogo-Forca
```

**2. Abra o projeto**

Abra o arquivo `index.html` diretamente no navegador — não precisa de servidor local!

---

<div align="center">

Feito com 💙 — adivinhe a palavra e vença a forca!

⭐ Se gostou, deixe uma estrela no repositório!

</div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=120&section=footer"/>
