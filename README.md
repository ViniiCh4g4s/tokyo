# Tokyo - Descubra a Capital do Japão

Landing page informativa sobre Tokyo, apresentando a cidade, suas principais atrações turísticas e experiências culturais.

## Sobre o Projeto

Uma página web responsiva que convida o visitante a explorar Tokyo através de seções visuais e informativas. O site é dividido em:

- **Hero** — Introdução com grid de imagens e chamada para explorar a cidade
- **Sobre** — Destaca os pilares de Tokyo: segurança, tecnologia e gastronomia
- **Atrações** — Cards com os pontos turísticos imperdíveis: Templo Senso-ji, Shibuya Crossing, Torre de Tokyo, Palácio Imperial, Akihabara e Harajuku
- **Cultura** — Experiências únicas como cerimônia do chá, teatro Kabuki, culinária japonesa e jardins

## Tecnologias

- **HTML5** — Estrutura semântica com acessibilidade (atributos `aria`, `role`)
- **Tailwind CSS v4** — Estilização utilitária via CDN do browser
- **CSS puro** — Menu mobile funcional usando apenas checkbox (sem JavaScript)

## Estrutura

```
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── hero/
│       ├── places/
│       ├── hero.webp
│       └── logo_tokyo.webp
└── README.md
```

## Destaques Técnicos

- Layout totalmente responsivo (mobile, tablet e desktop)
- Menu mobile implementado com CSS puro (checkbox hack), sem dependência de JavaScript
- Parallax na imagem hero com `background-attachment: fixed`
- Smooth scroll nativo via CSS
- Imagens em formato WebP para melhor performance
