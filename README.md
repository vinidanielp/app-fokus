# 🎯 Fokus

**Fokus** é um aplicativo de produtividade baseado na técnica Pomodoro, desenvolvido para ajudar você a otimizar seu tempo e mergulhar no que realmente importa.

> � **Projeto desenvolvido para fins de estudo** durante o curso de React Native da Alura.

## ✨ Funcionalidades

- ⏱️ **Timer Pomodoro** com três modos:
  - **Foco**: 25 minutos de concentração intensa
  - **Pausa Curta**: 5 minutos de descanso
  - **Pausa Longa**: 15 minutos de relaxamento
- 📋 **Gerenciamento de Tarefas** para organizar suas atividades
- 🎨 **Interface moderna e intuitiva** com design responsivo
- 🌐 **Multiplataforma**: Web, Android e iOS

## 🚀 Como Executar

### Pré-requisitos

- [Node.js](https://nodejs.org/) instalado (versão 18 ou superior)
- [Git](https://git-scm.com/) para clonar o repositório

### Instalação

```bash
# Clone o repositório
git clone <url-do-repositorio>

# Navegue até a pasta do projeto
cd fokus

# Instale as dependências
npm install
```

### 🌐 Executar na Web

```bash
npm run web
```

O aplicativo será aberto automaticamente no navegador em `http://localhost:8081`

### 📱 Executar no Android

**Opção 1: Usando Expo Go (mais rápido)**

```bash
npm run android
```

1. Instale o [Expo Go](https://play.google.com/store/apps/details?id=host.exp.exponent) no seu dispositivo Android
2. Escaneie o QR Code que aparece no terminal
3. O app será carregado no Expo Go

**Opção 2: Usando Emulador**

1. Instale o [Android Studio](https://developer.android.com/studio)
2. Configure um emulador Android (AVD)
3. Inicie o emulador
4. Execute: `npm run android`

### 🍎 Executar no iOS

**Requisito**: macOS com Xcode instalado

**Opção 1: Usando Expo Go**

```bash
npm run ios
```

1. Instale o [Expo Go](https://apps.apple.com/app/expo-go/id982107779) no seu iPhone/iPad
2. Escaneie o QR Code que aparece no terminal
3. O app será carregado no Expo Go

**Opção 2: Usando Simulador**

1. Instale o [Xcode](https://apps.apple.com/us/app/xcode/id497799835)
2. Execute: `npm run ios`
3. O simulador será iniciado automaticamente

## 🛠️ Tecnologias Utilizadas

- **[React Native](https://reactnative.dev/)** - Framework para desenvolvimento mobile
- **[Expo](https://expo.dev/)** - Plataforma para desenvolvimento universal
- **[Expo Router](https://docs.expo.dev/router/introduction/)** - Navegação baseada em arquivos
- **[React Navigation](https://reactnavigation.org/)** - Navegação entre telas
- **[AsyncStorage](https://react-native-async-storage.github.io/async-storage/)** - Armazenamento local

## 📂 Estrutura do Projeto

```
fokus/
├── app/                    # Rotas e telas do aplicativo
│   ├── index.jsx          # Tela inicial
│   ├── pomodoro.jsx       # Tela do timer Pomodoro
│   ├── tasks/             # Tela de tarefas
│   ├── add-task/          # Adicionar tarefa
│   └── edit-task/         # Editar tarefa
├── components/            # Componentes reutilizáveis
├── assets/               # Imagens e recursos estáticos
└── package.json          # Dependências do projeto
```

## 📝 Scripts Disponíveis

```bash
npm start          # Inicia o servidor de desenvolvimento
npm run web        # Executa na web
npm run android    # Executa no Android
npm run ios        # Executa no iOS
npm run lint       # Verifica o código com ESLint
```

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do aprendizado de React Native, explorando conceitos como:

- Componentes funcionais e hooks
- Navegação entre telas
- Gerenciamento de estado
- Armazenamento local
- Desenvolvimento multiplataforma
- Técnica Pomodoro para produtividade
- CRUD de tarefas a fazer e concluídas

---

**Desenvolvido com 💙 durante o curso de React Native da Alura**
