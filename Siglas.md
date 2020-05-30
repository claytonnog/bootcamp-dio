# Siglas:

## SOAP & REST
**SOAP** é um protocolo de transferência de mensagens em formato XML para uso em ambientes distribuídos. O padrão SOAP funciona como um tipo de framework que permite a interoperabilidade entre diversas plataformas com mensagens personalizadas.

Aplicando este padrão em Web Services, geralmente usa-se o WSDL para descrever a estrutura das mensagens SOAP e as ações possíveis em um endpoint.

Uma das maiores vantagens disso é que várias linguagens e ferramentas conseguem ler e gerar mensagens facilmente. Várias linguagens de programação permitem a geração de objetos de domínio, Stubs e Skeletons a partir da definição do WSDL, permitindo a comunicação remota via RPC através de chamadas a métodos remotos, inclusive com argumentos complexos, como se fossem chamadas locais.

O problema desse padrão, é que ele adiciona um overhead considerável, tanto por ser em XML quanto por adicionar muitas tags de meta-informação. Além disso, a serialização e desserialização das mensagens pode consumir um tempo considerável.

**REST** é outro um protocolo de comunicação, baseado no protocolo de hipermídia HTTP. Porém ele não impõe restrições ao formato da mensagem, apenas no comportamento dos componentes envolvidos.

A maior vantagem do protocolo REST é sua flexibilidade. O desenvolvedor pode optar pelo formato mais adequado para as mensagens do sistema de acordo com sua necessidade específica. Os formatos mais comuns são JSON, XML e texto puro, mas em teoria qualquer formato pode ser usado.

Isso nos leva a outra vantagem: quase sempre Web Services que usam REST são mais "leves" e, portanto, mais rápidos.

O problema com o REST pode surgir justamente por causa de suas vantagens. Como a definição do corpo de dados fica totalmente a cargo do desenvolvedor, os problemas de interoperabilidade são mais comuns.

FONTE: https://pt.stackoverflow.com/questions/11183/quais-as-principais-diferen%C3%A7as-entre-soap-rest

## API
**API** é um conjunto de rotinas e padrões de programação para acesso a um aplicativo de software ou plataforma baseado na Web. A sigla API refere-se ao termo em inglês "Application Programming Interface" que significa em tradução para o português "Interface de Programação de Aplicativos".

FONTE: https://canaltech.com.br/software/o-que-e-api/

## WSDL & RPC
**WSDL** é um a descrição em formato XML de um Web Service que utilizará SOAP / RPC como protocolo. É o acrônimo de Web Services Description Language (Linguagem de Descrição de Serviços Web).

**RPC** — Remote Procedure Calls (em português, chamada de procedimentos remotos) é um modelo que define a forma como são realizadas as chamadas a operações remotas através de web services.

FONTE: https://medium.com/@alexjosesilva/introdu%C3%A7%C3%A3o-ao-wsdl-abece3a8bab5

## XSD
**Arquivos XSD** (XML Schema Definition) são usados para descrever o “formato/padrão” que um arquivo XML deve seguir, ou seja, ele tem que indicar quais nodes (<node1><subnode1/></node1>) ele pode conter, quais subnodes e atributos esses nodes podem ter, e muito mais.

FONTE: http://virtualgroup.com.br/o-que-sao-os-arquivos-xsd/

## MQTT

https://www.gta.ufrj.br/ensino/eel878/redes1-2018-1/trabalhos-vf/mqtt/