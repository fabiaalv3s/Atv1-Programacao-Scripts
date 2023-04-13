# Atv1-Programacao-Scripts

#### Descrição  da  atividade: fazer  umaplicativo web para  mostrar os  dados  do último sorteio da Mega-senae Lotofácil.

## REQUISITOS FUNCIONAIS

**i.** A aplicação deverá consumir os resultados disponibilizados na API: https://servicebus2.caixa.gov.br/portaldeloterias/api/home/ultimos-resultados;

**ii.** A página deverá exibir oúltimo resultado da Mega-sena e Lotofácil:

**iii.** Os resultados devemser carregados ao inicializar a aplicação;

**iv.** Enquanto   o   resultado   não   estiver   disponível   deverá   ser   exibida   uma   mensagem   de   carregando centralizada na tela na vertical e horizontal.


## REQUISITOS NÃO FUNCIONAIS

**a)** A aplicação deverá ser codificada usando React TypeScript;

**b)** O projeto deverá teros seguintes pacotes: assets (arquivo de imagens PNG), components(pacote com os componentes  utilizados  na  página),pages(terá  apenas  uma  página), contexts(contextoe  Provider),hooks  (função  que  retorna  os  recursos  do  Contexto), services(faza conexão  com  a  API  de  Loterias  da Caixa)e types(interfaces);

**c)** Cada item da página deverá ser um componentee os estilos CSS devem estar num arquivo CSS vinculado ao componente;

**d)** A aplicação deverá rodar na porta 3001;

**e)** O ícone da página deverá serhttps://loterias.caixa.gov.br/Style%20Library/images/favicon.ico;

**f)** Gerar uma versão build da aplicação e subirela na porta 3002;

**g)** Utilize    a    fonte    Roboto em    todos    os    textos. 
Dica:    adicione    o    pacote @fontsource/roboto(https://www.npmjs.com/package/@fontsource/roboto)e importe ele no arquivo src/index.tsx;

**h)** Utilize axios para processar as requisições HTTP.

