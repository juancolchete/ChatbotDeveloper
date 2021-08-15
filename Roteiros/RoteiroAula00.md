# Visão geral blip chat Chatbot Developer Aula 00 Módulo 01

Hoje oficialmente começa o nosso curso chatbot developer utilizando a plataforma Take Blip.

## O que é o blip chat?

Se trata uma plataforma da Take Blip de criação de chatbot utilizando Low Code, que é uma tecnologia que permite a criação de soluções sem a necessidade de muito conhecimento de programação.  Os contatos inteligentes são criados com a utilização de blocos setas. representadas por um fluxograma. a plataforma tem diversos recursos que facilitam o desenvolvimento como por exemplo a utilização de requisições HTTP que permite o consumo de APIs REST, atendimento humano com a tecnologia do Blip Desk que facilita o processo de transbordo, utilização de scripts para manipulação e tratamento de dados, utilização de variáveis locais e de configuração. Ela permite a criação de chatbots com a  estrutura de router e bot especialistas, além de  integrados como WhatsApp, Facebook, Menssager, Instagram, Telegram entre outros.

## O que será abordado neste curso?

O objetivo principal é facilitar o uso dessa poderosa plataforma de criação contatos inteligentes e dar uma ótima base de acordo com as boas práticas de mercado para se tornar um chatbot developer, passando pelos conceitos principais, desde a criação do primeiro contato inteligente até o uso de scripts, realização de requisições HTTP, utilização de recursos, transbordo, uso de scripts e novidades do Blip Chat.

## Visão geral do curso

Agora vou mostrar a visão geral do curso 

Módulo 1 criação do primeiro chatbot

objetivo dar os primeiros passos na plataforma, conceitos iniciais,criar o primeiro contato inteligente, falar do debugger, testes e váriavies

Módulo 2 Principais Recursos

Objetivo Trabalhar com requisições HTTP e tratando dados com JavaScript, primeiro projeto bot do Telegram utilizando a API do GitHub

Módulo 3 Boas práticas

Apresentar as melhores práticas do mercado e de escalabilidade para facilitar na manutenção agilizar a entrega.

Módulo 4 Atendimento Humano

Trabalhar com atendimento humano, principais configurações e recursos

Módulo 5  Integrações

Entrando mais a fundo no Blip Chat, integração com o Salesforce, Dropbox, Hubspot e diversos outros serviços

Módulo 6 Novidades

Novidades e acompanhamentos de melhorias do Blip chat

# Estrutura básica

**Bloco de início:** tem como funcão receber a primera interação do usuário e passar para o próximo, nele geralmente ficam variáveis gerais do bot, scripts e requisições genéricas.

**Bloco de exeções:** tem como função receber todo comportamento que não foi desejado, no fluxo normal do bot, como por exemplo erro na validação da entrada de usuário, erros inesperados e mandar uma mensagem para o usuário, por padrão este bloco redireciona para o início

**Adicionar blocos:** este botão permite adicionar mais blocos no fluxo seja blocos padrões ou blocos de atendimento humano.

**Publica fluxo**: este botão realiza a publicação de uma nova versão do fluxo.

Engrenagem de configuração: ao clicar nela aparece as configurações gerais do bot como variáveis, versões e ações globais

**Pesquisar:** esse botão permite pesquisar por blocos presente no bot e seus recursos internos

**Atendimento humano:** este botão permite fazer todas as configurações relacionadas ao transbordo

## Configurações gerais conteúdo

Submenu onde os componentes visuais ficam dispostos, neste exemplos temos uma mensagem de digitando, um texto e uma entrada de usuário, é permitido a utilização de no máximo 25 mensagens por bloco estas podem ser: texto, quick reply, imagem, carrossel, menu, áudio, vídeo, digitando, pedir localização, web link, conteúdo HTTP e conteúdo dinâmico.

## Configurações gerais condições de saída

É onde é configurada toda a lógica de redirecionamento do bot, cada condição de saída direciona a um bloco no fluxo, se nenhuma delas forem satisfeitas o usuário é redirecionado para o bloco de exceções.

## Configurações gerais **Ações**

As ações podem ser de dois tipos, de entrada de de saída.

**Ações de entrada:** são executadas antes do primeiro bloco de conteúdo aparecer na tela.

Ações de saída:  ****são executadas após o último bloco de conteúdo aparecer na tela.

nestas ações é possível adicionar requisições HTTP, registro de eventos, definição de contatos, redirecionamentos variáveis, scripts, gerenciamento de lista de distribuição executar script, definir variáveis, consultar assistente de conteúdo e processar comando.