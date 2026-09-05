<p align="center">
  <img src="Drift_icon.png" alt="Ícone do CutLabIA Studio" width="128" height="128">
</p>

<h1 align="center">CutLabIA Studio</h1>

<p align="center">
  <strong>O editor de vídeo gratuito para desktop que deixa seus vídeos com cara de pronto — não de "razoável".</strong>
</p>

<p align="center">
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest"><img src="https://img.shields.io/github/v/release/Velifag/Cut-Lab-IA-Studio?label=release" alt="Última versão"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-GPL--3.0-blue.svg" alt="Licença: GPL-3.0"></a>
  <img src="https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS%20%7C%20Android-lightgrey" alt="Plataformas: Linux | Windows | macOS | Android">
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.pt-BR.md"><strong>Português (Brasil)</strong></a> ·
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio">GitHub</a> ·
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest">Download</a> ·
  <a href="https://github.com/Velifag/Cut-Lab-IA-Studio/issues">Issues</a> ·
  <a href="LICENSE">Licença</a>
</p>

CutLabIA Studio é um editor de vídeo para desktop — um fork do [Drift](https://github.com/CutWire-Studios/Drift)
da CutWire Studios, distribuído sob a mesma licença GPL-3.0. Importe seus clipes, adicione efeitos,
legendas, figurinhas e música, e exporte um vídeo com acabamento profissional — **sem assinatura,
sem marca d'água e sem precisar de conta**.

Feito para as edições que as pessoas realmente fazem: Reels e Shorts, clipes de jogos, trabalhos
escolares, tutoriais, demonstrações de produto, memes e qualquer coisa que você queira deixar com
uma boa cara sem viver dentro de um navegador ou pagar mensalidade.

O que você vê na pré-visualização é o que você exporta. Um único compositor, um único resultado,
sem surpresas.

## Download

Baixe a versão para sua plataforma na
[última release](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest):

| Plataforma | Pacote |
|----------|---------|
| Linux | [AppImage](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |
| Windows | [Instalador (.exe)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) · [Versão portátil (zip)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |
| macOS | [Imagem de disco (.dmg, Apple Silicon)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |
| Android | [APK (arm64-v8a)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) · [APK (armeabi-v7a)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) · [APK (x86_64)](https://github.com/Velifag/Cut-Lab-IA-Studio/releases/latest) |

No celular, baixe `Drift-*-arm64-v8a.apk` da última release e instale (ou use `adb install Drift-*-arm64-v8a.apk`). Use a versão `x86_64` para emuladores.

Veja [todas as releases](https://github.com/Velifag/Cut-Lab-IA-Studio/releases) para versões anteriores e changelogs completos.

<!-- Ainda não distribuído no Flathub sob este nome — aquela listagem (org.cutwire.Drift) é da
     própria CutWire Studios. Uma submissão ao Flathub para este fork precisaria de um app id
     e uma revisão próprios. -->

## Capturas de tela

<p align="center">
  <img src="docs/screenshots/main-window.png" alt="O editor CutLabIA Studio: biblioteca de mídia à esquerda, pré-visualização de vídeo no centro, inspetor de propriedades à direita, linha do tempo embaixo" width="900">
</p>

<p align="center"><em>Tudo em uma única janela — mídia, pré-visualização, inspetor e linha do tempo</em></p>

<p align="center">
  <img src="docs/screenshots/timeline.png" alt="Linha do tempo com quatro faixas empilhadas: dois overlays de imagem, um título e uma faixa de vídeo mostrando miniaturas em filme" width="900">
</p>

<p align="center"><em>Uma linha do tempo multi-faixa de verdade, com overlays, títulos e miniaturas em filme</em></p>

<table>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/effects-panel.png" alt="Navegador de efeitos mostrando pré-visualizações em miniatura ao vivo de presets de glitch e distorção" width="380"><br>
      <strong>Efeitos que vendem o visual</strong><br>
      Cada preset é pré-visualizado em um quadro real
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/transitions-panel.png" alt="Navegador de transições com pré-visualizações animadas de presets de crossfade, wipe e push" width="380"><br>
      <strong>Transições com cara de caro</strong><br>
      Solte uma onde dois clipes se sobrepõem
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/stickers-panel.png" alt="Navegador de figurinhas com emojis agrupados por categoria" width="380"><br>
      <strong>Figurinhas e emojis na hora</strong><br>
      Busque, arraste e solte no canvas
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/text-styles.png" alt="Presets de estilo de texto incluindo neon, karaokê, fundo de palavra e manuscrito" width="380"><br>
      <strong>Títulos que realmente são vistos</strong><br>
      Neon, karaokê, destaques e estilos de palavra impactantes
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/templates-panel.png" alt="Navegador de templates mostrando visuais com múltiplos efeitos como Beat Drop e Glitch Cut" width="380"><br>
      <strong>Templates de visual em um clique</strong><br>
      Combos sincronizados com a música como Beat Drop e Glitch Cut
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/audio-effects.png" alt="Navegador de efeitos de áudio com EQ, compressor, limitador, noise gate, de-esser e nivelador de voz" width="380"><br>
      <strong>Áudio com som intencional</strong><br>
      EQ, compressor, gate, de-esser e ferramentas de voz
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/speed-fade.png" alt="Inspetor de velocidade e fade com presets de velocidade, reversão e sliders de fade in/out" width="380"><br>
      <strong>Velocidade, reversão e fades</strong><br>
      Câmera lenta, rampas, reversão e entradas/saídas limpas
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/subtitle-editor.png" alt="Editor de legendas listando linhas de legenda cronometradas, com a linha no ponto de reprodução destacada" width="380"><br>
      <strong>Legendas geradas a partir da própria fala</strong><br>
      Gere e depois edite cada linha
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="docs/screenshots/subject-cutout.png" alt="Diálogo de recorte de assunto com um marcador de clique na pessoa e o assunto isolado destacado" width="380"><br>
      <strong>Clique no assunto. Fique só com ele.</strong><br>
      Isole uma pessoa ou objeto em um clipe próprio
    </td>
    <td width="50%" align="center">
      <img src="docs/screenshots/export-dialog.png" alt="Diálogo de exportação com presets de redução de resolução e configurações avançadas de codificador" width="420"><br>
      <strong>Exportação igual à pré-visualização</strong><br>
      Presets simples à mão, controle extra quando você quiser
    </td>
  </tr>
</table>

## Recursos que realmente aparecem na edição

**Uma linha do tempo que se comporta como um editor de verdade.** Corte, divida, encaixe, faça
ripple, silencie ou oculte faixas, e desfaça qualquer coisa. Empilhe overlays, títulos e B-roll em
vez de brigar com um brinquedo de faixa única.

**Visuais em segundos, não em horas.** Efeitos por GPU, transições estilosas e templates de visual
reutilizáveis — para um clipe ir de material bruto a um resultado pronto sem abrir outro app.

**Texto, figurinhas, emojis e formas no canvas.** Títulos neon, legendas estilo karaokê, figurinhas
de reação e chamadas ficam no mesmo editor do corte.

**Legendas automáticas que você consegue corrigir de verdade.** A fala vira linhas de legenda
cronometradas. Edite o texto, ajuste o tempo e exporte com legendas que combinam com quem assiste
no mudo.

**Recortes, máscaras e chroma key.** Clique em um assunto e isole-o no próprio clipe. Mascare partes
de uma cena, ou remova um fundo verde quando precisar de uma composição mais limpa.

**Movimento que acompanha a batida.** Rampas de velocidade, reversão, fades e cortes que encaixam
na música — o tipo de ritmo que faz um clipe parecer planejado, não jogado.

**Ferramentas de áudio que limpam a mixagem.** Volume, fades, EQ, compressão, remoção de ruído e
efeitos de voz, para narração e música conviverem em vez de brigarem.

**Multicâmera para quando uma câmera não é suficiente.** Veja todos os ângulos ao mesmo tempo,
alterne entre câmeras e salve o resultado como um corte limpo — sem reconstruir a linha do tempo
na mão.

**Pacotes de projeto para compartilhar e fazer backup.** Empacote um projeto com sua mídia para que
a edição inteira viaje com você, em vez de quebrar assim que um caminho de arquivo muda.

**Exportação igual à pré-visualização.** MP4 com presets de qualidade, loops em GIF e exportação de
um trecho a partir de uma área de trabalho In/Out. O que você aprovou é o que você recebe.

## Acesso de agente — deixe uma IA editar com você

O CutLabIA Studio tem um **servidor MCP** embutido para ferramentas de IA locais. Ative o acesso de
agente e o Cursor, Claude Code, ou outro agente compatível pode trabalhar no projeto aberto:
importar mídia, posicionar e cortar clipes, mudar efeitos, capturar uma imagem da composição e
exportar.

Isso é um gancho de editor de verdade, não um chatbot colado numa página web. O agente vê a linha
do tempo e pode fazer edições que você consegue desfazer.

O acesso de agente fica **desligado até você ativá-lo**, e só escuta na sua própria máquina.
Configuração completa e notas de segurança estão no [guia do MCP](docs/MCP.md).

## Addons, sem inchar a instalação

Fontes, figurinhas, efeitos extras e modelos de transcrição de fala são baixados dentro do
CutLabIA Studio quando você precisa deles. Mantenha o app leve e baixe só os pacotes que combinam
com o vídeo que você está fazendo.

Abra o Gerenciador de Addons pelo cabeçalho, ou siga o aviso de instalação quando um recurso
precisar de um pacote.

## Por que escolher o CutLabIA Studio

A maioria dos editores "gratuitos" quer uma conta, uma marca d'água ou uma assinatura assim que o
vídeo começa a ficar bom. O CutLabIA Studio é o oposto: **seu, no seu computador, GPLv3, sem
barreira de login.**

É rápido o suficiente para um corte de rede social de 30 segundos e completo o suficiente para um
projeto de verdade — legendas, efeitos, áudio, recortes, multicâmera e uma linha do tempo assistida
por IA se você quiser.

## Ajude a traduzir o Drift

[![Translation status](https://hosted.weblate.org/widget/cutwire-drift/drift-desktop/multi-auto.svg)](https://hosted.weblate.org/engage/cutwire-drift/)

## Para desenvolvedores

Build, empacotamento, arquitetura e o protocolo do agente estão em `docs/`:

- [Build, testes, empacotamento e arquitetura](docs/BUILDING.md)
- [Efeitos por GPU](docs/gpu-effects.md)
- [Transições por GPU](docs/gpu-transitions.md)
- [Arquitetura do Time Echo](docs/time-echo-architecture.md)
- [Acesso de agente / MCP](docs/MCP.md)

## Ajuda e feedback

Encontrou um bug ou tem uma ideia? Abra uma
[issue no GitHub](https://github.com/Velifag/Cut-Lab-IA-Studio/issues).

## Licença

GPLv3 — veja [LICENSE](LICENSE).

## Histórico de estrelas

<a href="https://www.star-history.com/?repos=Velifag%2FCut-Lab-IA-Studio&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=Velifag/Cut-Lab-IA-Studio&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=Velifag/Cut-Lab-IA-Studio&type=date&legend=top-left" />
   <img alt="Gráfico de histórico de estrelas" src="https://api.star-history.com/chart?repos=Velifag/Cut-Lab-IA-Studio&type=date&legend=top-left" />
 </picture>
</a>

<p align="center">🌐 <a href="https://cutlabiastudio.com">cutlabiastudio.com</a></p>
