# Teste para Front-end Web Developer

## Introdução
O objetivo desse teste é verificar o mínimo de conhecimento sobre semântica HTML e também recursos comumente utilizados em CSS.
Tempo de execução será um dos fatores a serem considerados, porém é importante que o teste seja feito com primor, mesmo que entregue em cima do laço.

## O desafio
O canditado deve montar o HTML e CSS de um artigo do portal Jornal Semente. Esse distinto jornal pode ser descrito como "o jornal que traz o melhor sobre desenvolvimento humano com linguagem simples, direta e acessível".

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

### Restrições e informações
- Tipografia: Poppins e Merryweather;
- Cabeçalho deve ocupar toda a largura da tela, mas o conteúdo dentro deve ter no máximo 1000px de largura;
- Conteúdo deve ter no máximo 680px de largura;
- Uso livre de grids pré-montados;
- Todas as imagens estão disponíveis em "..src/images";
- Você deve obrigatoriamente utilizar ao menos um recurso do SCSS;
- Não é necessário, mas caso queira escrever algum JS escreva em "..src/js".

### Validação do teste
O resultado final deverá ser um arquivo zip da pasta "dist" a ser enviado para a pessoa que lhe enviou o desafio.