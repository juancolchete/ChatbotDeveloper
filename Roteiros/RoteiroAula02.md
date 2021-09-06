# Variáveis Chatbot Developer Aula 02 Módulo 01

## O que é variável?

Se trata de um espaço na memória do computador capaz de armazenar, um dado, por exemplo nome, número, data de nascimento, e-mail e diversos outros valores, aqui no blip a gente pode trabalhar com elas nas ações de cada bloco.

## Variáveis configurações gerais

São variáveis que ao importar um fluxo, seus valores são mantidos,  nesta seção a gente pode fazer a gestão de diversos comportamentos do bots e ajustar os parâmetros, configurações que podem ser feitas são:

 **Confiabilidade de IA** variável que define a porcentagem que será aceita para utilizar as conclusões da IA

T**racking automático:** quando habilitado adiciona um registro de evento para cada bloco presente no fluxo.

**Contexto de roteador:**  permite que o bot trabalhe no conceito de bots especialistas e roteadores, permitindo o redirecionamento e a passagem de variáveis de um contato inteligente para o outro.

**Expiração da sessão:** é o tempo em segundos de expiração da sessão dos usuários em caso de inatividade. Quando a expiração ocorre , o usuário volta para o estado inicial do fluxo. Se este valor não estiver definido, a expiração não ocorre

**limite de ações:** é a configuração que permite limitar o tempo em máximo de execução das ações caso esse tempo seja estourado a execução e abortada.

**identificador do fluxo** é a chave única que o fluxo contém, ela pode ser alterada, porém se isto acontecer as sessões serão resetadas,

**variáveis de configuração** são variáveis locais do chatbot geralmente são usada para dados constantes, como por exemplo chaves de APIs, urls Bases entre outras aplicações, elas podem ser substituídas por variáveis comuns mas são importantes pois é uma boa prática armazenar os valores que são constantes nela, valores estes que raramente mudam.

## Biblioteca de variáveis

Aqui ficam disponíveis para consulta as variáveis padrão do Blip Chat e uma descrição que ajuda bastante no desenvolvimento dos contatos inteligentes.