# Visão geral blip chat Chatbot Developer Aula 00 Módulo 01

Hoje oficialmente começa o nosso curso chatbot developer utilizando a plataforma Take Blip.

## O que é o blip chat?

Se trata uma plataforma da Take Blip de criação de chatbot utilizando Low Code, que é uma tecnologia que permite a criação de soluções sem a necessidade de muito conhecimento de programação.  Os contatos inteligentes são criados com a utilização de blocos e setas. representadas por um fluxograma. a plataforma tem diversos recursos que facilitam o desenvolvimento como por exemplo a utilização de requisições HTTP que permitem o consumo de APIs REST, atendimento humano com a tecnologia do Blip Desk que facilita o processo de transbordo, além disso tem como recurso utilização de scripts para manipulação e tratamento de dados, utilização de variáveis locais e de configuração. O builder permite a criação de chatbots com a  estrutura de router e bots especialistas, além de  integrar com WhatsApp, Facebook, Menssager, Instagram, Telegram entre outros canais.

## O que será abordado neste curso?

O objetivo principal é facilitar o uso dessa poderosa plataforma de criação de contatos inteligentes e dar uma ótima base de acordo com as boas práticas de mercado para se tornar um chatbot developer, passando pelos conceitos principais, de criação do primeiro contato inteligente realização de requisições HTTP , utilização de recursos, transbordo, uso de scripts, e novidades do Blip Chat.

## Visão geral do curso

No Módulo 1 nos vamos fazer a criação do primeiro chatbot

O objetivo é dar os primeiros passos na plataforma, aprender conceitos iniciais, criar o primeiro contato inteligente, falar do debugger, testes e váriavies

No Módulo 2 nos vamos abordar os Principais Recursos

O objetivo é Trabalhar com requisições HTTP e tratamento de dados com JavaScript além de construir o primeiro projeto de bot utilizando o canal do Telegram tendo como base a API do GitHub

No Módulo 3 vamos estudar e aplicar as Boas práticas

A ideia é apresentar as melhores práticas do mercado e de escalabilidade para facilitar na manutenção e agilizar a entrega.

No Módulo 4 vamos explorar e configurar o Atendimento Humano

Trabalhar com transbordo, principais configurações e recursos

No Módulo 5 vamos trabalhar com Integrações

O nosso objetivo é entrar mais a fundo no Blip Chat, na integração com o Salesforce, Dropbox, Hubspot e diversos outros serviços

No Módulo 6 vamos trabalhar com Inteligência artificial 

Vamos estudar o Dialog Flow e a aplicação da inteligência artificial no chatbot

E por último no Módulo 7 vamos trabalhar com as Novidades

Trazendo recursos interessantes que acabaram de ser lançados.

# Estrutura básica

**Bloco de início:** ele tem como função receber a primeira interação do usuário e passar para o próximo bloco, nele geralmente ficam variáveis gerais do bot, scripts e requisições genéricas.

**Bloco de exceções:** ele tem como função receber todo comportamento que não foi desejado, no fluxo normal do bot, como por exemplo erro na validação da entrada de usuário, caso seja um erro configurado nas condições de saída ele exibe a mensagem de erro, em caso de não ser mapeado ele volta para o bloco inicio.

**Adicionar blocos:** este botão permite adicionar mais blocos no fluxo seja blocos padrões ou blocos de atendimento humano.

**Publicar fluxo**: este botão realiza a publicação de uma nova versão do fluxo em todos os canais conectados.

**Engrenagem de configuração**: ao clicar nela aparece as configurações gerais do bot como variáveis, versões e ações globais .

**Biblioteca de variáveis:** contem todas as variáveis nativas do builder e uma breve explicação de seu conteúdo.

**Pesquisar:** esse botão permite pesquisar por blocos presentes no bot e seus recursos internos.

**Atendimento humano:** este botão permite fazer todas as configurações relacionadas ao transbordo

## Configurações gerais conteúdo

Submenu onde os componentes visuais ficam dispostos. Neste exemplo temos uma mensagem de digitando, um texto e uma entrada de usuário. É permitido a utilização de no máximo 25 mensagens por bloco estas podem ser: texto, quick reply, imagem, carrossel, menu, áudio, vídeo, digitando, pedir localização, web link, conteúdo HTTP e conteúdo dinâmico.

## Configurações gerais condições de saída

É onde é configurada toda a lógica de redirecionamento do bot, cada condição de saída direciona a um bloco no fluxo, se nenhuma delas forem satisfeitas o usuário é redirecionado para a saída padrão neste exemplo está configurada para o bloco de exceções.

## Configurações gerais **Ações**

As ações podem ser de dois tipos, de entrada de ou de saída.

**Ações de entrada:** elas ****são executadas antes do primeiro bloco de conteúdo aparecer na tela.

**Ações de saída:**  ****elas ****são executadas após o último bloco de conteúdo aparecer na tela.

nestas ações é possível adicionar requisições HTTP, registro de eventos, definição de contatos, redirecionamentos, variáveis, scripts, gerenciamento de lista de distribuição executar script, definir variáveis, consultar assistente de conteúdo e também processar comando.

## Inteligência Artificial

Através dos provedores de IA podemos configurar a Inteligência Artificial do nosso bot, podendo assim validar se as saídas estão de acordo com o esperado e ir aprimorando o modelo de testes. 

## Canais

De acordo com a necessidade dos clientes podemos configurar os canais do chatbot para melhor atende-lo, a vantagem do Blip Chat é que ao construir o bot uma vez ele pode ser utilizado em todos os canais que tiverem conectados

## Análise

Essa é a parte, é responsável por fornecer as informações do contato inteligente em forma de relatório, assim permitindo a tomada de ações em prol de otimizar o bot para os usuários além de nutrir com informações importantes de desempenho

## Configurações

Seção responsável por realizar configurações básicas, boas vindas menu persistente e obter os dados de conexão para consumir a API da Take Blip

## Equipe

Área responsável por fazer todo o gerenciamento de permissões do bot, é o lugar para adicionar e remover membros da equipe concedendo os níveis de acesso.

## Testes

Essa é a região de testes, nela é possível validar o comportamento do bot, realizar o debug, acompanhando o caminho percorrido pelo contato inteligente, registros de eventos, requisições HTTP, execuções de scripts, variáveis e conteúdo dinâmico.

## Obrigado :)

Gostaria de agradecer a atenção de todos, muito obrigado por me assistir até aqui, e no mais, desejo bons estudos e vou deixar as minhas redes sociais para quem quiser interagir.
