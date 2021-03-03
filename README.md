# Teste para Front-end Web Developer

## Introdução
O objetivo desse teste é verificar o mínimo de conhecimento sobre semântica HTML e também recursos comumente utilizados em CSS.

## O desafio
O canditado deve montar o HTML e CSS/SASS de um artigo do portal Jornal Semente. Esse distinto jornal pode ser descrito como "o jornal que traz o melhor sobre desenvolvimento humano com linguagem simples, direta e acessível".

### O portal
O portal, iniciado em 2017, é escrito em português brasileiro para ser lido tanto nos computadores quanto no celular. Há pessoas que dizem que o acessam também por tablets.
Dentre os assuntos estão: certificados, certificação, diploma, carreira, profissionalizar, profissionalizante, crescimento profissional, desenvolvimento humano.
Possui conta no Twitter (@jornalsementeREAL) e no LinkedIn (@jornalsementeREAL), mas não possui no Facebook.
Considerando que há um usuário logado, o portal deve ser composto por:
- cabeçalho: marca, menu global (artigos, sobre o portal, contato);
- corpo: conteúdo relacionado ao item ativo do menu global;
- footer: marca, mídia social do portal, site map, endereço (Rua Zé das Coves, 171 - 3º andar - São José de Pádua - XP - Brasil), direitos registrados.

### Informações sobre o que deve ter no corpo/artigo:
Link do artigo: https://docs.google.com/document/d/1PJB7I07BwXKNIUr12OOaQZKhkigY0P3qMSl4Hp7noTs/edit?usp=sharing
- Avatar do autor;
- Nome do autor;
- Título do artigo;
- Lead/subtítulo do artigo;
- Assuntos relacionados/Tags do artigo;
- Data de publicação;
- Tempo estimado de leitura;
- O artigo em si;
    - Deve ter uma citação/olho;
    - Deve ter uma lista não ordenada;
    - Deve ter uma imagem com legenda.
- Compartilhar com Twitter e LinkedIn;
- Uma listagem com três artigos recomendados para ler em seguida.

## Parte técnica

### Instalação
1. Certifique-se que você possui npm e node.js instalados;
2. Abra uma tela de comando (*prompt*);
3. Vá até o diretório do Teste;
4. Digite **npm install**, para que as dependencias sejam instaladas;
5. Digite **gulp**;
6. Será criada uma pasta com a versão de distribuição do "Teste" chamada "dist";
6. Uma janela do navegador será aberta com "Hello, World!" escrito.


### A User Interface a ser transposta para HTML/CSS
As UIs se encontram na pasta ../src/ui do projeto.
Há 2 formatos em relação a dispositivos: Desktop e Mobile.


### Restrições e informações
- Tipografia: Poppins e Merryweather;
- Cabeçalho deve ocupar toda a largura da tela, mas o conteúdo dentro deve ter no máximo 1000px de largura;
- Conteúdo deve ter no máximo 680px de largura;
- Uso livre de grids pré-montados;
- Todas as imagens estão disponíveis em "..src/images";
- Você deve obrigatoriamente utilizar ao menos um recurso do SCSS;
- Não é necessário, mas caso queira escrever algum JS escreva em "..src/js".

### O que será avaliado?

- Semântica do HTML (Tags semanticamente corretas para cada caso)
- Organização e escrita do SASS
- Utilização do CSS
- Fidedignidade em relação à UI proposta
- Responsividade


### Como entregar?

Você deverá criar um fork do projeto no Github e depois de finalizar o teste, pode nos enviar o endereço do fork ou enviá-lo em arquivo zip para vagas@programasemente.com.br com o assunto "Teste para vaga de Front - Seu nome" (onde "seu nome" deve ser substituído pelo seu nome).

### Prazo

Até 3 dias úteis após a primeira conversa com o Gerente de TI
