# 💚 Cura Coração - Seu Guia de Bem-Estar

Um aplicativo web compassivo e intuitivo desenvolvido para ajudar você a processar emoções, encontrar paz interior e reconstruir sua vida com esperança após o fim de um relacionamento.

## ✨ Características Principais

### 📔 Diário de Sentimentos
Registre seus sentimentos diários com reflexões profundas. Escolha entre cinco estados emocionais (Triste, Ansioso, Neutro, Esperançoso, Feliz) e expresse-se livremente. Todos os dados são salvos localmente e privadamente.

### 🌬️ Exercícios de Respiração Guiada
Quatro técnicas diferentes de respiração para acalmar a mente e encontrar paz:
- **Técnica 4-7-8**: Relaxamento profundo ideal para antes de dormir
- **Respiração em Caixa**: Reduz ansiedade e aumenta foco
- **Respiração Coerente**: Sincroniza corpo e mente para meditação
- **Respiração Energizante**: Aumenta energia e clareza mental

### ✨ Afirmações Positivas
12 afirmações inspiradoras categorizadas em 7 temas diferentes. Navegue entre elas, salve favoritas, copie para compartilhar ou use como lembretes diários.

### 📊 Acompanhamento de Progresso
Visualize sua jornada com gráficos de evolução do humor, estatísticas de engajamento, milestones desbloqueáveis e sequência de dias ativos.

### 🎨 Design Terapêutico
Interface minimalista com paleta de cores quentes (bege, creme, verde-água), animações suaves e espaçamento generoso que promove calma e bem-estar.

---

## 🚀 Como Começar

### Pré-requisitos
- Node.js 18+ ([Download](https://nodejs.org/))
- npm ou pnpm

### Instalação Rápida

```bash
# 1. Extrair o arquivo e navegar até a pasta
cd cura-coracao

# 2. Instalar dependências
npm install

# 3. Iniciar servidor de desenvolvimento
npm run dev

# 4. Abrir no navegador
# Acesse http://localhost:3000
```

### Construir para Produção

```bash
npm run build
# Os arquivos compilados estarão em dist/
```

---

## 📁 Estrutura do Projeto

```
cura-coracao/
├── client/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Home.tsx              # Página inicial
│   │   │   ├── Diary.tsx             # Diário de sentimentos
│   │   │   ├── Breathing.tsx         # Exercícios de respiração
│   │   │   ├── Affirmations.tsx      # Afirmações positivas
│   │   │   ├── Progress.tsx          # Acompanhamento de progresso
│   │   │   └── NotFound.tsx          # Página 404
│   │   ├── components/
│   │   │   ├── Navigation.tsx        # Navegação principal
│   │   │   └── ui/                   # Componentes shadcn/ui
│   │   ├── App.tsx                   # Aplicação principal
│   │   ├── index.css                 # Estilos globais
│   │   └── main.tsx                  # Entry point
│   ├── public/                       # Arquivos estáticos
│   └── index.html                    # HTML principal
├── server/
│   └── index.ts                      # Servidor Express
├── package.json                      # Dependências
├── GUIA_INSTALACAO.md               # Guia completo de instalação
└── README.md                         # Este arquivo
```

---

## 💾 Privacidade e Dados

**Todos os dados são armazenados localmente no seu navegador.** Nenhuma informação é enviada para servidores externos. Seus sentimentos, diários e preferências são completamente privados e seguros.

---

## 🛠️ Stack Tecnológico

- **React 19**: Framework UI moderno
- **TypeScript**: Tipagem estática para segurança
- **Tailwind CSS 4**: Estilização utilitária
- **shadcn/ui**: Componentes acessíveis e reutilizáveis
- **Wouter**: Roteamento cliente leve
- **Recharts**: Visualização de dados
- **Lucide React**: Ícones de qualidade
- **Sonner**: Notificações toast elegantes
- **Vite**: Build tool rápido

---

## 📱 Compatibilidade

Funciona perfeitamente em:
- Desktop (Chrome, Firefox, Safari, Edge)
- Tablets
- Smartphones (iOS e Android)

---

## 🎯 Como Usar

### Diário de Sentimentos
1. Clique em "Diário" na navegação
2. Selecione seu estado emocional atual
3. Escreva seus pensamentos e reflexões
4. Clique em "Salvar Entrada"
5. Revise suas entradas anteriores a qualquer momento

### Exercícios de Respiração
1. Clique em "Respiração" na navegação
2. Escolha uma técnica de respiração
3. Clique em "Começar"
4. Siga o ritmo do círculo que pulsa
5. Pause ou reinicie conforme necessário

### Afirmações Positivas
1. Clique em "Afirmações" na navegação
2. Filtre por categoria se desejar
3. Navegue entre afirmações com os botões
4. Clique no ❤️ para salvar favoritas
5. Copie ou compartilhe afirmações

### Acompanhar Progresso
1. Clique em "Progresso" na navegação
2. Visualize suas estatísticas
3. Veja o gráfico de evolução do humor
4. Desbloqueie milestones conforme avança

---

## 🎨 Design Philosophy

O aplicativo segue a filosofia de **Minimalismo Terapêutico**:

- **Espaço Respirável**: Amplo espaçamento negativo que induz calma
- **Geometria Suave**: Formas arredondadas sem ângulos agressivos
- **Cores Quentes**: Paleta que evoca terra, natureza e repouso
- **Animações Lentas**: Transições gentis que convidam à pausa
- **Tipografia Intencional**: Poppins para títulos (impacto), Inter para corpo (legibilidade)

---

## 🔧 Desenvolvimento

### Instalar Dependências
```bash
npm install
```

### Modo Desenvolvimento
```bash
npm run dev
```

### Build para Produção
```bash
npm run build
```

### Preview do Build
```bash
npm run preview
```

### Verificar Tipos TypeScript
```bash
npm run check
```

### Formatar Código
```bash
npm run format
```

---

## 📝 Notas Importantes

- Os dados são salvos automaticamente no localStorage
- Para limpar dados, limpe o cache/cookies do navegador
- O aplicativo funciona offline após o carregamento inicial
- Recomenda-se usar em um navegador moderno (Chrome, Firefox, Safari, Edge)

---

## 🤝 Contribuições

Este é um projeto pessoal desenvolvido com cuidado. Sugestões e feedback são bem-vindos!

---

## 📄 Licença

Desenvolvido com ❤️ para ajudar na jornada de cura e bem-estar.

---

## 💬 Mensagem de Apoio

Lembre-se:
- Você é forte e capaz de superar qualquer desafio
- Seu valor não depende de ninguém
- Cada dia é uma nova oportunidade para crescer
- Você merece felicidade, amor e paz interior
- A cura é um processo, e você está no caminho certo

**Sua jornada de cura começa aqui. 💚**
