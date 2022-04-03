# Questões a partir do livro 'Doing Digital History'



> Digital ofecere novas ferramentas para o 'toolbox' do historiador, não substitutos para as antigas'. p. 20

- O digital substituirá as ferramentas básicas da operação historiográfica?
- Como isso afeta a construção do conhecimento histórico?

> Humanidades digitais é uma questão de abordagem: se você está critica e ativamente utilizando ferramentas digitais para auxiliar seu trabalho de epsquisa, ensino e aprendizagem, você provavelmente está praticando humanidades digitais. p.21

- Então é apenas uma questão metodológica?
- Não envolvem conhecimentos de programação?

Naturalização das ferramentas: esquecemos de refletir sobre como elas "mudaram completamente o funcionamento de nossa profissão" (25)

Buscas online através de palavras-chave: como replicar? A busca é individualizada e muda de momento a momento.

- Registro metodológico é central. O que na programação é chamado de "documentação". Minha proposta aqui é fazer isso através do controle de versões

> Citar apenas as versões analógicas das fontes enterra os vieses e torna muito difícil para os leitores reconhecerem e confrontarem-nos. p. 38

- Isso é muito comum no uso da HDB.

> Antes de iniciar sua pesquisa, é vital comprender como suas fontes digitais foram criadas, e como ficaram disponíveis para você. p. 44

- Como começa seu projeto de pesquisa em história? Suas fontes são digitais ou digitalizadas?
- 1º:  obter ou criar uma versão legível por computador dos seus dados.
- Como o processo de digitalização afeta sua pesquisa?
- Compreender esse processo deve ser tarefa básica em nossa profissão.
- Constumam ser pouco documentados
- Direitos de propriedade + desigualdades de acesso e digitalização

E as interfaces gráficas (GUI)?

- Difícil avaliar precisamente o que você está pesquisando, acessando e  quais as escolhas técnicas e teóricas por trás dos resultados mostrados na tela.

- Quão representativos são no conjunto de dados?

- Elas restringem suas perguntas ou abrem possibilidades de novas?

- Literacia digital: 

  > "A literacia arquivística digital requer a compreensão de como a produção  de arquivos digitais se baseia em designs técnicos que influenciam a sua usabilidade. Isso significa que (todos) os historiadores precisam  adquirir competência digital em um nível profissional paralelo às  habilidades que temos em compreender como a classificação e  categorização de fontes afetam nossa interação com arquivos analógicos e moldam nossas questões de pesquisa. (JENSEN, 2021, p. 6)"

E os documentos digitalizados?

- Como o processo de digitalização afeta sua pesquisa?
- Acessados, lidos e trabalhados emulando práticas analógicas.
- OCR, HTR.

Como coletar e organizar esses dados?

- CSV, JSON, XML, TEI, RDF
- PDF? JPG?
- Como lidar com esses diferentes formatos?
- Metadados? Navegar, descobrir e organizar. Mas também um objeto em si mesmo (61)

> "Os métodos de pesquisa digital criam demandas novas e às vezes mais  rigorosas de precisão, pensamento metodológico, auto-organização e  colaboração do que a pesquisa histórica tradicional" (FRIDLUND; OIVA;  PAJU, 2020, pos. 543).

## Controle de versões como método de documentação da pesquisa

História Digital = Colaboração, abertura, compartilhamento

Como gerenciar seus dados e mantê-los seguros?

> - metadata (como você descreve seus dados, tanto internamente quanto externamente)
> - controle de versões (o que fazer se você fizer uma lambança no processo)
> - documentação (uma descrição narrativa do projeto)
> - preservação (como os dados podem ser mantidos para uso no futuro)

Você já fez isso?

```shell
trabalho_final.docx
trabalho_final2.docx
trabalho_final_final.docx
trabalho_final_commentários_orientador.docx
trabalho_final_corrigido.docx
trabalho_final_versão_enviar.docx
```

É fundamental criar um plano para organização, documentação, preservação e compartilhamento dos dados, métodos e resultados da pequisa.

Podemos enfrentar boa parte desses desafios utilizando git.

Veja essa lição de [James Backer sobre preservação dos dados de investigação](https://programminghistorian.org/pt/licoes/preservar-os-seus-dados-de-investigacao) para outras estratégias e referências.

### O que é git?

- *Version Control System*
	- Distribuído
	- Repositório Local
	- Livre e gratuito
- Vantagens:
	- Controle de histórico
	- Trabalho em equipe
	- Ramificações (Branches)
	- Segurança
	- Organização
	- integração com repositórios remotos

#### GitHub

- Plataforma de hospedagem de códigos e arquivos
- Possui controle de versões utilizando Git;
- Rede Social;
- Vantagens:
	- repositórios ilimitados
	- Forks
	- Colaboração e trabalho com equipes grandes
	- gestão de projetos
	- automação de tarefas
	- GitHub Pages

#### Documentando o processo

- mensagens de commit 
- criação de README.md em cada pasta
- Encarar o processo de documentação como um processo público, mesmo que não seja publicado. 

## Datasets para pesquisa em história

> Datasets são sempre configurados pelas circunstâncias contingentes de sua criação e curadoria. (71)

É possível lidar com datasets prontos, mas por outro lado, ainda dependemos muito de fontes digitalizadas pouco estruturadas. Assim, temos poucos datasets de dados e metadados disponíveis.

Exemplo da HDB

Criar uma ferramenta para coletar dados da internet (web scraper) é um desafio, mas muitas vezes é um caminho fundamental para o desenvolvimento de pequisas de história digital = aplicar métodos mais sofisticados de análise e visuzliação do que apenas emular práticas analógicas.

> "A raspagem, dito de maneira bastante formal, é uma técnica importante  para a coleta automatizada de dados online. É uma das práticas mais  distintas associadas às formas atuais de pesquisa social digital,  aquelas que são marcadas pelo surgimento da Internet e a nova  onipresença dos dados digitais na vida social. Scrapers, para dizer de  forma mais informal, são bits de código de software que possibilitam o  download automático de dados da Web e a captura de algumas das grandes  quantidades de dados sobre a vida social que estão disponíveis em  plataformas online como Google, Twitter e Wikipédia". (MARRES;  WELTEVREDE, 2013, p. 313)



--

Etapas do web scraping

análise da página Web


rastreio ou raspagem da página Web

organização dos dados

--

Problemas e limitações


instabilidade dos websites


limitado para uma página específica


curva de aprendizado elevada

--

Mas é apenas uma técnica?

> "também é uma prática de análise” (MARRES; WELTEVREDE, 2013, p. 317)

> "nossos ajudantes digitais já estão cheios de "teoria" e "julgamento". Como acontece com qualquer metodologia, eles contam com conjuntos de premissas, modelos e estratégias. A teoria já está trabalhando no nível mais básico quando se trata de definir unidades de análise, algoritmos e procedimentos de visualização" (RÖHLE; RIEDER, 2012, p. 70).

--

É apenas um acelerador

--

1. Coleta, organização


2. Produção de conjunto de dados que dialoguem com os interesses de pesquisa


3. Transparência e registro metodológico


4. Explicita escolhas teóricas

--

Considerações finais: seremos todos programadores?
