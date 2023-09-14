# O que é Computação Nuvem?
Objetivo desse repositório armazenar estudos da computação em nuvem {Azure e GCP}

A computação em nuvem, também conhecida como "cloud computing" em inglês, é um modelo de computação que envolve o fornecimento de recursos de computação, como servidores, armazenamento, redes, bancos de dados, software e outros serviços pela internet. Em vez de empresas ou indivíduos precisarem possuir e manter seus próprios data centers e infraestrutura de TI, eles podem usar os serviços de provedores de nuvem para atender às suas necessidades de computação.
Como a computação em nuvem usa a Internet para fornecer esses serviços, ela não precisa ficar restrita pela infraestrutura física da mesma forma que um datacenter tradicional. Isso significa que, se você precisar aumentar rapidamente sua infraestrutura de TI, não precisará esperar para construir um novo datacenter; você pode usar a nuvem para expandir rapidamente seu volume de TI.

Existem três principais modelos de serviço na computação em nuvem:

Infraestrutura como Serviço (IaaS): Neste modelo, os provedores de nuvem fornecem recursos de infraestrutura virtualizados, como máquinas virtuais, redes e armazenamento. Os usuários podem controlar o sistema operacional, aplicativos e outros aspectos da infraestrutura, enquanto o provedor de nuvem gerencia o hardware subjacente.

Plataforma como Serviço (PaaS): Aqui, os provedores de nuvem oferecem uma plataforma de desenvolvimento e hospedagem que inclui ferramentas e serviços para criar, implantar e gerenciar aplicativos. Os usuários não precisam se preocupar com a infraestrutura subjacente, focando apenas no desenvolvimento de software.

Software como Serviço (SaaS): Nesse modelo, os provedores de nuvem fornecem aplicativos de software hospedados na nuvem que os usuários podem acessar através da internet. Os usuários não precisam se preocupar com o gerenciamento de servidores, atualizações de software ou manutenção, pois tudo é tratado pelo provedor.


![image](https://github.com/TatianaFlorentino/computacaonuvem/assets/41309689/eced21c2-f754-4ed6-83bd-4b834ca0c458)

Com um datacenter local, você é responsável por tudo. Com a computação em nuvem, essas responsabilidades mudam. O modelo de responsabilidade compartilhada está fortemente vinculado aos tipos de serviço de nuvem (abordados posteriormente neste roteiro de aprendizagem): IaaS (infraestrutura como serviço), PaaS (plataforma como serviço) e SaaS (software como serviço). A IaaS coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade. Na outra ponta do espectro, o SaaS coloca a maior parte da responsabilidade no provedor de nuvem. A PaaS, sendo um meio termo entre IaaS e SaaS, situa-se no meio desses dois cenários e distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

![image](https://github.com/TatianaFlorentino/computacaonuvem/assets/41309689/8c169053-ecad-477c-b5c4-9548de044527)


## Escalabilidade
Outro grande benefício da computação em nuvem é a escalabilidade dos recursos de nuvem. A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

A escala geralmente vem em duas variedades: vertical e horizontal. A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos. A escala horizontal é adição ou subtração do número de recursos.

Dimensionamento vertical
Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. Por outro lado, se você percebesse que superestimou as necessidades, poderia reduzir verticalmente, diminuindo as especificações de CPU ou RAM.

Dimensionamento horizontal
Com a escala horizontal, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

## Cenários
Alguns cenários comuns em que o **PaaS** faz sentido incluem:

Estrutura de desenvolvimento: O PaaS fornece uma estrutura que os desenvolvedores podem usar como base para desenvolver ou personalizar aplicativos baseados em nuvem. Semelhante à forma como você cria uma macro do Excel, o PaaS permite aos desenvolvedores criar aplicativos usando componentes de software internos. São incluídos recursos de nuvem, como escalabilidade, alta disponibilidade e a funcionalidade de multilocatário, reduzindo a quantidade de codificação que os desenvolvedores precisam realizar.
Análise ou business intelligence: as ferramentas fornecidas como serviço com o PaaS permitem que as organizações analisem e minerem dados, encontrando insights e padrões e prevendo resultados para aprimorar a previsão, as decisões de design de produto, o retornos sobre investimentos e outras decisões de negócios.

____________________________________________________________________________________________________________________________________________________________________________________________________________________

O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto. Com o **SaaS**, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Email, software financeiro, aplicativos de mensagens e software de conectividade são exemplos comuns de uma implementação de SaaS.

Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.


## Referências : 

[Treinamento Microsoft](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/5-define-cloud-models)


Um modelo baseado em consumo oferece vários benefícios, como:

* Sem custos prévios.
* Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
* A capacidade de pagar para obter mais recursos quando necessário.
* A capacidade de parar de pagar por recursos que não são mais necessários.


Palavras-Chaves: # PaaS  #Nuvem #Azure #GCP #AWS #SAAS #PaaS #VMware
