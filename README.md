# resumo-cloud-lab
Este repositório contém o resumo do conteúdo aprendido e anotado durante o desenvolvimento do lab na DIO

## O que é computação em nuvem?
Computação em nuvem é um modelo de negócio que entrega serviços de computação como servidores, armazenamento, banco de dados, redes, software e entre outros serviços pela internet, com acesso sob demanda e pagamento conforme o uso.

## Como funciona?
Em vez de comprar, instalar e manter servidores físicos ou infraestrutura local (modelo chamado on-premice), você acessa recursos computacionais remotamente, fornecidos por provedores como:

- **Amazon Web Services (AWS)**
- **Microsoft Azure**
- **Google Cloud Platform (GCP)**

Esses provedores operam data centers ao redor do mundo que hospedam os serviços e recursos.

Você pode também operar com uma infraestrutura no modelo on-premice juntamente com o modelo cloud. Isso é chamado modelo de nubem híbrida e geralmente são utilizadas por empresas que tem uma demanda sazonal, ou seja, há uma época específica do ano que essa empresa tem uma demanda maior do que o habitual, então ela contrata um serviço de nuvem apenas para suprir essa demanda.

## Regiões e Zonas
Uma região é a localização geográfica do mundo onde o provedor de nuvem mantém vários data centers. Isso permite que os recursos estejam mais próximos dos usuários, diminuindo a latência e melhorando a experiência de uso. Um provedor pode ter **São Paulo, Brasil** na sua lista de regiões por exemplo.

Dentro de cada região, existem duas ou mais zonas que fornecem alta disponibilidade, ou seja, se uma zona falhar por N motivos, as outras continuam funcionando e o usuário ainda consegue acessar os serviços. Um provedor pode ter sp1, sp2, sp3 em sua lista de zonas por exemplo.

## Serviços de Computação do Azure
A computação do Azure fornece recursos sob demanda como processadores, memória, rede e sistemas operacionais. Entre os principais serviços, destacam-se:

#### Máquinas Virtuais do Azure (VMs)
- Serviço de IaaS que emula computadores físicos, oferecendo controle total sobre processador, memória, armazenamento e rede.

#### Azure Functions
- Serviço baseado em eventos, que executa código sob demanda, otimizando recursos durante a inatividade.

#### Serviços de Aplicativo
- Plataforma PaaS para criar e escalar aplicações web e APIs com suporte a diversas linguagens (.NET, Java, Node.js etc.).

