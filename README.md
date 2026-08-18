# projeto-pratico

Repositório criado para a avaliação prática de Git e GitHub.

## Funcionalidade: Atualização do IOF em produtos de seguro

Esta funcionalidade permitirá atualizar o percentual de IOF (Imposto sobre
Operações Financeiras) aplicado aos produtos de seguro oferecidos pela
empresa, contemplando as seguintes linhas:

- Seguro Automóvel
- Seguro Empresarial
- Seguro Vida

O sistema passará a calcular o valor do prêmio considerando a alíquota de
IOF vigente para cada tipo de seguro, permitindo ajustes futuros sempre que
a legislação for atualizada.


### Critérios de aceite

- O sistema deve permitir cadastrar a alíquota de IOF vigente para cada
  produto (Automóvel, Empresarial e Vida) de forma independente.
- O cálculo do prêmio deve refletir automaticamente a alíquota configurada.
- Alterações na alíquota devem ser registradas com data de vigência, para
  permitir consulta do histórico de mudanças.

  
## Versionamento Semântico

Este projeto utiliza o [Versionamento Semântico (SemVer)](https://semver.org/lang/pt-BR/)
para nomear suas versões, seguindo o padrão `MAJOR.MINOR.PATCH` (ex: `1.0.0`).

- **MAJOR**: incrementado quando são feitas alterações incompatíveis com
  versões anteriores (*breaking changes*), ou seja, mudanças que quebram a
  compatibilidade com quem já usa o projeto.
- **MINOR**: incrementado quando novas funcionalidades são adicionadas de
  forma compatível com versões anteriores, sem quebrar nada que já existia.
- **PATCH**: incrementado quando são feitas correções de bugs compatíveis
  com versões anteriores, sem adicionar novas funcionalidades.

Exemplo: a versão `1.0.0` representa a primeira versão estável do projeto.
Uma correção de bug geraria `1.0.1`; uma nova funcionalidade geraria `1.1.0`;
uma mudança que quebra compatibilidade geraria `2.0.0`.