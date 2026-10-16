# 🎬 Katalog Design System

Catálogo interativo de componentes visuais desenvolvido em Flutter para documentar, visualizar e testar os elementos de interface utilizados como referência para o Katalog — Catálogo de Filmes e Jogos.

O aplicativo funciona como uma biblioteca de componentes reutilizáveis. A tela inicial apresenta as categorias do Design System e permite navegar pelas galerias, visualizar variações e experimentar os estados de interação de cada componente.

## Objetivo

O projeto tem como objetivo aplicar os conhecimentos desenvolvidos na disciplina por meio da criação de um Design System em Flutter.

A proposta é organizar e documentar os padrões visuais e os componentes reutilizáveis do Katalog, facilitando a padronização das interfaces, a manutenção do código e a consistência da experiência do usuário.

O aplicativo não tem como objetivo implementar o catálogo completo de filmes e jogos. Seu foco é demonstrar os componentes que podem ser utilizados na construção das interfaces do sistema.

## Design no Figma

O Figma pode ser utilizado como referência para a identidade visual, os componentes e as telas do Katalog Design System.

- **Arquivo do Design System:** [Inserir link do Figma, caso exista]
- **Arquivo das telas do Katalog:** [Inserir link do Figma, caso exista]

## Funcionalidades

- Página inicial com as categorias do Design System;
- Navegação entre as galerias de componentes;
- Visualização de componentes reutilizáveis;
- Demonstração de variações e estados de interação;
- Botões com diferentes estilos e comportamentos;
- Campos de entrada e pesquisa;
- Cards para apresentação de filmes e jogos;
- Seletores de favoritos e status;
- Componentes de avaliação por estrelas;
- Navegação entre as telas de demonstração;
- Organização modular dos componentes;
- Aplicação de tema visual compartilhado;
- Interações para testar o comportamento dos componentes.

## Categorias do Design System

| Categoria | Componentes |
|---|---|
| Ações | Botões primários, secundários e de ícone |
| Navegação | Menus, abas e elementos de navegação |
| Entradas e filtros | Campos de texto, pesquisa e filtros |
| Cards e conteúdo | Cards de filmes, jogos e estatísticas |
| Seletores e controles | Favoritos, seleção de status e opções |
| Avaliações | Estrelas, notas e componentes de avaliação |
| Estados e feedback | Mensagens de erro, sucesso, carregamento e estado vazio |

## Estados Representados

Os estados são demonstrados de acordo com o comportamento esperado de cada componente:

- **Padrão:** aparência inicial do componente;
- **Pressionado:** resposta visual ao acionamento;
- **Focado:** campo ativo para entrada de dados;
- **Preenchido:** campo que contém informações;
- **Selecionado:** opção escolhida pelo usuário;
- **Desmarcado:** opção disponível, mas não selecionada;
- **Desabilitado:** componente indisponível para interação;
- **Carregamento:** indicação de processamento;
- **Erro:** indicação de entrada inválida ou falha;
- **Sucesso:** confirmação visual de uma ação concluída.

## Identidade Visual

A identidade visual do Katalog Design System deve manter consistência com a proposta do catálogo de filmes e jogos.

A paleta inicial sugerida utiliza tons escuros e detalhes dourados:

| Elemento | Cor | Código |
|---|---|---|
| Fundo principal | Azul-escuro | `#0F172A` |
| Superfícies e cartões | Azul-acinzentado | `#1E293B` |
| Destaques e ações | Dourado | `#FBBF24` |
| Texto principal | Branco suave | `#F1F5F9` |
| Texto secundário | Cinza | `#94A3B8` |
| Sucesso | Verde | `#22C55E` |
| Erro | Vermelho | `#EF4444` |

Essas cores são uma proposta inicial e devem ser ajustadas caso o grupo já tenha definido uma identidade visual no Figma.

## Arquitetura

O projeto utiliza Flutter e Dart para organizar os componentes visuais e as telas de demonstração.

A estrutura proposta separa os elementos compartilhados, as categorias de componentes e as telas do catálogo:

```text
katalog_design_system/
├── lib/
│   ├── main.dart
│   ├── app.dart
│   ├── common/
│   │   ├── theme/
│   │   │   ├── app_colors.dart
│   │   │   └── app_theme.dart
│   │   └── widgets/
│   ├── components/
│   │   ├── action_button/
│   │   ├── navigation/
│   │   ├── inputs/
│   │   ├── media_card/
│   │   ├── selectors/
│   │   └── ratings/
│   └── screens/
│       ├── home/
│       └── samples/
├── test/
├── pubspec.yaml
└── README.md
```

A estrutura deverá ser atualizada conforme os arquivos efetivamente criados no projeto.

## Tecnologias e Ferramentas

- **Flutter:** framework para desenvolvimento da aplicação;
- **Dart:** linguagem de programação;
- **Material Design:** recursos e padrões de interface do Flutter, quando utilizados;
- **Figma:** referência para prototipação e identidade visual, caso adotado;
- **Git e GitHub:** versionamento e documentação do projeto.

## Organização dos Componentes

Os componentes devem ser desenvolvidos de forma reutilizável, permitindo que suas propriedades e seus estados sejam configurados de acordo com a necessidade de cada tela.

Essa organização facilita a manutenção, reduz a duplicação de código e contribui para a consistência visual do Katalog.

## Testes e Validação

A validação do Design System deve considerar:

- Navegação entre as categorias;
- Exibição correta dos componentes;
- Funcionamento das interações;
- Comportamento dos estados;
- Consistência visual entre as telas;
- Reutilização dos componentes;
- Execução dos testes automatizados, quando implementados.

## Sobre

O Katalog Design System é um projeto acadêmico desenvolvido em Flutter no contexto da disciplina de Engenharia de Software.

Seu propósito é demonstrar a criação de uma biblioteca organizada de componentes reutilizáveis, documentando suas categorias, variações e estados de interação para servir como referência visual e técnica para o Katalog — Catálogo de Filmes e Jogos.

## Status do Projeto

Em desenvolvimento — organização da identidade visual, implementação dos componentes e construção das galerias de demonstração.
