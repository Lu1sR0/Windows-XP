<div align="center">

# Windows XP — Disquetech

Site que recria a área de trabalho do Windows XP no navegador para apresentar o grupo de TCC Disquetech e seus projetos.

[![Ver site](https://img.shields.io/badge/VER_SITE-0D0D0D?style=for-the-badge&logo=netlify&logoColor=FF003C)](https://disquetechwin.netlify.app)

![HTML5](https://img.shields.io/badge/HTML5-0D0D0D?style=for-the-badge&logo=html5&logoColor=FF003C)
![CSS](https://img.shields.io/badge/CSS-0D0D0D?style=for-the-badge&logo=css&logoColor=FF003C)
![JavaScript](https://img.shields.io/badge/JavaScript-0D0D0D?style=for-the-badge&logo=javascript&logoColor=FF003C)
![jQuery](https://img.shields.io/badge/jQuery-0D0D0D?style=for-the-badge&logo=jquery&logoColor=FF003C)

</div>

## Sobre

Criado por mim para o meu grupo de TCC do técnico em Desenvolvimento de Sistemas da **ETEC Professor Basilides de Godoy** (2024). Em vez de um site institucional comum, a apresentação do grupo é uma área de trabalho do Windows XP: cada ícone abre uma janela com um projeto do TCC ou com informações da equipe.

## Funcionalidades

- **Tela de carregamento** animada antes de exibir a área de trabalho.
- **Área de trabalho em grade** com ícones arrastáveis entre as células (Drag and Drop API nativa).
- **Janelas no estilo XP**, com barra de título (minimizar, maximizar e fechar), barra de menus e barra de endereço, abertas via seletor CSS `:target`.
- **Barra de tarefas** com botão Iniciar, indicador do programa aberto, relógio, data e botão de tela cheia (Fullscreen API).
- **Menu Iniciar** no visual clássico, com atalhos e a opção "Desligar o computador", que pede confirmação antes de sair do site.
- **Versão mobile**: em telas de até 768 px, o visitante é redirecionado para o [site da Disquetech](https://disquetech.netlify.app).

### Programas da área de trabalho

| Ícone | O que abre |
| --- | --- |
| Nossa Equipe | Cards com foto e função de cada integrante do grupo |
| Powerpoint | Apresentação da empresa, incorporada do OneDrive |
| Monte seu PC | O app [Monte seu PC](https://github.com/Lu1sR0/Monte-seu-PC), em Flutter, rodando dentro da janela |
| PAC MAN | Jogo Pac-Man em canvas, carregado sob demanda (baseado no projeto open source [daleharvey/pacman](https://github.com/daleharvey/pacman)) |
| Disquetech | O [site institucional](https://github.com/Lu1sR0/Disquetech) da Disquetech |
| Vídeo | Demonstração do [sistema e-commerce](https://github.com/Lu1sR0/E-Commerce-TCC) desenvolvido no TCC |

## Tecnologias

- **HTML5 e CSS** — layout da área de trabalho, janelas, barra de tarefas e menu Iniciar (fonte Tahoma, como no XP).
- **JavaScript** — arrastar e soltar ícones, abertura e fechamento de programas, barra de tarefas, relógio, data, tela cheia e redirecionamento mobile.
- **jQuery** — inicialização do relógio ao carregar a página.
- **Netlify** — hospedagem.

## Estrutura

```
Windows-XP/
├── index.html                  # área de trabalho, janelas, menu Iniciar e scripts
├── style.css                   # visual do Windows XP
├── pacman.html                 # jogo Pac-Man (canvas)
├── logodisquetechsrlnova.png   # logo da Disquetech
└── img/                        # ícones, botões de janela e fotos da equipe
```

## Como rodar localmente

```bash
git clone https://github.com/Lu1sR0/Windows-XP.git
cd Windows-XP
```

Abra o `index.html` no navegador ou use a extensão **Live Server** do VS Code.

> Use uma janela com mais de 768 px de largura (abaixo disso o site redireciona para a versão mobile). Algumas janelas carregam conteúdo externo (OneDrive, Vimeo e os apps publicados no Netlify), então é preciso estar conectado à internet.

## Equipe

| Integrante | Função |
| --- | --- |
| Samuel de Medeiros | Desenvolvedor Back-end |
| Roberto Peixoto | Desenvolvedor Back-end |
| [Luis Roberto](https://github.com/Lu1sR0) | Desenvolvedor Front-end |
| Sandy Cristine | Desenvolvedora Front-end |
| Ruan Keven | Desenvolvedor de banco de dados |
| Luis Otávio | Desenvolvedor de banco de dados |

---

<div align="center">
Desenvolvido por <a href="https://github.com/Lu1sR0">Luis Roberto</a> · <a href="https://outframe.dev">Outframe</a>
</div>
