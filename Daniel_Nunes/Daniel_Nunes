**De onde veio isso?**
Uma metodologia de controle de qualidade nos conceitos da indústria 4.0

**Introdução**

A indústria 4.0 é um movimento de origem alemã que teoriza a evolução dos métodos de produção industrial em consequência de movimentos sociais e desenvolvimento tecnológico da última década. O termo foi cunhado em 2011 nomeando uma iniciativa do governo alemão para o desenvolvimento do seu, já consolidado, mercado industrial (1).
Tendo em mente o conceito de rastreabilidade que tem ganho crescente destaque nos processos industriais, este projeto busca desenvolver uma metodologia de coleta de dados qualitativos para controle de qualidade interno. 

**Concepção**

Atendendo aos requisitos de projeto solicitados, o projeto contará com quatro estágios de aquisição de dados: leitura de código de barras, verificação do nível do líquido, medição da temperatura do líquido e captura da cor do líquido. Para que estas medições possam acontecer, ainda serão implementados sensores de presença para cada estágio e um display para interface com o usuário. O dispositivo principal do projeto, responsável pelo controle de todos os periféricos supracitados será implementado com uma plataforma microcontrolada.

**Leitura do código de barras**

Usando um leitor de códigos do tipo 1D (unidirecional) posicionado na altura regular de onde espera-se posicionar o código de barras da embalagem, espera-se obter uma leitura que possibilite identificar o produto e posteriormente anexar a informação da inspeção realida ao lote.

_(Aguardando chegada do componente para maior detalhamento e estudo de funcionamento)._

**Verificação do nível de conteúdo**

Para esta medição, será utilizado o sensor JSN-SR04T. Entrance as características deste módulo, vale destacar que seu emissor e seu sensor são dispostos de forma radial, necessitando uma menor abertura para medição, ponto crucial por ter-se uma garrafa como objeto de estudo.

_(Módulo em mãos, implementação a seguir)_

**Medição da temperatura do conteúdo**

Tratando-se de um produto alimentício, é primordial para a implementação de um controle de qualidade eficiente a medicação da temperatura do líquido no interior da embalagem. Assim, nesta etapa, posicionará-se um sensor de temperatura de forma coaxial ao gargalo da garrafa aberta, apontado diretamente para o conteúdo. Devido sua disponibilidade, será utilizado o sensor MLX90614.

**Medição da cor do conteúdo**

Outra característica importante de ser observada para atestar que a qualidade do produto está de acordo com um padrão pré-estabelescido é a coloração do líquido engarrafado. Está medição será realida com o sensor TCS3200.

**Sensor de presença**

Tendo-se definido como requisito que este projeto seja desenvolvido imaginando sua implementação em uma linha de produção, faz-se necessário o sensoriamento e presença do produto em cada etapa de medição. Asim monitorando seu deslocamento no trajeto da produção. Este sensoriamento dar-se-á por meio de simples resistores variáveis sensíveis à luz infravermelha, sendo necessário o desenvolvimento posterior de um circuito de conformização do sinal proveniente destes para o espectro digital.

**Unidade de controle**

Toda o controle e processamento destes dados será implementado utilizando um módulo Arduino Uno devido sua praticidade e vasta gama de documentação da aplicações utilizando este.

**Display**

Apesar de ser imaginado para uma implementação automatizada em uma linha de produção, o protótipo contará com um display LCD para interface com o usuário. Por este meio, será possível comunicar possíveis divergências com dos parentros medidos em relação aos estabelecidos.

1 - https://online-journals.org/index.php/i-jim/article/download/7072/4532
