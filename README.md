# MER - Ordem de Serviços em Oficina Mecânica
## Modelo de Entidade e Relacionamento vinculado ao Controle e Gerenciamento de Ordem de Serviços em Oficina Mecânica.
### Levantamento de Requisitos:
- Clientes solicitam serviços de revisão periódica ou manutenção;
- Peças e Serviços podem estar cobertos pela garantida do fabricante do veículo;
- O veículo para qual o serviço é solicitado é designado para uma equipe de mecânicos;
- A equipe de mecânicos identifica as peças e serviços necessários a serem efetuados no veículo;
- A equipe de mecânicos abre uma ordem de serviço com as peças, os serviços, valor e data de liberação do veículo;
- Os valores de peças e serviços que compõem a OS devem ser obtidos em tabelas de referência de peças e mão-de-obra;
- O Cliente pode ou não autorizar a OS;
- A mesma equipe que abriu a ordem de serviço fica responsável pela execução da mesma se aprovada pelo cliente;
- Os mecânicos que compõem uma equipe devem ser identificados por um código, nome, endereço e especialidade;
- Cada especialidade tem um custo horário;
- Cada peça tem um valor e uma quantidade em estoque;
- A OS deve ter as seguintes informações: número, data de emissão, valor, status, data de conclusão do serviço;
- Uma OS pode ter vários tipos de peças e de serviços associados.
