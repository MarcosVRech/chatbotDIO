PROJETO DIO DE CHATBOT FEITO NO AZURE

O projeto consistiu em um chatbot simples com leitura de PDF, feito no sistema Azure através do AI Foundry.

Primeiramente configurei o Modelo base, selecionei o GPT-4o, junto com o text-embedding-3-large. 
![5](https://github.com/user-attachments/assets/d2e40d74-b06b-4e56-ab76-bcc01fbd1cdb)

A descrição geral ficou da seguinte maneira:
![6](https://github.com/user-attachments/assets/26d0654e-5cba-4734-8a2c-2728d6a67c7f)


Logo após, fiz a configuração do index, e adicionei três arquivos PDFs, sobre [Metodologias Àgeis](https://periodicos.ufca.edu.br/ojs/index.php/cienciasustentabilidade/article/download/314/308/), [Engenharia de Requisitos](https://www.maxwell.vrac.puc-rio.br/6954/6954_3.PDF) e [Arquitetura de Software
](https://repositorio.pucgoias.edu.br/jspui/bitstream/123456789/6996/1/LiandraOliveira_final_2023_.pdf). 

Em seguida fiz as seguintes perguntas e obtive as respostas:


1-Qual a importância da engenharia de requisitos?

A engenharia de requisitos é fundamental para o desenvolvimento de sistemas, pois ajuda a sistematizar o processo de definição de requisitos, garantindo que o software atenda às necessidades dos usuários e seja inserido no universo de informações ao qual ele pertence 1 . Segundo [Leite 94], a engenharia de requisitos busca otimizar a criação de sistemas com maior qualidade, dentro de custos compatíveis, ao mesmo tempo em que reduz os problemas associados à definição e evolução dos requisitos durante o desenvolvimento 2 .
Além disso, ela desempenha um papel crucial na identificação dos problemas a serem resolvidos e nos serviços que o sistema deve prestar, considerando restrições tecnológicas, sociais, políticas e culturais 3 . A falta de atenção dedicada à engenharia de requisitos pode levar a falhas em grandes projetos, devido à definição incorreta ou incompleta dos requisitos 3 .


2-O que são metodologias ágeis?

As metodologias ágeis são práticas e métodos de desenvolvimento de software que surgiram como uma alternativa às metodologias tradicionais, como o modelo em cascata. Elas têm como objetivo principal tornar o desenvolvimento de software mais rápido, com custo controlado e qualidade aprimorada 1 .
Essas metodologias são baseadas em ciclos iterativos de desenvolvimento, permitindo a adaptação dos requisitos ao longo do processo, mesmo após o início do desenvolvimento. Diferentemente das metodologias tradicionais, que tentam prever todos os detalhes do projeto no início, as metodologias ágeis são adaptativas, aceitando e se preparando para mudanças 1 .
Além disso, elas são orientadas a pessoas, priorizando a interação entre os membros da equipe e o funcionamento do software, em vez de seguir rigidamente processos pré-determinados. O papel do processo, nesse contexto, é dar suporte ao trabalho da equipe de desenvolvimento 1 .


3-O que é arquitetura de softwares?

A arquitetura de softwares é o estudo da organização global de sistemas de software, incluindo o relacionamento entre subsistemas e componentes. Ela se tornou um fator crucial no projeto de sistemas de grande porte 1 . Inicialmente, essa área não despertava interesse até o final da década de 1980, quando Mary Shaw destacou a importância de considerar o nível organizacional ou arquitetural dos sistemas 1 .
Com o crescimento dos sistemas de software em escala e complexidade, surgiu a necessidade de empregar técnicas para conectar módulos, gerenciar configurações e versões, além de considerar fatores como desempenho e qualidade. Nesse contexto, a arquitetura de software passou a lidar com sistemas grandes e complexos 1 . Ela possibilita reconhecer estruturas comuns, entender arquiteturas existentes para decisões de projeto, e fornecer descrições para análise e desenvolvimento de novos sistemas 1 .

O resultado foi satisfatório, fez o que era esperado, porém, ao fazer o teste de aplicativo WEB o sistema me informou que não era possível realizar a escolha de um local, e por este problema eu não consegui realizar o teste Web.
Este erro possivelmente aconteceu porque eu coloquei a localização do meu único container  em um local diferente de onde eu havia selecionado o local do ChatBot. 
