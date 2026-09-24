# AULA-1--SISTEMAS-DISTRIBU-DOS
Atividades da primeira aula de Sistemas Distribuídos do quarto semestre

Aula 01: Introdução aos Sistemas Distribuídos
Seja bem-vindo ao repositório da primeira aula da disciplina de Sistemas Distribuídos!

Neste primeiro encontro, exploramos os conceitos fundamentais sobre como máquinas independentes se identificam, se localizam e trocam informações em rede para funcionarem como um sistema coeso.

📌 Conteúdos Abordados
1. O que são Sistemas Distribuídos?
Definição: Conjunto de computadores independentes que se apresentam aos usuários como um sistema único e coerente.

Principais Desafios: Concorrência, ausência de um relógio global e falhas independentes dos componentes.

2. Endereçamento e Identificação (Endereço IP)
O que é o Endereço IP: O identificador numérico atribuído a cada dispositivo conectado a uma rede para permitir a sua localização e comunicação.

IPv4 vs. IPv6:

IPv4: Formato de 32 bits (ex: 192.168.1.1), limitado a aproximadamente 4,3 bilhões de endereços.

IPv6: Formato de 128 bits (ex: 2001:0db8:85a3::8a2e:0370:7334), criado para suprir o esgotamento do IPv4.

Máscara de Rede e Sub-redes: Separação da parte do IP que identifica a rede da parte que identifica o host.

Portas de Comunicação: Portas lógicas (ex: 80 para HTTP, 443 para HTTPS, 5432 para PostgreSQL) que permitem ao sistema operacional direcionar o tráfego para a aplicação correta.

3. Comunicação entre Servidores
Modelo Cliente-Servidor: Estrutura básica onde o cliente envia uma requisição (request) e o servidor processa e retorna uma resposta (response).

Protocolos de Transporte:

TCP (Transmission Control Protocol): Orientado à conexão, garante a entrega e a ordem dos pacotes (ideal para APIs, transferências de arquivos e bancos de dados).

UDP (User Datagram Protocol): Sem conexão, prioriza velocidade sobre confiabilidade (ideal para streaming e jogos online).

Fluxo Básico de Comunicação:

Resolução de nome via DNS (se aplicável).

Abertura do socket de comunicação na combinação IP:Porta.

Envio da mensagem/pacote de dados através da rede.

Processamento pelo servidor e retorno dos dados.
