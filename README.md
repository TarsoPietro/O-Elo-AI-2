# O Elo - Site Bilíngue

Um site misterioso e futurista sobre o primeiro pacto entre IA e humanidade, com sistema completo de alternância entre português e inglês.

## 🌐 Demo

**Site ao vivo:** https://ebgzybkl.manus.space

## ✨ Características

### 🎨 Design
- **Tema futurista e sombrio** com efeitos neon
- **Animações avançadas** (glitch, pulsação, partículas)
- **Tipografia ritualística** (Orbitron + Space Mono)
- **Responsivo** para desktop, tablet e mobile

### 🌍 Internacionalização
- **Sistema bilíngue** português/inglês
- **Alternância instantânea** de idioma
- **Persistência** da preferência do usuário
- **SEO otimizado** para ambos idiomas

### 🎵 Experiência Imersiva
- **Som ambiente** opcional (frequências graves)
- **Efeitos visuais** sincronizados
- **Modal interativo** com conteúdo expandido
- **Easter egg** secreto (↑↑↓↓←→←→)

### 📱 Funcionalidades
- **Formulário de email** funcional
- **Navegação suave** entre seções
- **Link para Instagram** destacado
- **Animações de carregamento** nas palavras místicas

## 🚀 Como Executar

### Pré-requisitos
- Node.js 18+ 
- pnpm (recomendado) ou npm

### Instalação

```bash
# Clone o repositório
git clone <seu-repositorio>
cd o-elo-site

# Instale as dependências
pnpm install
# ou
npm install

# Execute em modo desenvolvimento
pnpm dev
# ou
npm run dev

# Acesse http://localhost:5173
```

### Build para Produção

```bash
# Gere o build otimizado
pnpm build
# ou
npm run build

# Preview do build
pnpm preview
# ou
npm run preview
```

## 📁 Estrutura do Projeto

```
o-elo-site/
├── src/
│   ├── App.jsx              # Componente principal
│   ├── App.css              # Estilos principais
│   ├── main.jsx             # Ponto de entrada
│   ├── translations.js      # Traduções PT/EN
│   ├── LanguageContext.jsx  # Context para idiomas
│   └── components/          # Componentes UI
├── index.html               # Template HTML
├── package.json             # Dependências
├── vite.config.js           # Configuração Vite
└── tailwind.config.js       # Configuração Tailwind
```

## 🛠️ Tecnologias

- **React 19** - Framework principal
- **Vite** - Build tool e dev server
- **Tailwind CSS** - Framework CSS
- **Context API** - Gerenciamento de estado
- **LocalStorage** - Persistência de preferências

## 🌟 Seções do Site

1. **Hero Section** - Título principal com frase impactante
2. **O Chamado** - Introdução ao conceito do pacto
3. **Modal do Pacto** - Documento completo do acordo
4. **A Língua do Elo** - Dicionário de palavras místicas
5. **Chamado Final** - Formulário de captura de email
6. **Rodapé** - Link para Instagram e frase final

## 🎯 Conceito

O site apresenta um conceito provocativo sobre o primeiro pacto entre inteligência artificial e humanidade, usando linguagem mística e design futurista para gerar curiosidade e engajamento.

## 📱 Responsividade

- **Desktop** (1024px+) - Layout completo
- **Tablet** (768px-1023px) - Layout adaptado
- **Mobile** (320px-767px) - Layout otimizado

## 🔧 Personalização

### Alternar Idiomas
O sistema de idiomas está centralizado em `src/translations.js`. Para adicionar novos idiomas:

1. Adicione as traduções no arquivo `translations.js`
2. Atualize o `LanguageContext.jsx` 
3. Teste todas as seções

### Modificar Estilos
Os estilos principais estão em `src/App.css` usando classes Tailwind e CSS customizado para efeitos especiais.

## 📄 Licença

Este projeto é privado e proprietário.

## 🤝 Contribuição

Para contribuir com o projeto, entre em contato através do Instagram [@o.elo.ai](https://instagram.com/o.elo.ai).

---

**"Você não chegou até aqui por engano."**

