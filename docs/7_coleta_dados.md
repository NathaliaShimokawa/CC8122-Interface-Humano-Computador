# 1. Identificação de Necessidades dos Usuários e Requisitos de IHC: 
## 1.1 Que dados coletar?
O sistema precisa coletar dados que permitam compreender o comportamento visual e as preferências dos usuários durante a navegação.

| Tipo de dado                    | Descrição                                                                                | Finalidade                                                         |
| ------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **Dados pessoais básicos**      | Idade, gênero, profissão, região geográfica                                              | Segmentação de perfis                  |
| **Dados visuais (eyetracking)** | Posição e direção do olhar, tempo de fixação em elementos, mapa de calor visual          | Identificar áreas de maior atenção e interesse                     |
| **Dados técnicos**              | Dispositivo, resolução de tela, navegador utilizado, qualidade da iluminação e da câmera | Garantir a precisão do rastreamento e a compatibilidade do sistema |
| **Feedbacks qualitativos**      | Opiniões sobre usabilidade, conforto, confiança e percepção de privacidade               | Ajustar o design e a interface conforme preferências dos usuários  |


## 1.2 De quem coletar?
Os dados serão coletados de diferentes perfis de personas que representam os públicos do sistema.

| Persona / Perfil                        | Tipo de dado                                                                                                       | Justificativa                                                                                             |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| **Roberto Carvalho (persona primária)** | Dados analíticos e relatórios de comportamento dos usuários, feedback sobre clareza e objetividade das informações | Entender necessidades de gestores e tomadores de decisão que usarão o sistema como ferramenta estratégica |
| **Carla Ribeiro (persona secundária)**  | Dados visuais (eyetracking), comportamento de navegação, percepção de privacidade e facilidade de uso              | Avaliar a interação do consumidor final com o sistema e o impacto da personalização                       |
| **Cláudia Mendes (persona negativa)**   | Opiniões e resistências à adoção de tecnologias novas                                                              | Entender limitações de aceitação do produto e barreiras de usabilidade em perfis mais tradicionais        |
| **Equipe de marketing e UX da empresa** | Necessidades de análise, métricas utilizadas, dificuldades com ferramentas atuais                                  | Identificar requisitos técnicos e funcionais do sistema para integração corporativa                       |

---

# 2. Aspectos Éticos
O projeto deve obrigatoriamente considerar aspectos éticos, pois se apoia em tecnologias que dependem da coleta de dados pessoais e comportamentais (olhar, expressões faciais, tempo de foco). Esses dados têm potencial de identificação e interpretação subjetiva, exigindo proteção ética e legal. Assim, o uso do TCLE garante que a coleta seja voluntária, informada e segura, respeitando a autonomia e privacidade do participante.

| Princípio Ético          | Aplicação no Projeto                                                                                                                                                                                          |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Autonomia**            | O usuário deve decidir livremente participar, mediante assinatura digital do Termo de Consentimento Livre e Esclarecido (TCLE). Ele será informado sobre o objetivo, os dados coletados e o uso previsto. |
| **Beneficência**         | A tecnologia deve gerar benefícios tanto para o usuário (melhor experiência e personalização) quanto para as empresas (maior eficiência em campanhas).                                                        |
| **Não maleficência**     | Garantia de que nenhum dado sensível (imagem facial ou gravação) será divulgado, armazenado de forma identificável ou utilizado fora do escopo da pesquisa.                                                   |
| **Justiça**              | Todos os participantes terão o mesmo direito à informação, à recusa e à exclusão de seus dados, sem discriminação de perfil ou opinião.                                                                       |
| **Transparência e LGPD** | O sistema deve seguir a Lei Geral de Proteção de Dados (LGPD), informando claramente como e por que os dados serão utilizados e permitindo que o usuário os exclua quando desejar.                        |

---

# 3.​ Ferramentas de Coleta de Dados (três técnicas diferentes)
## 3.1 Questionário Estruturado Online (Google Forms)
-Técnica quantitativa 
-Aplicada a: Usuários finais (Carla, Cláudia) e Gestores (Roberto)
-**Obejtivo:** Identificar percepções, hábitos e expectativas dos usuários em relação a plataformas de análise visual e comportamento de compra online, além de avaliar nível de familiaridade com tecnologia e privacidade.
-**Como aplicar:** O questionário será disponibilizado online (Google Forms) e respondido de forma anônima, com TCLE apresentado no início. Deve ser aplicado antes dos testes com o sistema para compreender o perfil e expectativas do participante.
-**Instrumento:**
Bloco 1 – Identificação e perfil
1. Idade: 

2. Sexo/Gênero: 

3. Grau de familiaridade com tecnologia (1 a 5): ☐1 ☐2 ☐3 ☐4 ☐5

Bloco 2 – Comportamento e uso

4. Com que frequência você realiza compras online? ☐Diariamente ☐Semanalmente ☐Mensalmente ☐Raramente
   
5. O que mais influencia suas decisões de compra online? ☐Preço ☐Imagem ☐Descrição ☐Comentários ☐Publicidade
  
6. Você costuma prestar atenção em banners e anúncios durante a navegação? ☐Sim ☐Não ☐Às vezes

Bloco 3 – Expectativas e privacidade
7. Você permitiria o uso da sua câmera para personalizar sua navegação (por exemplo, rastreando seu olhar)? ☐Sim ☐Não ☐Depende das explicações

8. Quais preocupações você teria com esse tipo de tecnologia?
( ) Privacidade dos dados
( ) Armazenamento de imagens
( ) Uso indevido das informações
( ) Outros: ____________

9. O que você considera essencial em uma plataforma que analisa comportamento visual?
( ) Clareza nos resultados
( ) Facilidade de uso
( ) Rapidez
( ) Segurança e transparência


## 3.2 Entrevista Semiestruturada
-Técnica qualitativa 
-Aplicada a: Persona primária (Roberto Carvalho) e equipe de marketing
-**Obejtivo:** Compreender necessidades estratégicas e dificuldades enfrentadas por gestores e analistas na análise de comportamento do usuário em plataformas digitais.
-**Como aplicar:** Antes de iniciar, será apresentado o TCLE e reforçado que os dados serão confidenciais e usados apenas para fins de pesquisa.
-**Instrumento:**
Parte 1 – Contexto e rotina profissional
1. Poderia descrever brevemente suas principais responsabilidades na área de marketing?

2. Quais ferramentas você utiliza atualmente para analisar o comportamento dos usuários no site da empresa?

3. Quais informações você considera mais importantes para avaliar o desempenho de campanhas?

Parte 2 – Dores e desafios
4. Quais as principais dificuldades que sua equipe enfrenta ao tentar entender o comportamento dos visitantes no site?
 
5. Você sente falta de informações visuais (como o que o usuário realmente olha)?
   
6. Como costuma ser o processo de tomada de decisão quando há problemas de conversão?

Parte 3 – Expectativas e percepções sobre o sistema
7. Como você imagina uma ferramenta ideal de análise de comportamento visual?

8. Que tipo de dados ou relatórios seriam mais úteis no seu dia a dia?
   
9. Quais preocupações você teria com o uso de tecnologias que dependem de câmera ou rastreamento de olhar?
    
10. Você acredita que uma solução como o eyetracking poderia trazer resultados mensuráveis para a empresa?


## 3.3 Grupo Focal
-Técnica qualitativa colaborativa 
-Aplicada a: Usuários finais do site (Carla Ribeiro e perfis semelhantes)
-**Obejtivo:** Explorar percepções, emoções e reações dos usuários diante de protótipos ou vídeos de demonstração do sistema de eyetracking, analisando confiança, conforto e usabilidade percebida.
-**Como aplicar:** Apresentar brevemente o projeto e o TCLE e mostrar um protótipo do sistema em funcionamento (demo).
-**Instrumento:**
Parte 1 – Primeiras impressões
1. Qual foi sua primeira reação ao ver o sistema em funcionamento?

2. Você se sentiria confortável em permitir o uso da câmera? Por quê?

Parte 2 – Expectativas e percepção de valor
3. Você acredita que esse tipo de tecnologia realmente pode personalizar sua experiência de compra?

4. Há algo que geraria desconforto ou faria você desistir de usá-la?

Parte 3 – Melhorias e sugestões
5. Que elementos do design poderiam melhorar a sensação de controle e transparência?

6. Se fosse indicar esse sistema para alguém, o que você destacaria como principal benefício? 
