# 🎵 Clonando Layout Spotify

## 📱 Avaliação — Clonando o Layout de um App Famoso

**Disciplina:** Mobile  
**Tópico:** 6. Conceitos da Interface do Usuário — Layouts em XML e ConstraintLayout

---

# 🎯 Objetivo do Projeto

Este projeto foi desenvolvido para a avaliação **"Clonando o Layout de um App Famoso"**, cujo objetivo é recriar visualmente a interface de um aplicativo conhecido utilizando **Android Studio**, **XML** e **ConstraintLayout**.

A atividade tem como foco exclusivamente a construção da interface do usuário, sem desenvolvimento de funcionalidades, buscando reproduzir o aplicativo original com a maior fidelidade visual possível.

Foram considerados:

- Proporção dos elementos;
- Espaçamento entre componentes;
- Organização da tela;
- Cores;
- Tipografia;
- Posicionamento utilizando Constraints.

---

# 🎧 Aplicativo escolhido

## Spotify

O aplicativo escolhido para reprodução foi o **Spotify**.

A tela desenvolvida foi baseada na **tela inicial (Home) do Spotify**, recriando a estrutura visual do aplicativo original.

A interface contém elementos como:

- Avatar do usuário;
- Categorias de conteúdo;
- Cards de atalhos;
- Listas musicais;
- Recomendações;
- Mixes personalizados;
- Estações de rádio;
- Mini player;
- Barra de navegação inferior.

---

# 🛠️ Tecnologias utilizadas

- Android Studio
- XML
- ConstraintLayout
- Material Design
- Drawable Resources
- Styles
- Colors
- Git
- GitHub

---

# 📐 Conceitos aplicados

## ConstraintLayout

O projeto utiliza o **ConstraintLayout** como estrutura principal da interface.

Todos os componentes foram posicionados utilizando constraints, sem o uso de posições fixas ou coordenadas absolutas.

Foram utilizados:

```xml
layout_constraintTop_toTopOf
layout_constraintBottom_toBottomOf
layout_constraintStart_toStartOf
layout_constraintEnd_toEndOf
```

Esses recursos permitem criar uma interface adaptável para diferentes tamanhos de tela.

---

# 🧩 Componentes utilizados

Durante o desenvolvimento foram utilizados componentes de interface Android:

| Componente | Utilização |
|------------|------------|
| ConstraintLayout | Estrutura principal da tela |
| ScrollView | Área com rolagem vertical |
| TextView | Textos e títulos |
| ImageView | Capas, ícones e imagens |
| View | Cards e elementos decorativos |
| Guideline | Organização e alinhamento |

---

# 🎨 Estrutura da interface

## Cabeçalho

O topo da tela foi desenvolvido contendo:

- Avatar do usuário;
- Botões de categoria;
- Filtros de conteúdo.

Categorias:

- Tudo;
- Músicas;
- Podcasts.

---

# 🎵 Cards de atalhos

Foram recriados cards semelhantes aos presentes no Spotify:

- Músicas Curtidas;
- Rádio;
- Playlists.

Cada card possui:

- Imagem;
- Fundo personalizado;
- Texto;
- Organização utilizando ConstraintLayout.

---

# 🎶 Seções musicais

A tela possui diversas seções inspiradas no aplicativo original:

## Não sai do seu fone

Lista de músicas recomendadas.

---

## Seus mixes mais ouvidos

Cards de mixes personalizados.

---

## Estações de rádio populares

Reprodução visual de estações baseadas em artistas.

---

## Recomendações para hoje

Sugestões musicais.

---

## Singles e álbuns que todo mundo gosta

Cards de músicas e álbuns populares.

---

## Suas playlists

Área contendo playlists do usuário.

---

# 🎧 Mini Player

Na parte inferior da tela foi criado um mini player semelhante ao Spotify.

Elementos utilizados:

- Capa da música;
- Nome da faixa;
- Nome do artista;
- Ícones de controle;
- Barra de progresso.

---

# 📱 Barra de navegação inferior

Foi recriada a barra inferior do aplicativo contendo:

- Início;
- Buscar;
- Sua Biblioteca;
- Premium;
- Criar.

---

# 📂 Estrutura do projeto

```text
clonando-layout-spotify
│
├── app
│   └── src
│       └── main
│           │
│           ├── java
│           │
│           ├── res
│           │   │
│           │   ├── drawable
│           │   │
│           │   ├── layout
│           │   │   └── activity_main.xml
│           │   │
│           │   └── values
│           │       ├── colors.xml
│           │       └── styles.xml
│           │
│           └── AndroidManifest.xml
│
├── gradle
│
├── build.gradle
│
└── settings.gradle
```

---

# 🖼️ Comparação visual

## Referência original do Spotify

Imagem utilizada como base para reprodução do layout.

*(Adicionar print da tela original do Spotify)*


---

## Layout desenvolvido

Resultado final da interface criada no Android Studio.

*(Adicionar print da aplicação funcionando)*

---

# 📚 Aprendizados

Com o desenvolvimento deste projeto foi possível praticar:

- Criação de interfaces Android utilizando XML;
- Organização de layouts com ConstraintLayout;
- Uso correto de Constraints;
- Criação de estilos personalizados;
- Organização de cores no arquivo `colors.xml`;
- Uso de recursos Drawable;
- Reprodução de interfaces reais de aplicativos.

---

# 🚀 Resultado

O projeto apresenta uma reprodução visual da tela inicial do Spotify utilizando apenas recursos de interface Android.

O desenvolvimento buscou manter fidelidade ao design original através da organização dos elementos, espaçamento, alinhamento e utilização correta do ConstraintLayout.

---

# 👨‍💻 Desenvolvedor

**Gabriel Santos**

Projeto desenvolvido para a disciplina de Mobile.
