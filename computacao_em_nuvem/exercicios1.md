# 📘 Exercícios Teóricos – Modelos de Serviço em Nuvem

---

## 🔹 Questão 1 – Conceitual

Explique o que são **modelos de serviço em computação em nuvem** e qual é o objetivo dessa classificação.

Na computação em nuvem, os modelos de serviço definem o que a empresa de nuvem entrega e o que o usuário precisa gerenciar.
exemplo 👇
🔧 Você gerencia:

Sistema operacional

Aplicações

Dados

🏢 O provedor cuida:

Hardware

Rede

Data center

📌 Exemplos:

AWS EC2

Google Compute Engine

Azure Virtual Machines

💡 É como alugar um computador virtual.

## 🔹 Questão 2 – IaaS

Defina o modelo **IaaS (Infrastructure as a Service)** e cite **duas responsabilidades do usuário** nesse modelo.

Gerenciar o sistema operacional (instalação, configuração e atualizações).

Instalar e manter as aplicações e os dados que rodam na infraestrutura.

## 🔹 Questão 3 – PaaS

No modelo **PaaS**, quais camadas são gerenciadas pelo provedor de nuvem e quais ficam sob responsabilidade do usuário?

🔹 Gerenciadas pelo provedor de nuvem:

Infraestrutura (servidores, armazenamento e rede)

Sistema operacional

Middleware e runtime da plataforma

🔹 Sob responsabilidade do usuário:

Código da aplicação

Dados da aplicação

Configurações da aplicação

## 🔹 Questão 4 – SaaS

Explique por que o **SaaS** é considerado o modelo com **menor nível de controle do usuário**, mas também o **mais fácil de usar**.

O SaaS (Software as a Service) é considerado o modelo com menor nível de controle do usuário porque toda a infraestrutura, plataforma, sistema operacional e o próprio software são totalmente gerenciados pelo provedor de nuvem. O usuário não pode alterar configurações internas do sistema, nem controlar atualizações ou a forma como o software é executado.

Ao mesmo tempo, ele é o mais fácil de usar justamente por isso: o usuário não precisa instalar, configurar ou manter nada. Basta acessar o software pela internet e utilizá-lo. Assim, o SaaS reduz a complexidade técnica, o tempo de implantação e a necessidade de conhecimento especializado, tornando o uso rápido e simples.

## 🔹 Questão 5 – Associação

Associe corretamente os modelos de serviço às descrições:

( a ) Permite ao usuário apenas utilizar o software via navegador.
( b ) Oferece infraestrutura virtualizada como servidores e redes.
( c ) Fornece uma plataforma pronta para desenvolvimento de aplicações.

a) IaaS
b) PaaS
c) SaaS

---

## 🔹 Questão 6 – Responsabilidade Compartilhada

Explique o conceito de **responsabilidade compartilhada** na computação em nuvem, citando um exemplo prático.

Em uma máquina virtual na AWS, o provedor garante que os servidores físicos, a rede e o data center estejam seguros. Já o usuário é responsável por configurar o sistema operacional, aplicar atualizações, definir regras de firewall e proteger os dados armazenados.

## 🔹 Questão 7 – Comparação

Compare **IaaS, PaaS e SaaS** quanto ao **nível de controle**, **complexidade de uso** e **perfil do usuário**.

Aqui vai a comparação clara e organizada entre IaaS, PaaS e SaaS, focando em nível de controle, complexidade de uso e perfil do usuário:

Modelo	Nível de controle	Complexidade de uso	Perfil do usuário
IaaS	Alto – o usuário controla SO, aplicações e dados	Alta – exige conhecimento técnico e administração	Administradores de sistemas, equipes de TI, empresas que precisam de flexibilidade
PaaS	Médio – controle sobre código e dados, não sobre infraestrutura	Média – simplifica o ambiente de desenvolvimento	Desenvolvedores e equipes de software
SaaS	Baixo – quase nenhum controle sobre o sistema	Baixa – u

## 🔹 Questão 8 – Verdadeiro ou Falso

Analise as afirmativas:

( v ) No modelo SaaS, o usuário é responsável por atualizações do sistema.
( v ) O modelo IaaS oferece maior flexibilidade que o SaaS.
( f ) No modelo PaaS, o desenvolvedor não precisa se preocupar com o sistema operacional.

---

## 🔹 Questão 9 – Situação-problema

Uma empresa deseja apenas utilizar um sistema de e-mail corporativo, sem se preocupar com instalação, manutenção ou servidores.

a) Qual modelo de serviço em nuvem é o mais adequado?
 Modelo de serviço mais adequado:
SaaS (Software as a Service).
b) Justifique sua resposta.
 Justificativa:
O modelo SaaS é o mais adequado porque oferece o software pronto para uso, acessado pela internet, sem que a empresa precise se preocupar com instalação, manutenção, atualizações ou gerenciamento de servidores. Toda a infraestrutura e o funcionamento do sistema de e-mail são responsabilidade do provedor de nuvem, permitindo que a empresa foque apenas no uso do serviço.


## 🔹 Questão 10 – Dissertativa

Explique por que o modelo **PaaS** é considerado ideal para equipes de desenvolvimento de software.

O modelo **PaaS (Platform as a Service)** é considerado ideal para equipes de desenvolvimento de software porque oferece uma **plataforma completa e pronta** para criar, testar e implantar aplicações, sem a necessidade de gerenciar infraestrutura ou sistema operacional. Nesse modelo, o provedor de nuvem cuida de servidores, rede, armazenamento, sistema operacional e ambiente de execução, enquanto a equipe de desenvolvimento foca exclusivamente no **código, na lógica da aplicação e nos dados**.

Isso aumenta a produtividade, reduz a complexidade técnica e acelera o ciclo de desenvolvimento, além de facilitar a escalabilidade e a padronização dos ambientes. Dessa forma, o PaaS permite que as equipes se concentrem na inovação e na entrega de software, em vez de tarefas de manutenção de infraestrutura.

