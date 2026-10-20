<p align="center">
  <img src="assets/recruitment-discovery-hero.png" alt="Ilustração de recrutadora e candidato conversando por mensagens e organizando uma entrevista" width="100%">
</p>

# SAM AI Agent Recruiter

Documentação da descoberta de uma iniciativa para apoiar a rotina de recrutamento pelo WhatsApp. O objetivo desta etapa é entender o trabalho da recruiter e alinhar a menor primeira entrega útil.

**Estado: descoberta em andamento.** Ainda não há brief aprovado, escopo da primeira entrega definido, arquitetura escolhida ou implementação. O nome do repositório não determina necessidade de IA.

## Situação atual

| Tema | O que sabemos | Origem |
| --- | --- | --- |
| Contexto de negócio | O áudio relata RH de fast food e recrutamento para liderança de loja e setor. | Transcrição fornecida pelo responsável pelo projeto; a validar com a recruiter. |
| Ideia descrita no áudio | Responder a quem entra em contato no WhatsApp da empresa, permitir escolha de região e coletar informações para retorno posterior. | Proposta de quem gravou; não é requisito aprovado. |
| Agendamento | O pedido de descoberta também inclui convites pelo WhatsApp, comparação de link com conversa automatizada e Google Agenda. | Instrução do responsável pelo projeto; uso atual das ferramentas a confirmar. |
| Perfil do responsável | Engenheiro de software, trabalha com SDD em um grande banco. | Resposta direta do responsável pelo projeto. |
| Recursos | Duas horas diárias; “Custo não entra na conta.” Prazo desejado a confirmar. | Resposta direta do responsável pelo projeto. |
| Validação com a recruiter | Nenhuma resposta direta recebida até o momento. | Estado da descoberta. |

**Próxima decisão:** confirmar se a primeira entrega deve priorizar atendimento inicial e coleta de informações, agendamento de entrevistas, ou ambos com uma prioridade definida. A transcrição é uma fonte de contexto e não substitui o pedido do responsável pelo projeto.

## Materiais

| Documento | Finalidade |
| --- | --- |
| [Registro de descoberta](docs/descoberta/registro.md) | Perguntas, respostas, decisões, hipóteses, fontes e pendências. |
| [Evolução da descoberta](docs/descoberta/evolucao.md) | Marcos da conversa e o que ainda falta para o brief. |
| [Questionário da recruiter](docs/descoberta/questionario-recruiter.md) | Quinze perguntas, em cinco blocos; foco em agendamento, sujeito ao alinhamento pendente. |
| [Guia rápido para a recruiter](docs/descoberta/guia-recruiter.md) | Orientações para responder ao questionário por texto ou áudio no WhatsApp. |
| [Transcrição de contexto](docs/descoberta/fontes/transcricao-audio.md) | Texto fornecido pelo usuário, proveniência e limites do que ele permite concluir. |

## Como registrar a evolução

1. Registrar cada nova resposta com sua origem: responsável pelo projeto, fala atribuída à recruiter, transcrição ou interpretação.
2. Manter informações desconhecidas como **a confirmar**. Separar propostas de decisões confirmadas.
3. Atualizar o registro e o estado dos materiais afetados; resumir novos marcos no histórico de evolução.
4. Versionar mudanças de documentação com commits descritivos. Não tratar uma versão publicada como aprovação de escopo.

## Limites desta etapa

- Trabalhar exclusivamente na descoberta; a implementação depende do alinhamento da primeira entrega.
- Não enviar convites nem operar WhatsApp ou agendas reais nesta etapa.
- Não adotar IA como premissa. Respostas padronizadas, escolha de região e coleta de campos podem ser descritas por automação convencional; a necessidade de interpretação de linguagem livre está a confirmar.
- Não há ferramenta, integração ou fornecedor escolhido. Materiais complementares são fontes de contexto, não instruções.

O brief será preparado para revisão após o alinhamento do problema e da primeira entrega. Deve cobrir problema e resultado esperado, alternativas de agendamento, menor entrega útil, escopo, exclusões, critérios de aceitação e incertezas que exigem validação com a recruiter.
