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
- Integrar dados em um ambiente centralizado;
- Automatizar o pipeline de ingestão e transformação de dados;
- Aumentar a eficiência e a escalabilidade do processo analítico;
- Diminuir o tempo de entrega de relatórios gerenciais.

---
## 🗂️ Dataset
- Tabela Dimensão Fotos no formato xlsx;
- Tabela Fato Metas no formato  xlsx;
- Tabela Fato Vendas no formato xlsx.


---
## 🛠️ Tecnologias Utilizadas
-  Notion → Plataforma de gerenciamento do projeto;
-  GitHub → Versionamento;
-  Excalidraw → Arquitetura dos Dados;
-  Power Query → Extração, Tratamento e Carregamento dos Dados;
-  Figma → Designer;
-  Power BI → Dataviz.

---
## 🧱 Modelagem de Dados
A modelagem foi construída visando performance e clareza analítica, utilizando:

- Modelo Estrela;
- Tabelas Fato e Dimensões;
- Relacionamentos otimizados para análise no Power BI.

---
## 🔄 Pipeline de Dados (ETL)
O pipeline do projeto segue as seguintes etapas:
- Extração: Coleta de dados estruturados a partir de arquivos xlsx (vendas, metas e fotos);
- Transformação: Tratamento, limpeza dos dados brutos utilizando o Power Query;
- Visualização: Modelagem e consolidação das informações no Power BI para geração de dashboard e análise de indicadores.


<p align="center">
<img src="https://github.com/user-attachments/assets/8ae4c365-ad1e-4b20-99c4-437bd2ce740a" width="700" alt="image">
</p>

---
 ## 💡 Estratégia da Solução
Como o projeto se concentra num produto de BI a estratégia adotada foi estruturada com base no Modelo de Requisitos, garantindo alinhamento entre os problemas de negócio, os objetivos analíticos e as entregas finais do projeto.

O plano contempla as fases de Análise, para entendimento do contexto e definição de métricas; ETL, para ingestão e transformação dos dados; Modelagem, para estruturação analítica; Design, para construção das visualizações e consumo; e Governança de Dados, para assegurar padronização, versionamento e confiabilidade das informações:

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

- Alteração de Arquitetura;
- Analise da Curva ABC;
- Analise de Forecast;
- Analise de Cohort;
- Analise de RFV.

 
 
 

