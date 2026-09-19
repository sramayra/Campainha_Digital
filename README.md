# Campainha Digital

Projeto acadêmico de extensão desenvolvido para o curso de Redes de Computadores. O sistema propõe uma alternativa de baixo custo para o registro de entregas e visitas em um condomínio residencial, utilizando QR Code e integração com WhatsApp.

## Como funciona

O QR Code fixado na entrada do condomínio direciona para o site (`index.html`). O visitante ou entregador seleciona seu perfil e a unidade de destino, e o sistema gera automaticamente uma mensagem padronizada, enviada via WhatsApp ao responsável pela portaria. Nenhum dado pessoal do morador (telefone, e-mail) é exibido durante o processo.

## Arquivos do repositório

- **`index.html`** — código-fonte completo do site (HTML, CSS e JavaScript). Não utiliza banco de dados nem dependências externas além de fontes web.
- **`_config.yml`** — arquivo de configuração exigido pelo GitHub Pages para publicação do site estático.
- **`qrcode.png`** — imagem do QR Code utilizado na aplicação prática, fixado na entrada do condomínio, direcionando para o link do site publicado.
- **`apresentacao.pptx`** — material utilizado na palestra de apresentação e treinamento realizada com os moradores.
- **`respostas_formulario.xlsx`** — planilha com a extração das respostas do formulário de avaliação aplicado após a implementação do sistema, contendo duas abas: dados brutos das respostas e análise/tabulação dos resultados.

## Tecnologias utilizadas

HTML, CSS e JavaScript puro. Hospedagem via GitHub Pages. Geração de QR Code e coleta de dados via ferramentas gratuitas externas (não incluídas neste repositório).

## Escopo e limitações

Este projeto foi desenvolvido como parte de uma atividade acadêmica, com aplicação real e restrita a um único condomínio, para fins de comprovação prática dos objetivos propostos. O sistema depende de um número de WhatsApp fixo como intermediário e não possui camada de autenticação, banco de dados ou infraestrutura própria de servidor.

## Contexto acadêmico

Repositório mantido como evidência de desenvolvimento e implementação para fins de avaliação institucional.
