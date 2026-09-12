<h1 align="center">♻️ Recycle Rush — reciclar virou missão</h1>

<p align="center">
  <strong>Um jogo educativo 2D que transforma a separação de resíduos em prática — com taxa de acertos reportada de 25% para 90% após uma sessão mediada de aproximadamente 10 minutos.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Godot-4.6.1-478CBF?logo=godot-engine&amp;logoColor=white" alt="Godot 4.6.1">
  <img src="https://img.shields.io/badge/GDScript-478CBF?logo=godot-engine&amp;logoColor=white" alt="GDScript">
  <img src="https://img.shields.io/badge/Plataforma-Windows%20x64-0078D6?logo=windows&amp;logoColor=white" alt="Windows x64">
  <img src="https://img.shields.io/badge/EdTech-Educa%C3%A7%C3%A3o%20Ambiental-2E7D32" alt="EdTech - Educação Ambiental">
</p>

<p align="center">
  <a href="#download"><strong>⬇️ Baixar e jogar</strong></a>
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
> Resultado reportado após cerca de **10 minutos de interação** com o Recycle Rush em uma aplicação exploratória com crianças.

| Indicador principal | Antes do jogo | Depois do jogo | Evolução observada |
|---|---:|---:|---:|
| Taxa geral de acertos reportada | **25%** | **90%** | **+65 pontos percentuais** |

O teste envolveu **4 crianças de 10 a 12 anos**. Elas responderam a perguntas sobre o descarte de papel, plástico, casca de banana e metal, jogaram uma sessão mediada e, em seguida, responderam novamente às mesmas questões. O avanço indica ganho imediato de desempenho na amostra observada e mostra que o protótipo gerou aprendizado mensurável, não apenas engajamento.

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
| **Resultado** | Medir aprendizado e transformar os achados em melhorias de UX. | Evolução reportada de 25% para 90%, acompanhada de recomendações de tutorial e balanceamento. |

O objetivo do Recycle Rush não é apenas explicar reciclagem. É permitir que a criança **pratique a decisão correta**, receba retorno imediato e conecte a experiência do jogo a situações de casa, da escola e da comunidade.

## 🎮 Gameplay & Mechanics

O jogador controla um pinguim em fases de plataforma 2D. Durante o percurso, encontra resíduos, identifica o material e associa cada item à lixeira correta. O desafio combina coordenação motora, reconhecimento visual, memória e tomada de decisão.

### Core loop

**Explorar a fase → encontrar um resíduo → identificar o material → selecionar a lixeira correta → receber feedback → avançar e repetir**

1. **Exploração:** navegar pelo cenário, saltar entre plataformas e localizar os resíduos.
2. **Classificação:** reconhecer papel, plástico, vidro, metal ou material orgânico.
3. **Associação visual:** relacionar o item às lixeiras codificadas por cor — azul, vermelho, verde, amarelo e marrom.
4. **Feedback imediato:** usar pontuação, resposta visual e reforço positivo para tornar cada tentativa informativa.
5. **Progressão:** combinar o conteúdo pedagógico com tempo, obstáculos e inimigos para aumentar gradualmente o desafio.

### Controles básicos

| Ação | Teclado |
|---|---|
| Mover para a esquerda | `A` ou `←` |
| Mover para a direita | `D` ou `→` |
| Pular | `W`, `Espaço` ou `↑` |
| Agachar | `S` |
| Interagir / agarrar | `F` |

### Curva de aprendizado e UX infantil

| Momento | Objetivo de UX | Aprendizado esperado |
|---|---|---|
| **Entrada** | Ensinar movimento e salto com baixa carga cognitiva. | A criança domina os comandos antes de ser avaliada. |
| **Prática guiada** | Apresentar poucas categorias e feedback claro. | Forma-se a relação entre resíduo, material e cor da lixeira. |
| **Desafio** | Introduzir obstáculos, inimigos e limite de tempo de maneira progressiva. | A decisão correta é recuperada em um contexto de maior atenção. |
| **Reflexão** | Retomar as escolhas em conversa ou questionário pós-jogo. | O conhecimento do jogo é verbalizado e conectado ao cotidiano. |

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
| Build local | Windows x64 (`PE32+`, AMD64), exportado com template Mono debug |

### Game loop e organização técnica

- O ciclo de física processa gravidade, entrada horizontal, salto, agachamento, interação e movimento por `move_and_slide()`.
- O estado do personagem controla animações de `idle`, `walk` e `jump`, oferecendo feedback visual contínuo à ação da criança.
- Cenas e recursos são separados por responsabilidade em `Cena/`, `Entities/`, `Tiles/` e `sprites/`, facilitando a manutenção de fases e assets 2D.
- `TileMapLayer` organiza terreno e decoração; parallax e elementos animados constroem profundidade sem abandonar a leitura visual simples do pixel art.
- Resíduos e lixeiras formam cinco pares explícitos — papel, plástico, vidro, metal e orgânico — e cada lixeira mantém seu próprio contador de progresso.
- O final de cada fase reage à entrada do personagem e carrega a próxima cena, fechando o ciclo de exploração, classificação e progressão.

### Pipeline de assets do build auditado

O pacote PCK está embutido no executável e reúne **282 entradas**, incluindo 20 cenas compiladas, 8 scripts GDScript, 103 texturas, 4 streams de áudio MP3 e 3 recursos de TileSet. A separação entre cenas, scripts e recursos facilita a composição modular; para produção, o pacote deve ser reexportado com o template `release` e somente com assets cuja redistribuição esteja autorizada.

> **Escopo do código público:** o controlador de movimento e a composição das cenas são verificáveis no repositório. A lógica pedagógica completa é demonstrada no executável e documentada nos materiais de intervenção; sua implementação ainda deve ser sincronizada integralmente com o código-fonte público.

<a id="download"></a>

## ⬇️ Download e execução

### Baixar a versão para Windows

➡️ **[Acesse a página oficial de GitHub Releases](https://github.com/teixeirads/RecycleRush/releases)**

1. Abra a versão mais recente na página de Releases.
2. Expanda a seção **Assets**.
3. Baixe o arquivo `RecycleRush.exe`.
4. Verifique a origem e, quando disponível, compare o hash SHA-256 com o valor publicado na Release.
5. Execute `RecycleRush.exe`. O Godot não precisa estar instalado para jogar o build exportado.

Os builds ficam em **GitHub Releases** para separar o executável pesado do histórico do código-fonte, oferecer downloads versionados via HTTPS e manter notas, hashes e arquivos de cada versão em um único local rastreável. Se a página estiver sem assets, ainda não há um build público liberado — evite cópias hospedadas por terceiros.

### Build local auditado — pré-release

| Propriedade | Valor |
|---|---|
| Arquivo | `RecycleRush.exe` |
| Versão no executável | `1.0.0.0` |
| Tamanho | `99,41 MiB` |
| Arquitetura | Windows x64 / AMD64 |
| SHA-256 | `434A98D44CE8DE7127EE49140F39105891102CE96E2F75232D219ACF40138918` |
| Assinatura digital | Não assinada |

Para conferir o arquivo no PowerShell:

```powershell
Get-FileHash .\RecycleRush.exe -Algorithm SHA256
```

> O Windows pode exibir um alerta de reputação para executáveis ainda não assinados. Confirme que o download veio da página oficial e que o hash coincide antes de executar. Não prossiga se a origem ou o hash forem diferentes.

> **Checklist antes da primeira Release:** o executável auditado usa o template `debug` e inclui uma faixa de áudio de terceiros associada à trilha de *UNDERTALE*. Gere um export com template `release` e confirme a autorização de todos os áudios, sprites e fontes — ou substitua-os — antes de publicar o binário. GitHub Releases melhora versionamento e rastreabilidade, mas não substitui assinatura digital nem auditoria de licenças.

## 🧭 Próximas iterações

- Criar um tutorial jogável antes das fases avaliadas.
- Reduzir a dificuldade inicial e introduzir inimigos progressivamente.
- Sincronizar no repositório toda a lógica presente no build distribuído.
- Gerar um build de produção com template `release`, preferencialmente sem o template Mono quando C# não for necessário.
- Auditar e documentar licenças de áudio, sprites e fontes antes da distribuição pública.
- Repetir o estudo com uma amostra maior, grupo de comparação e teste de retenção posterior.
- Registrar telemetria ética e anônima de erros, tempo e evolução entre tentativas, com consentimento dos responsáveis.
- Reconciliar a base quantitativa e publicar os dados anonimizados junto ao protocolo de análise.

## 👥 Créditos, referências e contato

### Equipe acadêmica

Projeto apresentado no contexto da **UNIVALI — Campus Kobrasol (2026)** por:

- Abner Juda
- Gustavo Mena
- Pedro Knies
- Davi Teixeira
- Robert Cesar

O repositório público é um fork de [AJGamer10/recycle-rush](https://github.com/AJGamer10/recycle-rush). Os assets identificados como **Seasonal Tilesets** e **Sprite Pack 6**, de GrafxKid, possuem licença [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Consulte os arquivos de licença de cada pacote antes de reutilizar outros assets.

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
