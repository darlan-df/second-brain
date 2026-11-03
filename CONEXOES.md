# Mapa de conexões entre os domínios

A biblioteca não trata as disciplinas como compartimentos independentes. A relação entre dois domínios deve indicar **o que é transferido**, **qual decisão depende disso** e **como verificar o resultado**.

## Tipos de conexão

- **Fundamenta:** um conceito ajuda a explicar outro.
- **Depende de:** um trabalho precisa de uma entrada produzida em outro domínio.
- **Mede:** fornece evidências e indicadores.
- **Transforma:** implementa mudanças em processos, sistemas, serviços ou comportamentos.
- **Restringe:** explicita riscos, governança, ética ou limites operacionais.

## Conexões prioritárias

| Origem | Conexão explícita | Destino |
|---|---|---|
| [Negócios e estratégia](conhecimentos/negocios-e-estrategia/README.md) | Direciona resultados, prioridades e capacidades necessárias | [Arquitetura empresarial](conhecimentos/arquitetura-empresarial/README.md) |
| [Arquitetura empresarial](conhecimentos/arquitetura-empresarial/README.md) | Relaciona capacidades, processos, pessoas, dados e tecnologia | [Gestão por processos](conhecimentos/gestao-processos/README.md) |
| [Experiência do cliente](conhecimentos/experiencia-cliente/README.md) | Mostra necessidades, jornadas e fricções para orientar mudanças | [Gestão por processos](conhecimentos/gestao-processos/README.md) |
| [Gestão por processos](conhecimentos/gestao-processos/README.md) | Identifica problemas e oportunidades que podem demandar iniciativas temporárias | [Gestão de projetos](conhecimentos/gestao-projetos/README.md) |
| [Gestão de projetos](conhecimentos/gestao-projetos/README.md) | Entrega mudanças que precisam ser incorporadas ao trabalho cotidiano | [Pessoas e mudança](conhecimentos/pessoas-e-mudanca/README.md) |
| [Dados e decisão](conhecimentos/dados-e-decisao/README.md) | Mede resultados e ajuda a testar hipóteses em processos e serviços | [Gestão por processos](conhecimentos/gestao-processos/README.md) |
| [Dados e decisão](conhecimentos/dados-e-decisao/README.md) | Define evidências, qualidade e avaliação de soluções | [Inteligência artificial](conhecimentos/inteligencia-artificial/README.md) |
| [Inteligência artificial](conhecimentos/inteligencia-artificial/README.md) | Pode apoiar investigação, documentação e decisões, sob validação humana | [Gestão por processos](conhecimentos/gestao-processos/README.md) |
| [Negócios e estratégia](conhecimentos/negocios-e-estrategia/README.md) | Define valor e critérios para priorizar oportunidades | [Inteligência artificial](conhecimentos/inteligencia-artificial/README.md) |
| [Experiência do cliente](conhecimentos/experiencia-cliente/README.md) | Evidencia efeitos reais das mudanças sobre quem recebe o serviço | [Negócios e estratégia](conhecimentos/negocios-e-estrategia/README.md) |

## Trilhas transversais para estudo e casos práticos

### T1 — Problema de experiência do cliente

Sinal do cliente → jornada e pontos de contato → processo operacional → capacidades e sistemas → análise de dados → alternativas → projeto de melhoria → adoção → medição da experiência.

### T2 — Queda de produtividade

Resultado de negócio → indicador e qualidade dos dados → investigação do processo → estrutura, papéis e tecnologia → hipóteses de causa → redesenho → implementação → monitoramento.

### T3 — Avaliação de IA em uma operação

Objetivo de negócio → problema operacional → processo e contexto → dados e riscos → alternativa sem IA versus com IA → viabilidade → projeto piloto → avaliação → adoção/governança.

### T4 — Mudança organizacional

Objetivo estratégico → capacidades afetadas → processos e áreas envolvidos → entregas e dependências → competências e comunicação → implantação → evidências de adoção → resultados de negócio.

## Como registrar novas relações

Ao consolidar um conhecimento, indicar: **origem**, **destino**, **tipo de relação**, **justificativa**, **exemplo verificável** e **fonte** (quando aplicável). Evitar setas que apenas afirmam uma associação sem explicá-la.

[Voltar à biblioteca](README.md)
