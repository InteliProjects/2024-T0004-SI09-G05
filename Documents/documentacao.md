_

_
_

_

_


_
_

_

_


_
_

_

_


_
_

_

_


_
_

_

_


_
_

_

_


_

_


_
_

_

_


_
_

_

_


_
_

_

_


_


# Documentação Projeto



## INSTITUTO DE TECNOLOGIA E LIDERANÇA – INTELI



### DASHBOARD de Saúde Mental 

#### Parceiro de projeto: Volkswagen


#### Autores: 

Gabriela de Morais da Silva

Gustavo Monteiro

Larissa Gouveia de Carvalho

Matheus Fidelis dos Santos Pinto

Rodrigo Moraes Martins



#### Data de criação: 10 de Abril de 2024


#### SÃO PAULO – SP, 2024

**Controle do Documento**

Histórico de revisões

| Data | Autor | Versão | Resumo da Atividade |
| --- | --- | --- | --- |
| 09/02/2024 | Larissa Carvalho | 1.0 | Criação do Documento |
| 09/02/2024 | Larissa Carvalho | 1.1 | 4.1 Canvas Proposta de Valor |
| 14/02/2024 | Gabriela de Morais da Silva | 1.2 | 7. Funcionalidades Wireframe |
| 14/02/2024 | Larissa Carvalho | 1.3 | 7. Funcionalidades Wireframe |
| 15/02/2024 | Rodrigo Martins | 1.4 | 6. Arquitetura do Sistema |
| 15/02/2024 | Matheus Fidelis | 1.5 | 5.1 Personas |
| 15/02/2024 | Larissa Carvalho | 1.6 | 6. Arquitetura do Sistema |
| 15/02/2024 | Gustavo Monteiro | 1.7 | 4.2 Matriz de Risco |
| 01/03/2024 | Larissa Carvalho | 1.8 | 7.1 Mockcups Avançados  |
| 03/03/2024 | Larissa Carvalho | 1.9 | 7.1 Mockcups Avançados  |
| 16/03/2024 | Gustavo Monteiro | 2.0 | 9. Análise Heurística |
| 17/03/2024 | Matheus Fidelis e Rodrigo Martins | 2.1 | 11. API de Integração |
| 18/03/2024 | Gabriela de Morais da Silva | 2.2 | 4.2 Matriz de Risco |
| 31/03/2024 | Gustavo Monteiro | 2.3 | 12 Teste de Usabilidade Presencial Moderado |

_

_

_


_


_

_


_

## Sumário

Índice de figuras

Índice de tabelas

1. Introdução
2. Problema
3. Objetivos
4. Análise de Negócios
    
    4.1 Canvas Proposta de Valor
    
    4.2 Matriz de Risco
    
    4.3 Análise Pestel
    
    4.4 TAM SAM SOM

    4.5 Análise PESTEL

    4.6 Análise Financeira: Investimento Estratégico para o Futuro
   
    
6. Análise de Experiência do Usuário
    
    5.1 Personas
    
    5.2 Jornadas do Usuário
    
    5.3 User Stories
    
7. Arquitetura do Sistema

    7.1 Mockups Avançados 
    
    6.1 Arquitetura UML
    
8. Esboços e Wireframes de Dashboards

9. API de Integração

10. Análise Heurística do Dashboard Plantas
   9.1 Tabelas de Análise Heurística
   9.2 Conclusão da Análise

11. Dashboard

12. API de Integração

13. Teste de Usabilidade Presencial Moderado

14. Documentação Técnica
    13.1 Dashboard
    13.2 API

15. Plano de Comunicação

16. Referências


## <a name="c1"></a>1. Introdução
&emsp;&emsp;Este documento descreve o projeto para a criação de um Dashboard de Saúde Mental vs Indicadores de Engajamento, desenvolvido para a Volkswagen do Brasil Indústria de Veículos Automotores LTDA. O projeto visa fornecer uma solução personalizada para a análise de dados relacionados à saúde mental dos colaboradores e aos indicadores de engajamento em cada área da empresa. Por meio de uma abordagem analítica, o dashboard permitirá uma visualização intuitiva e significativa dos dados, fornecendo insights valiosos para apoiar a tomada de decisões estratégicas.

## <a name="c2"></a>2. Problema
&emsp;&emsp;Atualmente, a Volkswagen do Brasil enfrenta desafios relacionados à dispersão de informações em várias fontes e sistemas. A falta de integração e análise eficiente desses dados resulta em ineficiências operacionais, dificuldades na tomada de decisões e potenciais riscos associados à falta de visibilidade sobre a saúde mental dos colaboradores e ao nível de engajamento em cada área da empresa. A ausência de uma plataforma unificada para acessar e interpretar esses dados impede a identificação de tendências, padrões e insights valiosos que poderiam orientar estratégias organizacionais mais eficazes e centradas nas pessoas.

## <a name="c3"></a>3. Objetivos
&emsp;&emsp;O objetivo principal deste projeto é desenvolver um dashboard personalizado que atenda às necessidades específicas da Volkswagen do Brasil após uma análise detalhada dos dados disponíveis. Este dashboard analítico será construído para permitir uma visualização intuitiva e significativa dos dados relacionados à saúde mental dos colaboradores e aos indicadores de engajamento em cada área da empresa. Para alcançar esse objetivo, o projeto irá implementar uma API desenvolvida na plataforma .NET Core para coletar e tratar os dados, garantindo sua preparação para análise estatística. <br>
&emsp;&emsp;Além disso, será desenvolvido um painel de controle utilizando Angular e TypeScript, que permitirá aos usuários acessar e analisar os dados de forma eficaz e rápida. A análise estatística dos dados será importante para identificar padrões, tendências e correlações nos dados corporativos, fornecendo insights valiosos para a tomada de decisões estratégicas na Volkswagen do Brasil. <br>
&emsp;&emsp;Outro objetivo importante é fornecer à empresa ferramentas que possibilitem a avaliação do desempenho e o monitoramento periódico de indicadores chave (KPIs), auxiliando na identificação de áreas que requerem atenção e ação corretiva. O projeto será implementado de maneira iterativa, garantindo a integração eficaz e o correto funcionamento de cada componente, bem como a escalabilidade e o desempenho necessários para lidar com volumes significativos de dados. <br>
&emsp;&emsp;Ao alcançar esses objetivos, o projeto contribuirá significativamente para fortalecer a capacidade da Volkswagen do Brasil de tomar decisões informadas, otimizar operações e permanecer competitiva no mercado, com foco em análises analíticas em vez de análises em tempo real. <br>

## <a name="c4"></a>4. Análise de Negócios
A aplicação de ferramentas de negócio é importante para o sucesso e a sustentabilidade das organizações em um ambiente competitivo.

Uma ferramenta comumente utilizada no mundo dos negócios oferece análises abrangentes do mercado e ambiente empresarial, considerando fatores internos e externos, como oportunidades, ameaças, viabilidade de mercado, segmentação, público-alvo, e elementos

### <a name="c5"></a>4.1 Canvas Proposta de Valor
&emsp;&emsp;O Canvas Proposta de Valor é uma ferramenta de gestão estratégica que auxilia na criação e desenvolvimento de novos produtos, serviços e negócios. Essa ferramenta é dividida em dois blocos: o perfil do cliente e a proposta de valor. <br>
&emsp;&emsp;No bloco de proposta de valor, é necessário definir qual é o produto desenvolvido, quais são os principais criadores de ganho que o cliente tem ao adquirir o produto e quais são os aliviadores de dores que o cliente terá.  Já no perfil do cliente, deve-se identificar quais são as tarefas que ele irá realizar, quais são os principais ganhos e dores do atual processo. <br>
&emsp;&emsp;Abaixo segue o Canvas Proposta de Valor completo: <br>

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Canvas_Proposta_de_Valor.jpg">
</div>


Figura 01: Canvas Proposta de Valor

**4.1.1 Perfil do Cliente**

&emsp;&emsp;O cliente é uma empresa que busca otimizar sua gestão de informações e avaliação de desempenho, visando melhorar a eficiência operacional e promover o crescimento sustentável. Um dos desafios da Volkswagen é a dispersão de dados em várias fontes e sistemas, a dificuldade de integração e interpretação dessas informações, e a necessidade de monitorar aspectos cruciais da saúde mental dos colaboradores. <br>
&emsp;&emsp;Sendo assim, o cliente busca soluções que permitam uma análise mais abrangente e eficaz do seu cenário corporativo. <br>

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Perfil_do_Cliente.png">
</div>
Figura 02: Perfil do Cliente

- **Tarefas do Cliente**
    - **Gerenciar informações dispersas em várias fontes e sistemas:**  o cliente precisa lidar com dados provenientes de diversas fontes e sistemas, o que dificulta a integração e análise unificada dessas informações.
    - **Avaliar o desempenho da empresa e identificar áreas que requerem atenção:** é necessário avaliar o desempenho dos colaboradores da empresa e identificar áreas específicas que necessitam de melhorias ou ajustes para impulsionar o crescimento.
    - **Avaliar a saúde mental dos colaboradores:** além dos aspectos operacionais, o cliente reconhece a importância de monitorar a saúde mental dos colaboradores para promover um ambiente de trabalho saudável e produtivo.
    - **Monitorar indicadores de engajamento em cada área:** acompanhamento do engajamento dos colaboradores em cada área da empresa para identificar pontos fortes e oportunidades de desenvolvimento.

- **Dores**
    - **Falta de integração entre os dados:** a falta de integração dificulta uma visão unificada e coerente do panorama corporativo.
    - **Informações dispersas nas planilhas:** as informações relevantes estão dispersas em várias planilhas, o que torna o acesso e a análise mais complexos e demorados.
    - **Uso de dados brutos para geração manual de gráficos:** a geração manual de gráficos a partir de dados brutos demanda tempo e esforço, além de aumentar a possibilidade de erros.
    - **Aumento de absenteísmo dos colaboradores:** o aumento do absenteísmo indica possíveis problemas no ambiente de trabalho que precisam ser identificados e abordados.
    - **Dificuldade de acessibilidade e leitura das informações dispersas em planilhas:** a dispersão de informações em planilhas dificulta a acessibilidade e a leitura eficiente dos dados.
    - **Dados de diretorias diferentes separados de forma manual:** a separação manual de dados provenientes de diferentes diretorias dificulta a análise comparativa e a identificação de padrões corporativos.

- **Ganhos**
    - **Descoberta de insights para impulsionar a eficiência operacional e crescimento:** uma análise mais abrangente e integrada dos dados pode revelar insights valiosos para impulsionar a eficiência operacional e promover o crescimento da empresa.
    - **Identificação de padrões e tendências corporativas:** a análise de padrões e tendências permite uma compreensão mais profunda do ambiente corporativo, facilitando a tomada de decisões estratégicas.
    - **Dados disponibilizados de forma inteligível:** a disponibilização de dados de forma inteligível facilita a interpretação e análise por parte dos gestores e demais stakeholders da empresa.
    - **Propor ações para reduzir absenteísmo:** a análise dos dados pode auxiliar na identificação de causas subjacentes ao aumento do absenteísmo, permitindo a proposição de ações corretivas eficazes.
    - **Uso de dados para embasar ações na empresa:** a utilização de dados como base para a tomada de decisões promove uma gestão mais assertiva e orientada por evidências.

**4.1.2 Proposta de Valor**

&emsp;&emsp;A proposta de valor se destina a empresas que buscam uma abordagem inovadora e eficaz para gerenciar informações corporativas e promover um ambiente de trabalho saudável e produtivo. Sendo assim, a solução é um Dashboard personalizado de saúde mental e indicadores de engajamento, oferecendo uma solução completa e integrada para a análise e monitoramento do desempenho organizacional. <br>
&emsp;&emsp;Com uma combinação de tecnologia avançada e uma interface intuitiva, é possível proporcionar insights e ferramentas poderosas para impulsionar a eficiência operacional, mitigar riscos e promover o crescimento sustentável dos colaboradores da Volkswagen.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Proposta_de_Valor.png">
</div>
Figura 03: Proposta de Valor

- **Produtos e Serviços**
    - Dashboard personalizado de saúde mental e indicadores de engajamento, fornecendo uma visão abrangente e intuitiva do cenário corporativo.
    - Utilização de uma API .NET Core para coletar dados de forma eficiente e integrada, garantindo uma análise completa e atualizada em tempo real.

- **Alívio das Dores**
    - **Centralização de dados na mesma plataforma:** dados em uma única plataforma, eliminando a dispersão e facilitando a análise integrada.
    - **Representação visual de setores que estão em atenção de acordo com indicadores:** visualização de forma clara e intuitiva sobre os setores que demandam atenção com base nos indicadores, permitindo uma abordagem proativa.
    - **Acessos dos gráficos separados por diretorias:** os acessos aos gráficos são separados por diretorias, facilitando a análise específica de cada área da empresa.
    - **Mitigação de riscos associados à falta de informações sobre a saúde mental dos colaboradores:** o Dashboard fornecerá insights sobre a saúde mental dos colaboradores, ajudando a mitigar riscos e promover um ambiente de trabalho saudável.
    - **Redução da necessidade de trabalho manual com dados brutos:** isso será possível por conta da automatização dos processos e assim, a empresa economizará tempo e recursos.
    - **Geração de relatórios a partir dos gráficos do dashboard:** os usuários podem gerar relatórios diretamente a partir dos gráficos do Dashboard, simplificando o processo de comunicação e compartilhamento de informações.

- **Criadores de Ganho**
    - **Possibilidade de gerar dados com cruzamento de variáveis distintas:** a plataforma permite a análise de dados com cruzamento de variáveis, oferecendo insights mais profundos e personalizados.
    - **Gráficos demonstrando o histórico dos indicadores de saúde mental dos colaboradores:** gráficos que exibem o histórico dos indicadores de saúde mental, permitindo uma análise mais profunda e identificação de tendências.
    - **Utilização de filtros para novas configurações de dados:**
    - Os usuários podem utilizar filtros para personalizar as configurações de dados, adaptando o Dashboard às suas necessidades específicas.
    - **Criação e atualização automática de gráficos:** os gráficos são criados e atualizados automaticamente, eliminando a necessidade de intervenção manual e garantindo dados sempre atualizados.
    - **Acesso via web e possibilitando acessos diários a dados críticos através do dashboard:** o acesso via web permite aos usuários acessar o Dashboard de qualquer lugar, a qualquer momento, facilitando a tomada de decisões ágeis e informadas.
    - **Disponibilidade de informações indicadas nos gráficos:** as informações relevantes são indicadas nos gráficos, facilitando a interpretação e análise por parte dos usuários.

 Link para melhor acesso: https://miro.com/app/board/uXjVNv_uYXg=/
 
### <a name="c6"></a>4.2 Matriz de Risco
  
&emsp;&emsp;Diante a influência de diferentes variáveis, o desenvolvimento de um projeto fica suscetível a riscos internos e externos, necessitando ações para mitigar os impactos desses riscos (Rodrigues, 2019). Para isso, a elaboração de uma matriz de risco, indicando os riscos mapeados e o plano de ação para cada risco e um integrante responsável pode trazer mais segurança para o alcance dos objetivos definidos do projeto. 

Tabela 01: Matriz de Risco
| **${\color{purple}Porcentagem}$** 	| ${\color{blue}}$  | ${\color{blue}}$  | ${\color{red}Ameaças}$  	|  ${\color{greenyellow}}$  	|   ${\color{greenyellow}}$  	|   ${\color{greenyellow}}$  	|   ${\color{greenyellow}}$  	|   ${\color{blue}Oportunidades}$  	|   ${\color{greenyellow}}$  	|   ${\color{greenyellow}}$  	|
|---	|---	|---  |---  |---	|---	|---	|---	|---	|---	|---	|
| **${\color{purple}90}$** 	| **${\color{gold}-}$**| **${\color{gold}-}$**| **${\color{red}-}$**| **${\color{red}-}$**| **${\color{red}Ameaça 02}$**| **${\color{green}Oportunidade 01}$**| **${\color{green}-}$**| **${\color{green}-}$**| **${\color{gold}-}$**| **${\color{gold}-}$**|
| **${\color{purple}70}$** 	| **${\color{green}-}$**	| **${\color{gold}-}$**| **${\color{gold}Ameaça14}$**| **${\color{red}Ameaças12, 15}$**| **${\color{red}-}$**| **${\color{green}-}$**| **${\color{green}-}$**| **${\color{gold}-}$**| **${\color{gold}-}$**| **${\color{red}-}$**|
| **${\color{purple}50}$** 	| **${\color{green}-}$**	| **${\color{gold} Ameaça 17 }$**| **${\color{gold}Ameaça 03, 16}$**| **${\color{red}Ameaça 07}$**| **${\color{red}Ameaça 08}$**| **${\color{green}-}$**| **${\color{green}-}$**| **${\color{gold}-}$**| **${\color{gold}-}$**| **${\color{red}-}$**|
| **${\color{purple}30}$** 	| **${\color{green}Ameaça 09}$**	| **${\color{green}-}$**| **${\color{gold}Ameaça 04, 10}$**| **${\color{gold}Ameaça 05, 11}$**| **${\color{red}Ameaça 06}$**| **${\color{green}-}$**| **${\color{gold}-}$**| **${\color{gold}-}$**| **${\color{red}-}$**| **${\color{red}-}$**|
| **${\color{purple}10}$** 	| **${\color{green}-}$**	| **${\color{green}-}$**| **${\color{green}-}$**| **${\color{green}-}$**| **${\color{gold}Ameaça13}$**| **${\color{gold}-}$**| **${\color{red}-}$**| **${\color{red}-}$**| **${\color{red}-}$**| **${\color{red}-}$**|
| Impacto 	| Muito Baixo  | Baixo  | Moderado  	|  Alto  	|   Muito Alto  	|   Muito Alto  	|   Alto  	|   Moderado  	|   Baixo  	|   Muito Baixo  	|

| **${\color{blue}Número}$** 	| **${\color{blue}Oportunidades}$**  |       |       |       |
|---	|---	|---	|---	|---	|
| **01** 	| Contribuição para a Saúde Organizacional, melhorando o ambiente de trabalho e a produtividade. |        |       |       |
| **${\color{red}Número}$** 	|  **${\color{red}Riscos}$**    	| Descrição       | Responsável      |   Plano de ação    |
| **02** 	| Redução de tempo de desenvolvimento. | Devido a compromissos como estágio os desenvolvedores terão complicações para finalizar as atividades a tempo.       |   Gabriela    |  Fazer plannings bem estruturadas, indicar o andamento das atividades durante as dailys e principalmente caso tenha impedimento avisar o quanto antes para reorganizar o planejamento.     |
| **03** 	| Falta de experiência com novo framework e linguagem.	|   Os desenvolvedores podem não ter experiência suficiente para a construção do dashboard usando o framework e linguagem nova.     |   Gustavo    |  Reforçar que caso esteja tendo dificuldades avisar o grupo para ajudarmos e caso não seja solucionado entraremos em contato com professores ou outras equipes.     |
| **04** 	|  Dificuldade na integração e cruzamento dos dados. 	|  Por conta do grande número de pesquisas e dados não conseguirmos criar cruzamentos interessantes de dados por dificuldades técnicas.      |  Larissa     |  Realizar uma análise descritiva e preditiva das tabelas de pesquisa para criarmos hipóteses. Além disso validar constantemente com o cliente se concordam ou não com o cruzamento.     |
| **05** 	|  Pouca usabilidade da solução. 	| Desenvolvedores criarem uma interface pouco  interativa e adaptável ao cliente       |   Matheus    |  Estar sempre atento em atender as heurísticas de Nielsen. Além de validar com o professor de UX e com o cliente durante os encontros de 15 em 15 dias.     |
| **06** 	|  Falta de compreensão das dores e necessidades do cliente. 	| Dificuldade em agregar valor ao produto por dificuldades em entender as necessidades dos clientes       |  Rodrigo     |   Sempre revisar os documentos base  como canva de proposta de valor e persona. Além disso estar atento para os feedbacks do cliente durante os encontros.    |
| **07** 	|  Falhas na comunicação da equipe. 	| Falta de avisos antecipando faltas ou  impedimentos       | Gabriela      | Reforçar a necessidade de comunicar principalmente os problemas para que sejam resolvidos o quanto antes. Além disso sempre que alguém terminar uma tarefa avisar para poder dar continuidade a outras tasks.      |
| **08** 	|   Sobrecarga de tarefas sobre membros da equipe.	|  Desequilíbrio na separação das tarefas      | Gustavo      |  Realizar Grooming uma vez na sprint para que estejamos de acordo com o que cada integrante está responsável e mitigar a sobrecarga de atividades para integrantes.     |
| **09** 	|  Conversas paralelas. 	|  Conversas paralelas com membros de outras equipes prejudicar o pouco tempo que há de desenvolvimento      |   Larissa    |  Chamar a atenção dos integrantes caso ocorra e caso mantenha falar com o orientador.     |
| **10** 	| Não contemplar o nível de segurança e acessos na solução desenvolvida.  	| Dificuldade em manter segurança no sistema e falta de entendimento  do organograma do cliente e criar acessos fora da realidade dos times.       |   Matheus    |  Estar atento aos estudos de segurança da informação e estudar organograma dos times do cliente     |
| **11** 	|  Valor de desenvolvimento do projeto ultrapassar o valor de retorno do investimento. 	|    O custo elevado e a falta de escalabilidade da arquitetura da solução não entregar um ROI satisfatório    |   Rodrigo    |   Constantemente explorar novas formas e tecnologias que sejam mais escaláveis e econômicas    |
| **12** 	|  Erros por versionamento diferentes dos pacotes de Visual Studio e Angular. 	|    Com o versionamento  diferente, entre máquinas, de pacotes necessários para o desenvolvimento do projeto podem surgir erros  nos frameworks, criando impedimentos para o projeto.    |   Gabriela    |   Conferir os componentes utilizados para o desenvolvimento de etapas do projeto e atualizar as ferramentas para versões mais recentes.     |
| **13** 	|  Falta de adesão em padrões de interoperabilidade dos dados. 	|    Falta de padronização e na aplicação de protocolos, afetando a natureza dos dados durante o compartilhamento dos mesmos entre os componentes do sistema    |   Gustavo    |   Educar a equipe sobre os padrões relevantes e realizar revisões regulares.     |
| **14** 	|  Problema de compatibilidade entre os componentes do sistema. 	|    Durante a integração entre diferentes sistemas podem ocorrer erros que impeçam o funcionamento do sistema    |   Larissa    |   Realizar testes para identificar os pontos que necessitam atenção    |
| **15** | Divergências no planejamento sem aviso prévio | Durante o desenvolvimento da sprint, os membros da equipe não estão aderindo ao planejamento estabelecido e às mudanças acordadas com o orientador, resultando em retrabalho, aumento de tarefas pendentes e entregas de baixa qualidade. | Matheus | Caso esteja acontecendo continuar comunicando no slack a divergência de ideias e falar com o ourientador para que ele esteja ciente da situação. Além disso, os outros participantes devem continuar com o planejamento original ja alinhado com o orientador e o grupo anteriormente. |
| **16** | Pouco tempo para apresentar entregáveis da sprint. | Devido a imprevistos, o grupo se encontra com tempo reduzido para validar seus entregáveis com o cliente. Essa limitação de tempo dificulta  a dedicação necessária a certos aspectos secundários, que ainda assim são igualmente importantes. | Rodrigo | Antes da apresentação validar com o professor se os tópicos abordados são relevantes para os ouvintes e priorizar o que vamos apresentar. |
| **17** | Menos tempo de desenvolvimento por conta de feriados durante a sprint. | Devido a ocorrência de feriádos, o desenvolvimento fica comprometido, podendo diminuir a qualidade das entregas e prejudiacr a comunicação do time. | Gabriela | Fazer o acompanhamento das atividades e planejar contando com dias a menos. |

Link para melhor acesso: https://docs.google.com/spreadsheets/d/10-qtx7T5Yksek21xpOtHjLZ-XvU9VvKJkcevXV9tF6Y/edit#gid=0

### <a name="c7"></a>4.4. TAM/ SAM/ SOM

No ambiente empresarial atual, o bem-estar mental dos colaboradores é uma parte crítica do sucesso organizacional. Ao monitorar de forma eficaz a saúde mental dos funcionários não só contribui com um ambiente de trabalho saudável, mas também ajuda significativamente para a produtividade, a satisfação no trabalho e a retenção de talentos.

Nesta análise a seguir, é explorado o potencial de um dashboard projetado para monitorar a saúde mental dos colaboradores em uma organização. Utilizaremos o modelo TAM/SAM/SOM como estrutura para avaliar a viabilidade e o alcance desse produto no mercado.

O modelo TAM/SAM/SOM é uma ferramenta usada para entender o tamanho total do mercado (TAM), a parte desse mercado que podem atender (SAM) e a parcela que realmente conseguem capturar (SOM). Essa análise ajuda na identificação das oportunidades de crescimento e na definição de estratégias de negócios mais eficazes.



#### TAM - Total Addressable Market

Nota-se a crescente conscientização sobre a importância do suporte à saúde mental no ambiente profissional. Estudos globais indicam que o mercado de saúde mental corporativa está em crescimento desde a pandemia, com um TAM estimado em 200 bilhões de dólares. Isso abrange todas as empresas que têm interesse em promover a saúde mental e o bem-estar de seus colaboradores, independentemente do setor ou localização, visto que pesquisas apontam que o desgaste mental dos colaboradores levam a diminuição da produtividade e aumento da taxa de turnover, por exemplo. Por isso, empresas que lideram o movimento de conscientização são Google, Salesforce, Unilever, Patagonia e Microsoft, que têm implementado uma variedade de iniciativas e programas para apoiar a saúde mental de seus funcionários. Com a aplicação das iniciativas as organizações notaram que não apenas melhoram a qualidade de vida de seus colaboradores, mas também contribui para uma força de trabalho mais produtiva e engajada.

#### SAM - Serviceable Available Market

No contexto brasileiro, algumas empresas têm se destacado por suas iniciativas voltadas para a promoção da saúde mental de seus colaboradores. A partir de uma pesquisa nota-se que o mercado financeiro é o que mais investe nesse tema, mas outras empresas como por exemplo a Natura, oferece programas de apoio psicológico e emocional, além de promover práticas de mindfulness e meditação. Outra empresa é a Ambev, que implementou o programa "CARE", com treinamentos, conteúdos e revisão de processos. Eles também possuem embaixadores dos benefícios em saúde mental, que promovem autoconhecimento e suporte psicológico, psiquiátrico, social, financeiro e jurídico. Essas iniciativas demonstram o compromisso das empresas brasileiras em priorizar o bem-estar emocional de seus colaboradores, contribuindo para um ambiente de trabalho mais saudável e produtivo. Por fim, o SAM é estimado em 230 milhões de reais.

#### SOM - Serviceable Obtainable Market

Considerando a concorrência no mercado de soluções de saúde mental corporativa, juntamente com fatores geográficos e de penetração no mercado, o SOM pode ser estimado em uma porcentagem menor do SAM.

Em São Paulo, um exemplo de empresa com forte capacidade de comercialização de soluções de saúde mental corporativa é a Vittude. Sendo uma plataforma online, a Vittude oferece serviços de psicoterapia e programas de bem-estar emocional para empresas, possibilitando uma ampla penetração no mercado paulistano. Sua estratégia de marketing digital e parcerias estratégicas com grandes empresas locais demonstram sua habilidade em alcançar e engajar clientes em potencial.

A Conexa Saúde, também sediada em São Paulo, é um exemplo que se destaca por sua capacidade de atender às necessidades específicas do mercado corporativo. A empresa oferece uma variedade de serviços, como consultas virtuais com psicólogos e psiquiatras, programas de prevenção e gestão de estresse, e ferramentas de autoajuda personalizadas.

Se considerarmos o SAM de 230 milhões de reais e levando em conta a presença de competidores estabelecidos e a penetração potencial no mercado, poderíamos especular que uma nova empresa entrando neste espaço poderia visar capturar cerca de 10 a 15% do SAM em seus primeiros anos, dependendo de sua eficácia em marketing, a qualidade de suas soluções e a rapidez com que consegue estabelecer parcerias estratégicas.

Portanto, se tomarmos uma abordagem conservadora e mirarmos em 10% do SAM, nosso SOM seria de aproximadamente 23 milhões de reais. No entanto, se forem adotadas estratégias de mercado agressivas e inovadoras, e a empresa conseguir diferenciar seu produto no mercado, é possível que essa porcentagem possa ser mais alta, talvez chegando até 15%, o que elevaria o SOM para cerca de 34,5 milhões de reais.


### <a name="c8"></a>4.5. Análise PESTEL

Utilizada para entender o ambiente externo em que as empresas atuam, é uma análise sobre fatores que podem influenciar o desempenho, sendo divididos em seis categorias:

- Politico: Envolve as políticas governamentais, regulamentações comerciais, entre outros;
- Econômico: Aborda temas como taxas de crescimento econômico, taxas de câmbio, etc, que afetam a demanda de consumidores, custos de produção e as oportunidades de investimento;
- Socioeconômico: Avalia as tendências sociais e demográficas, como por exemplo nas mudanças de comportamento de consumidores, estilos de vida e valores culturais, que afetam o desenvolvimento de produtos e serviços.
- Tecnológico: Avanços em pesquisas, automação, inovações tecnológicas, entre outras, que podem fornecer uma vantagem competitiva e novos tipos de produtos.
- Ambiental: Impacto das questões ambientais nos negócios, como sustentabilidade, regulamentações ambientais, mudanças climáticas e conservação do meio ambiente.
- Legal: Aborda temas ligados a licenças comerciais, danos à reputação e leis de propriedade intelectual e segurança de produtos, e o impacto de ações judiciais à empresa.

Em relação aos tópicos acima, seguem os pontos levantados sobre o parceiro de projeto, Volkswagen: 


#### Político:
- Regulamentações: Além de estar sujeita a regulamentações e normas governamentais em relação à produção de veículos, após o escândalo de emissões de diesel em 2015, este se tornou um ponto que requer muita atenção.
- Políticas governamentais de incentivo ao setor automotivo: Mudanças nas políticas governamentais em relação a incentivos fiscais, tarifas de importação e exportação podem afetar a competitividade da Volkswagen nos mercados globais, considerando novas políticas de incentivo a carros elétricos.
- Regulamentações em Saúde Mental: A evolução das regulamentações relacionadas à saúde mental, como leis de proteção à saúde mental no ambiente de trabalho, podem impactar as políticas internas da empresa em relação ao bem-estar dos funcionários.
- Políticas de Saúde Mental: Mudanças nas políticas governamentais voltadas para a saúde mental podem influenciar os programas de apoio e prevenção adotados pela empresa em relação ao estresse e transtornos mentais no ambiente de trabalho.

Escândalos passados, além de afetar a reputação da empresa, instiga uma maior regulamentação pelo poder público e novas políticas de fiscalização ou até mesmo restrição, por parte de alguns países, afetando diretamente a empresa.

Medidas de Mitigação:

> Implementação de Políticas Internas: Desenvolver e implementar políticas internas claras e abrangentes relacionadas à saúde mental no trabalho, alinhadas com as regulamentações governamentais e as melhores práticas da indústria.

> Engajamento com Autoridades e Especialistas: Manter um diálogo contínuo com autoridades governamentais e especialistas em saúde mental para entender e adotar as melhores estratégias e práticas no ambiente de trabalho.

#### Econômico:
- Ciclos econômicos: A saúde econômica dos principais mercados onde a Volkswagen opera influencia diretamente a demanda por veículos.
- Taxas de câmbio: Flutuações nas taxas de câmbio podem afetar os custos de produção e os preços de venda, especialmente em mercados internacionais.
- Investimentos em Saúde Mental: A alocação de recursos financeiros para programas de saúde mental dentro da empresa pode ser afetada por fatores econômicos, como disponibilidade de verbas e prioridades de investimento em tempos de crise econômica.
- Custos Associados à Saúde Mental: Flutuações econômicas podem influenciar os custos relacionados ao tratamento e prevenção de problemas de saúde mental entre os funcionários, impactando os orçamentos destinados a essas iniciativas.

Os ciclos econômicos influenciam a demanda por veículos, enquanto as flutuações nas taxas de câmbio afetam os custos de produção, sendo refletidos no preço final dos produtos.

Medidas de Mitigação:

> Implementação de Políticas Internas: Desenvolver e implementar políticas internas claras e abrangentes relacionadas à saúde mental no trabalho, alinhadas com as regulamentações governamentais e as melhores práticas da indústria.

> Engajamento com Autoridades e Especialistas: Manter um diálogo contínuo com autoridades governamentais e especialistas em saúde mental para entender e adotar as melhores estratégias e práticas no ambiente de trabalho.

#### Socioeconômico:
- Preferências do consumidor: Mudanças nas preferências dos consumidores por veículos mais ecológicos, seguros e conectados impactam diretamente o desenvolvimento e a comercialização dos produtos da Volkswagen.
- Tendências demográficas: A demografia da população, como envelhecimento da população ou mudanças nas taxas de urbanização, pode afetar a demanda por diferentes tipos de veículos.
- Papel dos Sindicatos: A relação com sindicatos e organizações trabalhistas pode influenciar políticas internas relacionadas ao bem-estar e saúde mental dos funcionários, bem como questões trabalhistas e de ambiente de trabalho.
- Conscientização e Educação: Mudanças na conscientização e educação da sociedade em relação à saúde mental podem criar um ambiente mais receptivo para programas de apoio e prevenção dentro da empresa.
- Tendências Comportamentais: Alterações nas tendências comportamentais da população em relação ao estresse, equilíbrio trabalho-vida pessoal e busca por bem-estar podem influenciar as demandas e expectativas dos funcionários em relação à saúde mental.

 Medidas de Mitigação:
> Sensibilização e Treinamento: Promover campanhas de sensibilização e oferecer treinamentos regulares sobre saúde mental para todos os níveis da empresa, visando reduzir estigmas, aumentar a conscientização e capacitar gestores para lidar com questões relacionadas à saúde mental.

> Flexibilidade e Equilíbrio: Incentivar políticas de flexibilidade no trabalho, como horários flexíveis e opções de trabalho remoto, para promover um melhor equilíbrio entre vida pessoal e profissional.

> Diálogo com Sindicatos: Estabelecer um diálogo construtivo com sindicatos e organizações trabalhistas para entender suas preocupações e necessidades em relação à saúde mental dos trabalhadores e colaborar na implementação de medidas de apoio.

> Negociação Coletiva: Incluir cláusulas e acordos relacionados à saúde mental nas negociações coletivas com sindicatos, visando garantir políticas e práticas que promovam o bem-estar dos funcionários.

> Participação em Programas Sociais: Apoiar e participar de programas sociais e comunitários relacionados à saúde mental, em parceria com sindicatos e outras entidades, para ampliar o alcance e impacto das iniciativas de apoio psicológico e emocional.

As preferências dos consumidores por veículos ecológicos e conectados impactam o desenvolvimento e a comercialização dos produtos da Volkswagen. Mudanças demográficas também influenciam a demanda por diferentes tipos de veículos, e a presença forte de sindicatos no setor automotivo, principalmente de colaboradores de fábricas, indicam uma necessidade de maior atenção a esse tópico.

#### Tecnológico:
- Avanços em veículos autônomos e elétricos: A rápida evolução da tecnologia pode influenciar significativamente o desenvolvimento de novos produtos e a competitividade da Volkswagen.
- Inovações de fabricação: Novas tecnologias de fabricação podem melhorar a eficiência e reduzir os custos de produção.
- Plataformas Digitais de Saúde Mental: Avanços tecnológicos em plataformas de saúde mental, como aplicativos e ferramentas online, podem oferecer novas oportunidades para a empresa implementar programas de suporte remoto e acompanhamento psicológico.
- Tecnologias de Monitoramento: Desenvolvimentos em tecnologias de monitoramento de saúde, como sensores de bem-estar e análise de dados comportamentais, podem ser integrados para identificar padrões e sinais precoces de problemas de saúde mental entre os funcionários.

A rápida evolução tecnológica requer que a Volkswagen permaneça inovadora para manter a competitividade, especialmente em áreas como veículos autônomos e elétricos.

Medidas de Mitigação:
> Utilização de Tecnologias de Suporte: Implementar plataformas digitais de suporte à saúde mental, oferecendo recursos como consultas online, ferramentas de autocuidado e acompanhamento psicológico virtual.

> Análise de Dados para Identificação Precoce: Utilizar tecnologias de análise de dados para identificar padrões comportamentais entre os funcionários e identificar sinais precoces de estresse e esgotamento.

#### Ambiental:
- Sustentabilidade: A pressão por práticas mais sustentáveis está aumentando, o que pode impactar tanto as decisões de design e produção quanto a percepção do consumidor sobre a marca.
- Regulações ambientais: A Volkswagen está sujeita a regulamentações ambientais que podem afetar suas operações e exigir investimentos em tecnologias mais limpas.

Pressões por práticas sustentáveis e regulamentações ambientais podem exigir investimentos significativos em tecnologias mais limpas e práticas de produção sustentáveis.

Medidas de Mitigação:

> Transparência e Comunicação: Manter uma comunicação transparente com os stakeholders, incluindo os consumidores, sobre as iniciativas e compromissos da empresa em relação à sustentabilidade ambiental, promovendo uma imagem positiva da marca.

> Parcerias e Engajamento: Estabelecer parcerias estratégicas com organizações ambientais, governamentais e outras empresas do setor para compartilhar melhores práticas, colaborar em projetos ambientais e fortalecer ações coletivas em prol da preservação do meio ambiente.

#### Legal:
- Responsabilidade legal: A empresa enfrenta ações legais decorrentes de questões como o escândalo de emissões de diesel, exigindo gastos substanciais com multas e indenizações.
- Conformidade regulatória: A Volkswagen deve cumprir uma série de regulamentações locais e internacionais em relação à segurança, emissões e outros aspectos de seus produtos.
- Responsabilidade Legal em Saúde Mental: A empresa está sujeita a responsabilidades legais relacionadas à saúde mental dos funcionários, incluindo conformidade com leis de proteção à saúde mental no ambiente de trabalho e direitos dos trabalhadores em relação a licenças médicas e suporte psicológico.
- Conformidade Regulatória em Saúde Mental: A Volkswagen deve garantir a conformidade com regulamentações e normas relacionadas à saúde mental no local de trabalho, o que pode exigir políticas claras, treinamento adequado para gestores e disponibilidade de recursos para suporte emocional e psicológico dos funcionários.

 A empresa enfrenta custos substanciais decorrentes de ações judiciais e multas devido a questões legais, como o escândalo de emissões de diesel, destacando a importância da conformidade regulatória em suas operações.

 Medidas de Mitigação:
 > Conformidade e Transparência: Garantir total conformidade com as leis e regulamentações relacionadas à saúde mental, mantendo transparência nas políticas e práticas adotadas pela empresa.

 > Apoio Legal e Consultoria: Estabelecer parcerias com consultorias especializadas em saúde mental no ambiente de trabalho para garantir uma abordagem legalmente sólida e eficaz para lidar com questões relacionadas à saúde mental dos funcionários.

### <a name="c8"></a>4.6. Análise Financeira: Investimento Estratégico para o Futuro

O projeto de desenvolvimento do dashboard analítico para a Volkswagen do Brasil representa um investimento significativo, porém essencial para impulsionar a tomada de decisões estratégicas e mantê-la competitiva no mercado. Nossa equipe, formada por seis profissionais juniores com experiência prática na área de tecnologia, dedicou-se integralmente durante dois meses e meio para criar o Produto Mínimo Viável (MVP) dessa solução inovadora.

Para concretizar esse MVP, adotamos tecnologias de ponta, como Angular para o front-end e C# para o back-end, além de realizarmos o deploy na plataforma Render, reconhecida por sua eficiência, escalabilidade e excelente custo-benefício. Esse conjunto de recursos nos permitiu desenvolver uma solução robusta e adaptável, capaz de evoluir junto com as necessidades crescentes da Volkswagen.

O investimento financeiro nessa fase inicial foi criteriosamente planejado, levando em consideração os custos com recursos humanos e infraestrutura. O custo total dos salários dos seis desenvolvedores juniores, baseado na média salarial nos Estados Unidos, foi de aproximadamente US$ 89.130,00 (ou R$ 447.432,60, considerando a taxa de câmbio de 04/04/2024).

Além disso, optamos pela plataforma Render para hospedar nossa aplicação, que oferece recursos essenciais, como operação contínua, acesso remoto seguro, escalabilidade controlada e suporte para backups e recuperação de dados. O plano "Pro", escolhido por fornecer 4 GB de RAM e 2 CPUs, tem um custo mensal de US$ 95,00 (ou R$ 475,00), representando um investimento anual de US$ 468,00 (ou R$ 2.349,36) apenas para a infraestrutura de hospedagem.

No primeiro ano, o custo total do projeto, incluindo os salários dos desenvolvedores e a hospedagem por 9,5 meses adicionais, é estimado em US$ 89.598,00 (ou R$ 449.781,96). A partir do segundo ano, o custo anual será apenas o valor de hospedagem da infraestrutura, US$ 468,00 (ou R$ 2.349,36).

É importante ressaltar que essa análise financeira considera apenas os custos diretos com recursos humanos e infraestrutura de hospedagem. Custos adicionais, como licenças de software, treinamentos, despesas administrativas, atualizações e manutenção do sistema, não foram incluídos nesse cálculo inicial.

O investimento nesse projeto de dashboard representa um passo fundamental para a Volkswagen do Brasil, permitindo a integração de informações críticas e a geração de insights valiosos que nortearão as decisões estratégicas da empresa. Apesar do custo inicial substancial, os benefícios em termos de eficiência operacional, identificação de tendências e oportunidades de crescimento justificam plenamente esse investimento, que impulsionará a competitividade da Volkswagen no mercado altamente concorrencial em que atua.

## <a name="c9"></a>5. Análise de Experiência do Usuário
### 5.1 Personas

&emsp;&emsp;Personas são representações detalhadas e fictícias de usuários ideais que orientam o desenvolvimento de projetos e soluções. No contexto do nosso projeto atual na Volkswagen, que envolve o desenvolvimento de um dashboard de saúde mental vs indicadores de engajamento, identificamos duas personas principais: Paulo Andrade, o CEO visionário e inovador, e Helena Borges, a Vice-Presidente de Operações eficiente e focada no bem-estar dos colaboradores.

&emsp;&emsp;Essas personas são fundamentais para entender as necessidades e expectativas dos usuários finais da solução, oferecendo insights valiosos para a equipe de desenvolvimento. Além disso, as personas ajudam a equipe a visualizar os usuários finais do dashboard, definindo estratégias e recursos que atendam às suas necessidades específicas. Com base em suas dores e necessidades, como a fragmentação de dados e a necessidade de alinhar práticas de saúde mental com metas corporativas, podemos criar uma solução mais eficaz e alinhada com os objetivos da empresa.

### Persona 1: Paulo Andrade

- **Dores**: Desafios na tomada de decisões informadas devido à fragmentação de dados; pressão para manter o crescimento sustentável.
- **Necessidades**: Precisa de análises profundas sobre saúde mental e seu impacto nos resultados; integração de dados variados.
- **Nível de letramento digital**: Alto, com foco em estratégias baseadas em dados e inovação tecnológica.
- **Cenários de interação**: Reuniões executivas, planejamento estratégico, tomada de decisões baseada em dados.
- **Exemplos de uso e preferências**: Prefere dashboards intuitivos e análises detalhadas para direcionar decisões estratégicas.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Persona_2.png)

Figura 05: Persona 1

### Persona 2: Helena Borges

- **Dores**: coordenação de equipes com dados fragmentados; desafios em implementar práticas operacionais que promovam a saúde mental.
- **Necessidades**: ferramentas para integrar dados operacionais e de saúde mental; melhor comunicação entre departamentos.
- **Nível de letramento digital**: médio a alto, com foco em eficiência operacional e análise de dados.
- **Cenários de interação**: supervisão operacional, análise de desempenho de equipe, planejamento de recursos.
- **Exemplos de uso e preferências**: usa o sistema para otimizar processos operacionais, focando na eficiência e no bem-estar dos colaboradores.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Persona_1.png)

Figura 06: Persona 2

## <a name="c10"></a>6. Arquitetura do Sistema

Estrutura organizacional e aos princípios de design que guiam o desenvolvimento de um sistema de software. Isso inclui a divisão em módulos, a definição de interfaces e protocolos de comunicação, e a escolha das tecnologias adequadas para implementar as funcionalidades.
### 6.1 Arquitetura UML
Linguagem padronizada para modelagem de sistemas, amplamente utilizada na engenharia de software. Ela oferece uma variedade de diagramas, como diagramas de caso de uso, diagramas de classe, diagramas de sequência, entre outros, que permitem aos desenvolvedores representar visualmente a estrutura e o comportamento do sistema, bem como as interações entre seus componentes e usuários.

### 6.1.1 Caso de Uso

&emsp;&emsp;Um diagrama de caso de uso é uma ferramenta para a modelagem de sistemas, que fornece uma visão gráfica das funcionalidades do sistema e como os usuários interagem com ele. Através de símbolos e conectores, o diagrama ilustra os diferentes casos de uso, ou seja, as sequências de ações que os usuários executam para alcançar seus objetivos específicos.

&emsp;&emsp;A seguir a imagem do diagrama:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/assets/99209230/7f34ce79-ef24-4bde-a076-d0e09ff9ee6a)

Figura 07: Casos de Uso

1. **Ator Principal: CEO/VP RH**
    - Este ator representa os principais usuários que terão acesso à aplicação.
    
2. **Casos de Uso:**
    
   **Login:**
    
    - **Descrição:** permite ao CEO/VP realizar Login na plataforma
    - **Caso de uso incluído**: verificar senha, sempre que o CEO/VPexecutar o Login, ocorrerá uma verificação de senha.
    - **Caso de Uso Estendido**: exibir erro Login, caso a senha não exista no sistema, ocorrerá uma notificação de erro.
    
    **Funcionalidades do login**:
    
    - O funcionário acessa a página de login do sistema.
    - Ele insere seu nome de usuário (ou e-mail) e senha nos campos correspondentes.
    - Após inserir as credenciais, o funcionário clica no botão de "Login".
    - O sistema valida as credenciais fornecidas pelo funcionário.
    - Se as credenciais forem válidas, o funcionário é redirecionado para a página principal do sistema. Caso contrário, uma mensagem de erro é exibida.
    
    **Fluxos Alternativos:**
    
    1. **Autenticação inválida**:
        - Se as credenciais fornecidas durante o login forem inválidas, o sistema exibe uma mensagem de erro e solicita que o funcionário insira credenciais válidas.
    
    **Pré-condições:**
    
    - O funcionário deve ter credenciais válidas para acessar o sistema.
    - Os dados a serem consultados devem estar disponíveis no sistema.
    
    **Pós-condições:**
    
    - O funcionário obtém acesso aos dados detalhados conforme solicitado, permitindo visualizações sobre a saúde mental e os indicadores de engajamento da empresa.
    
    b. **Consultar Dados Gerais:**
    
    - **Descrição:** permite ao CEO/VP consultar dados gerais das plantas, Business Partners (BP) e engajamento de todos os colaboradores.
    
    **Funcionalidade de consultar dados gerais**:
    
    - Após o login bem-sucedido, o funcionário visualiza a página principal do sistema.
    - Ele navega para a seção de "Dashboard" no menu principal ou na interface do usuário.
    - O sistema carrega e exibe os dados gerais disponíveis para visualização.
    - O funcionário pode interagir com os dados gerais, como visualizar gráficos, tabelas ou relatórios relevantes.
    
    **Fluxo Principal**:
    
    1. **Acessar dados gerais**:
        - O CEO ou o VP acessa a plataforma que dá acesso a visualização de dados gerais do sistema.
    2. **Visualizar informações gerais**:
        - Após acessar a plataforma do dashboard, o funcionário pode visualizar as informações gerais disponíveis, como dados sobre a saúde mental dos colaboradores, principais causas de afastamento, porcentagem de , entre outras.
    
    **Pré-condições:**
    
    - O funcionário deve estar autenticado no sistema.
    - Os dados gerais devem estar disponíveis no sistema.
    
    **Pós-condições:**
    
    - O funcionário obtém acesso às informações gerais da empresa, permitindo uma compreensão global do desempenho e das operações.
    
    c. **Consultar Dados por Planta:**
    
    - **Descrição:** permite ao CEO/VP consultar dados específicos por planta.
    
    **Funcionalidade de consultar dados por planta**:
    
    - O funcionário pode consultar dados específicos relacionados a uma planta da empresa (se aquela planta estiver dentro da sua regra de acesso).
    - Ele navega para a seção de "Plantas" no menu principal.
    - A plataforma exibirá uma lista de plantas disponíveis para seleção.
    - O funcionário seleciona uma planta específica da lista.
    - O sistema carrega e exibe os dados relacionados à planta selecionada, como dados sobre a saúde mental dos colaboradores, incluindo:
        - total de colaboradores;
        - total de atestados referentes aquela planta;
        - gráfico sobre as causas das doenças;
        - entre outros dados relevantes.
    
    **Fluxo Principal:**
    
    1. **Selecionar planta**:
        - O funcionário seleciona a planta, a qual deseja visualizar os dados.
    2. **Acessar dados da planta**:
        - Após selecionar a planta, o funcionário acessa a funcionalidade de visualização de dados específicos da planta (se ele tiver permissão de acesso referente aquela planta).
    3. **Visualizar detalhes da planta**:
        - O funcionário pode visualizar as informações detalhadas da planta selecionada, incluindo número total de colaboradores, porcentagem de pessoas saudáveis e pessoas afastadas, gráfico sobre os motivos de afastamento, entre outros.
    
    **Pré-condições:**
    
    - O funcionário deve estar autenticado no sistema.
    - O funcionário só pode acessar dados da planta que possuem permissão de acesso.
    
    **Pós-condições:**
    
    - O funcionário obtém acesso às informações detalhadas da planta selecionada, permitindo uma análise mais profunda.
    
    d. **Consultar dados por BP (Business Partner):**
    
    - **Descrição:** permite ao CEO/VP consultar dados específicos por Business Partner.
    
    **Funcionalidade de consultar dados por business partner**:
    
    - O funcionário tem a possibilidade de consultar dados por Business Partner.
    - Ele navega para a seção de "Business Partner" no menu principal.
    - O sistema exibe uma lista de Business Partners disponíveis para seleção.
    - O funcionário seleciona um Business Partner específico da lista.
    - O sistema carrega e exibe os dados relacionados ao Business Partner selecionado, como as informações relevantes sobre a saúde mental dos colaboradores, com visualizações de gráficos, cards e tabelas.
    
    **Fluxo Principal:**
    
    1. **Selecionar business partner**:
        - O funcionário seleciona o Business Partner do qual deseja consultar os dados.
    2. **Acessar dados do business partner**:
        - Após selecionar o Business Partner, o funcionário visualiza dados específicos do Business Partner.
    3. **Visualizar informações do business partner**:
        - O funcionário pode visualizar as informações relacionadas ao Business Partner selecionado.
    
    **Pré-condições:**
    
    - O funcionário deve estar autenticado no sistema.
    - Os dados do Business Partner selecionado devem estar disponíveis no sistema.
    
    **Pós-condições:**
    
    - O funcionário obtém acesso às informações detalhadas do Business Partner selecionado.
    
    e. **Consultar dados de engajamento:**
    
    - **Descrição:** permite ao CEO/VP consultar dados de engajamento dos colaboradores.
    
    **Funcionalidade de consultar dados de engajamento:**
    
    - O funcionário visualizar sobre os dados de engajamento dos colaboradores.
    - Ele navega para a seção de "Engajamento" no menu principal.
    - O sistema carrega e exibe os dados de engajamento disponíveis, como pesquisas de satisfação, feedbacks ou outras métricas relacionadas ao engajamento dos colaboradores.
    
    **Fluxo Principal:**
    
    1. **Acessar dados de engajamento**:
        - O funcionário acessa a funcionalidade de consulta de dados de engajamento no sistema.
    2. **Visualizar informações de engajamento**:
        - Após acessar a funcionalidade, o funcionário pode visualizar as informações de engajamento dos colaboradores, incluindo métricas de satisfação, participação em pesquisas, como por exemplo a GPTW, entre outros indicadores.
    
    **Pré-condições:**
    
    - O funcionário deve estar autenticado no sistema.
    - Os dados de engajamento dos colaboradores devem estar disponíveis no sistema.
    
    **Pós-condições:**
    
    - O funcionário obtém acesso às informações de engajamento dos colaboradores, permitindo uma avaliação do nível de envolvimento e engajamento da equipe.
    
    f. **Filtrar dados:**
    
    - **Descrição**: permite que os funcionários refinem os conjuntos de dados exibidos no sistema de acordo com critérios específicos, fornecendo uma maneira flexível e personalizável de acessar informações relevantes.
    
    **Funcionalidade de filtrar dados**:
    
    - O funcionário decide quais critérios deseja usar para filtrar os dados. Isso pode incluir datas específicas, plantas, gênero, área, categorias, tipos de dados, ou outras variáveis relevantes.
    - O sistema exibe uma interface que permite ao funcionário definir os critérios de filtragem desejados.
    - O funcionário seleciona o tipo de filtragem, como datas, áreas, categorias específicas, ou outras opções disponíveis.
    - O sistema processa os critérios de filtragem e atualiza os dados exibidos de acordo com as escolhas do funcionário.
    - O funcionário pode analisar os dados refinados, identificar tendências, padrões ou insights relevantes com base nos critérios selecionados.
    
    **Fluxo Principal:**
    
    1. **Acessar funcionalidade de filtro**:
        - O funcionário acessa a funcionalidade de filtro disponível na plataforma.
    2. **Selecionar critérios de filtro**:
        - O funcionário seleciona os critérios de filtro desejados, como data, tipo de dado, área, entre outros.
    3. **Aplicar filtro**:
        - O funcionário aplica o filtro selecionado aos dados disponíveis no sistema.
    4. **Visualizar dados filtrados**:
        - Após aplicar o filtro, o funcionário pode visualizar os dados filtrados, que correspondem aos critérios definidos.
    
    **Pré-condições:**
    
    - O funcionário deve estar autenticado no sistema.
    - Os dados disponíveis no sistema devem ser passíveis de filtragem.
    
    **Pós-condições:**
    
    - O funcionário obtém acesso aos dados filtrados de acordo com os critérios definidos, permitindo uma análise mais específica e personalizada.
    

### 6.1.2 Componentes

Um diagrama UML de componentes é uma ferramenta para visualizar e entender a estrutura modular de um sistema de software. Ele ilustra como os diferentes componentes, como classes, interfaces, bibliotecas e arquivos, se relacionam entre si e as dependências entre eles. <br>

![componentes](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Diagrama_Componentes_1.png)

Figura 08: Diagrama de Componentes

**Notações:**

- Seta com semi circunferência significa que o componente depende de receber uma informação.
- Seta com circunferência significa que o componente envia uma informação para outro componente.
- Retângulo com dois retângulos menores nas laterais significa que é um componente.

**Explicação:**

- **Angular App**: representa a aplicação front-end desenvolvida em Angular para o dashboard.
- **Dashboard Component**: componente front-end desenvolvido em Angular e TypeScript, responsável por fornecer uma interface para os usuários interagirem com o dashboard, coletando dados analíticos e apresentando insights.
- **Server (.NET Core)**: representa a aplicação back-end desenvolvida em C# com .NET Core.
- **API .NET Core**: componente que fornece uma API para comunicação entre o front-end (Angular) e o back-end (.NET Core).
- **Database Principal (PostgreSQL)**: componente que armazena os dados analíticos utilizados pelo back-end.
- **Banco de Dados Registro**: armazena os dados de registro processados pelo back-end.

### 6.1.3 Diagrama de Classes

O diagrama de classes apresenta uma visão estrutural do sistema, mostrando as classes e suas relações, bem como atributos e métodos associados. Ele é uma ferramenta crucial para entender a arquitetura do sistema e como as diferentes partes interagem entre si.

Neste diagrama, temos classes como **`Usuario`**, **`Funcionario`**, **`Administrador`**, **`BusinessPartner`**, **`Dashboard`**, **`API_Dados`** e **`Planta`**. Cada uma dessas classes possui atributos e métodos específicos que descrevem suas características e comportamentos. Além disso, as relações de herança e associação entre as classes indicam como elas estão conectadas e como as informações fluem entre elas.

As restrições de acesso definem as permissões de cada tipo de usuário, como a capacidade de visualizar dados específicos ou realizar determinadas ações, uma vez que o sistema deve garantir a segurança e a integridade dos dados do sistema.

![diagrama_classe](https://github.com/Inteli-College/2024-T0004-SI09-G05/assets/99209230/dff51f43-2727-4b5f-ab2c-98b17619f552)


Figura 09: Diagrama de Classes

### 1. Classe `Usuario`

- **Descrição**: representa um usuário genérico do sistema.
- **Atributos**:
    - name: String - nome do usuário.
    - email: String - endereço de e-mail do usuário.
    - password: String - senha do usuário
- **Métodos**:
    - login(email: string, password: string): boolean - permite que o usuário faça login no sistema.
    - logout: void - permite que o usuário saia do sistema.
    

### 2. Classe `Funcionario` (herda de `Usuario`)

- **Descrição**: representa um funcionário da empresa.
- **Atributos**:
    - role: String - cargo do funcionário.
    - departament: String - departamento do funcionário.
- **Métodos**:
    - showBasicInfo: void - permite acesso a informações básicas relacionadas ao funcionário.
    

### 3. Classe `Administrador` (herda de `Funcionario`)

- **Descrição**: representa um administrador com acesso completo ao sistema, como por exemplo CEO ou VP RH.
- **Atributos**:
    - accessLevel: String = "complete" - nível de acesso do administrador.
- **Métodos**:
    - showAllData: void - permite visualizar todos os dados no sistema.
    

### 4. Classe `BusinessPartner` (herda de `Funcionario`)

- **Descrição**: representa um Business Partner com acesso a dados específicos de plantas.
- **Atributos**:
    - plantsAssigned: Planta[] - lista de plantas atribuídas ao Business Partner.
- **Métodos**:
    - showDataPlants: void - permite visualizar dados específicos das plantas atribuídas.
    

### 5. Classe `Dashboard`

- **Descrição**: interface de usuário para visualização de dados.
- **Atributos**:
    - widgets: List<Widget>- componentes do Dashboard.
    - filterData(): void - permite filtrar os dados
- **Métodos**:
    - generateReports(): void - gera relatórios baseados nos dados.
    - displayWidgets(usuario: Usuario): void - exibe o dashboard baseado no tipo de usuário e suas permissões.

### 6. Classe `API_Dados`

- **Descrição**: interface para coleta e processamento de dados.
- **Atributos**:
    - dataSource: String - fonte dos dados a serem coletados.
- **Métodos**:
    - colectData: Object[] - coleta dados da fonte especificada.
    - processData: void - processa os dados coletados.
    

### 7. Classe `Planta`

- **Descrição**: representa uma planta industrial ou unidade de negócios.
- **Atributos**:
    - plantName: String - Nome da planta.
    - stakeHoldersCount: int - número de colaboradores na planta.
    - healthKPIS: Object[] - indicadores de saúde mental na planta
- Métodos
    - showKPIS:Objetc[] - retorna os indicadores da planta
    

### **Relações e Restrições de Acesso**

- **Herança**: indica que uma classe é uma especialização de outra.
- **Associação**: indica interações entre diferentes classes, como entre **`Usuario`** e **`Dashboard`**.
- **Restrições de Acesso**: especificadas em cada classe, definem o nível de acesso e as permissões de cada tipo de usuário.

Link para melhor acesso: https://lucid.app/lucidchart/30ea7a0b-3e05-4a45-953c-6b906cee91a2/edit?invitationId=inv_b07ac491-2ad0-485b-a338-4e9fe646d8e4&page=0_0#

## 7. Esboços e Wireframes de Dashboards

Esboços iniciais que representam visualmente a disposição dos elementos da interface, como gráficos, tabelas e controles, permitindo uma avaliação preliminar da usabilidade e do fluxo de interação do dashboard.


### 7.1 Mockups Avançados

Maior nível de detalhamento e realismo a partir dos esboços iniciais, incorporando elementos visuais mais elaborados, como cores, estilos de fonte e imagens representativas de dados. Esses mockups proporcionam uma visão mais concreta do design final do dashboard, possibilitando a validação de conceitos, a identificação de melhorias

### Login

&emsp;&emsp;Iremos criar as contas e as autenticações necessárias para manter os dados seguros. Somente o cargo de CEO terá acesso a todas as páginas mostradas a seguir.

&emsp;&emsp;Nessa tela é possível o usuário acessar com:

- login;
- senha.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Login.jpg">
</div> <br>

Atualização da Tela de Login:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Login%20(1).png)

Características-chave dos **mockups** detalhados e navegáveis:

- **Título da Aplicação:**

Mental Matters

- **Descrição:**

Essa tela representa a página de login do sistema Mental Matters, uma plataforma que promove equipes saudáveis e pessoas felizes. A tela de login é a porta de entrada para os usuários autenticarem-se no sistema e acessarem suas respectivas contas.

- **Componentes:**

Logotipo no canto superior esquerdo, o logotipo da marca "Volkswagen" é exibido, simbolizando a identidade visual do sistema.

- **Campos de Entrada:**

Existem dois campos de entrada etiquetados como "Usuário" e "Senha". Nestes campos, os usuários devem inserir suas credenciais de login (nome de usuário ou endereço de email e senha) para acessar o sistema.

- **Botão de Entrar:**

Está localizado abaixo dos campos de entrada, o botão "Entrar" permite que os usuários submetem suas credenciais para autenticação. Após a validação, os usuários serão redirecionados para a página inicial do sistema, dependendo das permissões de acesso do usuário.

- **Experiência do Usuário:**

A tela de login do Mental Matters é minimalista e intuitiva, facilitando a interação do usuário. Os campos de entrada e o botão de login são facilmente identificáveis. O design limpo e simples permite que os usuários se concentrem em realizar o login com facilidade.

**a. Interatividade**: 

A tela de login apresenta interatividade por meio do botão "Entrar", que permite aos usuários submeterem suas credenciais para autenticação. 

**b. Design Integral**: 

O mockup da tela de login reflete o design final em todos os aspectos, incluindo a paleta de cores, tipografia, imagens, ícones e outros elementos gráficos. A paleta de cores é harmoniosa, e os elementos gráficos estão alinhados com a identidade visual do sistema.

**c. Fluxo Lógico**: 

Possui um fluxo de navegação lógico e intuitivo. A hierarquia entre os elementos é clara, com o logotipo no canto superior esquerdo, o título centralizado abaixo do logotipo e os campos de entrada e o botão de login ao lado deles. No entanto, como um mockup estático, o fluxo de navegação não pode ser experimentado ativamente.

### Dash CEO

&emsp;&emsp;A primeira página a ser acessada é a do Dashboard. Nessa aba terão informações macro sobre os colaboradores do Brasil.

&emsp;&emsp;Nessa tela é possível observar:

- menu com as seguintes opções de páginas:
    - dashboard;
    - plantas;
    - business Partner;
    - engajamento;
    - configurações;
    - logout.
- há uma funcionalidade de pesquisa pela barra de navegação;
- um ícone que aparecerá a foto do colaborador;
- um ícone de notificações;
- para o CEO, aparecerá a visão geral sobre os colaboradores da empresa como por exemplo:
    - número total de colaborados;
    - porcentagem geral de homens e mulheres na empresa;
    - número total de plantas com gráficos de pizza sobre o bem-estar emocional dos colaboradores;
    - número total dos colaboradores que são business partner com gráficos de pizza sobre o bem-estar emocional dos colaboradores.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/ceo.jpg">
</div> <br>

Atualização da Tela do CEO:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Dash%20CEO.png)

- **Componentes:**

**Logotipo:** no canto superior esquerdo, o logotipo da marca "Mental Matters" é exibido, simbolizando a identidade visual do sistema.

**Menu Lateral:** localizado à esquerda da tela, o menu lateral contém itens de navegação que permitem aos usuários acessar diferentes seções do sistema, como “Dasboard”, "Plantas", "Business Partner", "Engajamento" e "Logout".

**Total de Colaboradores:** exibida no topo da tela, a seção "Total de Colaboradores" mostra o número total de colaboradores da empresa Volkswagen.

**Gráfico de Gêneros:** este gráfico circulante representa a distribuição de gêneros entre os colaboradores, fornecendo uma visão rápida da composição demográfica do time.

**Seção de Plantas:** esta seção exibe informações sobre as plantas disponíveis no sistema, que estão ligadas a localização e relacionadas ao bem-estar emocional dos colaboradores.

**Seção do Business Partner:** esta seção fornece informações sobre os detalhes relacionados ao engajamento dos colaboradores nas pesquisas da empresa.

**Seção de Diretorias:** esta seção fornece informações sobre os detalhes relacionados ao engajamento dos colaboradores nas pesquisas da empresa.

- **Funcionalidades:**

**Navegação no Menu Lateral:**

Os itens de menu no painel lateral permitem que os usuários naveguem entre as diferentes seções do sistema, fornecendo acesso a recursos e informações adicionais.
**Experiência do Usuário:**

A tela do dashboard do Mental Matters é clara e informativa, fornecendo uma visão geral dos recursos e informações disponíveis no sistema. O menu lateral permite uma navegação fácil e intuitiva, e os gráficos e seções fornecem informações relevantes sobre a composição do time e o bem-estar de cada um. O design organizado permite que os usuários se concentrem em acessar e interagir com os recursos do sistema de maneira eficaz.

**a. Interatividade**: 

A tela do dashboard, como um mockup estático, não apresenta interatividade real. No entanto, a interatividade incluí o menu lateral, que sugere que os itens de navegação são clicáveis e redirecionarão os usuários para diferentes seções do sistema.

**b. Design Integral**: 

O mockup do dashboard reflete o design final em todos os aspectos, com: paleta de cores, tipografia, imagens, ícones e outros elementos gráficos. 

**c. Fluxo Lógico**: 

A tela possui um fluxo de navegação lógico, uma vez que a hierarquia entre os elementos é clara, com o logotipo no canto superior esquerdo, o menu lateral contendo itens de navegação à esquerda e as seções de informações ("Nota da empresa GPTW", "Colaboradores ", "Seção de Plantas", "Seção do Business Partner" e “Seção de Diretorias") à direita. Isso permite que os usuários entendam como a solução final funcionará.

### Plantas

&emsp;&emsp;Na página “Plantas”, é possível visualizar dados gerais sobre as 4 plantas que a Volkswagen possui no Brasil. Para aprofundar a visualização sobre horistas e mensalistas, o usuário poderá clicar no modal “Mensalistas X Horistas” e será direcionado para outra página correspondente. Caso tenha necessidade de visualizar com mais atenção uma planta em específico, basta selecioná-la ao lado direito e será direcionado para outra página.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/plantas.jpg">
</div> <br>

Atualização da Tela Plantas:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Plantas%20(1).png)

- **Componentes:**

**Logotipo:** no canto superior esquerdo, o logotipo da marca "Mental Matters" é exibido, simbolizando a identidade visual do sistema.

**Menu lateral:** localizado à esquerda da tela, o menu lateral contém itens de navegação que permitem aos usuários acessar diferentes seções do sistema, como “Dashboard”, "Plantas", "Business Partner", "Engajamento" e "Logout".

**Seções de plantas:** Esta seção exibe informações sobre as plantas disponíveis no sistema, que estão ligadas à localização e relacionadas ao bem-estar emocional dos colaboradores.

**Detalhes da planta:** Esta seção fornece detalhes sobre cada planta, incluindo seu nome, localização e métricas de bem-estar.

**Mapa Interativo:** Este mapa mostra a localização de cada planta, permitindo que os usuários interajam com ele clicando em cada marcador para exibir os detalhes da planta.

- **Funcionalidades:**

**Navegação no menu lateral:**

os itens do menu à esquerda permitem que os usuários naveguem entre as diferentes seções do sistema, fornecendo acesso a recursos e informações adicionais.

**Experiência do usuário:**

o dashboard "Plantas" é claro e informativo, fornecendo uma visão geral das plantas disponíveis e suas métricas associadas de bem-estar emocional. O menu lateral permite uma navegação fácil e intuitiva, enquanto a página de plantas fornece informações adicionais sobre a localização de cada planta.

**Interatividade:**

a seção de detalhes de cada planta, com o ícone de fábrica permite que os usuários cliquem em cada uma delas, a que desejar em específico para exibir os detalhes da planta selecionada.

**Design Integral:**

o dashboard "Plantas" reflete o design final em todos os aspectos, incluindo a paleta de cores, tipografia, imagens, ícones e outros elementos gráficos.

**Fluxo Lógico:**

o dashboard tem um fluxo de navegação lógico, com uma hierarquia clara entre os elementos. O logotipo está localizado no canto superior esquerdo, o menu lateral contém itens de navegação, e as seções de plantas e ícones de fábrica estão localizadas à direita da tela. 

### Planta específica
    
&emsp;&emsp;Quando o usuário seleciona uma planta em específico que deseja visualizar, ele é direcionado para uma página em que ele consegue ter a visão geral sobre:
- o total de colaboradores referente a planta selecionada;
- total de atestados;
- porcentagem de tipo da causa;
- qual gênero mais possui atestado;
- business partner com mais atestado;
- haverá também a visualização a partir de gráficos que apresentará dados sobre a saúde emocional dos colaboradores, bem como: total de atestados X causas, causas X área, entre outros.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/plantaespec.jpg">
</div> <br>

Atualização da Tela de Plantas em Específico:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Planta%201.png)

Este é o dashboard "Planta 1" do sistema Mental Matters. Aqui estão os componentes deste dashboard:

- **Cabeçalho:** contém o logotipo do Mental Matters no canto superior esquerdo, representando a identidade visual do sistema.
- **Menu:** está à esquerda da tela contém itens de navegação que permitem aos usuários acessar diferentes seções do sistema, como "Dashboard", "Plantas", "Business Partner", "Engajamento" e "Logout". A opção "Voltar para Plantas" permite que os usuários retornem à seção de Plantas.
- **Título:** O título "Planta 1" indica a planta específica para a qual este dashboard está exibindo informações.
- **Ano:** O ano "2023" é exibido, indicando que os dados mostrados são para este ano.
- **Métricas:** A seção Métricas exibe várias informações sobre a planta, incluindo:
    - O número de funcionários multiplicado pelo número de avaliações.
    - A média de funcionários e avaliações.
    - O número de trabalhadores horários.
    - A pontuação média GPTW (Great Place to Work) para a planta e a pontuação GPTW geral da empresa.
    - O número de ausentes e o total de avaliações.
    - As pontuações de ambiente de trabalho e vida pessoal.
    - O número de funcionários com problemas genéticos e outros motivos de ausência.
    - O turno com mais avaliações e o BP ou diretor com mais avaliações.
- **Funcionários:** A lista de funcionários com seus nomes e o número de avaliações que eles tomaram é exibida.

No geral, este dashboard fornece uma visão geral completa das métricas e dos dados da planta selecionada, permitindo que os usuários acessem e entendam facilmente as informações de que precisam. 

**a. Interatividade**:

- O dashboard é interativo, permitindo que os usuários cliquem nos itens do menu lateral para navegar entre as diferentes seções do sistema.
- Ao passar o mouse sobre as métricas da planta, é exibido um tooltip com uma descrição da métrica.
- Ao clicar na seta "Voltar para Plantas" no canto superior esquerdo, os usuários são redirecionados para a página anterior.

**b. Design Integral**:

- O dashboard reflete o design final em todos os aspectos, incluindo a paleta de cores, tipografia, imagens, ícones e outros elementos gráficos.
- A escolha de cores é consistente com a identidade visual do sistema, com tons de azul e branco predominantes.
- A fonte é clara e legível, facilitando a leitura das métricas e informações exibidas.

**c. Fluxo Lógico**:

- O fluxo de navegação é lógico e intuitivo, com o logotipo no canto superior esquerdo, o menu lateral contendo itens de navegação à esquerda e as seções de informações ("Métricas" e "Funcionários") à direita.
- As métricas estão organizadas em seções claramente definidas, com uma hierarquia bem definida entre as diferentes métricas.
- Ao clicar no menu lateral, os usuários são redirecionados para diferentes seções do sistema, permitindo que eles encontrem as informações de que precisam de maneira eficaz.

### Horistas X Mensalistas

&emsp;&emsp;Nessa tela, será possível visualizar gráficos que mostram o número de horistas X número de mensalistas X Planta, além disso, conterá gráficos sobre o bem-estar dos colaboradores com dados sobre horistas e mensalistas como: total de atestados, porcentagem de pessoas que estão saudáveis, e pessoas afastadas. Nessa tela, também aparecerá informações sobre detalhes dos atestados, como motivo, quantidade, área, etc.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/horistasMensa.jpg">
</div> <br>

Atualização da Tela Horistas e Mensalistas:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Horistas%20Mensalistas.png)

A tela fornecida é um dashboard relacionado a dados de empresa, abrangendo informações sobre "Horistas, mensalistas e executivos" em diferentes locais. Analisando-a com base nos três tópicos propostos:

**a. Interatividade**: 

a tela em si não é interativa, mas provavelmente faria parte de um sistema maior onde as interações estarão habilitadas. No entanto, a tela contém elementos interativos implícitos, como botões e links ("Mental Matters", "Dashboard", "Plantas", "Business Partner", "Engajamento", "Logout", e "Voltar para Visão Geral").

**b. Design integral**: 

o design integral está presente na tela, com a utilização consistente de cores, fontes e estilo. A paleta de cores é predominantemente branca com cinza e azul para destaques. A fonte é legível e usada consistentemente em todo o layout.

**c. Fluxo lógico:** 

há uma clara hierarquia de informações, começando com títulos e seções principais em destaque, seguidas por dados detalhados sobre "Horistas, mensalistas e executivos" em diferentes locais. A navegação entre as diferentes seções também é aparente, graças aos links no topo da tela.

### BP Geral

&emsp;&emsp;Nessa tela, o Business Partner terá a visualização sobre:
- o total de respostas nas pesquisas por BP;
- gráfico que mostra o número de BP com:
    - mais atestados;
    - menos atestados;
- gráficos que mostram como está o engajamento em relação ao GPTW, entre outros;
- tem uma funcionalidade em que o usuário poderá selecionar no canto direito qual Business Partner ele tem interesse em ver mais detalhes, basta clicar no BP e ele será direcionado para uma outra tela.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/businesspartner.jpg">
</div> <br>

Atualização da Tela do BP Geral:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Business%20Partner.png)

A tela fornecida é uma parte de um dashboard relacionado a dados de engajamento dos (BPs) e diretores. Analisando-a com base nos três tópicos propostos:

**a. Interatividade**: 

a tela em si não é interativa, mas provavelmente faria parte de um sistema maior onde as interações estarão habilitadas. No entanto, a tela contém elementos interativos implícitos, como a caixa de seleção para escolher um BP/diretor para obter mais informações e o link "Logout" no canto superior direito.

**b. Design integral**: 

o design integral está presente na tela, com a utilização consistente de cores, fontes e estilo. A paleta de cores é predominantemente branca com cinza e azul para destaques. A fonte é legível e usada consistentemente em todo o layout.

**c. Fluxo Lógico**: 

embora a tela seja estática, o fluxo lógico pode ser inferido a partir da organização dos dados. Há uma clara hierarquia de informações, começando com títulos e seções principais em destaque, seguidas por dados detalhados sobre o engajamento entre BPs e diretores. A navegação entre as diferentes seções também é aparente, graças ao link no topo da tela, e a interação adicional permite que os usuários selecionem um BP/diretor específico para obter mais informações.
    
### BP específico

&emsp;&emsp;Quando o usuário seleciona o BP em específico que ele deseja ver os detalhes, ele vai para essa página que mostra:
- o número total de colaboradores;
- gráficos que mostra sobre o bem-estar por gênero com:
    - total de homens e mulheres;
    - total de mulheres e homens saudáveis;
    - total de mulheres e homens afastados;
- gráficos sobre as plantas referentes ao BP selecionado com:
    - total de horistas e mensalistas;
    - total de atestados de horistas e mensalistas;
- gráfico sobre o detalhe dos atestados e visualização da porcentagem de tipo de causa;
&emsp;&emsp;Será possível uma visualização geral sobre o detalhe de engajamento do GPTW, com gráficos de acordo com a planta e a porcentagem de respostas por local.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/bpespeci.jpg">
</div> <br>

Atualização da Tela de BP Específico:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Business%20Partner%201.png)

**a. Interatividade:** 

pelo contexto, podemos perceber que o dashboard possui diversos elementos interativos, como o botão “Sair”, o botão “Voltar para Business Partner” e as diferentes abas e seções pelas quais o usuário pode navegar.

**b. Design integral:** 

o contexto mostra que o painel tem um design consistente, usando o mesmo esquema de cores, tipografia e ícones. O layout também é organizado e fácil de ler, tornando-o fácil de usar.

**c. Fluxo lógico**:

o dashboard possui um fluxo claro e lógico, com diferentes seções divididas em abas para facilitar a navegação. O utilizador pode facilmente encontrar a informação que procura, como as estatísticas “Total de colaboradores”, “Engajamento GPTW” e “Engajamento STIBA”, bem como as secções “Bem estar” e “Principal causa de afastamento”. No geral, o painel foi projetado de forma a facilitar a compreensão e a interação do usuário.
    
### Engajamento

&emsp;&emsp;Essa tela de engajamento possui informações sobre:
- total de colaboradores;
- total de respostas na pesquisa GPTW;
- porcentagem de respostas por gênero;
- porcentagem de horistas X mensalistas;
- gráfico que mostra a visualização total de respostas por BP;
    
&emsp;&emsp;Nessa tela, o usuário conseguirá ter uma visualização geral sobre como está o engajamento da empresa e de seus principais indicadores.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/engajamento.jpg">
</div>

Atualização da Tela de Engajamento:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Engajamento.png)

**a. Interatividade**: 

esse mockup é uma versão simplificada de um dashboard mais interativo.

**b. Design integra**l: 

há um esquema de cores e tipografia consistentes. O layout é organizado e fácil de ler, com títulos e seções claras. O uso de ícones e gráficos também ajuda a apresentar os dados de forma visualmente atraente.

**c. Fluxo lógico:** 

o mockup possui um fluxo claro e lógico, com diferentes seções divididas em abas para facilitar a navegação. O utilizador pode encontrar facilmente a informação que procura, como as estatísticas "Satisfação GPTW" e "Satisfação STIBA", bem como as secções "Engajamento GPTW X BP" e "Engajamento STIBA X BP". O uso de filtros também permite ao usuário personalizar a visualização dos dados. No geral, o mockup foi projetado de forma a facilitar a compreensão e a navegação do usuário.

Link para melhor acesso: https://www.figma.com/file/3P55bZKlZp5CQvhujCimsq/Wireframe-Dashboard---Projeto-Volkswagen?type=design&node-id=118%3A235&mode=design&t=K7qeGQDIv0jinIBF-1 



## 8. API de Integração

A API de integração é um componente essencial em sistemas que requerem comunicação e interoperabilidade entre diferentes módulos, aplicativos ou sistemas externos, oferecendo uma interface padronizada e segura para troca de dados e funcionalidades

### 8.1 Introdução
    
Este projeto de API foi desenvolvido seguindo os princípios da Clean Architecture, visando a separação de interesses, a independência de frameworks e a facilidade de manutenção e testabilidade. A estrutura do projeto é organizada em camadas distintas, com a lógica de negócios centrada no domínio e os detalhes de implementação, como banco de dados e interfaces do usuário, mantidos externamente a essa camada central. Isso permite que a aplicação seja resiliente a mudanças, seja em tecnologias ou em regras de negócio.
![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/pasta_API.png)

A seguir, detalhamos os aspectos mais significativos da nossa API, com foco em Autenticação, Gestão de Erros, Segurança, Logging e Versionamento.

### 8.2 Autenticação e Autorização
Utilizados na segurança da informação e controle de acesso em sistemas de software, autenticação é o processo de verificar a identidade de um usuário, garantindo que quem está tentando acessar um sistema seja realmente quem afirma ser. A autenticação é feita por meio de credenciais, como login e senha, tokens de acesso, chaves criptográficas ou métodos biométricos, impedindo o acesso não autorizado. Já a autorização determina o que um usuário pode ou não fazer após ter sido autenticado.

A autorização será baseada em papéis e permissões, onde diferentes tipos de usuários terão acesso a diferentes funcionalidades e dados, onde os administradores, CEO e VP de RH terão acesso completo ao sistema, incluindo a capacidade de visualizar e modificar todos os dados e configurações.
Os funcionários terão acesso restrito, podendo apenas visualizar dados gerais e específicos relacionados ao seu departamento ou planta.
Os Business Partners terão acesso a dados específicos de plantas com as quais estão associados, permitindo-lhes visualizar informações relevantes para suas responsabilidades.

Assim, para garantir a segurança dos dados e proteger contra acessos não autorizados, a autenticação na nossa API é feita utilizando o número pessoal do empregado como identificador. O endpoint `/api/v1/auth/authenticate` espera um `POST` com um corpo JSON contendo o `N_pessoal`. Apenas empregados com cargos de 'PRESIDENTE EXECUTIVO' ou 'VICE-PRESIDENTE' receberão um token JWT que permite acesso a informações restritas.

**Exemplo de resposta para usuário não autorizado:**

```json
{
  "message": "Acesso restrito ao presidente e vice-presidente."
}

```

### 8.3 Gestão de Erros

A API possui um mecanismo de gestão de erros que capta exceções não tratadas e retorna respostas padronizadas. O `ThrowController` é configurado para capturar e formatar essas exceções.

**Exemplos de mensagens de erro:**

- **Erro de servidor interno (500 Internal Server Error)**: "Ocorreu um erro ao obter empregados."
- **Recurso não encontrado (404 Not Found)**: "Nenhum empregado encontrado."

Em ambiente de desenvolvimento, a API fornece detalhes do stack trace para facilitar a depuração, enquanto em produção, esses detalhes são omitidos para segurança.
### 8.4 Segurança

A segurança é reforçada por meio do uso de tokens JWT, onde uma chave secreta gerada aleatoriamente é usada para assinar os tokens, garantindo que eles sejam válidos e não manipulados. A API também utiliza a autorização baseada em roles, permitindo que apenas usuários com certos cargos executem ações específicas.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/seguranca_API.png)

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/seguranca_API_2.png)

### 8.5 Estrutura de Dados
Organização e formato dos dados dentro de um sistema de software, que define como os dados são armazenados, acessados, manipulados e processados pelo sistema.

A estrutura de dados para a API do dashboard de saúde mental deve ser projetada de forma a garantir a eficiência na troca de informações e a facilidade de manipulação dos dados. Aqui está a definição precisa das estruturas de dados utilizadas para a entrada e saída da API, incluindo descrição dos campos, tipos de dados e validações:

Usuário:

- ID: Identificador único do usuário (string ou número).
- Nome: Nome do usuário (string).
- Email: Endereço de e-mail do usuário (string).
- Senha: Senha do usuário (string).
- Cargo: Cargo ou função do usuário na empresa (string).
- Departamento: Departamento ao qual o usuário está associado (string).

Planta:

- ID: Identificador único da planta (string ou número).
- Nome: Nome da planta (string).
- Localização: Localização geográfica da planta (string).
- Número de Colaboradores: Total de colaboradores trabalhando na planta (inteiro).

Configurações de Permissões:

- ID: Identificador único da configuração de permissões (string ou número).
- ID do Usuário: Identificador único do usuário ao qual as permissões se aplicam (string ou número).
- Permissões: Lista de permissões concedidas ao usuário, como acesso a determinadas funcionalidades do sistema ou a dados específicos (string).


### 8.6 Monitoramento e Logging
Necessários para acompanhar o desempenho, segurança e integridade de um sistema de software ao longo do tempo.
Foi implementado um sistema de registro (logging) para registrar eventos e armazenar de forma que fiquem acessíveis apenas para os administradores autorizados.
O Logging é implementado utilizando o `ILogger` para registrar informações importantes, avisos e erros, diagnosticar problemas, investigar atividades suspeitas e auditar o uso do sistema ao longo do tempo. Cada ação relevante, como uma tentativa de autenticação ou a obtenção de dados, é logada, incluindo detalhes como a hora do evento e informações específicas da solicitação, ajudando na identificação e resolução de problemas.
![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Loggin_API.png)

### 8.7 Versionamento

### **Versão 1.0 da API**

#### **Endpoint: GET /api/v1/empregado**

- **Função**: Retorna uma lista de todos os empregados.
- **Permissões**: Acesso autorizado requerido.
- **Retorno**: Uma lista de **`EmpregadoDTO`**, que inclui campos como **`n_pessoal`**, **`sg_emp`**, **`texto_rh`**, **`centro_cst`**, **`centro_custo`**, **`cargo`**, e **`data_nascimento`**.

#### **Endpoint: POST /api/v1/auth/authenticate**

- **Função**: Autentica um empregado e retorna um token de acesso.
- **Permissões**: Acesso restrito ao presidente e vice-presidente.
- **Retorno**: Em caso de sucesso, retorna um objeto contendo o token de acesso.

### **Versão 2.0 da API**

A versão 2.0 mantém os mesmos endpoints que a versão 1.0, mas com as seguintes alterações ou melhorias (a serem detalhadas conforme a evolução do projeto).



## 9. Análise Heurística do Dashboard Plantas


O design de sistemas e aplicações web para visualização de dados, como dashboards, deve aplicar conceitos de usabilidade levando em conta as necessidades do usuário, preferências e possíveis barreiras para utilizar a solução. Assim, realizar uma análise heurística pode identificar problemas em áreas específicas, de usabilidade ou visualização de dados, que podem impedir o uso de forma efetiva (LeRouge et al, 2017). 

A análise heurística envolve o processo de avaliação de uma interface web a partir de princípios como a lista das Heurísticas de Nielsen, que ajudam a projetar uma interface que possa não apenas apresentar um design agradável visualmente, mas também funcional (Moma, 2017).

Apesar de as heurísticas de Nielsen apresentarem áreas de avaliação relevantes, como visibilidade do status do sistema, compatibilidade entre o sistema e o mundo real, entre outros tópicos, poucos apresentam pontos de avaliação sobre visualização de dados (LeRouge et al, 2017), por isso foram utilizados outros pontos, descritos nas tabelas da seção 9.1, que abordam aspectos da visualização de dados em uma interface web de um dashboard. Dito isso, alguns aspectos das Heurísticas de Nielsen não foram abordados nesta análise, como apontado por Dowding & Merril (2018), sendo estes prevenção de erros, auxiliar usuários a se recuperarem de erros, e documentação, já que este último será contemplado com a completude da documentação total do projeto desenvolvido. 

O score de cada subtópico das heurísticas avaliadas variam de 0 a 5, onde quanto mais alto o valor, maior a correspondência à heurística indicada.

### 9.1 Tabelas de Análise Heurística

#### 1. Manipulação e multidimensionalidade dos dados 

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
1.a | Permite visualização de três variáveis ou mais no mesmo gráfico | Os gráficos apresentados na interface não possuem essa característica | Apresenta um problema funcional onde o usuário não poderá realizar cruzamento de informações, tendo acesso apenas a informações mais básicas de estimativas totais dos dados| Os gráficos de barras e rosca são gráficos que utilizam entre uma e duas variáveis | Média | 0 | Adicionar um elemento a mais no gráfico de barras que contemple uma média geral. 
1.b | Possui filtros nos gráficos  | Não apresenta essa característica | Apesar de não ser um problema, limita a manipulação do dado para melhor entender um cenário ou investigar uma situação | Não existe indicador para essa funcionalidade | Média | 0 | Adição de um gráfico que possibilite o filtro por gênero, faixa etária, etc. 
1.c | Suporta ampliação ou redução na visualização do gráfico | Não apresenta essa funcionalidade | Não Suporta essa funcionalidade de ampliação ou redução, mas a interface não possui gráficos que se beneficiem dessa funcionalidade | O gráfico possui um tamanho fixo | Baixa | 0 | Não é necessária a adição dessa funcionalidade de acordo com os gráficos apresentados, sendo esses de barra e de rosca. 
1.d | Suporta entrada de valores ou alteração das variáveis | Não apresenta essa funcionalidade | Os gráficos possuem valor recebidos apenas do banco de dados, sem possibilitar adição ou alteração de variáveis | Os gráficos não possuem indicador de mudança de valores ou variáveis | Baixa | 0 | Nesse caso, a adição de filtros pode se beneficiar, para complementar análises 

Média do Score da Heurística: 0


#### 2. Visibilidade do Status do Sistema e feedback

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
2.a | A interface possui um título ou header coerente com o conteúdo | O título da página é claro para preparar o que o usuário sobre o conteúdo que terá acesso | Não foi identificado problema | Os elementos são distintos pelo tamanho e posição, indicando que o primeiro elemento da página do dashboard é o nome da página | Alto | 5 | - 
2.b | A interface possui um feedback visual nos menus, itens clicáveis, etc  | A página possui itens clicáveis que são indicados por cores mais claras, em contraste com o que foi selecionado, com uma cor mais escura | Não foi identificado problema | Itens clicáveis dispostos na página indicam possibilidade de serem clicados | Alta | 5 | - 
2.c | O usuário é informado sobre a atualização dos dados | Há um indicador do ano que os dados são referentes, mas não em qual mês estes foram atualizados| A ausência de detalhes de atualização dos dados pode confundir o usuário sobre cenários em que está investigando | Há um título "Dados 2023", mas não há indicador de que mês ou período este se refere | Alta | 3 | Adicionar uma legenda nos gráficos ao lado do texto "Dados 2023" sobre o mês ou período dos dados 
2.d | Alguns elementos se destacam ao selecionar ou em estado hover do cursor | Os elementos do menu mudam de cor no estado hover do mouse | Não foi identificado problema | A cor do botão muda de cor ao entrar no estado hover | Alta | 4 | É recomendável que todos os botões possuam a funcionalidade de indicar que são clicáveis na função hover 

Média do Score da Heurística: 4

#### 3. Compatibilidade entre o sistema e o mundo real

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
3.a | Ícones e imagens utilizadas são familiares | Ícones utilizados são facilmente reconhecidos para situar o usuário sobre o conteúdo | Não foi identificado problema | Imagens das plantas indicam que são fábricas da montadora | Média | 5 | - 
3.b | Um usuário com médio letramento digital pode identificar as fontes dos dados  | É possível compreender as fontes dos dados utilizadas para gerar os gráficos apresentados | Não foi identificado problema | Os gráficos apresentam no título as fontes das variáveis de forma simplificada | Alta | 5 | - 
3.c | Um usuário com médio letramento digital pode formular uma relação de causa e efeito | É possível fazer as conexões entre variáveis e o resultado gerado pelos gráficos da interface | Não foi identificado problema	 | Por possuírem variáveis simples, a relação causa e efeito é facilmente feita | Alta | 5 | - 
3.d | Cores usadas atendem convenções e expectativas culturais | AS cores utilizadas nos gráficos são distintas e facilitam o entendimento do conteúdo | Não foi identificado problema	 | As cores no gráfico de barras apresentam cores distintas, e nos gráficos de rosca fazem referência do impacto do número sobre o valor apresentado | Média | 5 | - 

Média do Score da Heurística: 5


#### 4. Layout, Organização Espacial e Perspectiva

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
4.a | A página prioriza os conteúdos mais importantes a serem visualizados | A ordem dos gráficos apoia a prioridade e a ordem de análise | Não foi identificado problema	 | A ordem dos gráficos apoia a análise geral, para depois partir para o específico permitindo comparação entre os valores apresentados | Alta | 4 | Como sugestão poderia disponibilizar o valor de todas as plantas ao lado da imagem das plantas da empresa 
4.b | Se adapta a diversos tipos de tela  | A página suporta telas de celular para visualização | Não foi identificado problema	 | ordem dos gráficos aparece corretamente em visualização mobile | Média | 5 | A ausência dessa característica torna difícil a sua implementação posteriormente, sendo recomendável ser implementada no início do desenvolvimento das demais páginas
4.c | Utiliza tipos de gráficos compatíveis com os dados apresentados | Os gráficos utilizados são compatíveis para tornar a apresentação dos dados limpa sem detalhes desnecessários | Não foi identificado problema	 | Os tipos de gráficos aplicados aos dados torna reduzida a presença de elementos que podem poluir a tela | Alta | 5 | - 
4.d | Componentes utilizados são padronizados | Os componentes utilizados apresentam padronização dos elementos e conteúdos | Não foi identificado problema	 | As cores, blocos e formatos são harmônicos e complementam a leitura dos gráficos | Alta | 5 | - 

Média do Score da Heurística: 4,5

#### 5. Consistência e Propriedades Visuais

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
5.a | Identidade visual compatível com marca do parceiro | As cores são semelhantes às utilizadas pelo parceiro de negócio, incluindo formas e blocos utilizados | Não foi identificado problema	 | A cor primária ser branca reduz a confusão que excesso de cores podem causar, e a utilização de cores secundárias como azul tornam elementos semelhantes à cor da logo da empresa | Média | 5 | - 
5.b | Agrupa elementos que se relacionam/complementam  | Os componentes presentes na interface estão agrupados de maneira lógica para complementar a leitura e análise | Não foi identificado problema	 | As notas da planta com maior e menor nota GPTW necessitam estar próximas para comparação, e o gráfico principal acima facilita análise comparativa entre as plantas e a maior e menor nota GPTW | Alta | 5 | - 
5.c | Apresenta pista visual sobre qual página está atualmente ativa | A página ativa fica evidente pelo menu da navbar, porém pode confundir o usuário já que existe um botão "Plantas" no menu | O nome ativo ser Dashboard pode confundir o usuário do sistema	 | O nome da página ativa é "Dashboard" e existe um botão do menu "Plantas" | Moderado | 4 | Alterar o botão ativo na página de "Dashboard" para "Plantas"
5.d | Apresenta entre 4 e 7 cores facilmente diferenciáveis | A interface possui pouca variação de cores, direcionando melhor a atenção do usuário em elementos prioritários | Não foi identificado problema	 | No total foram utilizadas entre 4 e 5 cores distintas, considerando o espectro cromático, que direcionam a atenção do usuário para pontos específicos | Moderada | 5 | - 
5.e | Nomes dos gráficos são consistentes na página | Os gráficos possuem nomes consistentes na interface | As legendas do gráfico principal, sendo as siglas das Plantas da montadora pode não ser claro para usuários sem familiaridade, apesar de ser um dashboard direcionado è executivos da empresa	 | Cada gráfico possui um nome distinto que não se confunde com os outros elementos da tela, e se relacionam com as legendas escolhidas para os gráficos | Moderada | 4 | Ajustar o nome das legendas para o nome completo da planta, evitando confusões 

Média do Score da Heurística: 5

#### 6. Reconhecimento em vez de memorização

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
6.a | Mensagens, elementos e gráficos estão dispostos onde o olhar tem maior probabilidade de percorrer pela página | Os componentes da interface possuem uma organização lógica que acompanha o movimento natural do olhar do usuário | Não foi identificado problema	 | Os elementos estão dispostos em ordem de prioridade seguindo um movimento em "Z" do olhar ao interagir com uma página web, começando com o ícone da marca, o título da página, o gráfico principal, as plantas disponíveis e finalizando com a nota da GPTW  | Alta | 5 | - 
6.b | Espaços em branco utilizados para criar simetria e guiar o olhar do usuário  | Os espaços em branco apresentam uma suporte para separar os elementos e facilitar a leitura dos gráficos da interface | Não foi identificado problema	 | A distância dos elementos e os componentes delimitados facilitam a diferenciação entre os mesmos e o seu conteúdo | Média | 4 | O espaço vazio ao lado do gráfico da planta com menor nota da GPTW apresenta um pouco de desequilíbrio, que poderia ser preenchido por algum elemento que facilite navegação para outras páginas ou uma funcionalidade adicional 
6.c | Possui cores que chamam atenção do usuário para elementos relevantes | As cores direcionam a atenção para os gráficos, que são os elementos prioritários para análise do usuário | Não foi identificado problema	 | O uso de cores fica praticamente restrito aos gráficos do dashboard, direcionando a atenção do usuário para os componentes relevantes para análise, sem distrações | Média | 5 | - 

Média do Score da Heurística: 4,5

#### 7. Adaptabilidade e flexibilidade de uso

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
7.a | Apresenta customização dos gráficos | Não apresenta essa característica | A ausência de customização de gráficos reduz a utilização do dashboard para elementos fixos que podem não corresponder à análises do usuário | Não existe indicador para essa funcionalidade | Média | 0 | A adição dessa funcionalidade aumenta a adaptação do usuário com o produto, adicionando inclusive suporte para daltonismo
7.b | Apoia usuários que apresentam daltonismo  | Os gráficos presentes no dashboard possui cores que não contemplam todos os tipos de daltonismo | Apesar de apoiar alguns espectros de daltonismo, existe o daltonismo que não distingue as cores azuis das verdes | O gráfico principal possui cores sem muito contraste, considerando o daltonismo que não diferencia verde de azul | Alta | 3 | Adicionar mais contraste que possibilita distinguir as variáveis do gráfico principal 

Média do Score da Heurística: 1,5

#### 8. Poluição Visual e Densidade de Dados

#Número | Descrição da avaliação | Observações |Problemas Identificados | Evidência | Criticidade | Score | Sugestão/Recomendação | 
--- | --- | --- | --- |--- |--- |--- |--- 
8.a | Apresenta estética minimalista | O dashboard apresenta estética minimalista | Não foi identificado problema	 | A interface possui poucos elementos que são facilmente distinguíveis entre si | Média | 5 | - 
8.b | Utiliza ícones distintos entre si  | Os ícones foram usados moderadamente, evitando confundir o usuário | Não foi identificado problema	 | Os ícones utilizados não foram excessivamente implementados ou apresentam muita variabilidade que poderia requerer atenção do usuário para a diferenciação entre eles | Média | 5 | - 
8.c | Utilização textual ou descritiva apenas quando necessário  | A parte textual do dashboard é reduzida, evitando uma solução expositiva que requer muita leitura | Não foi identificado problema	 | Descrições, títulos e legendas utilizadas de maneira pontual na interface | Média | 5 | Poderia ser adicionado um texto explicativo sobre alguns elementos dos gráficos, para indicar mais detalhes para o usuário, quando o cursor ativar o modo hover sobre o elemento 
8.d | Possui um contraste adequado entre os elementos do gráfico  | Possui certo contraste entre os elementos do gráfico principal | O pouco contraste pode dificultar leitura por pessoas daltônicas | Os gráficos principais utilizam cores claras no gráfico principal | Média | 3 | Aumentar um pouco o contraste pode facilitar a leitura por parte dos usuários 
8.e | Separa os elementos da página por sessões distintas  | Os elementos são dispostos de forma a facilitar a distinção entre eles, e separa os elementos do menu, gráficos, e ícones das plantas para mais detalhes. | Não foi identificado problema	 | O espaço entre o menu, a seção dos gráficos, e a seção Detalhes é um pouco maior, indicando que são seções diferentes | Média | 5 | - 
8.f | Evita o uso de elementos desnecessários na interface  | Se aproveitando de uma estética minimalista, a página não possui elementos desnecessários, permanecendo os necessários para o usuário avaliar e navegar | Não foi identificado problema	 | A ausência de elementos desnecessários que poderiam tirar a atenção do usuário sobre os componentes presentes no dashboard | Baixa | 5 | - 

Média do Score da Heurística: 4,5

### 9.2 Conclusão da Análise


<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Grafico_Radar_Heuristica.png">
</div>


Após a análise realizada, e com base no gráfico de radar da média do score das heurísticas abordadas, vários pontos de melhoria surgem, incluindo pontos críticos que requerem atenção dos desenvolvedores. 

Em relação à Manipulação e Multidimensionalidade dos Dados, que recebeu um score zero em todos os itens, a ausência de gráficos com maior diversidade de variáveis limita o uso do dashboard para análises mais completas e complexas. Isso pode ser remediado com adição de uma página sobre plantas específicas com maior cruzamento de dados. Já a ausência de filtros no dashboard avaliado pode prejudicar o uso da solução, por manter análises mais rasas por parte do usuário, tornando mais difícil explorar e compreender os dados.

Outro ponto de atenção é sobre Adaptabilidade e Flexibilidade de Uso, que indica a ausência de customização e não cobre todos os tipos de daltonismo, tornando-se assim ineficaz com usuários que apresentem essa condição, restringindo a usabilidade da solução.

Já heurísticas que receberam uma pontuação alta se referem à clareza das informações disponibilizadas na interface, trazendo um feedback visual mais limpo, com um layout organizado, mantendo a padronização dos componentes e compatibilidade com o visual da marca. Isso proporciona uma experiência mais fluida e orientada ao usuário, com uma condução lógica entre os elementos da tela.

## 10. Dashboard - Versão 2

### Introdução

Neste artefato, apresentamos a segunda versão do Dashboard, que foi integrado com a API de Integração. O Dashboard foi desenvolvido seguindo os princípios de DRY (Don't Repeat Yourself), garantindo eficiência, coesão e reutilização de componentes. Abaixo detalhamos os principais aspectos desta versão.

### Interface do Dashboard Atualizada

A interface do Dashboard - Versão 2 foi atualizada para refletir os novos dados e funcionalidades da API V2. Esta nova interface inclui:

- **Gráficos Interativos:** Utilizamos a biblioteca NgApexcharts para criar gráficos interativos que exibem as métricas e informações relevantes. Por exemplo, o gráfico de barras exibe o número de colaboradores e atestados por planta.

```tsx
import { ChartComponent } from 'ng-apexcharts';

@Component({
  selector: 'app-plantas',
  templateUrl: './plantas.component.html',
  styleUrls: ['./plantas.component.css'],
})
export class PlantasComponent {
  @ViewChild('chart') chart!: ChartComponent;
  public chartOptions: Partial<ChartOptions>;

  constructor(private apiConnect: ApiconnectService) {
    this.chartOptions = {
      series: [],
      chart: {
        height: 350,
        width: 500,
        type: 'bar',
        zoom: {
          enabled: false,
        },
      },
      // outras configurações...
    };
  }

  ngOnInit() {
    this.apiConnect.getCid2023EmployeesCertificate().subscribe((response: HttpResponse<UnidadeResponse>) => {
      // processamento dos dados e atualização do gráfico...
    });
  }
}

```

![image](https://github.com/Inteli-College/2024-T0004-SI09-G05/assets/99209230/17b9f71e-e201-4ee1-ac84-da9ed8e32323)


### Integração com API V2

O Dashboard - Versão 2 está integrado exclusivamente com a API de Integração V2 para obter os dados necessários. A integração foi realizada utilizando o serviço `ApiconnectService` para fazer solicitações HTTP à API V2 e recuperar os dados.

```tsx
@Injectable({
  providedIn: 'root'
})
export class ApiconnectService {
  BASE_URL = enviroment.apiUrl;
  constructor(private http: HttpClient) { }

  getCid2023EmployeesCertificate(): Observable<HttpResponse<UnidadeResponse>> {
    return this.http.get<UnidadeResponse>(`${this.BASE_URL}Cid/colaboradores-atestados-por-unidade`, { observe: 'response'});
  }
}

```

![image](https://github.com/Inteli-College/2024-T0004-SI09-G05/assets/99209230/4625e564-a2de-4745-bccb-fa022b56f442)


### Princípio DRY

O princípio DRY foi aplicado de forma eficaz no código-fonte do Dashboard - Versão 2. As duplicações de código foram minimizadas e os componentes foram projetados para serem reutilizáveis. Por exemplo, na atualização dos dados do gráfico, evitamos repetir a lógica de processamento de dados.

```tsx
this.apiConnect.getCid2023EmployeesCertificate().subscribe((response: HttpResponse<UnidadeResponse>) => {
  // processamento dos dados e atualização do gráfico...
});

```
![image](https://github.com/Inteli-College/2024-T0004-SI09-G05/assets/99209230/8236c649-3382-455c-8577-aa192939030a)


### Responsividade

O Dashboard - Versão 2 é responsivo e se adapta a diferentes tamanhos de tela e dispositivos. Isso foi alcançado utilizando técnicas de design responsivo e CSS flexível para garantir uma experiência consistente em todas as plataformas.

```css
/* Exemplo de estilo responsivo */
@media screen and (max-width: 600px) {
  .chart-container {
    width: 100%;
  }
}

```

### Performance

A performance do Dashboard - Versão 2 foi otimizada para garantir uma carga rápida e uma experiência fluida para o usuário. Isso inclui a minimização do tamanho dos recursos, a redução do número de solicitações de rede e o uso eficiente de cache sempre que possível.

```tsx
// Exemplo de cache de dados
@Injectable({
  providedIn: 'root'
})
export class CacheService {
  private cache = new Map<string, any>();

  constructor() { }

  get(key: string) {
    return this.cache.get(key);
  }

  set(key: string, value: any) {
    this.cache.set(key, value);
  }
}

```

### Conclusão

O Dashboard - Versão 2 representa um avanço significativo em relação à versão anterior, com melhorias na interface, integração com a API, aderência ao princípio DRY, responsividade e performance. Esperamos que esta versão atenda aos padrões de qualidade estabelecidos e proporcione uma experiência de usuário aprimorada.

## 11. Documentação da API de Integração - Versão 2
## Introdução
Esta é a segunda versão da API de integração, desenvolvida para incluir comunicação com o Dashboard - Versão 2. Além disso, foram adicionados novos serviços de feature para tratamento e manipulação de dados do front-end, permitindo uma interação mais avançada com o dashboard.
## Estrutura da API
A API consiste em endpoints que fornecem acesso aos recursos necessários para a integração com o Dashboard - Versão 2 e para a manipulação de dados do front-end.
## Endpoints
### Gptw
- **Descrição:** Fornece acesso aos dados do GPTW.
- **Endpoints:**
  - **GET /api/v2/gptw**: Retorna todos os dados do GPTW.
    - **Parâmetros de consulta:** Nenhum.
    - **Autenticação:** Requer autenticação com o papel "PresidenteFuncionarioPolicy".
    - **Formato de resposta:** JSON.
    - **Exemplo de resposta:**
      ```json
      [
          {
              "nniveis": "value",
              "uo_abrev": "value",
              "rrh": "value",
              "local": "value",
              "empr": "value",
              "gremp": "value",
              "grpempregados": "value",
              "sgemp": "value",
              "centrocst": "value",
              "unidorg": "value",
              "descr_uo": "value",
              "idadedoempregado": "value",
              "gn": "value",
              "data_adm": "value"
          }
      ]
      ```
### Empregado
- **Descrição:** Fornece acesso aos dados dos empregados.
- **Endpoints:**
  - **GET /api/v2/empregado**: Retorna todos os dados dos empregados.
    - **Parâmetros de consulta:** Nenhum.
    - **Autenticação:** Requer autenticação com os papéis "PRESIDENTE EXECUTIVO" ou "VICE-PRESIDENTE".
    - **Formato de resposta:** JSON.
    - **Exemplo de resposta:**
      ```json
      [
          {
              "n_pessoal": "value",
              "sg_emp": "value",
              "texto_rh": "value",
              "centro_cst": "value",
              "centro_custo": "value",
              "cargo": "value",
              "data_nascimento": "value"
          }
      ]
      ```
### Cid2023
- **Descrição:** Fornece acesso aos dados do CID2023.
- **Endpoints:**
  - **GET /api/v2/cid2023**: Retorna todos os dados do CID2023.
    - **Parâmetros de consulta:** Nenhum.
    - **Autenticação:** Requer autenticação.
    - **Formato de resposta:** JSON.
    - **Exemplo de resposta:**
      ```json
      [
          {
              "mes": "value",
              "atestados": "value",
              "cid": "value",
              "descricao": "value",
              "dias": "value",
              "diretoria": "value",
              "unidade": "value"
          }
      ]
      ```
### Atestados por Unidade
- **Descrição:** Retorna um dicionário contendo informações sobre o número de colaboradores e atestados por unidade.
- **Endpoints:**
  - **GET /api/v2/cid2023/atestados-unidades**: Retorna as informações de colaboradores e atestados por unidade.
    - **Parâmetros de consulta:** Nenhum.
    - **Autenticação:** Requer autenticação.
    - **Formato de resposta:** JSON.
    - **Exemplo de resposta:**
      ```json
      {
          "unidade1": {
              "colaboradores": 100,
              "atestados": 20
          },
          "unidade2": {
              "colaboradores": 80,
              "atestados": 15
          }
      }
      ```
## Integração com Dashboard V2
A API de integração se comunica com o Dashboard - Versão 2 por meio dos endpoints fornecidos acima. Os dados são transmitidos em formato JSON para garantir uma comunicação eficiente entre os sistemas.
## Serviços de Feature
Foram adicionados novos serviços de feature para tratamento e manipulação avançada de dados pelo front-end. Esses serviços permitem uma interação mais sofisticada com o dashboard e incluem:
- **Recursos avançados de manipulação de dados:** Permitindo a realização de operações complexas nos dados fornecidos pela API.
- **Recursos de consulta avançada:** Permitindo a recuperação de dados com base em critérios específicos definidos pelo usuário.
## Estrutura de Dados Atualizada
As estruturas de dados (JSON) utilizadas para a entrada e saída da API foram atualizadas para incluir os novos recursos adicionados. Isso garante a consistência e a compatibilidade dos dados transmitidos entre a API e o Dashboard - Versão 2.
## Autenticação e Autorização
A API utiliza o esquema de autenticação JWT (JSON Web Token) para autenticar os usuários e autorizar o acesso aos recursos. Além disso, foram adicionadas políticas de autorização para garantir que apenas usuários autorizados possam acessar determinados endpoints.
## Gestão de Erros
A API continua a fornecer mensagens de erro informativas e orientações claras para solucionar problemas. Foram adicionados novos cenários relacionados aos feature services para garantir um tratamento adequado de erros e status codes.
## Monitoramento e Logging
Propomos mecanismos de monitoramento atualizados, considerando as novas funcionalidades adicionadas. Isso inclui métricas de desempenho e registros (logs) para facilitar a depuração e o diagnóstico de problemas.
## Padrão de Qualidade
A API de Integração - Versão 2 segue as diretrizes estabelecidas, incluindo as novas funcionalidades adicionadas. Ela mantém:
- **Interoperabilidade:** Capacidade de interoperar eficazmente com sistemas e serviços distintos, incluindo o Dashboard - Versão 2.
- **Documentação Clara e Completa:** Documentação precisa, atualizada e facilmente compreensível, incluindo os novos serviços.
- **Segurança:** Rigoroso controle de segurança, especialmente

## 12. Teste de Usabilidade Presencial Moderado

Usabilidade é o termo utilizado para abordar a interação entre um usuário e um sistema, sendo a interface deste a principal porta desta interação. E usabilidade se difere de funcionalidade, já que um sistema pode ser funcional, mas ser rejeitado por um usuário devido à uma má usabilidade (Carvalho, 2002).

Segundo Carvalho (2002), usabilidade compreende três aspectos principais:

- Facilidade de aprendizado da solução, onde novos usuários devem apresentar interesse ao utilizar a solução proposta, em comparação com o processo já existente;
- Facilidade de utilização da solução, em decorrência do aprendizado, o sistema deve apresentar uma facilidade de utilização;
- Satisfação do usuário, contemplando tanto a usabilidade quanto a funcionalidade, trazendo uma satisfação do usuário sobre o sistema proposto.

Testes de usabilidade são utilizados para avaliar a qualidade do software em desenvolvimento a partir de critérios de usabilidade estabelecidos (Ferreira, 2002). Nesse sentido, usuários desempenham o papel de avaliar a usabilidade, identificar problemas, oportunidades e validar soluções. Esses testes envolvem a interação direta entre os usuários-alvo e o produto em questão, proporcionando insights sobre como ele é percebido, compreendido e utilizado na prática.

Os testes com usuários oferecem uma abordagem empírica para avaliar a usabilidade, permitindo que os desenvolvedores obtenham feedback direto dos usuários finais. Ao observar e interagir com os usuários durante o uso do produto, é possível identificar pontos de dor, áreas de confusão e oportunidades de melhoria. Esses insights orientam ajustes no design e na funcionalidade do produto, garantindo uma experiência mais satisfatória para o usuário final (Ferreira, 2002).

A abordagem dos testes com usuários podem assumir diferentes configurações, dependendo do tipo de sistema em desenvolvimento, e das qualidades necessárias a serem avaliadas, podendo ser avaliações formais em laboratório, e até abordagens mais ágeis, pontuais, realizadas de forma remota. Porém, independente da metodologia utilizada, o objetivo final é entender as necessidades, expectativas e comportamentos dos usuários para criar produtos que atendam de forma eficaz e intuitiva às suas demandas (Carvalho, 2002).

Nesse sentido, a relação da acessibilidade com a usabilidade, segundo Ferreira (2008), apresenta a característica matemática da simetria, onde um elemento retém as mesmas características, mesmo após sofrer transformações, já que as transformações não alteram o objeto. Com isso, a acessibilidade permite o acesso ao sistema por uma diversidade de usuários, apresentando o mesmo conteúdo de diferentes formas. Além disso, aspectos acessíveis também agregam ao sistema uma maior usabilidade, tornando-o mais flexível de acordo com as necessidades do usuário.

Nesse contexto, as WCAG (Web Content Accessibility Guidelines) podem auxiliar nos critérios avaliativos, já que fornecem diretrizes específicas para garantir a acessibilidade de conteúdos na web. Ao aplicar as WCAG durante a avaliação de usabilidade de um sistema, os avaliadores podem verificar se o design, a interação e o conteúdo do sistema atendem aos padrões de acessibilidade estabelecidos, permitindo uma avaliação mais abrangente e precisa da experiência do usuário. Isso contribui para identificar e corrigir possíveis barreiras de acessibilidade (Sales, 2024).

### Heurísticas e critérios

Após a análise heurística realizada anteriormente, vários pontos de melhoria surgem como:

- Manipulação e Multidimensionalidade dos Dados: A capacidade de manipular e interpretar dados em várias dimensões não está totalmente desenvolvida, o que pode limitar a compreensão e a utilidade da solução.
- Adaptabilidade e Flexibilidade de Uso: A falta de customização torna a solução menos adaptável às necessidades individuais dos usuários, enquanto a ausência de suporte para todos os tipos de daltonismo prejudica a acessibilidade para aqueles com essa condição.

Para abordar essas questões e validar os pontos positivos observados na análise heurística, serão aplicados os seguintes critérios de avaliação com base no guia WCAG durante os testes:

1. Compreensível - palavras incomuns - AAA: Avalia a clareza e a familiaridade do vocabulário utilizado na interface. É importante evitar o uso de termos complexos ou pouco familiares para garantir que os usuários compreendam facilmente as informações apresentadas.
2. Operável - Cabeçalhos e rótulos - AA: Refere-se à facilidade de operação da interface, incluindo a clareza dos cabeçalhos e rótulos de campos. Cabeçalhos e rótulos devem ser descritivos e intuitivos para facilitar a navegação e a interação do usuário.
3. Perceptível - Redimensionar texto - AA: Diz respeito à capacidade de ajustar o tamanho do texto para atender às preferências do usuário. A possibilidade de redimensionar o texto é essencial para garantir que todos os usuários possam ler facilmente as informações apresentadas, independentemente de suas necessidades visuais.
4. Robusto - Nome, função, valor - A: Avalia a consistência e a precisão das informações apresentadas, incluindo a clareza dos nomes, funções e valores dos elementos da interface. É importante que essas informações sejam apresentadas de forma coerente e compreensível para garantir uma experiência de usuário robusta e confiável.

### Metodologia

Como apontado por Wangenheim et al (2014), um dos principais métodos de avaliação de usabilidade de uma solução é a de apresentar tarefas típicas com um sistema, buscando medir o desempenho dos usuários, ressaltando que existem aspectos subjetivos, que podem ser reforçados aplicando um questionário pós-teste.

O Teste de usabilidade foi feito de forma presencial e com a presença de moderação de um avaliador, buscando avaliar características qualitativas, em um aspecto explorador. O teste permeou aspectos heurísticos, ou seja, critérios estabelecidos com base em boas práticas e conhecimentos prévios sobre usabilidade, e aspectos discursivos, que envolveram a observação e análise das interações dos usuários com o sistema, incluindo suas percepções, comentários e feedbacks durante a sessão de teste.

Observa-se que o estágio atual de desenvolvimento do projeto ainda requer polimento, especialmente no que diz respeito à integração completa dos dados e à apresentação visual das informações. O teste foi realizado durante o estágio de integração dos dados, resultando em uma falta de informações visuais detalhadas em alguns componentes do dashboard. No entanto, essa lacuna não prejudica significativamente o teste, considerando a natureza do que se deseja evidenciar de usabilidade e navegação entre páginas. Pelo contrário, essa fase pode colaborar para melhorar o tipo de dado apresentado em cada componente de gráfico entre as páginas do dashboard, permitindo ajustes e refinamentos que tornem a experiência do usuário final mais completa e satisfatória.

### Usuários Participantes

Os testes foram realizados por três (3) usuários, utilizando códigos para identificação de cada usuário, sendo U01 para o Usuário de Teste 1, U02 para o Usuário de Teste e U03 para o Usuário de Teste 3, onde todos os participantes responderam um questionário demográfico antes de iniciar as avaliações de usabilidade (Tabela 01), proporcionando informações importantes para contextualizar os resultados dos testes e entender melhor as diferentes perspectivas e habilidades dos usuários envolvidos.

Os resultados serão analisados de forma qualitativa e quantitativa, comparando respostas diferentes e agrupando observações que são semelhantes entre os usuários.

#### Tabela 01: Questionário de perfil demográfico.
Questão de Perfil Demográfico | 
--- | 
Qual a sua idade?  | 
Qual gênero se identifica? | 
Qual seu nível de escolaridade? | 
Qual sua área de especialização? | 
Qual cargo ocupa atualmente? | 

### Perfil dos Avaliadores

O avaliador desempenha um papel central durante a sessão de teste, sendo responsável por todas as etapas do processo. Sua função inclui interagir com o participante, coletar informações relevantes, analisar os resultados dos testes e comunicá-los de forma clara e precisa à equipe de desenvolvimento. Além disso, ele é encarregado de toda a preparação para o teste, incluindo o material necessário, organização do ambiente e coordenação das atividades dos outros membros da equipe de teste. Após a conclusão do teste, o avaliador colabora com os demais membros da equipe para garantir que os objetivos estabelecidos tenham sido alcançados (Ferreira 2002).

Este teste contou com dois avaliadores por sessão, nos seguintes papéis:

- Observador, responsável por monitorar o usuário que está realizando o teste. Registrando o comportamento do usuário durante a interação com o produto, dificuldades encontradas, pontos de confusão e qualquer feedback verbalizado pelo usuário. Além disso, o Observador também é responsável por registrar se o usuário conseguiu completar com sucesso as tarefas propostas durante o teste, identificando possíveis obstáculos ou áreas de melhoria no processo de interação.
- Perito Organizador de Informações, que desempenha o papel de organização e execução eficiente do teste de usabilidade. Possui um profundo conhecimento técnico sobre o produto em teste, garantindo seu funcionamento correto durante toda a sessão. Antes do teste realiza a apresentação inicial do teste para usuários teste, o fornece o roteiro para a execução do teste e os questionários a serem preenchidos.

### Roteiro do Teste

Com o objetivo de verificar a integridade do dashboard de saúde mental, incluindo a avaliação do reconhecimento das informações e a percepção de um storytelling na construção dos gráficos, foram realizados testes em sessões que contavam com apenas um usuário participante e dois avaliadores, que partiram da tela inicial na página de login, contando que os usuários pudessem realizar todos os passos do roteiro (Tabela 02) em até dez (10) minutos.

#### Tabela 02: Roteiro utilizado para teste de usabilidade presencial moderado.
Número | Categoria WCAG | Teste |Objetivo do Teste | 
--- | --- | --- | --- |
1 | Operável | Acesse o dashboard para encontrar as plantas de fábrica | Examinar se os cabeçalhos e rótulos são eficazes em orientar os usuários através das diferentes seções do dashboard e na interação com os elementos da tela	 | 
2 | Compreensível | Encontre a planta que possui a menor nota da avaliação Stiba | Avaliar a compreensão e a familiaridade dos usuários com a terminologia utilizada no dashboard	 | 
3 | Robusto | De acordo com o engajamento, é possível fazer alguma correlação sobre essa nota recebida? | Assegurar que as informações apresentadas são coerentes e relevantes para realizar correlações	 | 
4 | Perceptível | Redimensione a tela para ver mais detalhadamente o gráfico. Isso ajudou ou prejudicou sua experiência? | Verificar a acessibilidade do dashboard, incluindo a capacidade de redimensionar a página sem perda de usabilidade	 | 

Cada sessão individual com os usuários teste seguiu o fluxo indicado na Figura 11, o que foi necessário para garantir consistência e padronização nos testes, facilitando a análise e comparação dos resultados. No total, foram realizados testes com três usuários, os quais foram orientados por um avaliador perito e observados por um avaliador observador ao longo de aproximadamente 15 minutos cada sessão.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/Fluxo_avaliação.png">
</div>

Figura 11. Planejamento da organização da sessão de testes com cada usuários, com as etapas e o tempo estipulado.

Ao final do teste, foi aplicado o questionário de pós-teste (Tabela 03). Esse questionário visa aprofundar a compreensão da experiência dos usuários, permitindo que eles expressem suas opiniões, sentimentos e percepções sobre o uso do sistema. Esses aspectos subjetivos são essenciais para uma avaliação completa da usabilidade da solução, complementando as informações obtidas durante a interação direta com o produto.

#### Tabela 03: Questionário de pós-teste.
Pós-Teste |
--- | 
Como você avalia a compreensão dos termos utilizados no dashboard? | 
Os cabeçalhos e rótulos facilitaram a identificação das informações em cada página? | 
As informações apresentadas no dashboard foram relacionadas aos tópicos abordados nos cabeçalhos e rótulos? | 
Você percebeu alguma sequência lógica na posição dos gráficos nas páginas? |

### Resultados e discussão

O grau de severidade dos resultados obtidos durante os testes de usabilidade será abordado de forma detalhada nas Considerações Finais e Propostas de Melhorias. Essa análise levará em consideração o impacto que esses problemas podem ter na experiência geral do usuário e na eficácia do sistema. A partir dessa avaliação, serão delineadas propostas de melhorias específicas para cada ponto identificado, visando otimizar a usabilidade, a acessibilidade e a eficiência do dashboard.

Os dados quantitativos que foram obtidos durante os testes são relevantes para avaliar o desempenho dos participantes. Segundo a Tabela 04, todos os 3 participantes conseguiram concluir com sucesso o teste proposto, o que indica uma taxa de conclusão de 100%. Além disso, o tempo médio para concluir o teste foi de 3 minutos e 22 segundos, mostrando uma eficiência adequada na execução das tarefas, de acordo com o tempo estipulado de 5 minutos para finalizar o roteiro. É relevante destacar que nenhum dos usuários precisou de ajuda ou cometeu erros durante o teste.

#### TABELA 04: Resultados quantitativos obtidos após a conclusão de cada sessão de testes.
Descrição da Métrica | Resultado | 
--- | --- | 
Número de usuários que concluíram com sucesso o teste | 3 | 
Tempo médio para concluir o teste (hh/mm/ss) | 00:03:22 | 
Quantidade de usuários que pediram ajuda | 0 | 
Quantidade de usuários que cometeram erros no teste | 0 | 

Analisando os dados qualitativos dos testes de usabilidade realizados no dashboard, é possível identificar padrões e observações da experiência dos usuários. As informações detalhadas podem ser encontradas nas planilhas originais dos testes, disponíveis nos links abaixo, possibilitando consultas adicionais aos dados. Além disso, nos links das planilhas, há evidências em forma de fotos e vídeos que complementam as informações, fornecendo uma visão mais completa e detalhada dos testes realizados.

Link para os resultados qualitativos obtidos no teste do U01: https://docs.google.com/spreadsheets/d/1gSNU3ssyA783ijQ8NWyAAHGhXG8a4Y1uLq_KwL308EY/edit#gid=1383999259
Link para os resultados qualitativos obtidos no teste do U02: https://docs.google.com/spreadsheets/d/1gSNU3ssyA783ijQ8NWyAAHGhXG8a4Y1uLq_KwL308EY/edit#gid=727346428
Link para os resultados qualitativos obtidos no teste do U03: https://docs.google.com/spreadsheets/d/1gSNU3ssyA783ijQ8NWyAAHGhXG8a4Y1uLq_KwL308EY/edit#gid=1953320251

####  TABELA 05: Resultados qualitativos obtidos no teste U01.
Número | Categoria WCAG | Resultado |Observações | 
--- | --- | --- | --- |
1 | Operável | Feito |  Pouco esforço | 
2 | Compreensível | Feito | -    | 
3 | Robusto | Feito | Notou que a Planta Taubaté possui mais respostas da GPTW do que outras plantas. Observação: O usuário não entendeu que o título diz diretoria e o gráfico faz correlação entre plantas.    | 
4 | Perceptível | Feito | "Piorou a experiência ao aumentar o zoom" (U01). Porém mostrou que ficou incomodado pois quando a tela estava no seu tamanho "Normal" de 100%, o frontend ficava desajustado. Vídeo - https://drive.google.com/file/d/1eLjOkXP1DWFp_7A-mKZYfnzCmDjJ_1iB/view?usp=drive_link    | 


####  TABELA 06: Resultados qualitativos obtidos no teste U02.
Número | Categoria WCAG | Resultado |Observações | 
--- | --- | --- | --- |
1 | Operável | Feito |  Foi a única que entendeu que plantas seria em dois lugares | 
2 | Compreensível | Feito | Sem dificuldades     | 
3 | Robusto | Feito | Não foi fácil. Gráficos muito soltos e espalhados pelas telas.     | 
4 | Perceptível | Feito | "Não mudou muito" (U02). A experiência manteve a mesma     | 


####  TABELA 07: Resultados qualitativos obtidos no teste U03.
Número | Categoria WCAG | Resultado |Observações | 
--- | --- | --- | --- |
1 | Operável | Feito |  Sem dificuldades, conseguiu entender os rótulos da sidebar | 
2 | Compreensível | Feito | Teve dificuldades, principalmente pois a sidebar se mantém fixa em "dashboard" mesmo mudando para outra página. Vídeo = https://drive.google.com/file/d/1faFIIUPDOjzTbxQudyhxzA3zrrBfUUIB/view?usp=drive_link    | 
3 | Robusto | Feito | Não foi possível fazer correlações, apenas conseguiu fazer afirmações como qual planta teve maior nota e etc. Melhorar as cores das barras, deu a sugestão de não colocar cores vermelho, amarelo e verde pois podem enviesar, como vermelho uma nota ruim e assim por diante.    | 
4 | Perceptível | Feito | "Prejudicou . Gráficos, mesmo sem redimensionar estão desalinhados." (U03)     | 


Os resultados qualitativos dos testes (Tabela 05, Tabela 06 e Tabela 07) mostram que todos os participantes conseguiram acessar o dashboard com pouco esforço, porém há alguma dificuldade na compreensão das terminologias utilizadas, apontadas em alguns casos, o que não impediu os participantes de identificar as plantas de fábrica nos diferentes elementos da tela, concluindo esta etapa sem grandes obstáculos.

Isso pode ser um indicativo da necessidade de uma curva de aprendizado mais longa para familiarização dos termos específicos da área na utilização do sistema, como observado durante os testes U01 e U03.

No teste realizado com o U03, foi apontada uma desconexão entre as informações em diversos tópicos avaliados, onde com os participantes U01 e U02 isso foi percebido com as observações relacionadas à robustez. Os participantes enfrentaram desafios para fazer correlações entre as notas recebidas, sugerindo melhorias na apresentação das informações.

Quanto à perceptibilidade, a capacidade de redimensionar a tela para visualização detalhada dos gráficos prejudicou a experiência dos usuários, que notaram desalinhamentos nos ajustes de zoom, onde o U02 ponderou que a experiência se manteve a mesma.

Alguns trechos coletados durante a observação apontam a necessidade de ajustes no dashboard:

"Consegui compreender os componentes isoladamente, mas não percebi uma conexão entre eles juntos." (U01).

"[...] os dados mostrados fizeram sentido para mim, mas a diagramação do dashboard poderia ser diferente." (U02).

"Para mim as cores [dos gráficos] enviesou minha leitura [...] ." (U03).

"Mesmo sem redimensionar, vê como os gráficos estão desalinhados?." (U03).

Como observado no planejamento do roteiro do teste, e apontado por Wangenheim et al (2014), a necessidade de um pós-teste com os participantes, para avaliar aspectos subjetivos foi essencial para coletar maiores informações e feedbacks após a realização do roteiro proposto, onde os resultados podem ser observados na tabela 08.

####  TABELA 08: Resultados qualitativos obtidos no questionário de pós-teste com todos os participantes.
Pós-Teste | Resposta U01 | Resposta U02 | Resposta U03 | 
--- | --- | --- |--- |
Como você avalia a compreensão dos termos utilizados no dashboard? | Os termos da sidebar estão compreensíveis, porém os títulos dos componentes não se conectam com os títulos dos gráficos. | Ótimo | Os títulos dos componentes não se conectam com os títulos dos gráficos. |
Os cabeçalhos e rótulos facilitaram a identificação das informações em cada página? | Sim, como dito anteriormente, a sidebar e os títulos das páginas estão entendíveis, o que precisa melhorar é a localização dos gráficos. | Sim |Os textos anteriores aos títulos estão desconexos  |
As informações apresentadas no dashboard foram relacionadas aos tópicos abordados nos cabeçalhos e rótulos? | Não, pois os títulos não se conectam com as informações dos gráficos. | Sim, mas teve dificuldade para entender o motivo dos títulos dos gráficos |desconexos |
Você percebeu alguma sequência lógica na posição dos gráficos nas páginas? | Não. | Não, página em branco |Não. Melhorar a disposição dos gráficos. Ficou em dúvida o que era o "Trust index GPTW" |


### Considerações finais e propostas de melhorias:

Com base nos resultados quantitativos e qualitativos obtidos, juntamente com as observações diretas dos participantes, foi notado que a realização do teste de usabilidade remoto moderado com apenas três participantes evidenciou a necessidade de uma amostra maior para avaliações quantitativas mais robustas, já que uma amostra maior de participantes seria necessária para análises estatísticas significativas e generalizáveis, especialmente em relação a métricas quantitativas como taxas de conclusão, tempo médio de execução e ocorrência de erros. Devido ao número limitado de participantes, a ênfase do roteiro de testes foi direcionada principalmente para a análise qualitativa, permitindo uma compreensão mais aprofundada das experiências dos usuários, suas percepções, desafios e sugestões de melhoria.

Os resultados evidenciam uma necessidade de uma curva de aprendizado mais longa para familiarização dos termos específicos da área de saúde mental. Recomenda-se revisar a terminologia utilizada no sistema para torná-la mais clara e compreensível para os usuários, especialmente para aqueles que não estão familiarizados com os termos técnicos, não adicionando um impacto significativo, apenas necessitando de uma familiaridade com o sistema, durante a sua utilização para outras tarefas.

Isso ressalta também que o aspecto de usabilidade de facilidade de aprendizado foi atingido, com a ressalva de necessidade de um tempo um pouco maior de uso da solução para um melhor fluxo na utilização por parte do usuário, provavelmente devido ao outro aspecto de usabilidade, segundo Carvalho (2002), de facilidade de utilização da solução, que permitiu a navegação entre as páginas de forma efetiva, evidenciado no resultado quantitativo de que todos os participantes do teste concluíram todas as etapas.

Porém, no último aspecto, de satisfação do usuário, foi apresentado diversos problemas, representados nos critérios selecionados com base nas WCAGs, onde cada ponto pode ser verificado nos tópicos a seguir, onde a severidade foi apontada de acordo com o impacto na usabilidade do sistema foi percebido pelos avaliadores ou pelos participantes do teste, seguindo por sugestões e propostas de melhoria:

- Conexão entre Informações e Coerência na Apresentação (Severidade Média):

Foi observada uma desconexão entre as informações apresentadas em diferentes seções do dashboard, como ilustrado na figura 12 e figura 13, dificultando a correlação de dados pelos usuários, o que pode causar confusão e dificuldade na interpretação dos dados. Já a figura 14-A sugere a apresentação dos dados de maneira separada, e a figura 14-B realiza as correlações, colocando à prova a real necessidade de duas formas de apresentação dos dados, como explanado pelo U02. Embora não seja um problema crítico que, por exemplo, impeça a utilização do sistema pelo usuário, impacta negativamente na usabilidade e na experiência.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/testeu1.png">
</div>

Figura 12. Evidência onde o título do componente não está de acordo com o título do gráfico, levando a uma confusão da informação apresentada.



<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/testeu3-2.png">
</div>

Figura 13. Evidência que apresenta confusão sobre o nome utilizado para a informação apresentada, não relacionada com demais elementos da página

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/testeu2.png">
</div>

Figura 14. Evidência duas formas de apresentar a mesma informação, que levou a um problema de conexão na apresentação das informações, e falta de coerência nos dados apresentados. 


Sugere-se melhorar a apresentação das informações de forma mais coesa e organizada, reavaliando a organização e disposição dos gráficos apresentados nas páginas, seguindo princípios de design centrado no usuário e boas práticas de visualização de dados garantindo uma experiência de usuário mais integrada e facilitando a interpretação dos dados.

- Adaptabilidade e Flexibilidade do Sistema (Severidade Baixa):

A falta de customização e suporte para todos os tipos de daltonismo foram identificados como pontos de melhoria, pois não impactam significativamente a usabilidade para a maioria dos usuários. É importante corrigir esses pontos para melhorar a acessibilidade, mas não são problemas críticos que impeçam o uso do sistema.

Recomenda-se implementar recursos de personalização no sistema, permitindo que os usuários adaptem a interface de acordo com suas necessidades individuais. Além disso, é importante garantir uma paleta de cores acessível para usuários com daltonismo, seguindo as diretrizes de acessibilidade da WCAG.

- Perceptibilidade e Ajustes Visuais (Severidade Baixa a Média):

Os usuários relataram dificuldades ao redimensionar a tela para visualização detalhada dos gráficos, devido a desalinhamentos nos ajustes de zoom, que já podem ser evidenciados na proporção de 100% de redimencionamento, como mostado na figura 15, que representam um problema médio, pois podem afetar a experiência de usuários que dependem desse recurso. Os desalinhamentos nos ajustes de zoom podem causar confusão visual e prejudicar a interpretação dos dados, mas não são críticos para o uso geral do sistema.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/testeu3-3.png">
</div>

Figura 15. Evidência que representa tanto o desalinhamento dos gráficos, como falta de conexão entre os gráficos apresentados.


Propõe-se realizar ajustes visuais para garantir que os elementos da interface sejam responsivos e mantenham sua integridade visual em diferentes tamanhos de tela, proporcionando uma experiência de usuário consistente e sem distorções.

- Melhoria na Diagramação e Cores dos Gráficos (Severidade Baixa a Média):

Além da necessidade e melhorar a usabilidade com uma funcionalidade de redimensionamento, foram mencionadas sugestões para melhorar a diagramação do dashboard, por apresentarem componentes desalinhados, como evidenciado na figura 15, e também evitar enviesamentos na leitura devido às cores dos gráficos, possível notar na evidência da figura 16, que representam dificuldades que podem ser corrigidas com ajustes visuais e de design. Embora impactem na experiência de usuário, não são problemas críticos que impeçam o uso do sistema, mas contribuem para uma experiência mais agradável e intuitiva.

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/testeu3.png">
</div>

Figura 16. Evidência sobre a utilização de cores que podem confundir o usuário, onde o vermelho enviesa a um elemento negativo, verde um elemento positivo, etc.


Recomenda-se revisar a diagramação estrutural para tornar o dashboard mais intuitivo e fácil de realizar correlações entres os diferentes componentes, além de utilizar uma paleta de cores que não prejudique a interpretação dos dados, seguindo as boas práticas de design de interfaces.

## 13. Documentação Técnica

A documentação técnica fornece informações detalhadas sobre o funcionamento e implementação de sistemas e componentes. Importante para desenvolvedores, equipes de suporte e stakeholders compreenderem o sistema, facilitando a manutenção, solução de problemas e evolução do software ao longo do tempo.


   ### 13.1 Frontend Angular para Dashboard de Saúde Mental vs Indicadores de Engajamento

Inclui descrições detalhadas das funcionalidades e componentes presentes no código do dashboard. Isso abrange desde a estrutura de pastas e arquivos do front-end até as consultas e APIs utilizadas para obter e apresentar os dados no dashboard.

#### Introdução

O Dashboard de Saúde Mental vs Indicadores de Engajamento é uma ferramenta importante para empresas que desejam monitorar e melhorar a saúde mental de seus colaboradores, enquanto simultaneamente avaliam os indicadores de engajamento em cada área. Este documento descreve a arquitetura e os componentes do frontend Angular desenvolvido para esse propósito. <br>

Este projeto de frontend em Angular visa criar uma aplicação web dinâmica e robusta, que ofereça uma boa experiência do usuário. Ao aproveitar a arquitetura modular e orientada a componentes do Angular, pretendemos desenvolver uma aplicação escalável, de fácil manutenção e com alto desempenho.
Com o Angular, temos acesso a um conjunto abrangente de ferramentas e recursos que nos permitem criar interfaces de usuário sofisticadas, manipular dados de forma eficiente e integrar serviços externos de maneira transparente. Além disso, a estrutura de código organizada e as práticas recomendadas do Angular facilitam a colaboração entre membros da equipe e promovem um desenvolvimento ágil.

Neste projeto, exploraremos não apenas os recursos essenciais do Angular, como módulos, componentes, serviços e roteamento, mas também otimização de desempenho e integração com APIs, para a obtenção dos dados do cliente que serão coletados para gerar gráficos relevantes. Nosso objetivo é entregar uma aplicação que atenda às necessidades do usuário final, ou seja, a criação de um Dashboard de Saúde Mental vs Indicadores de Engajamento de forma completa.
Ao longo deste processo, estaremos comprometidos em seguir as melhores práticas de desenvolvimento, garantindo a qualidade do código, a acessibilidade e a compatibilidade com diversos dispositivos e navegadores. Além disso, estaremos abertos a feedbacks e ajustes contínuos, visando aprimorar constantemente a experiência do usuário e a eficiência do aplicativo.

## Desenvolvimento

### 1. Componentes Principais

#### a) Tela de Login
- Autenticação e Autorização
- Antes de acessar o Dashboard, os usuários serão direcionados para a página de login. A autenticação será realizada com base nas credenciais fornecidas pelo usuário. Após o login bem-sucedido, o sistema determinará o tipo de acesso do usuário de acordo com as regras de negócio estabelecidas. <br>

Atualmente, a nossa tela de Login está da seguinte maneira:

<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/tela_de_login.png">


**BP (Business Partner)**: visualizará informações mais gerais das áreas que supervisionam. <br>
**CEO**: terá uma visão geral de todos os dados. 

<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/Tela_BP_Front.png">

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/homologation/imagens/tela_de_login.png">
</div>

A tela de Login, possui: <br>
- **Formulário de Login**: os usuários fornecerão suas credenciais para acessar o sistema. <br>
- **Autenticação**: validação das credenciais do usuário para autenticação. <br>
- **Redirecionamento**: após a autenticação bem-sucedida, o usuário será redirecionado para a página inicial correspondente ao seu tipo de acesso. <br>

#### b) Menu
- O menu será o ponto central de navegação para diferentes seções do Dashboard.
- inclui links para diferentes telas, como: Dashboard, Plantas, Engajamento, em que cada uma delas possui os dados e gráficos referentes aquele assunto.

A parte de menu contem:
- **Navegação**: permite aos usuários acessar diferentes seções do Dashboard.

#### c) Navegação entre Telas de Dashboard
- A navegação entre as telas do Dashboard será facilitada pelo menu principal.
- Inclui botões de navegação rápida dentro das próprias telas para permitir uma experiência de usuário fluida.
- Há um roteamento que permite a transição suave entre as diferentes telas do Dashboard.
  
#### d) Tela Principal do Dashboard
- A tela principal exibirá um resumo dos principais indicadores de saúde mental e engajamento.
- Inclui gráficos de barras, gráficos de pizza ou outros tipos de visualizações para representar os dados de forma clara e concisa.
- Permite a personalização dos dados exibidos com base nas preferências do usuário, e também há opções de filtro.

Essa tela terá:
- **Visão Geral**: exibição dos principais indicadores de saúde mental e engajamento.
- **Gráficos e Dados**: apresentação de gráficos e dados relevantes para a análise.

<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/Tela_Dashboard_Front.png">
<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/Tela_Dashboard2_Front.png">
<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/Tela_Dashboard3_Front.png">

#### Tela de Plantas

#### e) Tela de Plantas

- A tela de Plantas fornecerá informações detalhadas sobre cada área ou departamento da empresa.
- Incluirá gráficos de tendências ao longo do tempo, comparações entre áreas e outras métricas relevantes.
- Permite a navegação fácil entre diferentes plantas ou áreas da empresa.

Essa tela terá:
- **Representação Visual**: gráficos e informações que fornecem uma representação visual das métricas de saúde mental e engajamento.
- **Interatividade**: possibilidade de interação para explorar os dados em detalhes.


<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/Tela_Plantas_Front.png">

#### Tela de Engajamento

<img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/feature/ajustes-telas-front-dados-API/imagens/Tela_Engajamento_Front.png">

<div style="text-align:center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-DASHBOARD/blob/homologation/imagens/tela_de_dashboard.png">
</div>


### 2. Funcionamento das Telas

- O usuário será direcionado inicialmente para a tela principal do Dashboard após o login.
- A partir da tela principal, o usuário poderá navegar para diferentes seções usando o menu principal.
- Cada tela terá sua própria funcionalidade específica e apresentará dados relevantes de maneira intuitiva.
- A navegação entre telas será fluida, permitindo que os usuários explorem os dados com facilidade.
- As telas serão responsivas, adaptando-se a diferentes dispositivos e tamanhos de tela para uma experiência consistente em todos os dispositivos.

## 3. Documentação: Dashboard em Produção com Pipeline de CI/CD e Testes Unitários
### Introdução

Esta documentação descreve a implementação de um Dashboard em produção utilizando Angular como frontend. O projeto foi configurado com um pipeline de CI/CD, testes unitários e monitoramento para garantir uma implantação confiável e um monitoramento eficiente em ambiente de produção.

### Ambiente de Produção
O Dashboard foi implantado em um ambiente de produção confiável, garantindo alta disponibilidade e performance. O acesso ao Dashboard está disponível para os usuários finais através de um URL específico. O usuário pode clonar o repositório do Github e executar os seguintes comandos pelo terminal:
- cd dashboard;
- cd src;
- npm install;
- ng serve;
Isso abrirá o frontend pelo: http://localhost:4200/

### Ferramenta de CI/CD: GitHub Actions
O pipeline de CI/CD foi configurado utilizando o GitHub Actions para automatizar as etapas de compilação, teste e implantação.

### Etapas do Pipeline
- **Compilação**: o código fonte do Dashboard é compilado para garantir que não existam erros de sintaxe ou de compilação.

- **Testes Unitários**: os testes unitários são executados automaticamente para validar as funcionalidades críticas do Dashboard.

- **Implantação**: após a compilação e os testes, o Dashboard é implantado no ambiente de produção.

- **Monitoramento**: configuração do monitoramento para acompanhar o desempenho e a disponibilidade do Dashboard em produção.

### Testes Unitários
Foram implementados testes unitários para o código do Dashboard, visando cobrir os aspectos críticos e garantir o funcionamento correto das funcionalidades.

### Execução Automática no Pipeline de CI/CD
Os testes unitários são executados automaticamente durante o pipeline de CI/CD, garantindo que qualquer alteração no código seja validada antes da implantação em produção.

### Gestão de Erros e Logs
Foram implementados mecanismos de tratamento de erros eficazes para lidar com situações inesperadas e garantir a estabilidade do Dashboard em produção.

### Registros (Logs)
Logs detalhados são gerados e armazenados para facilitar a depuração e o diagnóstico de problemas em produção. Os logs podem ser acessados e analisados para identificar e resolver eventuais falhas ou erros.

## 4. Conclusão

O Dashboard de Saúde Mental vs Indicadores de Engajamento terá o seu frontend desenvolvido em Angular para este projeto, e oferecerá uma interface intuitiva e funcionalidades relevantes para permitir uma análise eficaz dos dados e uma tomada de decisão informada por parte da empresa. Com componentes bem definidos e uma dinâmica de navegação projetada, o Dashboard oferecerá uma boa experiência de usuário, capacitando a empresa Volkswagen a priorizar a saúde mental de seus colaboradores e impulsionar o sucesso organizacional.

Desenvolver um frontend em Angular para um projeto de Dashboard oferece benefícios significativos, a estrutura do Angular permite uma organização eficiente do código, facilitando a manutenção e escalabilidade do sistema. Além disso, sua arquitetura baseada em componentes promove reutilização de código e modularidade, resultando em um desenvolvimento mais rápido e consistente. Por fim, a vasta comunidade e a abundância de recursos tornam o aprendizado e a implementação do Angular acessíveis, contribuindo para a construção de tela e Dashboards importantes e intuitivos.

Este projeto foi gerado com [Angular CLI](https://github.com/angular/angular-cli) versão 17.2.3.

## Como executar

### Servidor de desenvolvimento

Execute `ng serve` para um servidor de desenvolvimento. Navegue até `http://localhost:4200/`. O aplicativo será recarregado automaticamente se você alterar algum dos arquivos de origem.

### Andaime de código

Execute `ng generate component nome-do-componente` para gerar um novo componente. Também pode-se usar `ng generate directiva|pipe|service|class|guard|interface|enum|module`.

### Construir

Execute `ng build` para construir o projeto. Os artefatos de construção serão armazenados no diretório `dist/`.

### Executando testes unitários

Execute `ng test` para executar os testes de unidade via [Karma](https://karma-runner.github.io).

### Executando testes ponta a ponta

Execute `ng e2e` para executar os testes ponta a ponta através de uma plataforma de sua escolha. Para usar este comando, você precisa primeiro adicionar um pacote que implemente recursos de teste ponta a ponta.

### Mais ajuda

Para obter mais ajuda sobre o Angular CLI, use `ng help` ou confira a página [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Rodando o Projeto 

Para rodar o projeto, é necessário navegar até o diretório: C:\Users\Inteli\Documents\GitHub\2024-T0004-SI09-G05-DASHBOARD\dashboard\src> <br>
Para isso, digite primeiramente: **cd dashboard** e em seguida **cd src**. <br>

Após isso execute os seguintes comandos: <br>
- **npm install**
- **ng serve**

Em seguida, vá para o link: http://localhost:4200/


### 13.1.1 Deploy Frontend

Nesta etapa do processo de deploy, o objetivo é a implantação do frontend do sistema, que inclui o dashboard desenvolvido para visualização e interação com os dados, mas esse processo enfrenta desafios significativos. 

O Git Actions automatiza a integração contínua e a entrega contínua (CI/CD), agilizando a compilação do código-fonte e sua implantação nos ambientes de produção. Isso reduz erros humanos, acelera a introdução de novas funcionalidades e assegura que o software esteja sempre funcional e testado.

Ao utilizar o Render para o deploy, adiciona-se uma camada de eficiência ao processo. Render é uma plataforma de hospedagem que simplifica a implantação na nuvem, integrando-se diretamente com Git Actions e outras ferramentas de CI/CD.

Durante o processamento do deploy do frontend, foi realizado o checkout do repositório para garantir a sincronização correta das informações. Em seguida, as dependências foram restauradas utilizando o comando npm install para disponibilizar todas as bibliotecas necessárias para o processo de construção seguinte. A etapa principal consistiu na compilação do frontend, executando o comando ng build --configuration=production.

No processo de compilação, foram gerados os arquivos principais do frontend, incluindo os scripts e estilos necessários para o funcionamento adequado da aplicação. Apesar de alguns avisos sobre a compatibilidade de pacotes com o framework alvo, a compilação foi bem-sucedida, resultando em uma geração completa do bundle.

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/deploy_front2.png" alt="Untitled">
</div>

Figura: Diagrama das etapas realizadas para o deploy do Dashboard, com o status como Sucesso.

Observação: Após o dia 13 de abril de 2024, as máquinas que suportam o deploy serão desligadas, pois este deploy foi configurado como parte de um ambiente temporário para fins de aprendizado e demonstração do projeto finalizado. Isso significa que qualquer acesso ou funcionalidade relacionada ao deploy não estará mais disponível após essa data.
   
   ### 13.2 API de Integração 

A documentação técnica da API abrange a especificação dos endpoints, parâmetros de requisição, formatos de resposta, autenticação e autorização necessárias para interagir com a API. Além disso, inclui exemplos de uso, casos de teste e considerações de segurança. 

#### Introdução

Este projeto de API foi desenvolvido seguindo os princípios da Clean Architecture, visando a separação de interesses, a independência de frameworks e a facilidade de manutenção e testabilidade. A estrutura do projeto é organizada em camadas distintas, com a lógica de negócios centrada no domínio e os detalhes de implementação, como banco de dados e interfaces do usuário, mantidos externamente a essa camada central. Isso permite que a aplicação seja resiliente a mudanças, seja em tecnologias ou em regras de negócio.

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2024.png" alt="Untitled">
</div>


A seguir, detalhamos os aspectos mais significativos da nossa API, com foco em Autenticação, Gestão de Erros, Segurança, Logging e Versionamente.

### 13.2.1 Autenticação

A autenticação na nossa API é feita utilizando o número pessoal do empregado como identificador. O endpoint `/api/v1/auth/authenticate` espera um `POST` com um corpo JSON contendo o `N_pessoal`. Apenas empregados com cargos de 'PRESIDENTE EXECUTIVO' ou 'VICE-PRESIDENTE' receberão um token JWT que permite acesso a informações restritas.

**Exemplo de solicitação de autenticação:**

```json
POST /api/v1/auth/authenticate
Content-Type: application/json

{
  "N_pessoal": 123456
}
```

**Respostas possíveis:**

- **200 OK**: Autenticação bem-sucedida, incluindo um token JWT no corpo da resposta.
- **400 Bad Request**: Número pessoal não encontrado ou inválido.
- **401 Unauthorized**: Empregado não tem permissão (não é presidente ou vice-presidente).

**Exemplo de resposta para usuário autorizado:**

```json
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6..."
}

```

**Exemplo de resposta para usuário não autorizado:**

```json
{
  "message": "Acesso restrito ao presidente e vice-presidente."
}

```

### 13.2.2 Gestão de Erros

A API possui um mecanismo de gestão de erros que capta exceções não tratadas e retorna respostas padronizadas. O `ThrowController` é configurado para capturar e formatar essas exceções.

**Exemplos de mensagens de erro:**

- **Erro de servidor interno (500 Internal Server Error)**: "Ocorreu um erro ao obter empregados."
- **Recurso não encontrado (404 Not Found)**: "Nenhum empregado encontrado."

Em ambiente de desenvolvimento, a API fornece detalhes do stack trace para facilitar a depuração, enquanto em produção, esses detalhes são omitidos para segurança.

# 9. Dashboard Integrado com o Backend (V2)

# Dashboard - Versão 2

## Introdução

Neste artefato, apresentamos a segunda versão do Dashboard, que foi integrado com a API de Integração. O Dashboard foi desenvolvido seguindo os princípios de DRY (Don't Repeat Yourself), garantindo eficiência, coesão e reutilização de componentes. Abaixo detalhamos os principais aspectos desta versão.

## Interface do Dashboard Atualizada

A interface do Dashboard - Versão 2 foi atualizada para refletir os novos dados e funcionalidades da API V2. Esta nova interface inclui:

- **Gráficos Interativos:** Utilizamos a biblioteca NgApexcharts para criar gráficos interativos que exibem as métricas e informações relevantes. Por exemplo, o gráfico de barras exibe o número de colaboradores e atestados por planta.

```tsx
import { ChartComponent } from 'ng-apexcharts';

@Component({
  selector: 'app-plantas',
  templateUrl: './plantas.component.html',
  styleUrls: ['./plantas.component.css'],
})
export class PlantasComponent {
  @ViewChild('chart') chart!: ChartComponent;
  public chartOptions: Partial<ChartOptions>;

  constructor(private apiConnect: ApiconnectService) {
    this.chartOptions = {
      series: [],
      chart: {
        height: 350,
        width: 500,
        type: 'bar',
        zoom: {
          enabled: false,
        },
      },
      // outras configurações...
    };
  }

  ngOnInit() {
    this.apiConnect.getCid2023EmployeesCertificate().subscribe((response: HttpResponse<UnidadeResponse>) => {
      // processamento dos dados e atualização do gráfico...
    });
  }
}

```

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2025.png" alt="Untitled">
</div>


### Integração com API V2

O Dashboard - Versão 2 está integrado exclusivamente com a API de Integração V2 para obter os dados necessários. A integração foi realizada utilizando o serviço `ApiconnectService` para fazer solicitações HTTP à API V2 e recuperar os dados.

```tsx
@Injectable({
  providedIn: 'root'
})
export class ApiconnectService {
  BASE_URL = enviroment.apiUrl;
  constructor(private http: HttpClient) { }

  getCid2023EmployeesCertificate(): Observable<HttpResponse<UnidadeResponse>> {
    return this.http.get<UnidadeResponse>(`${this.BASE_URL}Cid/colaboradores-atestados-por-unidade`, { observe: 'response'});
  }
}

```

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2026.png" alt="Untitled">
</div>


## Princípio DRY

O princípio DRY foi aplicado de forma eficaz no código-fonte do Dashboard - Versão 2. As duplicações de código foram minimizadas e os componentes foram projetados para serem reutilizáveis. Por exemplo, na atualização dos dados do gráfico, evitamos repetir a lógica de processamento de dados.

```tsx
this.apiConnect.getCid2023EmployeesCertificate().subscribe((response: HttpResponse<UnidadeResponse>) => {
  // processamento dos dados e atualização do gráfico...
});

```

## Responsividade

O Dashboard - Versão 2 é responsivo e se adapta a diferentes tamanhos de tela e dispositivos. Isso foi alcançado utilizando técnicas de design responsivo e CSS flexível para garantir uma experiência consistente em todas as plataformas.

```css
/* Exemplo de estilo responsivo */
@media screen and (max-width: 600px) {
  .chart-container {
    width: 100%;
  }
}
```

## Performance

A performance do Dashboard - Versão 2 foi otimizada para garantir uma carga rápida e uma experiência fluida para o usuário. Isso inclui a minimização do tamanho dos recursos, a redução do número de solicitações de rede e o uso eficiente de cache sempre que possível.

```tsx
// Exemplo de cache de dados
@Injectable({
  providedIn: 'root'
})
export class CacheService {
  private cache = new Map<string, any>();

  constructor() { }

  get(key: string) {
    return this.cache.get(key);
  }

  set(key: string, value: any) {
    this.cache.set(key, value);
  }
}
```

## Conclusão

O Dashboard - Versão 2 representa um avanço significativo em relação à versão anterior, com melhorias na interface, integração com a API, aderência ao princípio DRY, responsividade e performance. Esperamos que esta versão atenda aos padrões de qualidade estabelecidos e proporcione uma experiência de usuário aprimorada.


# 11. Documentação Backend (Sprint 3)

### Documentação da API de Integração - Versão 2

Na construção do nosso backend temos a seguinte estrutura de pasta no Visual Studio Code 2022:

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2034.png" alt="Untitled">
</div>


1. **GitHub Actions**:

- Pasta que contém scripts e configurações relacionadas ao GitHub Actions para automação de fluxos de trabalho.

2. **Polo.Dashboard.WebApi**:

- Nome do projeto principal, onde estão organizados os arquivos relacionados a esse projeto específico.

3. **Connected Services**:

- Pasta que contém serviços conectados ao projeto, como APIs externas ou recursos de nuvem.

4. **Dependências**:

- Pasta que contêm referências e dependências externas do projeto, como bibliotecas ou pacotes de terceiros.

5. **Properties**:

- Essa pasta geralmente contém arquivos de configuração e definições relacionadas às propriedades do projeto.

6. **launchSettings.json**:

- Arquivo de configuração que contêm configurações de inicialização para o projeto, como perfis de depuração e ambientes.

7. **Application**:

- Pasta que contêm arquivos relacionados à lógica de aplicação do projeto.

8. **Services**:

- Pasta que contêm classes de serviços ou componentes que fornecem funcionalidades específicas para o projeto.

9. **SwaggerConfig**:

- Pasta que contém configurações relacionadas à documentação de API usando Swagger.

10. **Controllers**:

- Pasta que contêm os controladores do projeto, que são responsáveis por lidar com as solicitações HTTP e fornecer respostas apropriadas.

11. **v1** e **v2**:

- Versões dos controladores. Cada versão pode conter controladores diferentes ou variações de implementações.

12. **Domain**:

- Contêm arquivos relacionados ao domínio do projeto, como entidades de negócios e lógica de domínio.

13. **DTOs**:

- Abreviação para "Data Transfer Objects". Nessa pasta há classes que são usadas para transferir dados entre subsistemas do projeto.

14. **Model**:

- Contêm classes que representam modelos de dados usados no projeto.

15. **Infraestrutura**:

- Pasta que contém arquivos relacionados à infraestrutura do projeto, como configurações de banco de dados e integrações externas.

16. **Repositories**:

- Pasta que contêm classes que implementam a lógica de acesso a dados, como operações de leitura/gravação no banco de dados.

17. **ConnectionContext.cs**:

- Arquivo de código-fonte que contêm a implementação de um contexto de conexão usado para interagir com o banco de dados.

18. **appsettings.json** e **Dockerfile**:

- Arquivos de configuração para o projeto, contendo configurações de aplicativo e definições de contêiner Docker, respectivamente.

### Descrição

Esta é a segunda versão da API de integração, desenvolvida para incluir comunicação com o Dashboard - Versão 2. Com o objetivo de oferecer uma experiência mais avançada e funcionalidades adicionais, esta versão inclui novos serviços de feature para tratamento e manipulação de dados do frontend. Esses recursos foram projetados para permitir uma interação mais sofisticada com o dashboard, proporcionando aos usuários uma visão mais abrangente e insights mais profundos.

### Estrutura da API

A API consiste em endpoints cuidadosamente projetados para fornecer acesso aos recursos necessários tanto para a integração com o Dashboard - Versão 2 quanto para a manipulação avançada de dados do frontend. Cada endpoint é documentado detalhadamente, especificando sua descrição, parâmetros de consulta, autenticação necessária, formato de resposta e exemplos ilustrativos.

### Endpoints

### 1. Gptw

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2035.png" alt="Untitled">
</div>


- **Descrição:** Fornece acesso aos dados do GPTW.
- **Endpoints:**

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2036.png" alt="Untitled">
</div>


1. **GET /api/v1/gptw**: Retorna todos os dados do GPTW.
    - **Parâmetros de consulta:** Nenhum.
    - **Autenticação:** Requer autenticação com o papel "PresidenteFuncionarioPolicy".
    - **Formato de resposta:** JSON.
    - **Exemplo de resposta:**
        
        ```json
        [
            {
                "nniveis": "value",
                "uo_abrev": "value",
                "rrh": "value",
                "local": "value",
                "empr": "value",
                "gremp": "value",
                "grpempregados": "value",
                "sgemp": "value",
                "centrocst": "value",
                "unidorg": "value",
                "descr_uo": "value",
                "idadedoempregado": "value",
                "gn": "value",
                "data_adm": "value"
            }
        ]
        
        ```
        

1. **GET /api/v1/Gptw/gptw-quantidaderespostas**: Retorna os dados de quantidade de respostas na GPTW por unidade.

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/1854ec91-0119-4f08-aec1-9b7580571a89.png)

1. **GET /api/v1/Gptw/engajamento**: Retorna a porcentagem sobre como está o engajamento da empresa na pesquisa GPTW.

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2037.png" alt="Untitled">
</div>


### 2. Empregado

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2038.png" alt="Untitled">
</div>

- **Descrição:** Fornece acesso aos dados dos empregados.
- **Endpoints:**
    
<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2039.png" alt="Untitled">
</div>
    

1. **GET /api/v1/Empregado**: Retorna todos os dados dos empregados.
    - **Parâmetros de consulta:** Nenhum.
    - **Autenticação:** Requer autenticação com os papéis "PRESIDENTE EXECUTIVO" ou "VICE-PRESIDENTE".
    - **Formato de resposta:** JSON.
    - **Exemplo de resposta:**
        
        ```json
        [
            {
                "n_pessoal": "value",
                "sg_emp": "value",
                "texto_rh": "value",
                "centro_cst": "value",
                "centro_custo": "value",
                "cargo": "value",
                "data_nascimento": "value"
            }
        ]
        
        ```
        

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/73758aae-94cf-4829-b7ee-27934f0987c3.png)

1. **GET /api/v1/Empregado/seg**: Retorna os dados sobre os segmentos dos empregados e também a quantidade.

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2040.png" alt="Untitled">
</div>

### 3. Cid2023

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2041.png" alt="Untitled">
</div>


- **Descrição:** Fornece acesso aos dados do CID2023.
- **Endpoints:**

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2042.png" alt="Untitled">
</div>


1. **GET /api/v1/Cid**: Retorna todos os dados do CID2023.
    - **Descrição**: os dados do CID2023 são referentes aos dados dos colaboradores como: quantidade de atestados, diretoria e planta.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:** Requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**
            
            ```json
            [
                {
                    "mes": "value",
                    "atestados": "value",
                    "cid": "value",
                    "descricao": "value",
                    "dias": "value",
                    "diretoria": "value",
                    "unidade": "value"
                }
            ]
            ```

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2043.png" alt="Untitled">
</div>
            

1. **GET /api/v1/Cid/colaboradores-atestados-por-unidade**: Retorna os dados sobre a quantidade de atestados dos colaboradores por planta.
    - **Descrição:** Retorna um dicionário contendo informações sobre o número de colaboradores e atestados por unidade.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:** Requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2044.png" alt="Untitled">
</div>


1. **GET /api/v1/Cid/certo-total**: Retorna os dados sobre o total de atestados por mês e por unidade.

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2045.png" alt="Untitled">
</div>

### 4. Stiba

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2048.png" alt="Untitled">
</div>

- **Descrição:** Notas da pesquisa Stiba
- **Endpoints:**
    
<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2049.png" alt="Untitled">
</div>
    
1. **GET /api/v1/Stiba**: 
    - Descrição: Todos os valores do Stiba.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:** Não requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**
            
            ```json
                {
                    "descricaoUO": "value",
                    "elegiveis": "value",
                    "particip": "value",
                    "notaStiba": "value"
                }
            ```
            

1. **GET /api/v1/media-nota**: 
    - Descrição: Média total das notas Stiba.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:** Não requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**
        
        ```json
        "value"
        ```
        
2. **GET /api/v1/media-local**: 
    - Descrição: Média das notas das plantas.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:** Não requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**
        
        ```json
            {
                "sigla_UO": "value",
                "average_nota_stiba": "value"
            }
        ```
        
3. **GET /api/v1/engajamento-local**: 
    - Descrição: Engajamento dos colaboradores à pesquisa Stiba entre as plantas.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:**  Não requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**
        
        ```json
            {
                "sigla_UO": "value",
                "average_engajamento": "value",
                "std_engajamento": "value"
            }
        ```
        
4. **GET /api/v1/engajamento-total**: 
    - Descrição: Engajamento total dos colaboradores à pesquisa Stiba.
        - **Parâmetros de consulta:** Nenhum.
        - **Autenticação:** Não requer autenticação.
        - **Formato de resposta:** JSON.
        - **Exemplo de resposta:**
        
        ```json
            {
                "avg": "value"
            }
        ```
        

### 5. Join

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2050.png" alt="Untitled">
</div>

- **Descrição:** Retorna os dados sobre mês, departamento, total de sessões, cargo, gênero, quantidade de atestados e a descrição detalhada por colaborador.
- **Endpoints:**

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2051.png" alt="Untitled">
</div>

1. **GET /api/v1/Join/join-data**:

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2052.png" alt="Untitled">
</div>

### 3.1 Testes

### 3.1.1 Pasta de testes Cid 2023

### 3.1.1.1 Introdução

A pasta possui um conjunto de testes que garantem a qualidade, confiabilidade e integridade do código. Esses testes abrangem desde a autenticação de usuários até o funcionamento correto do controlador e do repositório. 

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2046.png" alt="Untitled">
</div>


### 3.1.1.2 Estrutura de arquivos

- **`AuthenticateAsyncV2.cs`**: Este arquivo contém testes para a autenticação de usuários na API. Ele verifica se a autenticação funciona corretamente em diferentes cenários, como quando o usuário não é encontrado no banco de dados.

```csharp
using Xunit;
using Moq;
using Polo.Dashboard.WebApi.Controllers.v2;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;
using Polo.Dashboard.WebApi.Domain.DTOs;
using Microsoft.AspNetCore.Mvc;
using System.Threading.Tasks;
using System.Collections.Generic;

namespace Polo.Dashboard.WebApi.Tests
{
    public class AuthControllerTests
    {
        [Fact(DisplayName = "AuthenticateAsync returns BadRequest when user is not found")]
        public async Task AuthenticateAsync_ReturnsBadRequest_WhenUserNotFound()
        {
            // Arrange
            var mockEmpregadosRepository = new Mock<IEmpregadosRepository>();
            mockEmpregadosRepository.Setup(repo => repo.GetAsync()).ReturnsAsync(new List<EmpregadoDTO>());

            var mockRoleService = new Mock<IRoleService>();

            var controller = new AuthController(mockEmpregadosRepository.Object, mockRoleService.Object);

            // Act
            var result = await controller.AuthenticateAsync(new AuthenticateRequestDTO { N_pessoal = 999 });
            var badRequestResult = result as BadRequestObjectResult;

            // Assert
            Assert.NotNull(badRequestResult);
            Assert.Equal(400, badRequestResult?.StatusCode);
        }

        // ... outros testes ...
    }
}

```

- **`Cid2023ControllerTests.cs`**: Aqui estão os testes para o **`Cid2023Controller`**, verificando se ele lida corretamente com diferentes cenários de requisição. Os testes aqui garantem que o controlador responda corretamente a diferentes situações, como quando nenhum CID2023 é encontrado ou quando ocorre um erro ao recuperar os dados.

```csharp
using Xunit;
using Microsoft.Extensions.Logging;
using Moq;
using Polo.Dashboard.WebApi.Controllers.v1;
using Polo.Dashboard.WebApi.Domain.DTOs;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;
using Microsoft.AspNetCore.Mvc;
using AutoMapper;
using System.Collections.Generic;
using System.Threading.Tasks;

namespace Polo.Dashboard.WebApi.Tests.Cid2023
{
    public class Cid2023ControllerTests
    {
        [Fact(DisplayName = "Given empty Cid2023 list, should return NotFound")]
        public async Task GetAsync_ShouldReturnNotFound_WhenNoCid2023Found()
        {
            // Arrange
            var mockRepository = new Mock<ICid2023Repository>();
            mockRepository.Setup(repo => repo.GetAsync()).ReturnsAsync(new List<Cid2023DTO>());

            var mockLogger = new Mock<ILogger<Cid2023Controller>>();
            var mockMapper = new Mock<IMapper>();

            var controller = new Cid2023Controller(mockRepository.Object, mockLogger.Object, mockMapper.Object);

            // Act
            var result = await controller.GetAsync();

            // Assert
            var notFoundResult = Assert.IsType<NotFoundObjectResult>(result);
            Assert.Equal("Nenhum cid2023 encontrado.", notFoundResult.Value);
        }

        [Fact(DisplayName = "Given an error in retrieving Cid2023, should return StatusCode 500")]
        public async Task GetAsync_ShouldReturnStatusCode500_WhenErrorOccurs()
        {
            // Arrange
            var mockRepository = new Mock<ICid2023Repository>();
            mockRepository.Setup(repo => repo.GetAsync()).ThrowsAsync(new Exception("Test exception"));

            var mockLogger = new Mock<ILogger<Cid2023Controller>>();
            var mockMapper = new Mock<IMapper>();

            var controller = new Cid2023Controller(mockRepository.Object, mockLogger.Object, mockMapper.Object);

            // Act
            var result = await controller.GetAsync();

            // Assert
            var statusCodeResult = Assert.IsType<ObjectResult>(result);
            Assert.Equal(500, statusCodeResult.StatusCode);
        }
    }
}
```

- **`Cid2023RepositoryMock.cs`**: Fornece um mock do repositório do CID2023 para uso nos testes. Ele simula o comportamento do repositório real, permitindo que os testes sejam executados de forma isolada e previsível. Este arquivo é essencial para criar um ambiente controlado nos testes, garantindo que as interações com o repositório sejam consistentes e previsíveis, independentemente do estado atual dos dados.

```csharp
using Moq;
using Polo.Dashboard.WebApi.Domain.DTOs;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;
using System.Collections.Generic;
using System.Threading.Tasks;

public class Cid2023RepositoryMock
{
    public static Mock<ICid2023Repository> GetCid202
```

- **`Cid2023RepositoryTests.cs`**: Testes para garantir que o repositório do CID2023 funcione conforme o esperado em diferentes situações. Isso inclui testes para verificar se os dados são retornados corretamente e se o repositório lida adequadamente com erros.

```csharp
**using Xunit;
using Polo.Dashboard.WebApi.Domain.DTOs;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;
using System.Collections.Generic;
using System.Threading.Tasks;

namespace Polo.Dashboard.WebApi.Tests.Cid2023
{
    public class Cid2023RepositoryTests
    {
        [Fact(DisplayName = "Given valid Cid2023 list, should return it and greater than zero")]
        public async Task GetAsync_ShouldReturnListOfCid2023()
        {
            // Arrange
            var mockRepository = Cid2023RepositoryMock.GetCid2023Repository();
            var cid2023Repository = mockRepository.Object;

            // Act
            var result = await cid2023Repository.GetAsync();

            // Assert
            Assert.NotNull(result);
            Assert.IsType<List<Cid2023DTO>>(result);
            Assert.True(result.Count > 0);
        }
    }
}**
```

### 3.1.2 Pasta de Testes Empregados

### 3.1.2.1 Introdução

Os arquivos abaixo fazem parte de um conjunto de testes relacionados à gestão dos dados dos colaboradores. Partindo da autenticação de usuários até a interação com o repositório de empregados e o funcionamento do controlador de empregados. 

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2047.png" alt="Untitled">
</div>

### 3.1.1.2 Estrutura de arquivos

- **`AuthenticateAsync.cs`**: Este arquivo contém testes para a autenticação de usuários na API. Ele verifica se a autenticação funciona corretamente em diferentes cenários, como quando o usuário não é encontrado no banco de dados. O teste específico verifica se um BadRequest é retornado quando o usuário não é encontrado.

```csharp
using Microsoft.AspNetCore.Mvc;
using Moq;
using Polo.Dashboard.WebApi.Controllers.v1;
using Polo.Dashboard.WebApi.Domain.DTOs;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;
using Polo.Dashboard.WebApi.Application.Services;
using System.Collections.Generic;
using System.Threading.Tasks;
using Xunit;
using Polo.Dashboard.WebApi.Controllers.v2;

namespace Polo.Dashboard.WebApi.Tests.Empregados
{
    public class AuthControllerTests
    {
        [Fact(DisplayName = "Given an employee number and role, return UserNotFound ")]
        public async Task AuthenticateAsync_ReturnsBadRequest_WhenUserNotFound()
        {
            // Arrange
            var mockRepo = new Mock<IEmpregadosRepository>();
            var mockRoleService = new Mock<IRoleService>();

            mockRepo.Setup(repo => repo.GetAsync()).ReturnsAsync(new List<EmpregadoDTO>());

            var controller = new AuthController(mockRepo.Object, mockRoleService.Object);

            // Act
            var result = await controller.AuthenticateAsync(new AuthenticateRequestDTO { N_pessoal = 1 });

            // Assert
            Assert.IsType<BadRequestObjectResult>(result);
        }

    }
}

```

- **`EmpregadosRepositoryMock.cs`**: Este arquivo fornece um mock do repositório de empregados para uso nos testes. Ele simula o comportamento do repositório real, permitindo que os testes sejam executados de forma isolada e previsível. Os dados de empregados são criados para simular interações com o repositório.

```csharp
using Moq;
using Polo.Dashboard.WebApi.Domain.DTOs;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;

public class EmpregadosRepositoryMock
{
    public static Mock<IEmpregadosRepository> GetEmpregadosRepository()
    {
        var mockRepository = new Mock<IEmpregadosRepository>();
        var empregados = new List<EmpregadoDTO>
        {
            new EmpregadoDTO
            {
                n_pessoal = 0,
                sg_emp = "EX",
                texto_rh = "EX",
                centro_cst = 1222,
                centro_custo = "EX",
                cargo = "EX",
                data_nascimento = "01/01/2001"
            },
            new EmpregadoDTO
            {
                n_pessoal = 1,
                sg_emp = "EX2",
                texto_rh = "EX2",
                centro_cst = 33333,
                centro_custo = "EX2",
                cargo = "EX2",
                data_nascimento = "01/01/2002"
            }
        };

        mockRepository.Setup(r => r.GetAsync()).ReturnsAsync(empregados);

        return mockRepository;
    }
}
```

- **`EmpregadosRepositoryTests.cs`**: Aqui estão os testes para o repositório de empregados, garantindo que ele funcione conforme o esperado em diferentes situações. Isso inclui testes para verificar se os dados são retornados corretamente e se o repositório lida adequadamente com erros.

```csharp
**using Polo.Dashboard.WebApi.Domain.DTOs;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Polo.Dashboard.WebApi.Tests.Empregados
{
    public class EmpregadosRepositoryTests
    {
        [Fact(DisplayName = "Given valid Employee list, should return it and greater than zero" )]
        public async Task GetAsync_ShouldReturnListOfEmpregados()
        {
            // Arrange
            var mockRepository = EmpregadosRepositoryMock.GetEmpregadosRepository();
            var empregadosRepository = mockRepository.Object;

            // Act
            var result = await empregadosRepository.GetAsync();

            // Assert
            Assert.NotNull(result);
            Assert.IsType<List<EmpregadoDTO>>(result);
            Assert.True(result.Count > 0);
        }
    }
}**

```

- **`EmpregadosTests.cs`**: Este arquivo contém testes para a classe de modelo de empregados. Ele verifica se a criação de um objeto empregado atribui corretamente os valores às propriedades

```csharp
using Xunit;
using Polo.Dashboard.WebApi.Domain.Model;

namespace Polo.Dashboard.WebApi.Tests.Empregados
{
    public class EmpregadosTests
    {
        [Fact(DisplayName = "Given an employee atributes, then should create an employee")]
        public void Empregado_Constructor_ShouldSetProperties()
        {
            // Arrange
            int n_pessoal = 12345;
            string sg_emp = "ABC";
            string texto_rh = "Texto RH";
            int centro_cst = 6789;
            string centro_custo = "Centro Custo";
            string cargo = "Cargo";
            string data_nascimento = "01/01/1980";

            // Act
            var empregado = new Domain.Model.Empregados(n_pessoal, sg_emp, texto_rh, centro_cst, centro_custo, cargo, data_nascimento);

            // Assert
            Assert.Equal(n_pessoal, empregado.n_pessoal);
            Assert.Equal(sg_emp, empregado.sg_emp);
            Assert.Equal(texto_rh, empregado.texto_rh);
            Assert.Equal(centro_cst, empregado.centro_cst);
            Assert.Equal(centro_custo, empregado.centro_custo);
            Assert.Equal(cargo, empregado.cargo);
            Assert.Equal(data_nascimento, empregado.data_nascimento);
        }
    }
}
```

- **`GetAsync.cs`**: Este arquivo contém testes para o controlador de empregados, especificamente para o método GetAsync. Ele verifica se o método retorna um resultado Ok com a lista de empregados quando chamado. As dependências são simuladas usando mocks.

```csharp
**using Xunit;
using Moq;
using Microsoft.AspNetCore.Mvc;
using Polo.Dashboard.WebApi.Controllers.v1;
using Polo.Dashboard.WebApi.Domain.Model.Interfaces;
using Polo.Dashboard.WebApi.Domain.DTOs;
using System.Collections.Generic;
using System.Threading.Tasks;
using AutoMapper;
using Microsoft.Extensions.Logging;

namespace Polo.Dashboard.WebApi.Tests.Empregados
{
    public class EmpregadoControllerTests
    {
        [Fact]
        public async Task GetAsync_ReturnsOkResult_WithEmpregados()
        {
            // Arrange
            var mockRepository = new Mock<IEmpregadosRepository>();
            var empregadosDTOList = new List<EmpregadoDTO>
            {
                new EmpregadoDTO
                {
                    n_pessoal = 1,
                    sg_emp = "XXX",
                    texto_rh = "XXX",
                    centro_cst = 1,
                    centro_custo = "XXX",
                    cargo = "XXX",
                    data_nascimento = "XXX"
                },
                new EmpregadoDTO
                {
                    n_pessoal = 2,
                    sg_emp = "YYY",
                    texto_rh = "YYY",
                    centro_cst = 2,
                    centro_custo = "YYY",
                    cargo = "YYY",
                    data_nascimento = "YYY"
                }
            };

            mockRepository.Setup(repo => repo.GetAsync()).ReturnsAsync(empregadosDTOList);

            var mockMapper = new Mock<IMapper>();
            mockMapper.Setup(mapper => mapper.Map<List<EmpregadoDTO>>(It.IsAny<List<EmpregadoDTO>>()))
                .Returns((List<EmpregadoDTO> source) => source);

            var mockLogger = new Mock<ILogger<EmpregadoController>>();
            var controller = new EmpregadoController(mockRepository.Object, mockLogger.Object, mockMapper.Object);

            // Act
            var result = await controller.GetAsync();

            // Assert
            var actionResult = Assert.IsType<OkObjectResult>(result);
            var returnValue = Assert.IsType<List<EmpregadoDTO>>(actionResult.Value);
            Assert.NotEmpty(returnValue);
        }
    }
}**
```

### Controllers

### 1. GPTWController.cs

O **`GptwController`** é um controlador ASP.NET Core responsável por lidar com as requisições relacionadas aos dados GPTW (Great Place to Work) através de uma API REST. Este controlador expõe endpoints para obter informações sobre GPTW, quantidades de respostas locais e engajamento.

**Atributos do Controlador**

- **`[Route("api/v{version:apiVersion}/[controller]")]`**: define o padrão de rota para o controlador, incluindo uma versão da API.
- **`[ApiController]`**: indica que o controlador é uma API.
- **`[ApiVersion("1.0")]`**: especifica a versão da API que este controlador suporta.

**Métodos do Controlador**

### 1. **`GetAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém uma lista de GPTW.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/gptw`**

**Comportamento:**

- O método recupera os dados do repositório.
- Os dados são mapeados para DTOs usando o AutoMapper.
- Se nenhum GPTW for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

### 2. **`GetLocalCountsAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém a contagem de GPTW por local.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/gptw/gptw-quantidaderespostas`**

**Comportamento:**

- O método recupera a contagem de GPTW por local do repositório.
- Se nenhuma contagem for encontrada, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

### 3. **`GetEngajamentoAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém os dados de engajamento relacionados ao GPTW.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/gptw/engajamento`**

**Comportamento:**

- O método recupera os dados de engajamento do repositório.
- Se nenhum dado de engajamento for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

**Logging**

O controlador utiliza o **`ILogger`** para registrar informações, avisos e erros durante a execução dos métodos. Isso ajuda a monitorar e diagnosticar problemas na aplicação.

**Tratamento de Erros**

Todos os métodos do controlador têm um bloco **`try-catch`** para capturar exceções. Em caso de erro, é retornado um status 500 (Internal Server Error) junto com uma mensagem de erro genérica.

### 2. Cid2023Controller.cs

O **`Cid2023Controller`** é um controlador ASP.NET Core responsável por lidar com as requisições relacionadas aos dados CID 2023 através de uma API REST. Utiliza a versão 1.0 da API e expõe endpoints para obter informações sobre CID 2023, colaboradores e atestados por unidade, e o total de atestados.

**Atributos do Controlador**

- **`[Route("api/v{version:apiVersion}/[controller]")]`**: Define o padrão de rota para o controlador, incluindo uma versão da API.
- **`[ApiController]`**: Indica que o controlador é uma API.

**Métodos do Controlador**

### 1. **`GetAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém uma lista de CID 2023.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/cid2023`**

**Comportamento:**

- O método recupera os dados do repositório.
- Os dados são mapeados para DTOs usando o AutoMapper.
- Se nenhum CID 2023 for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

### 2. **`GetColaboradoresAtestadosPorUnidadeAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém informações de colaboradores e atestados por unidade.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/cid2023/colaboradores-atestados-por-unidade`**

**Comportamento:**

- O método recupera as informações de colaboradores e atestados por unidade do repositório.
- Se nenhuma informação for encontrada, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

### 3. **`GetCertoTotalAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém o total de atestados.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/cid2023/certo-total`**

**Comportamento:**

- O método recupera o total de atestados do repositório.
- Se nenhum total de atestados for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

**Logging**

O controlador utiliza o **`ILogger`** para registrar informações, avisos e erros durante a execução dos métodos. Isso ajuda a monitorar e diagnosticar problemas na aplicação.

**Tratamento de Erros**

Todos os métodos do controlador têm um bloco **`try-catch`** para capturar exceções. Em caso de erro, é retornado um status 500 (Internal Server Error) junto com uma mensagem de erro genérica.

### 3. EmpregadoController.cs

O **`EmpregadoController`** é um controlador ASP.NET Core responsável por lidar com as requisições relacionadas aos dados de empregados através de uma API REST. Expõe endpoints para obter informações sobre empregados e dados de segmentação.

**Métodos do Controlador**

### 1. **`GetAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém uma lista de empregados.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/empregado`**

**Comportamento:**

- O método recupera os dados do repositório.
- Os dados são mapeados para DTOs usando o AutoMapper.
- Se nenhum empregado for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

### 2. **`GetSegAsync()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém dados de segmentação.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/empregado/seg`**

**Comportamento:**

- O método recupera os dados de segmentação do repositório.
- Se nenhum dado de segmentação for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

**Logging**

O controlador utiliza o **`ILogger`** para registrar informações, avisos e erros durante a execução dos métodos. Isso ajuda a monitorar e diagnosticar problemas na aplicação.

**Tratamento de Erros**

Todos os métodos do controlador têm um bloco **`try-catch`** para capturar exceções. Em caso de erro, é retornado um status 500 (Internal Server Error) junto com uma mensagem de erro genérica.

### 4. JoinController.cs

É um controlador ASP.NET Core responsável por lidar com as requisições relacionadas aos dados de "join" através de uma API REST. Este controlado expõe um endpoint para obter informações de mês, departamento, total de sessões, cargo, gênero, descrição detalhada e quantidade de atestados por colaborador.

**Métodos do Controlador**

### 1. **`GetJoinData()`**

- **Tipo**: **`HttpGet`**
- **Descrição**: Obtém dados de "join": mês, departamento, total de sessões, cargo, gênero, descrição detalhada e quantidade de atestados por colaborador.
- **Retorno**: **`Task<IActionResult>`**
- **Endpoints**: **`/api/v1.0/join/join-data`**

**Comportamento:**

- O método recupera os dados do repositório.
- Os dados são mapeados para DTOs usando o AutoMapper.
- Se nenhum dado de "join" for encontrado, retorna um status 404 (Not Found).
- Se ocorrer um erro, retorna um status 500 (Internal Server Error).

**Logging**

O controlador utiliza o **`ILogger`** para registrar informações, avisos e erros durante a execução dos métodos. Isso ajuda a monitorar e diagnosticar problemas na aplicação.

**Tratamento de Erros**

O método do controlador tem um bloco **`try-catch`** para capturar exceções. Em caso de erro, é retornado um status 500 (Internal Server Error) junto com uma mensagem de erro genérica.

### 5. StibaController.cs

O **`StibaController`** é um controlador da API responsável por lidar com operações relacionadas aos dados do Stiba. Ele permite a obtenção de dados do Stiba, cálculo da média de notas, obtenção da média por local e obtenção do engajamento por local e total.

- Este controlador utiliza a injeção de dependência para obter o repositório do Stiba, o logger e o mapeador.
- Os métodos retornam os resultados em formato JSON.
- Caso ocorram erros durante as operações, o controlador retorna códigos de status e mensagens de erro.

Possui os seguintes métodos:

1. **GET /api/v{version}/stiba**
    - Descrição: Obtém todos os dados do Stiba.
    - Resposta:
        - 200 OK: Retorna a lista de dados do Stiba.
        - 404 Not Found: Caso não haja dados do Stiba disponíveis.
2. **GET /api/v{version}/stiba/media-nota**
    - Descrição: Calcula a média das notas do Stiba.
    - Resposta:
        - 200 OK: Retorna a média arredondada das notas.
        - 500 Internal Server Error: Em caso de erro ao calcular a média.
3. **GET /api/v{version}/stiba/media-local**
    - Descrição: Obtém a média por local no Stiba.
    - Resposta:
        - 200 OK: Retorna a média por local.
        - 500 Internal Server Error: Em caso de erro ao obter a média por local.
4. **GET /api/v{version}/stiba/engajamento-local**
    - Descrição: Obtém o engajamento por local no Stiba.
    - Resposta:
        - 200 OK: Retorna o engajamento por local.
        - 500 Internal Server Error: Em caso de erro ao obter o engajamento por local.
5. **GET /api/v{version}/stiba/engajamento-total**
    - Descrição: Obtém o engajamento total no Stiba.
    - Resposta:
        - 200 OK: Retorna o engajamento total.
        - 500 Internal Server Error: Em caso de erro ao obter o engajamento total.

### Integração com Dashboard V2

 A API de integração se comunica com o Dashboard - Versão 2 por meio dos endpoints fornecidos acima. Os dados são transmitidos em formato JSON para garantir uma comunicação eficiente entre os sistemas.

### Serviços de Feature

Foram adicionados novos serviços de feature para tratamento e manipulação avançada de dados pelo frontend. Esses serviços permitem uma interação mais sofisticada com o dashboard e incluem:

- **Recursos avançados de manipulação de dados:** Permitindo a realização de operações complexas nos dados fornecidos pela API.
- **Recursos de consulta avançada:** Permitindo a recuperação de dados com base em critérios específicos definidos pelo usuário.

### Estrutura de Dados Atualizada

As estruturas de dados (JSON) utilizadas para a entrada e saída da API foram atualizadas para incluir os novos recursos adicionados. Isso garante a consistência e a compatibilidade dos dados transmitidos entre a API e o Dashboard - Versão 2.

### Autenticação e Autorização

A API utiliza o esquema de autenticação JWT (JSON Web Token) para autenticar os usuários e autorizar o acesso aos recursos. Além disso, foram adicionadas políticas de autorização para garantir que apenas usuários autorizados possam acessar determinados endpoints.

### Gestão de Erros

A API continua a fornecer mensagens de erro informativas e orientações claras para solucionar problemas. Foram adicionados novos cenários relacionados aos feature services para garantir um tratamento adequado de erros e status codes. 

A API é capaz de identificar e comunicar erros específicos que podem ocorrer durante a execução. Cada tipo de erro é claramente identificado e acompanhado por uma mensagem adequada. Além disso, são utilizados os códigos de status HTTP apropriados para indicar o resultado da requisição, proporcionando uma compreensão rápida do estado da operação. Além do código de status HTTP, os corpos de resposta incluem detalhes adicionais para fornecer informações mais específicas sobre o erro ocorrido, ajudando na identificação e resolução do problema.

### Monitoramento e Logging

Propomos mecanismos de monitoramento atualizados, considerando as novas funcionalidades adicionadas. Isso inclui métricas de desempenho e registros (logs) para facilitar a depuração e o diagnóstico de problemas.

### Padrão de Qualidade

 A API de Integração - Versão 2 segue as diretrizes estabelecidas, incluindo as novas funcionalidades adicionadas. Ela mantém:

- **Interoperabilidade:** Capacidade de interoperar eficazmente com sistemas e serviços distintos, incluindo o Dashboard - Versão 2.
- **Documentação clara e completa:** Documentação precisa, atualizada e facilmente compreensível, incluindo os novos serviços.
- **Segurança:** Rigoroso controle de segurança, especialmente




### 13.2.3 Deploy Backend


O Git Actions permite automatizar todo o processo de integração contínua e entrega contínua (CI/CD), desde a compilação do código-fonte até a implantação nos ambientes de produção. Isso traz benefícios, como a redução de erros humanos, a agilidade na entrega de novas funcionalidades e a garantia de que o software esteja sempre em um estado funcional e testado. 

O uso do Render para realizar o deploy adiciona uma camada adicional de eficiência e praticidade ao processo. Render é uma plataforma de hospedagem que simplifica a implantação de aplicativos na nuvem, oferecendo integração direta com Git Actions e outras ferramentas de CI/CD.

Portanto, o deploy foi realizado utilizando do Git Actions para realizar o deploy não apenas simplifica o processo, mas também aumenta a eficiência e a confiabilidade da entrega de software.

O deploy do backend envolve uma série de etapas que garantem o funcionamento  do sistema. Inicia-se com o processo de construção (build) que compila e prepara o código-fonte para implantação. Durante essa fase, são realizadas verificações de integridade e configurações específicas conforme necessário.

Após a etapa de construção, o próximo passo é a implantação propriamente dita. Aqui, o sistema é configurado para ser executado no ambiente de produção, o que pode envolver a instalação de dependências, configuração de variáveis de ambiente, ajustes de segurança e outros procedimentos essenciais.

<div align="center">
  <img src="https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Untitled%2053.png" alt="Untitled">
</div>

Observação: Após o dia 13 de abril de 2024, as máquinas que suportam o deploy serão desligadas, pois este deploy foi configurado como parte de um ambiente temporário para fins de aprendizado e demonstração do projeto finalizado. Isso significa que qualquer acesso ou funcionalidade relacionada ao deploy não estará mais disponível após essa data.

Figura: Diagrama das etapas realizadas para o deploy da API, com o status como Sucesso.

Como é possível verificar na figura do diagrama de deploy da API do Backend, processo de construção foi bem-sucedido, levando 2 minuto e 35 segundos, que envolveu verificar a versão do runner, detalhes do sistema operacional, e outras configurações essenciais para o ambiente de execução.

Durante o processamento do deploy, foi realizado o checkout do repositório, garantindo que todas as informações necessárias fossem sincronizadas corretamente. 

Na etapa de restauração das dependências da API,  todas as bibliotecas necessárias foram verificadas, para que estivessem disponíveis para o processo de construção seguinte. Este último consistiu na compilação da API, utilizando o comando dotnet build com a configuração Release. Apesar de algumas advertências sobre a compatibilidade de pacotes com o framework alvo, a compilação foi concluída com sucesso.

Após o checkout, ocorreram tarefas pós-checkout para limpar quaisquer resíduos do processo anterior e configurar adequadamente as informações do Git. Finalmente, o job foi considerado completo, com a limpeza de processos órfãos para garantir um ambiente limpo para futuras execuções. Essas etapas são contribuíram para um deploy bem-sucedido da API.

É possível ter uma visualização disso no seguinte link:

https://two024-t0004-si09-g05-api-dgnb.onrender.com/api/v1/Cid/certo-total

Esse é um exemplo de deploy do endpoint Cid2023

A visualização é a seguinte:

![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05-API/blob/main/assets/Deploy_exemplo_cid.png)

## 14. Plano de Comunicação

### Plano de comunicação

Um plano de comunicação é uma ferramenta essencial para o sucesso de qualquer projeto, evento, campanha ou iniciativa. Ele serve como um roteiro estratégico que define como uma organização irá se comunicar com seu público-alvo, transmitindo mensagens claras e consistentes para alcançar seus objetivos.

Para desenvolver um plano de comunicação eficaz é preciso uma análise cuidadosa do contexto, do público-alvo e dos recursos disponíveis, além de uma estratégia para garantir que a mensagem seja entregue de forma adequada e compreendida corretamente pelos ouvintes.

### Propósito

O propósito deste plano de comunicação é informar e conscientizar os Business Partners de Recursos Humanos, o CEO Brasil e outros líderes de equipe sobre a implementação de uma nova aplicação de sistema interno na Volkswagen Brasil. 

A aplicação consiste em um dashboard que correlaciona dados das pesquisas "Great Place to Work - GPTW" e "STIBA" com dados de saúde mental dos colaboradores. 

Além disso, o plano visa ressaltar a importância da confidencialidade dos dados de saúde e a necessidade de evitar a divulgação inadequada de informações sensíveis, como as notas dos diretores, a fim de manter a integridade do processo.

### Público-alvo

Devido à sensibilidade dos dados, apenas colaboradores seniores e executivos terão acesso à solução:

- Business Partners de Recursos Humanos: Profissionais responsáveis por articular estratégias de RH e implementar políticas de desenvolvimento de pessoas.
- CEO Brasil: Líder máximo da empresa no país, responsável por definir a visão estratégica e garantir a eficiência operacional.
- Diretores e Gerentes de Departamentos: Responsáveis por liderar equipes e implementar iniciativas alinhadas aos objetivos organizacionais.
- Líderes de Equipe e Gestores de Recursos Humanos: Responsáveis por conduzir equipes e garantir o bem-estar dos colaboradores no dia a dia.

### Mensagens-chave

#### **Introdução da Nova Aplicação:**

O primeiro passo crucial na comunicação é realizar uma introdução do novo sistema interno. É essencial destacar a importância do dashboard na tomada de decisões estratégicas e na promoção de um ambiente de trabalho saudável e produtivo. Além disso, é fundamental ressaltar que essa solução integra dados sensíveis das pesquisas de clima organizacional e saúde mental dos colaboradores. Portanto, é preciso que haja cuidado e responsabilidade no manuseio e na proteção desses dados, garantindo a privacidade e a confidencialidade de cada colaborador. Ao contextualizar os benefícios esperados da implementação do novo sistema, como o aprimoramento do ambiente de trabalho e o aumento da satisfação e engajamento dos colaboradores, devemos enfatizar a importância de respeitar e proteger a privacidade dos dados sensíveis da equipe.

#### **Confidencialidade dos Dados de Saúde**

É crucial assegurar a confidencialidade e segurança dos dados de saúde mental dos colaboradores, reconhecendo sua sensibilidade e impacto pessoal. Na aplicação, são implementadas medidas robustas de proteção de dados, incluindo criptografia avançada e acesso restrito. Essas salvaguardas garantem a integridade e privacidade das informações dos colaboradores, reforçando o compromisso com a ética e responsabilidade no tratamento de dados sensíveis.

### Diretrizes de Comunicação

Na intenção de preservar a confidencialidade e integridade do processo de avaliação, é importante não divulgar as notas atribuídas aos diretores para outros colaboradores, garantindo assim a confidencialidade e integridade do processo de avaliação. Reforçar a importância de uma comunicação transparente e ética dentro da organização, incentivando a troca aberta de informações entre líderes de equipe e colaboradores, sempre respeitando a privacidade e confidencialidade.

### Suporte e Capacitação

Além dos pontos acima é preciso deixar claro que será fornecido um suporte contínuo e capacitação adequada aos usuários da nova aplicação. Disponibilização de treinamentos específicos e materiais de apoio detalhados para auxiliar no uso eficaz do sistema. Terão também canais de suporte técnico que estarão disponíveis para esclarecimento de dúvidas e resolução de problemas relacionados à utilização do dashboard.

### Cultura de Segurança de Dados:

Focando em fortalecer a cultura de segurança de dados na empresa, é de extrema importância destacar a responsabilidade individual de cada colaborador na proteção e preservação das informações confidenciais da organização. É fundamental conscientizar sobre os riscos associados à violação de dados e a importância de seguir as diretrizes de segurança estabelecidas para proteger a privacidade e integridade dos dados corporativos.

## Canais de Comunicação
![Untitled](https://github.com/Inteli-College/2024-T0004-SI09-G05/blob/main/assets/plano_comunicacao.png)

### **Elaboração do Plano de Comunicação**

- Desenvolvimento do plano de comunicação, incluindo definição de mensagens-chave, canais de comunicação e estratégias de implementação.
- Este passo é o que consiste este documento. Porém, pode ter a necessidade de ajustes.

### **Envio do E-mail Informativo**

- Envio de e-mail detalhado para os principais stakeholders, introduzindo a nova aplicação de sistema interno e destacando sua relevância e benefícios.
- Inclusão de informações sobre a próxima Reunião de Apresentação.

### **Realização da Reunião de Apresentação**

- Realização de reunião virtual ou presencial para apresentação detalhada do novo sistema.
- Explicação sobre a utilização do dashboard, medidas de segurança e diretrizes de comunicação.
- Abertura para esclarecimento de dúvidas e obtenção de feedback dos participantes.

### **Lançamento da Solução**

- Lançamento oficial da solução após a Reunião de Apresentação para iniciar a implementação.

### **Treinamento e Suporte**

- Agendamento de sessões de treinamento para os líderes de equipe e usuários-chave.
- Disponibilização de materiais de apoio, manuais de usuário e FAQs para consulta.
- Oferta de suporte técnico para esclarecimento de dúvidas e resolução de problemas relacionados ao uso do dashboard.

### **Publicação na Intranet e Distribuição de Materiais**

- Publicação de comunicados e materiais explicativos na intranet da empresa.

### **Reunião de Feedback**

- Reunião para coletar feedback dos stakeholders após a publicação da solução na intranet e distribuição de materiais.

## **Conclusão**

Este plano de comunicação visa assegurar uma transição suave e eficiente para o novo sistema interno na Volkswagen Brasil, garantindo que todos os principais stakeholders compreendam sua importância e utilização adequada. Ao transmitir as mensagens-chave de forma clara e abrangente, esperamos promover a transparência, o engajamento e o sucesso desta iniciativa, contribuindo para o fortalecimento da cultura organizacional e o bem-estar dos colaboradores.

### E-mail Oficial

Um e-mail oficial será enviado, detalhando a nova aplicação para o CEO e Business Partners de RH. Este e-mail explicará suas funcionalidades e os procedimentos de segurança a serem seguidos, enfatizando a necessidade de manter o sigilo das informações. Além disso, serão incluídos links para materiais de apoio e um contato para esclarecimento de dúvidas. Também serão fornecidas as datas das reuniões de apresentação e treinamento para garantir uma transição tranquila para a nova aplicação.

### Reuniões de Apresentação e Treinamento

A reunião de apresentação deve ser realizada tanto de forma virtual quanto presencial, conforme a conveniência dos colaboradores. O objetivo dela é oferecer uma apresentação detalhada do novo sistema. Este é o momento onde serão esclarecidas de dúvidas e os colaboradores irão fornecer feedback imediato, garantindo uma compreensão abrangente e eficaz do sistema. Além disso, deve ser agendado um conjunto de sessões de treinamento para capacitar os líderes de equipe no uso do dashboard. Essas sessões podem incluir demonstrações práticas, exemplos de casos de uso relevantes para as operações da equipe e exercícios interativos para garantir uma compreensão completa e eficiente do sistema.

### **Intranet e Materiais de Divulgação**

A comunicação interna na empresa pode ser facilitada através de uma combinação estratégica de recursos online e materiais de divulgação. Na intranet, são publicados comunicados e materiais explicativos para manter os colaboradores informados. Para auxiliar ainda mais os colaboradores, manuais de usuário e FAQs podem ser disponibilizados para consulta, fornecendo orientações detalhadas sobre procedimentos e respostas às perguntas mais comuns. 

### Reunião de Feedback

Após aproximadamente um mês do lançamento da solução, será realizada uma reunião de feedback. O objetivo dessa reunião é avaliar a experiência dos usuários com o novo sistema, identificar eventuais dificuldades ou sugestões de melhoria e discutir estratégias para otimizar a utilização e maximizar os benefícios do dashboard. Essa reunião será uma oportunidade para reforçar o compromisso da empresa com a escuta ativa dos colaboradores e o aprimoramento contínuo das soluções implementadas.

## Cronograma

Este cronograma foi elaborado considerando uma sequência lógica de atividades, começando pela elaboração do plano de comunicação, seguida pela comunicação inicial por e-mail, realização da Reunião de Apresentação da solução, lançamento da solução, treinamento e suporte aos usuários,  publicação na intranet e distribuição de materiais e finalização com a reunião de feedbacks.

## 15. Referências

- RODRIGUES, R. C., "Métodos adotados na Administração Pública para elaborar Matrizes de Risco." UNIFUCAMP, 2019.
- WELLBE, "Custos do adoecimento mental." Disponível em: [wellbe.co](https://wellbe.co/2023/09/29/custos-do-adoecimento-mental/). Acesso em: 03 mar. 2024.
- UNIVERSITY OF CALIFORNIA, BERKELEY, "Impacts of Poor Mental Health on Business." Disponível em: [executive.berkeley.edu](https://executive.berkeley.edu/thought-leadership/blog/impacts-poor-mental-health-business). Acesso em: 03 mar. 2024.
- SIEMENS ENERGY, "Breaking the silence on mental health." Disponível em: [siemens-energy.com](https://www.siemens-energy.com/global/en/home/stories/breaking-the-silence-on-mental-health.html?gclid=CjwKCAiA3JCvBhA8EiwA4kujZheOHVeaotoLQG2fl5G6CFJLUvDy5GCo8vY9OAx9I5DOKtJkV5br_BoC8qUQAvD_BwE&gad_source=1). Acesso em: 03 mar. 2024.
- JOHNSON, Terica, "What Role Does Leadership Play in Employee Mental Health?" LinkedIn. Disponível em: [linkedin.com](https://www.linkedin.com/pulse/what-role-does-leadership-play-employee-mental-health-terica-johnson). Acesso em: 03 mar. 2024.
- OPENAI. (2024). Chatbot GPT-3 [Large language model]. https://chat.openai.com/chat Acesso em: 29 fev. 2024.
- LEROUGE, C., et al. Using Heuristic Evaluation to Enhance the Visual Display of a Provider Dashboard for Patient-Reported Outcomes. EGEMS (Wash DC), 2017. Disponível em: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5983070/
- Dowding, D., Merrill, J. A. The Development of Heuristics for Evaluation of Dashboard Visualizations. Thieme - Applied Clinical Informatics, 2018. Disponível em: https://www.thieme-connect.com/products/ejournals/pdf/10.1055/s-0038-1666842.pdf
- Moma, G.. 10 Heurísticas de Nielsen para o Design de Interface. Brasil UX Design, 2017. Disponível em: https://brasil.uxdesign.cc/10-heur%C3%ADsticas-de-nielsen-para-o-design-de-interface-58d782821840.
- Wangenheim, C. G. V., et al. "SURE: uma proposta de questionário e escala para avaliar a usabilidade de aplicações para smartphones pós-teste de usabilidade" UCA, 2014.
- Silva, J. C. S., et al. "Usabilidade de um dashboard destinado à autorregulação de estudantes em Sala de Aula Invertida" CINTED-UFRGS, 2018.
- Carvalho, A. A. A., "Testes de Usabilidade: exigência supérflua ou necessidade?" Universidade do Minho, 2002.
- Ferreira, K. G. F., "Teste de Usabilidade" UNIVERSIDADE FEDERAL DE MINAS GERAIS, 2002.
- Ferreira, A., "Usabilidade e Acessibilidade no design para a Web" Universidade do Porto, 2008.
- Sales, M., "WCAG 2.2 de forma simples! ", guia WCAG, 2024. Disponível em: https://guia-wcag.com/
