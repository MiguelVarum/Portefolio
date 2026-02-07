# Portfólio - Miguel Varum

Portfólio pessoal de desenvolvedor de software com design moderno e responsivo.

## 📁 Estrutura do Projeto

```
portfolio-melhorado/
│
├── index.html              # Página principal
├── README.md              # Documentação
│
├── css/
│   └── style.css          # Estilos personalizados
│
├── js/
│   └── script.js          # Scripts personalizados
│
└── imgs/
    ├── logo.png           # Logótipo
    └── projects/          # Imagens dos projetos
```

## 🚀 Funcionalidades

- **Design Responsivo**: Adaptável a todos os dispositivos (desktop, tablet, mobile)
- **Carrossel de Projetos**: Apresentação automática de projetos na hero section
- **Animações Suaves**: Efeitos de scroll e hover para melhor experiência do utilizador
- **Navegação Smooth Scroll**: Navegação fluida entre secções
- **Performance Otimizada**: Código limpo e organizado

## 🎨 Tecnologias Utilizadas

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Bootstrap 5.3.3
- Font Awesome 6.4.0
- Google Fonts (Inter)

## 📝 Secções

1. **Hero/Início**: Apresentação com nome, função e carrossel de projetos
2. **Sobre**: Descrição profissional e objetivos
3. **Competências**: Cards com tecnologias e ferramentas
4. **Projetos**: Galeria de projetos em destaque
5. **Contacto**: Links para email, LinkedIn e GitHub

## 🎯 Carrossel de Projetos

O carrossel na hero section apresenta automaticamente os projetos com:
- Transição automática a cada 4 segundos
- Pausa ao passar o rato
- Navegação manual com setas
- Indicadores de slide
- Responsive em todos os dispositivos

## 🔧 Personalização

### Alterar Cores
Edite as variáveis CSS no ficheiro `css/style.css`:

```css
:root {
  --primary: #2563eb;
  --secondary: #8b5cf6;
  --accent: #06b6d4;
  /* ... outras cores */
}
```

### Adicionar Projetos ao Carrossel
Edite a secção do carrossel em `index.html` e adicione novos items:

```html
<div class="carousel-item">
  <img src="caminho/para/imagem.jpg" alt="Projeto">
  <div class="carousel-caption">
    <h5>Nome do Projeto</h5>
    <p>Descrição breve</p>
  </div>
</div>
```

### Atualizar Informações Pessoais
- **Email**: Linha 178 em `index.html`
- **LinkedIn**: Linha 181 em `index.html`
- **GitHub**: Linha 186 em `index.html`

## 📱 Responsividade

O site é totalmente responsivo com breakpoints otimizados:
- Desktop: > 768px
- Tablet: 768px
- Mobile: < 768px

## 🌐 Como Usar

1. Clone ou descarregue o repositório
2. Abra o ficheiro `index.html` num navegador
3. Ou faça deploy em qualquer serviço de hosting (GitHub Pages, Netlify, Vercel, etc.)

## 📦 Melhorias Implementadas

✅ Organização de ficheiros (CSS e JS separados)
✅ Carrossel automático de projetos na hero section
✅ Textos melhorados em português de Portugal
✅ Descrições mais profissionais e detalhadas
✅ Design moderno e responsivo
✅ Animações e transições suaves
✅ Código comentado e bem estruturado

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.

---

**Desenvolvido por Miguel Varum** | 2025
