# Primeiro contato com a plataforma Take Blip Aula 01 Módulo 01

## Primeiros passos

Para começar vamos acessar a plataforma do Blip Chat, o link é [portal.blip.ai](https://portal.blip.ai), nessa parte ficam disponíveis os contatos inteligentes que a gente criou, tem duas formas de começar, criando o seu chatbot do zero e criando um bot de Atendimento Manual, como vamos começar com o contato inteligente em branco vamos criar do zero, vou começar criando um bot de portfolio pessoal, ao decorrer da aula vou dar mais detalhes do chatbot

## Sobre o fluxo

Aqui estão os quatro blocos iniciais que aparecem quando a gente cria a nosso bot no builder, o bloco de Inicio contém uma entrada de usuário para começar o fluxo, este bloco tem condições de saída e as ações, lembrando que para o bot iniciar o fluxo, o usuário deve mandar uma mensagem qualquer, os blocos tem uma estrutura muito semelhante e o bloco de exceções é a saída  padrão da maioria dos blocos. O bloco de exceções é acionado geralmente quando ocorre um erro na validação dos dados, um erro planejado ou um erro inesperado quando este último ocorre o bot geralmente  redireciona para o bloco de erro padrão.

## Configurações Variáveis

Agora vou falar um pouco mais do menu de configurações, a partir dele a gente pode fazer a gestão de diversos comportamentos do bots e ajustar os parâmetros, a parte de **confiabilidade de IA** a gente vai ver mais no módulo de inteligência artificial e basicamente ele define a porcentagem que será aceita para utilizar as conclusões da IA, o **tracking automático** será abordado no módulo de Analise mas basicamente ele adiciona um registro de evento para cada bloco presente no fluxo, exceto início e exceções, o utilizar contexto de roteador permite que o bot trabalhe no conceito de bots especialistas e roteadores, a **expiração da sessão** é o tempo em segundos de expiração da sessão dos usuários em caso de inatividade. Em caso de expiração da sessão, o usuário volta para o estado inicial do fluxo. Se este valor não estiver definido, a expiração não ocorre tempo **limite de ações** é a configuração que permite limitar o tempo em máximo de execução das ações caso esse tempo seja estourado a execução e abortada, **identificador do fluxo** é a chave única de que o fluxo contém, ela pode ser alterada porém se isto acontecer as sessões serão resetadas, **variáveis de configuração** são varíavei locais do chatbot geralmente são usada para dados constantes, como por exemplo chaves de APIs, urls Bases entre outras aplicações, elas podem ser substituídas por variáveis comuns mas são importantes pois é uma boa prática armazenar os valores que são constantes nela, valores constantes são valores que raramente mudam.

## Configurações Versões

As versões são os arquivos JSON que o blip salva, a cada publicação se for necessário essa versão pode ser revertida porém estas versões estão limitadas a 5 então é interessante salvar o arquivo JSON em um sistema de versionamento para se caso ocorrer algum problema em seu bot você poder simplesmente importar a última versão funcional, vou abordar esse tema de forma mais completa no módulo de boas práticas.

## Ações Globais

**Ações de entrada:** estas são executadas antes do envio do primeiro conteúdo e antes das ações de entrada do bloco

**Ações de saída:** são executadas após o envio do último conteúdo ou resposta do usuário e depois das ações de saída do bloco

lembrando que elas irão ser executadas para cada bloco que o usuário interagir. 

## Biblioteca de variáveis

Aqui ficam disponíveis para consulta as variáveis padrão do Blip Chat e uma descrição, o que ajuda bastante no desenvolvimento dos chatbots, aqui nós vamos precisar pegar a variável contact.name

## Sobre o fluxo

A ideia do mão na massa da aula de hoje é criar um fluxo que se apresente ao usuário e dê saudações, para saudar precisaremos de obter o nome do usuário, com tudo isso feito vou colocar este bot na estrutura de roteador, que é a mais recomendada na criação de chatbots.