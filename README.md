<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/sociare-logo-branco.svg">
    <img src="assets/sociare-logo.svg" alt="Sociare" width="340">
  </picture>
</p>

<h3 align="center">Software de gestão para o terceiro setor</h3>

<p align="center">Financeiro, prestação de contas e a rotina de APAEs, ONGs e associações num lugar só.</p>

<p align="center">
  🔗 <a href="https://gestaosociare.com.br"><strong>gestaosociare.com.br</strong></a> &nbsp;·&nbsp; 📷 <a href="https://instagram.com/gestaosociare"><strong>@gestaosociare</strong></a> &nbsp;·&nbsp; 🟢 Piloto em andamento
</p>

---

## O problema

Toda instituição do terceiro setor conhece o fim de mês:

- notas e comprovantes espalhados entre pastas, e-mails e WhatsApp;
- recursos de convênios municipais, estaduais e federais, emendas e doações que **não podem se misturar**;
- uma prestação de contas montada à mão em planilha, a poucos dias do prazo, com medo de glosa;
- uma diretoria que muda a cada mandato e precisa entender os números rápido.

Quem faz a gestão passa mais tempo organizando papel do que cuidando da instituição.

## A solução

O **Sociare** organiza cada lançamento pela fonte de recurso desde a entrada da nota. Quando o mês fecha, a prestação de contas já está pronta, no formato que a instituição usa, com os comprovantes anexados e o histórico de quem fez cada alteração.

> O nome vem do latim *sociare*: unir, associar. O símbolo é um **S de dois elos** que se encaixam, como a instituição e quem ela atende, o recurso e quem presta contas dele.

## Como nasceu

O Sociare não começou numa tela em branco. O ponto de partida foi uma visita à **APAE de Américo Brasiliense/SP**, acompanhando de perto a gestora no fechamento do mês: a planilha que ela usa de verdade, as fontes de recurso, os prazos e o modelo cobrado pela prefeitura.

A partir daí, o processo seguiu quatro etapas:

1. **Imersão** nas dores reais da gestão, com os materiais do dia a dia.
2. **Direção visual**: cada tela desenhada e aprovada antes do código, no modo claro e no escuro, do celular ao monitor grande.
3. **Design system próprio**, com regras de cor, tipografia, linguagem e acessibilidade.
4. **Construção por partes**: cada módulo com plano escrito, conferência, testes automatizados e revisão de segurança antes de ser entregue.

## Para quem

| Perfil | O que o Sociare resolve |
| --- | --- |
| **Gestora** | Notas, fontes de recurso, prazos e o que falta para fechar o mês, sem procurar |
| **Diretoria** | Relatórios claros, entendidos em segundos, mesmo por quem não é da área |
| **Profissionais** | Agenda e atendidos pelo celular, entre uma sessão e outra |
| **Secretaria** | Agenda da equipe e avisos às famílias |
| **Contador** | Acesso de leitura ao financeiro, sem risco de alterar nada |

## Módulos

### Financeiro e prestação de contas · em piloto

- Lançamentos de entrada, saída e transferência, com comprovante anexado
- Separação por fonte de recurso: convênios, emendas, doações e Nota Fiscal Paulista
- Competência separada da data de pagamento, como a prestação exige
- Fechamento mensal por fonte, com trava do mês fechado
- Caixa do mês e resumo visual dos recursos do ano
- Relatórios em PDF, prontos para a prefeitura e o conselho

### Próximas fases

- **Equipe:** convite por e-mail, com papel e permissão para cada pessoa
- **Agenda:** horários da equipe, remarcação e confirmação das famílias
- **Clínico:** prontuário imprimível, faltas e sessões do mês
- **Assistência social:** atividades, frequência e intercorrências

## Segurança e LGPD

O Sociare lida com dados financeiros e com dados de pessoas com deficiência, que a LGPD trata como sensíveis. Por isso, segurança é parte do projeto desde a primeira linha:

- 🔒 **Isolamento por instituição:** cada instituição enxerga só os próprios dados, com a regra aplicada no banco de dados e testada a cada mudança.
- ✉️ **Acesso só por convite**, com verificação em duas etapas para quem cuida do financeiro e para a diretoria.
- 🧾 **Nada se perde:** registros são cancelados com motivo, nunca apagados, e o histórico mostra quem mudou o quê e quando.
- 🙈 **Privacidade do atendido:** avisos e notificações nunca trazem nome completo nem dado de saúde.
- 🇧🇷 **Dados hospedados no Brasil.**

## Feito para ser usado por todos

- Tipografia **Atkinson Hyperlegible**, criada para pessoas com baixa visão, e números em **IBM Plex Sans**, alinhados nas colunas.
- Modo claro e escuro, com contraste conferido nos dois.
- Situação sempre com **cor, ícone e palavra**, para quem tem daltonismo e para o relatório impresso em preto e branco.
- Funciona no computador comum da instituição e em celulares de 360 px.

## Identidade

| | Cor | Uso |
| --- | --- | --- |
| <img src="assets/cor-0B2A4A.svg" width="40" alt="#0B2A4A"/> | **Marinho** `#0B2A4A` | Confiança: cabeçalho, títulos e números |
| <img src="assets/cor-00DE94.svg" width="40" alt="#00DE94"/> | **Menta** `#00DE94` | A cor da marca: o S, o progresso e os destaques |
| <img src="assets/cor-087A5E.svg" width="40" alt="#087A5E"/> | **Verde-água** `#087A5E` | A ação principal de cada tela |
| <img src="assets/cor-F3F8F7.svg" width="40" alt="#F3F8F7"/> | **Fundo** `#F3F8F7` | Leveza para muitas tabelas e números |

## Tecnologias

<p>
  <img src="https://skillicons.dev/icons?i=react,ts,vite,supabase,postgres,githubactions&perline=6" alt="React, TypeScript, Vite, Supabase, PostgreSQL, GitHub Actions"/>
</p>

React, TypeScript e Vite no front. Supabase (PostgreSQL, autenticação, armazenamento de arquivos e funções) na região de São Paulo. Testes automatizados de navegador e de isolamento entre instituições. Publicação contínua pelo GitHub Actions.

<sub>Este repositório é a vitrine do projeto. O código-fonte é privado.</sub>

---

<p align="center">
  <strong>Quer o Sociare na sua instituição?</strong><br>
  Fale com a gente pelo <a href="https://instagram.com/gestaosociare">Instagram</a> ou pelo site <a href="https://gestaosociare.com.br">gestaosociare.com.br</a>.
</p>

<p align="center"><sub>Um produto da <a href="https://vintadigital.com.br">Vinta</a>: marketing e tecnologia. © 2026 Vinta.</sub></p>
