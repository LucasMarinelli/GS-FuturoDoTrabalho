# 🚀 Talently Hub - Conectando Talentos

Uma plataforma inteligente para profissionais que buscam migrar de carreira, oferecendo orientação personalizada, conexões significativas e oportunidades de vagas alinhadas ao seu perfil.

## 📋 Sobre o Projeto

**Talently Hub** é uma landing page moderna desenvolvida como parte do projeto "O Futuro do Trabalho". A plataforma conecta pessoas que desejam mudar de área profissional com recursos, cursos e oportunidades de emprego personalizadas.

### Objetivo Principal
Facilitar a transição de carreira através de:
- Análise de habilidades e identificação de gaps
- Sugestões de cursos personalizados
- Roadmap intuitivo para a nova área
- Conexões com profissionais que já fizeram a transição
- Vagas exclusivas alinhadas ao perfil

---

## ✨ Características Principais

### 🎯 Seções da Plataforma

1. **Header Responsivo**
   - Navegação principal com links de acesso rápido
   - Botão de ação "Conecte-se"
   - Design limpo e intuitivo

2. **Hero Section**
   - Mensagem principal inspiradora
   - Descrição clara da proposta de valor
   - Imagem representativa

3. **Formulário de Cadastro**
   - Campos: Nome, Área de Estudo, Área Desejada
   - Validação de campos obrigatórios
   - Design acessível com labels explícitas

4. **Plano Personalizado em 3 Etapas**
   - Análise de Habilidades
   - Sugestões de Cursos
   - Geração de Roadmap

5. **Conexões Recentes**
   - Histórias de sucesso de profissionais
   - Cards interativos com perfis
   - Exemplos de transições bem-sucedidas

6. **Vagas Exclusivas**
   - Lista de oportunidades disponíveis
   - Detalhes de vagas com benefícios
   - Requisitos e informações da empresa

7. **Footer Completo**
   - Links de navegação
   - Links de termos e políticas
   - Redes sociais
   - Copyright

---

## 🎨 Design e Tecnologia

### Stack Tecnológico
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com Flexbox
- **Fonte** - Google Fonts (Poppins)
- **Responsividade** - Design adaptável

### Paleta de Cores
- **Azul Principal**: `#0066FF` - Ações e destaques
- **Azul Escuro**: `#003A8C` - Títulos e textos principais
- **Cinza**: `#64748B` - Textos secundários
- **Branco**: `#FFFFFF` - Fundos claros
- **Cinza Claro**: `#F7F7F7` - Fundos secundários

### Tipografia
- **Fonte Principal**: Poppins (Google Fonts)
- **Pesos**: 400, 500, 600, 700
- **Tamanhos**: Escaláveis conforme seção

---

## ♿ Acessibilidade WCAG 2.1

O projeto foi desenvolvido seguindo os padrões de acessibilidade web:

### ✅ Implementações

- **Estrutura Semântica**: HTML5 com elementos semânticos (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- **ARIA Roles**: `banner`, `main`, `contentinfo`, `list`, `listitem`
- **Navegação por Teclado**: Todos elementos interativos acessíveis via TAB
- **Foco Visível**: Outline azul em todos botões, links e inputs
- **Formulários**: Labels explícitas com `for=""` e `id=""`
- **Alt Text**: Todas imagens com descrição descritiva
- **Contraste**: Razão mínima 4.5:1 entre texto e fundo
- **Tamanho Mínimo**: 44x44px para elementos clicáveis
- **Animações Seguras**: Sem flashes ou gatilhos visuais perigosos

📄 **Documentação Completa**: Veja `ACESSIBILIDADE.md` para detalhes técnicos

---

## 📁 Estrutura do Projeto

```
GS-FuturoDoTrabalho/
├── index.html                 # Arquivo principal HTML
├── README.md                  # Este arquivo
├── ACESSIBILIDADE.md          # Documentação de acessibilidade
├── src/
│   ├── css/
│   │   └── style.css          # Estilos CSS
│   └── assets/
│       ├── image-main.svg     # Imagem principal
│       ├── perfil1.svg        # Foto perfil 1
│       ├── perfil2.svg        # Foto perfil 2
│       ├── perfil3.svg        # Foto perfil 3
│       ├── imageItau.svg      # Logo empresa
│       ├── icon-instagram.svg # Ícone Instagram
│       ├── icon-facebook.svg  # Ícone Facebook
│       └── icon-X.svg         # Ícone X (Twitter)
└── .git/                      # Controle de versão
```

---

## 🚀 Como Usar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para carregar Google Fonts)

### Instalação Local

1. **Clone o repositório**
   ```bash
   git clone https://github.com/LucasMarinelli/GS-FuturoDoTrabalho.git
   cd GS-FuturoDoTrabalho
   ```

2. **Abra o arquivo HTML**
   - Duplo clique em `index.html`, ou
   - Use um servidor local:
     ```bash
     python -m http.server 8000
     # Acesse http://localhost:8000
     ```

3. **Visualize no navegador**
   - A página carregará com todos os estilos e funcionalidades

---

## 📱 Responsividade

O projeto foi desenvolvido com foco em responsividade:
- **Desktop**: Layout completo com todos elementos
- **Tablet**: Adaptação de espaçamento e tamanhos
- **Mobile**: Navegação otimizada e elementos redimensionados

> **Nota**: Ajustes CSS adicionais podem ser necessários para otimizar em telas muito pequenas

---

## 🔧 Customização

### Alterar Cores
Edite as variáveis de cor em `src/css/style.css`:
```css
/* Cores principais */
--primary-blue: #0066FF;
--dark-blue: #003A8C;
--text-gray: #64748B;
```

### Adicionar Novas Seções
1. Adicione o HTML em `index.html`
2. Crie os estilos correspondentes em `src/css/style.css`
3. Mantenha a semântica HTML e ARIA roles

### Atualizar Conteúdo
- Textos: Edite diretamente em `index.html`
- Imagens: Substitua arquivos em `src/assets/`
- Links: Atualize `href=""` nos elementos `<a>`

---

## 🧪 Testes de Acessibilidade

### Navegação por Teclado
```
1. Pressione TAB para navegar entre elementos
2. Pressione ENTER para ativar botões/links
3. Verifique se o foco é sempre visível
```

### Leitor de Tela
- **Windows**: NVDA (gratuito)
- **Mac**: VoiceOver (integrado)
- **Teste**: Navegue pela página e verifique as descrições

### Contraste
- Use ferramentas como [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- Verifique razão mínima de 4.5:1

---

## 📊 Performance

### Otimizações Implementadas
- ✅ Imagens em SVG (vetoriais, leves)
- ✅ CSS minificado e otimizado
- ✅ Lazy loading em imagens
- ✅ Preconnect para Google Fonts
- ✅ Sem dependências externas pesadas

### Métricas Recomendadas
- **Lighthouse Score**: Objetivo 90+
- **Tempo de Carregamento**: < 2 segundos
- **First Contentful Paint**: < 1 segundo

---

## 👥 Autores

- **Lucas Ponciani Marinelli**
- **Raffaely Soares Pinto**

---

## 📄 Licença

Este projeto é fornecido como está para fins educacionais e comerciais.

---

## 🤝 Contribuindo

Para contribuir com melhorias:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

## 📚 Recursos Adicionais

### Documentação
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Ferramentas Úteis
- [Google Fonts](https://fonts.google.com/)
- [SVG Optimizer](https://jakearchibald.github.io/svgomg/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [WAVE Accessibility Tool](https://wave.webaim.org/)

---







*Última atualização: 19 de Novembro de 2025*
