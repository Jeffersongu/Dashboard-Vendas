# 🛒 Dashboard-Vendas
<!-- Adicionando Gifs: -->
![Dashboard Vendas - Gifs](https://github.com/user-attachments/assets/3e5ba7cc-1496-44da-bd4a-e3f674f592eb)



---
## 📊 Problema de Negócio

**Visão Geral da Express:**

- A Express é uma renomada distribuidora de alimentos e bebidas com sede na cidade de São Paulo, Brasil. Há 10 anos no mercado, nossa empresa tem sido uma figura de destaque na indústria de distribuição, conectando fabricantes de produtos alimentícios e bebidas a uma ampla rede de clientes varejistas em todo o país.
- Desafios: Muito tempo para produzir relatórios em Excel e muito retrabalho.
- Detalhes dos Desafios: Levamos muito tempo na entrega dos relatórios de vendas que são desenvolvidos na área de vendas, limitando nossas análises. Queremos migrar do Excel para o Power BI e melhorar o layout dos nossos relatórios.


---
## 🔍 Contexto
 - Atualmente, a Express enfrenta desafios relacionados à eficiência e à escalabilidade de seus processos de análise de dados, especialmente no que diz respeito aos relatórios de vendas. As informações são extraídas de diferentes fontes e consolidadas manualmente em planilhas Excel, o que torna o processo moroso, suscetível a erros e altamente dependente de retrabalho. Essa abordagem impacta diretamente o tempo de entrega dos relatórios e limita a capacidade da área de vendas e da gestão em realizar análises mais profundas e em tempo hábil.


---
## 🎯 Objetivos do Projeto
- Estruturar o processo de análise de dados de vendas, reduzindo dependência de consolidações manuais em Excel;
- Integrar dados provenientes de múltiplas fontes em um ambiente centralizado;
- Automatizar o pipeline de ingestão e transformação de dados;
- Aumentar a eficiência e a escalabilidade do processo analítico;
- Diminuir o tempo de entrega de relatórios gerenciais.

---
## 🗂️ Dataset
- Tabela Dimensão Fotos no formato Planilha do Microsoft Excel;
- Tabela Fato Metas no formato Planilha do Microsoft Excel;
- Tabela Fato Vendas no formato Planilha do Microsoft Excel.


---
## 🛠️ Tecnologias Utilizadas
-  Notion;
-  SQL Server;
-  Pentaho;
-  GitHub;
-  Excalidraw;
-  Figma;
-  Power BI.

---
## 🧱 Modelagem de Dados
A modelagem foi construída visando performance e clareza analítica, utilizando:

- Modelo estrela;
- Tabelas fato e dimensões;
- Relacionamentos otimizados para análise no Power BI

---
## 📝 Modelo de Requisitos
O Modelo de Requisitos foi adotado para garantir alinhamento claro entre o problema de negócio, os objetivos analíticos e as entregas finais do projeto.

<p align="center">
<img src="https://github.com/user-attachments/assets/f384cbe7-20c4-454c-a949-4698d7688b99" width="800" alt="image">
</p>


---
## 📅 Definição do Cronograma do Projeto
 O cronograma do projeto será desenvolvido em cinco etapas: Análise, ETL, Modelagem, Designer e Governança dos Dados.

<p align="center">
  <img src="https://github.com/user-attachments/assets/9cccf3b5-b26e-42c2-889a-bb2ac1fd8964" width="700" alt="image">
</p>

 
---
 ## 📍 Premissas da Análise
Para a condução desta análise, foram estabelecidas algumas premissas com o objetivo de garantir consistência, confiabilidade e alinhamento com o contexto do negócio.
 - Assume-se que os dados de vendas fornecidos pela empresa representam fielmente as operações realizadas no período analisado, estando devidamente registrados nos sistemas de origem, sem perdas relevantes de informação.

 - Considera-se também que as bases de dados utilizadas possuem granularidade suficiente para permitir análises por período, produto, cliente e região, possibilitando a construção de indicadores de desempenho e comparações temporais.
 - Eventuais inconsistências, valores nulos ou duplicidades serão tratadas por meio de processos de limpeza e transformação de dados durante a etapa de preparação.

---
## 🔄 Pipeline de Dados (ETL)
O pipeline do projeto segue as seguintes etapas:

- Extração dos dados a partir de arquivos ou bases de dados utilizando Pentaho;
- Transformação (limpeza, padronização, tipagem e enriquecimento) com o Pentaho;
- Carga na Stage;
- Carga dos dados no Data Warehouse;
- Visualização dos dados no Power BI.

  
<p align="center">
  <img src="https://github.com/user-attachments/assets/71100f00-a783-4304-9a60-1e1f9fd43630" width="700" alt="image">
</p>


---
 ## 💡 Estratégia da Solução
A estratégia da solução foi estruturada com base em um Modelo de Requisitos, garantindo alinhamento entre o problema de negócio, os objetivos analíticos e as entregas finais do projeto.

A execução foi organizada em etapas sequenciais e controladas, permitindo rastreabilidade, qualidade e evolução contínua da solução de dados.

O plano contempla as fases de Análise, para entendimento do contexto e definição de métricas; ETL, para ingestão e transformação dos dados; Modelagem, para estruturação analítica; Design, para construção das visualizações e consumo; e Governança de Dados, para assegurar padronização, versionamento e confiabilidade das informações.

 ### Etapa 1: Análise de Projeto
 Nesta etapa, o foco é compreender profundamente o negócio do cliente. Isso envolve pesquisas, entrevistas e análises de documentos. O objetivo é identificar os desafios e necessidades do cliente, criando uma base sólida para as tarefas subsequentes.

 Etapa completa:


 ### Etapa 2: ETL
 Durante a fase ETL (Extração, Transformação e Carga), nosso foco é assegurar que os dados estejam prontos para análises relevantes. Na etapa de Extração, coletamos dados de diversas fontes; na Transformação, realizamos limpeza e adaptação; e na Carga, disponibilizamos os dados em formato propício para análises.

Etapa completa:


 ### Etapa 3: Modelagem
A Modelagem dos Dados representa a espinha dorsal do sistema, estabelecendo relacionamentos sólidos entre as tabelas e definindo a estrutura que suportará a análise de dados. Nessa fase, o foco está na criação de um modelo coeso e eficiente que atenda às necessidades específicas do negócio.

Etapa completa:

### Etapa 4: Designer do Projeto
 A fase de Design é fundamental para moldar a arquitetura e a estética da solução. Durante essa etapa, é crucial definir a estrutura da interface, os componentes visuais e a lógica de interação para proporcionar uma experiência eficiente aos usuários finais. Essas decisões têm um impacto significativo na usabilidade e na eficácia da solução, influenciando diretamente a qualidade da experiência do usuário final e a efetividade do projeto de BI como um todo.

Etapa completa:

### Etapa 5: Monitoramento
 A fase de Governança dos Dados é essencial para garantir a qualidade, integridade e segurança das informações manipuladas no projeto de BI. Nesse contexto, estabelecer políticas, normas e processos claros para a gestão dos dados é fundamental. A governança visa assegurar a confiabilidade das fontes de dados, promover a conformidade com regulamentações e padrões, além de definir papéis e responsabilidades na administração dos ativos de informação. Ao adotar práticas robustas de governança, a organização potencializa a tomada de decisões baseada em dados confiáveis e mitigação de riscos, contribuindo para o sucesso contínuo do projeto de BI.

Etapa completa:





---
O Modelo de Requisitos foi adotado para garantir alinhamento claro entre o problema de negócio, os objetivos analíticos e as entregas finais do projeto. 
- Essa abordagem permite estruturar a análise de dados de forma lógica e rastreável, conectando fontes de dados, métricas, análises e stakeholders em um único framework.

- A escolha desse modelo visa reduzir ambiguidades, priorizar indicadores relevantes para o negócio e assegurar que os dashboards desenvolvidos no Power BI atendam diretamente às necessidades da área comercial. Além disso, o uso do Modelo de Requisitos facilita a escalabilidade da solução, a manutenção dos relatórios e a comunicação entre áreas técnicas e de negócio.

<p align="center">
<img src="https://github.com/user-attachments/assets/f384cbe7-20c4-454c-a949-4698d7688b99" width="900" alt="image">
</p>

 ### Etapa 1: Análise de Projeto
 Nesta etapa, o foco é compreender profundamente o negócio do cliente. Isso envolve pesquisas, entrevistas e análises de documentos. O objetivo é identificar os desafios e necessidades do cliente, criando uma base sólida para as tarefas subsequentes:
 - Levantamento de Requisitos do Projeto;
 - Análise de Viabilidade;
 - Definição das Tecnologias Adotadas:
 - Por que o Notion?
   - Centraliza toda a documentação;
   - Organização de requisitos e decisões técnicas;
   - Facilita a rastreabilidade entre negócio, dados e entregas analíticas.
  - Por que o SQL Server?
    - Utilizado como camada de armazenamento e Data Warehouse por oferecer robustez, confiabilidade, bom desempenho analítico;
    - Fácil integração nativa com ferramentas de BI.
  - Por que o Pentaho?
    - Utilizado para garantir controle do fluxo de dados e a aplicação de boas práticas de tratamento;
    - Permite a escalabilidade e o reaproveitamento de transformações, reduzindo o tempo de manutenção.
  - Por que o GitHub?
    - O projeto é dividido em arquivos de texto (JSON), permitindo que o GitHub identifique exatamente o que foi alterado em cada medida ou visual;
    - A revisão de código que facilita a comparação entre versões, mostrando de forma clara o que mudou ao longo do desenvolvimento;
    - Segurança e colaboração com histórico do projeto organizado, tornando mais fácil trabalhar em equipe e dar manutenção no futuro. 
  - Por que o Excalidraw?
    - Adotado para simplificar a comunicação técnica da arquitetura e o desenho dos processos;
    - Auxilia na identificação prévia de gargalos no fluxo de dados através do mapeamento visual.
  - Por que o Figma?
    - Escolhido para a prototipação e definição do layout do dashboard, garantindo padronização visual, validação prévia de UX/UI;
    - Redução de retrabalho no Power BI.
  - Por que o Power BI?
    - Escolhido pela poderosa modelagem com DAX e alta interatividade para o usuário final;
    - Oferece insights rápidos através de filtros dinâmicos, transformando dados brutos em decisões estratégicas.
 - Definição do Cronograma do Projeto;

   O cronograma do projeto será desenvolvido em cinco etapas: Análise, ETL, Modelagem, Designer e Governança dos Dados.
   As etapas de projeto contém as tarefas que podem ser visualizadas na árvore hierárquica abaixo.
   E cada tarefa possui um conjunto de atividades com um cheklist.
   
<p align="center">
  <img src="https://github.com/user-attachments/assets/9cccf3b5-b26e-42c2-889a-bb2ac1fd8964" width="700" alt="image">
</p>

 - Alinhamento com os Stakeholders

 
 #### 4.2° ETL
 Durante a fase ETL (Extração, Transformação e Carga), nosso foco é assegurar que os dados estejam prontos para análises relevantes. Na etapa de Extração, coletamos dados de diversas fontes; na Transformação, realizamos limpeza e adaptação; e na Carga, disponibilizamos os dados em formato propício para análises.
 
 - A arquitetura de tratamento de dados foi definida considerando as restrições de acesso à origem, uma vez que não há conexão direta com o banco de dados do ERP. Por esse motivo, optou-se pela extração diária dos dados em arquivos Excel padronizados, garantindo consistência e previsibilidade no processo de ingestão.

- O uso do Pentaho (inicialmente Power Query) foi escolhido para centralizar as etapas de extração, tratamento e validação dos dados, permitindo controle do fluxo, reaproveitamento de transformações e facilidade de manutenção. A separação entre área de Stage e Data Warehouse segue boas práticas de arquitetura analítica, possibilitando validações antes da carga final, maior confiabilidade dos dados e redução de impactos em caso de falhas.

- Essa abordagem proporciona escalabilidade, organização do pipeline de dados e integração eficiente com o Power BI, assegurando que as análises sejam construídas sobre dados tratados, consistentes e alinhados às necessidades do negócio.
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/71100f00-a783-4304-9a60-1e1f9fd43630" width="800" alt="image">
</p>

 
 #### 4.3° Modelagem
A Modelagem dos Dados representa a espinha dorsal do sistema, estabelecendo relacionamentos sólidos entre as tabelas e definindo a estrutura que suportará a análise de dados. Nessa fase, o foco está na criação de um modelo coeso e eficiente que atenda às necessidades específicas do negócio.

- Como o sistema de origem não disponibiliza cadastros individuais de produtos e vendedores, optou-se por derivar as dimensões dProduto e dVendedor a partir da própria base de vendas, garantindo consistência entre chaves e eliminando dependência de fontes externas inexistentes. Essa decisão permitiu estruturar o modelo mesmo diante das limitações do ERP.

- Foram definidas as tabelas dCalendário, dProduto, dVendedor, fVendas e fMetas, seguindo boas práticas de modelagem dimensional. A separação entre tabelas fato e dimensão facilita a leitura do modelo, melhora a performance das consultas e amplia a flexibilidade analítica no Power BI.

- A criação das dimensões dProduto e dVendedor teve como objetivo reduzir o tamanho da tabela fVendas, mantendo nela apenas métricas e chaves, o que contribui para melhor desempenho, manutenção e escalabilidade do modelo.

- A tabela dCalendário foi criada para padronizar análises temporais e permitir o correto relacionamento entre as tabelas de vendas e metas, considerando diferentes campos de data (data de emissão e data da meta), evitando inconsistências em análises por período.

- Os relacionamentos foram definidos de forma que as dimensões filtrem as tabelas fato (dProduto → fVendas, dVendedor → fVendas e fMetas, dCalendário → fVendas e fMetas), garantindo integridade analítica, evitando ambiguidade nos filtros e assegurando previsibilidade nos cálculos.

<p align="center">
  <img src="https://github.com/user-attachments/assets/52707191-3b40-402f-84db-92effdd9b56d" width="800" alt="image">
</p>


- A construção do dashboard foi iniciada a partir do conceito de storytelling analítico, organizando as páginas em uma sequência lógica que conduz o usuário da visão geral para análises mais específicas. Essa abordagem foi escolhida para facilitar a interpretação dos dados e apoiar a tomada de decisão progressiva, partindo de indicadores macro para análises detalhadas.

- A primeira página concentra os principais KPIs (faturamento, quantidade de vendas, ticket médio e positivação), permitindo uma leitura rápida da performance comercial. As análises ao longo do tempo, por produto e por vendedor foram priorizadas para identificar tendências, gargalos e oportunidades de melhoria.

- As páginas seguintes foram estruturadas para análise de metas, desempenho por hierarquia comercial e ranking de vendedores, utilizando visuais comparativos e hierárquicos. Essa organização permite avaliar resultados individuais e coletivos, além de identificar os principais influenciadores do faturamento.

- A inclusão de análises de novos faturamentos, lucratividade, previsão e cestas de produtos foi definida para agregar valor estratégico ao dashboard, indo além do acompanhamento operacional e apoiando decisões táticas e comerciais.

- O desenvolvimento das medidas em DAX seguiu boas práticas de padronização, documentação e organização, garantindo legibilidade, manutenção e confiabilidade dos cálculos. A validação dos resultados foi realizada por meio de ferramentas como Analyze in Excel e Excel, assegurando consistência entre os dados e os indicadores apresentados.

- A escolha dos tipos de visualizações e a organização da interface priorizaram usabilidade, clareza e navegação intuitiva, reduzindo ruídos visuais e facilitando o consumo das informações por diferentes perfis de usuários.


<img width="1918" height="1026" alt="image" src="https://github.com/user-attachments/assets/9a01ee05-3540-48fe-bd7d-3f946d7b77f7" />
 
<br/>
 
 #### 4.4° Designer do Projeto
 A fase de Design é fundamental para moldar a arquitetura e a estética da solução. Durante essa etapa, é crucial definir a estrutura da interface, os componentes visuais e a lógica de interação para proporcionar uma experiência eficiente aos usuários finais. Essas decisões têm um impacto significativo na usabilidade e na eficácia da solução, influenciando diretamente a qualidade da experiência do usuário final e a efetividade do projeto de BI como um todo.

- O design do dashboard foi desenvolvido utilizando o Figma, ferramenta definida na etapa de Definição das Tecnologias Adotadas, por permitir prototipação rápida, padronização visual, validação prévia com stakeholders e redução de retrabalho durante a implementação no Power BI.

- O Guia Definitivo de Storytelling e Design de Dashboards foi utilizado como referência para assegurar que os visuais seguissem boas práticas de leitura, contraste, priorização de informação e alinhamento com os objetivos analíticos definidos, evitando excesso de elementos e ruído visual.

- A validação com o designer foi realizada para assegurar aderência às boas práticas de UX/UI e à identidade visual, reduzindo riscos de problemas de usabilidade antes da construção final no Power BI.

- Por fim, foi aplicado um checklist final de validação, garantindo que todos os critérios de layout, storytelling, legibilidade e padronização fossem atendidos antes da entrega, assegurando qualidade, consistência e facilidade de uso do dashboard.

<img width="1482" height="803" alt="image" src="https://github.com/user-attachments/assets/1c5a5a30-0156-4276-8e07-df6c0b7e7e5a" />
<br/>

 #### 4.5° Monitoramento
 A fase de Governança dos Dados é essencial para garantir a qualidade, integridade e segurança das informações manipuladas no projeto de BI. Nesse contexto, estabelecer políticas, normas e processos claros para a gestão dos dados é fundamental. A governança visa assegurar a confiabilidade das fontes de dados, promover a conformidade com regulamentações e padrões, além de definir papéis e responsabilidades na administração dos ativos de informação. Ao adotar práticas robustas de governança, a organização potencializa a tomada de decisões baseada em dados confiáveis e mitigação de riscos, contribuindo para o sucesso contínuo do projeto de BI.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5180af36-090a-4bab-a22f-d03188e6844e" width="800" alt="image">
</p>

 


 ## 5° Insights da Análise
 Não basta somente apresentar os dados ou visuais, é extremamente importante explicar com palavras o que o gráfico quer dizer, não acredite que os stakeholders entenderam os gráficos simplesmente observando, a parte técnica deve ser abstraída para que todos entendam. A análise dos dados permitiu identificar padrões relevantes como:

 ## 6° Resultados
 Conclusão das análises, depois que descrevemos os visuais e encontramos pontos de melhoria, qual é a conclusão geral, qual será a recomendação para solucionar o problema.
 Link para o relatório completo:

 ## 7° Próximos Passos
 O que faríamos com mais tempo para trabalhar neste projeto por exemplo:

- Desenvolvimento de Banco de Dados;
- Analise da Curva ABC;
- Analise de Forecast;
- Analise de Cohort;
- Analise de RFV.

 
 
 

