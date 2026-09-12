<h1 align="center">♻️ Recycle Rush — reciclar virou missão</h1>

<p align="center">
  <strong>Um jogo educativo 2D que transforma a separação de resíduos em decisões práticas — com evolução reportada de 25% para 90% de acertos em uma aplicação real com crianças.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Godot-4.6.1-478CBF?logo=godot-engine&amp;logoColor=white" alt="Godot 4.6.1">
  <img src="https://img.shields.io/badge/GDScript-478CBF?logo=godot-engine&amp;logoColor=white" alt="GDScript">
  <img src="https://img.shields.io/badge/Plataforma-Windows%20x64-0078D6?logo=windows&amp;logoColor=white" alt="Windows x64">
  <img src="https://img.shields.io/badge/EdTech-Educa%C3%A7%C3%A3o%20Ambiental-2E7D32" alt="EdTech - Educação Ambiental">
  <img src="https://img.shields.io/badge/Release-em%20prepara%C3%A7%C3%A3o-F9A825" alt="Release em preparação">
</p>

<p align="center">
  <a href="#download"><strong>⬇️ Download e instruções</strong></a>
  &nbsp;•&nbsp;
  <a href="#evidencias"><strong>🔬 Explorar as evidências</strong></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/teixeirads/RecycleRush/releases"><strong>📦 GitHub Releases</strong></a>
</p>

---

<a id="the-impact"></a>

## 🎯 The Impact — o resultado

> ### **25% → 90% de acertos**
>
> Resultado reportado após cerca de **10 minutos de interação** com o Recycle Rush em uma aplicação exploratória com crianças. Consulte a [análise da aplicação](docs/Semin%C3%A1rio%203%20-%20RecycleRush.pdf).

| Indicador principal | Antes do jogo | Depois do jogo | Evolução observada |
|---|---:|---:|---:|
| Taxa geral de acertos reportada | **25%** | **90%** | **+65 pontos percentuais** |

O teste envolveu **4 crianças de 10 a 12 anos**. Elas responderam a perguntas sobre o descarte de papel, plástico, casca de banana e metal, jogaram uma sessão mediada e, em seguida, responderam novamente às mesmas questões. Após a atividade, foi observada uma melhora imediata no desempenho da amostra. O desenho exploratório não permite atribuir causalidade isolada ao jogo, mas oferece um sinal concreto de potencial pedagógico.

### Como interpretar o resultado

- **Amostra:** 4 participantes, entre 10 e 12 anos.
- **Intervenção:** aproximadamente 10 minutos de jogo, com mediação da equipe nas fases mais difíceis.
- **Instrumento:** questionário pré e pós-jogo sobre separação de resíduos.
- **Leitura responsável:** trata-se de uma validação exploratória, sem grupo de controle e sem medição de retenção de longo prazo. O resultado sinaliza potencial pedagógico, mas não deve ser generalizado para toda a população infantil.

<details>
<summary><strong>Nota de transparência sobre a consolidação dos dados</strong></summary>

O Seminário 3 apresenta **25% → 90%** como taxa geral consolidada e utiliza esse resultado na conclusão. O mesmo documento também registra uma contagem de respostas que não coincide integralmente com esse percentual. Por isso, este README identifica 90% como **valor reportado** e recomenda reconciliar a planilha-base antes de uma publicação científica formal. Em ambas as leituras, os dados apontam melhora expressiva no desempenho imediato da pequena amostra.

</details>

## 🌱 Do problema à solução

| Etapa | Decisão de design | Evidência no projeto |
|---|---|---|
| **Problema** | O ensino exclusivamente teórico nem sempre sustenta a atenção ou transforma conceitos ambientais em decisões práticas. | Diagnóstico e fundamentação reunidos no Seminário 1. |
| **Solução** | Converter a separação de resíduos em um desafio de plataforma 2D, com associação visual entre objetos e lixeiras. | Protótipo desenvolvido em Godot, com personagem, fases, resíduos e lixeiras coloridas. |
| **Validação** | Comparar respostas antes e depois de uma sessão de jogo, além de observar dificuldades de navegação e compreensão. | Protocolo pré/pós-jogo e sessão mediada descritos nos Seminários 2 e 3. |
| **Resultado** | Medir o desempenho imediato e transformar os achados em melhorias de UX. | Ganho reportado no pós-teste, acompanhado de recomendações de tutorial e balanceamento. |

O objetivo do Recycle Rush não é apenas explicar reciclagem. É permitir que a criança **pratique a decisão correta**, receba retorno imediato e conecte a experiência do jogo a situações de casa, da escola e da comunidade.

## 🎮 Gameplay & Mechanics

O jogador controla um pinguim em fases de plataforma 2D. Durante o percurso, encontra resíduos, identifica o material e associa cada item à lixeira correta. O desafio combina coordenação motora, reconhecimento visual, memória e tomada de decisão. A sessão usada no estudo foi mediada pela equipe, especialmente nos trechos de maior dificuldade.

### Core loop

**Explorar a fase → encontrar um resíduo → identificar o material → selecionar a lixeira correta → receber feedback → avançar e repetir**

1. **Exploração:** navegar pelo cenário, saltar entre plataformas e localizar os resíduos.
2. **Classificação:** reconhecer papel, plástico, vidro, metal ou material orgânico.
3. **Associação visual:** relacionar o item às lixeiras codificadas por cor — azul, vermelho, verde, amarelo e marrom.
4. **Feedback imediato:** acompanhar o progresso por lixeira e tornar cada tentativa informativa; pontuação e reforços visuais adicionais integram a evolução planejada do design.
5. **Progressão:** combinar o conteúdo pedagógico com tempo, obstáculos e inimigos para aumentar gradualmente o desafio.

### Controles básicos

| Ação | Teclado |
|---|---|
| Mover para a esquerda | `A` ou `←` |
| Mover para a direita | `D` ou `→` |
| Pular | `W`, `Espaço` ou `↑` |
| Agachar | `S` |
| Interagir / agarrar | `F` |

### Curva de aprendizado recomendada após os testes

| Momento | Objetivo de UX | Estado no ciclo de produto |
|---|---|---|
| **Entrada** | Ensinar movimento e salto com baixa carga cognitiva. | Tutorial identificado como prioridade após a aplicação. |
| **Prática guiada** | Apresentar poucas categorias e feedback claro. | Progressão recomendada para a próxima iteração. |
| **Desafio** | Introduzir obstáculos, inimigos e tempo de maneira gradual. | Balanceamento necessário nas fases iniciais. |
| **Reflexão** | Retomar as escolhas em conversa ou questionário pós-jogo. | Etapa já utilizada no protocolo mediado. |

Os testes revelaram um ponto importante: algumas crianças tiveram mais dificuldade com a **mecânica de plataforma e os inimigos** do que com o conteúdo ambiental. A principal evolução de UX planejada é, portanto, um tutorial inicial, seguida pelo ajuste das fases de entrada e pela revisão da faixa etária recomendada.

<a id="evidencias"></a>

## 🔬 Evidence & Research — a ciência

Explore a fundamentação teórica, o desenho da intervenção e a análise dos dados nos documentos de apoio:

| Documento | Conteúdo | Por que consultar |
|---|---|---|
| [Seminário 1 — Fundamentação e diagnóstico](docs/Semin%C3%A1rio%201%20-%20RecycleRush.pdf) | Contextualização do problema, educação ambiental infantil, justificativa para aprendizagem lúdica, diagnóstico e primeiras imagens do jogo. | Explica **por que** uma intervenção prática e interativa foi escolhida. |
| [Seminário 2 — Metodologia da intervenção](docs/Semin%C3%A1rio%202%20-%20RecycleRush.pdf) | Gameplay proposto, protocolo de aplicação, questionários pré/pós, recursos, cronograma e indicadores planejados. | Documenta **como** a experiência pedagógica foi estruturada e avaliada. |
| [Seminário 3 — Aplicação e resultados](docs/Semin%C3%A1rio%203%20-%20RecycleRush.pdf) | Perfil dos participantes, sessão mediada, respostas antes/depois, evolução por categoria, análise crítica e próximos ajustes. | Mostra **o que aconteceu** na aplicação real e quais decisões de UX vieram dos dados. |

### Protocolo de validação

1. Aplicação de um questionário inicial sobre a separação de resíduos.
2. Sessão prática e mediada com o Recycle Rush.
3. Reaplicação das perguntas após o jogo, em dinâmica entre duplas.
4. Comparação do desempenho e registro das dificuldades observadas.
5. Conversão dos achados em backlog de produto: tutorial, balanceamento de fases, revisão dos inimigos e nova rodada de testes.

Esse ciclo conecta **pesquisa → design → implementação → evidência → iteração**, tratando o jogo como uma intervenção educacional em evolução.

## ⚙️ Technical Specs

| Item | Especificação |
|---|---|
| Engine | **Godot Engine 4.6.1 stable** |
| Linguagem | **GDScript** |
| Gênero | Plataforma educacional 2D |
| Fases identificadas | `main`, `forest` e `tropic` |
| Arquitetura de gameplay | `CharacterBody2D`, `AnimatedSprite2D` e `TileMapLayer` |
| Resolução interna | `400 × 208`, com stretch por `canvas_items` |
| Perfil de renderização | Mobile renderer; driver D3D12 no Windows |
| Build auditado | Windows x64 (`PE32+`, AMD64), exportado com template Mono debug |

### Game loop e organização técnica

- O controlador público processa gravidade, entrada horizontal, salto e movimento por `move_and_slide()`; o build aplicado também contém interação com resíduos e lixeiras.
- O estado do personagem controla animações de `idle`, `walk` e `jump`, oferecendo feedback visual contínuo à ação da criança.
- Cenas e recursos são separados por responsabilidade em `scenes/`, `entities/`, `tiles/` e `sprites/`, facilitando a manutenção de fases e assets 2D.
- `TileMapLayer` organiza terreno e decoração; parallax e elementos animados constroem profundidade sem abandonar a leitura visual simples do pixel art.
- Resíduos e lixeiras formam cinco pares explícitos — papel, plástico, vidro, metal e orgânico — e cada lixeira mantém seu próprio contador de progresso.
- O final de cada fase reage à entrada do personagem e carrega a próxima cena, fechando o ciclo de exploração, classificação e progressão.

<details>
<summary><strong>Auditoria técnica do build e pipeline de assets</strong></summary>

O pacote PCK está embutido no executável e reúne **282 entradas**, incluindo 20 cenas compiladas, 8 scripts GDScript, 103 texturas, 4 streams de áudio MP3 e 3 recursos de TileSet. A separação entre cenas, scripts e recursos facilita a composição modular; para produção, o pacote deve ser reexportado com o template `release` e somente com assets cuja redistribuição esteja autorizada.

| Propriedade | Valor |
|---|---|
| Arquivo local | `bin/RecycleRush.exe` |
| Versão no executável | `1.0.0.0` |
| Tamanho | `99,41 MiB` |
| Arquitetura | Windows x64 / AMD64 |
| SHA-256 | `434A98D44CE8DE7127EE49140F39105891102CE96E2F75232D219ACF40138918` |
| Assinatura digital | Não assinada |

</details>

> **Escopo do código público:** o controlador de movimento está em [`entities/character.gd`](entities/character.gd), a configuração em [`project.godot`](project.godot) e as cenas em [`scenes/`](scenes/). A lógica pedagógica completa é demonstrada no executável e documentada nos materiais de intervenção; sua implementação ainda deve ser sincronizada integralmente com o código-fonte público.

<a id="download"></a>

## ⬇️ Download e execução

### Como jogar pela versão para Windows

➡️ **[Acesse a página oficial de GitHub Releases](https://github.com/teixeirads/RecycleRush/releases)**

> **Status atual:** a primeira Release pública ainda está em preparação. Enquanto a página não exibir uma versão com assets, não há um download público recomendado.

Quando a Release estiver disponível:

1. Abra a versão mais recente na página de Releases.
2. Expanda a seção **Assets**.
3. Baixe o arquivo `RecycleRush.exe`.
4. Verifique a origem e, quando disponível, compare o hash SHA-256 com o valor publicado na Release.
5. Execute `RecycleRush.exe`. O Godot não precisa estar instalado para jogar o build exportado.

O executável distribuível ficará em **GitHub Releases** para separar o binário pesado do histórico do código-fonte, oferecer downloads versionados via HTTPS e reunir notas, hashes e arquivos de cada versão em um local rastreável. Isso melhora desempenho do repositório e segurança operacional, embora não substitua assinatura digital nem auditoria de licenças. Se a página estiver sem assets, evite cópias hospedadas por terceiros.

### Verificação do artefato local — pré-release

O arquivo em `bin/RecycleRush.exe` é um artefato local para validação e ainda não representa uma Release de produção. Para conferir sua integridade no PowerShell:

```powershell
Get-FileHash .\bin\RecycleRush.exe -Algorithm SHA256
```

O resultado esperado é `434A98D44CE8DE7127EE49140F39105891102CE96E2F75232D219ACF40138918`.

> O Windows pode exibir um alerta de reputação para executáveis ainda não assinados. Confirme que o download veio da página oficial e que o hash coincide antes de executar. Não prossiga se a origem ou o hash forem diferentes.

> **Checklist antes da primeira Release:** o executável auditado usa o template `debug` e inclui uma faixa de áudio de terceiros associada à trilha de *UNDERTALE*. Gere um export com template `release` e confirme a autorização de todos os áudios, sprites e fontes — ou substitua-os — antes de publicar o binário. GitHub Releases melhora versionamento e rastreabilidade, mas não substitui assinatura digital nem auditoria de licenças.

## 🧭 Próximas iterações

- Criar um tutorial jogável antes das fases avaliadas.
- Reduzir a dificuldade inicial e introduzir inimigos progressivamente.
- Atualizar as referências internas do projeto após a reorganização de `Cena/` para `scenes/`.
- Sincronizar no repositório toda a lógica presente no build aplicado.
- Gerar um build de produção com template `release`, preferencialmente sem o template Mono quando C# não for necessário.
- Auditar e documentar licenças de áudio, sprites e fontes antes da distribuição pública.
- Repetir o estudo com uma amostra maior, grupo de comparação e teste de retenção posterior.
- Registrar telemetria ética e anônima de erros, tempo e evolução entre tentativas, com consentimento dos responsáveis.
- Reconciliar a base quantitativa e publicar os dados anonimizados junto ao protocolo de análise.

## 👥 Créditos, referências e contato

### Equipe do estudo e do protótipo

Projeto apresentado no contexto da **UNIVALI — Campus Kobrasol (2026)** por:

- Abner Juda
- Gustavo Mena
- Pedro Knies
- Davi Teixeira
- Robert Cesar

O trabalho foi desenvolvido coletivamente no contexto acadêmico; as responsabilidades individuais ainda não estão documentadas no repositório. A manutenção deste fork público é realizada por [Davi de Souza Teixeira](https://github.com/teixeirads), a partir de [AJGamer10/recycle-rush](https://github.com/AJGamer10/recycle-rush).

Os assets identificados como **Seasonal Tilesets** e **Sprite Pack 6**, de GrafxKid, possuem licença [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Consulte os arquivos de licença de cada pacote antes de reutilizar outros assets.

> O repositório ainda não possui uma licença geral na raiz. A ausência de licença não concede permissão automática para copiar, modificar ou redistribuir o código.

### Referências e leituras de base

- NEVES, Gisele Aparecida dos Santos. [*Desafios da inserção da educação ambiental nas escolas para o alcance da sustentabilidade*](https://repositorio.uninter.com/handle/1/1161). UNINTER, 2022.
- LIMA, Célia Fernanda; FAJARDO, Vanessa. [*Falta de áreas verdes impacta a educação e a rotina escolar*](https://lunetas.com.br/falta-de-areas-verdes-impacta-a-educacao-e-a-rotina-escolar/). Portal Lunetas, 2024.
- [*Práticas sustentáveis: o impacto na formação ambiental dos alunos*](https://g1.globo.com/pr/parana/especial-publicitario/educacao-adventista/educacao-adventista/noticia/2024/12/26/praticas-sustentaveis-o-impacto-na-formacao-ambiental-dos-alunos.ghtml). G1, 2024.

### Contato

- GitHub: [@teixeirads](https://github.com/teixeirads)
- LinkedIn: [Davi de Souza Teixeira](https://www.linkedin.com/in/teixeiradss)
- Sugestões e bugs: [abra uma issue](https://github.com/teixeirads/RecycleRush/issues)

---

<p align="center">
  <strong>Aprender a reciclar é transformar uma escolha cotidiana em hábito.</strong>
</p>
