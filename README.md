# Open Player

## Português do Brasil

# Open Player

O **Open Player** é um player de mídia para desktop, desenvolvido com Electron e libVLC, criado para oferecer uma experiência simples, rápida e personalizável para reprodução de vídeos e áudios.

O projeto oferece suporte a diversos formatos de mídia, incluindo MP4, MKV, WebM, MOV, AVI, MPEG, MPG, M4V, OGV e outros formatos compatíveis com o libVLC. Também permite selecionar faixas de áudio e legendas, reproduzir conteúdos com múltiplos idiomas, trabalhar com legendas incorporadas ou externas e controlar volume, mute, velocidade, repetição e formato de vídeo.

## Principais recursos

- Reprodução de vídeos e áudios usando o motor **libVLC**.
- Suporte a múltiplos formatos de mídia.
- Seleção de faixas de áudio e legendas incorporadas.
- Suporte a legendas externas.
- Legendas forçadas ativadas automaticamente quando configuradas.
- Controle de volume, silenciar, velocidade de reprodução e sincronização de áudio e legenda.
- Retomada automática do ponto em que o vídeo foi interrompido.
- Repetição de vídeo, repetição da playlist e reprodução aleatória.
- Captura de quadros e geração de thumbnails.
- Ajuste do formato do vídeo: ajustar, cortar, esticar e tamanho real.
- Tela cheia, maximização, restauração e redimensionamento da janela.
- Suporte a controles XInput e DInput.
- Interface em português do Brasil e inglês.

## Modo Explorer

O **modo Explorer** permite organizar e navegar por vídeos diretamente dentro do player, sem precisar sair do aplicativo. É possível adicionar pastas e subpastas, visualizar os vídeos disponíveis, pesquisar arquivos, atualizar o conteúdo das pastas e abrir um vídeo diretamente pelo Explorer.

O modo Explorer também permite copiar vídeos para as pastas adicionadas, acompanhar o status de vídeos assistidos e, quando habilitado nas configurações, excluir vídeos com confirmação. Ao terminar um vídeo aberto pelo Explorer, o Open Player pode avançar automaticamente para o próximo vídeo da playlist. Essa função pode ser ativada ou desativada pelo usuário.

O player pode pausar o vídeo ao entrar no Explorer e retomar a reprodução ao voltar para o modo Play, conforme a configuração escolhida pelo usuário.

## Atalhos do player

Os atalhos podem ser personalizados nas configurações do Open Player. Os atalhos padrão incluem:

| Ação | Atalho padrão |
|---|---|
| Reproduzir ou pausar | Espaço |
| Voltar cinco segundos | Seta para a esquerda |
| Avançar cinco segundos | Seta para a direita |
| Tela cheia | F11 ou atalho configurado |
| Silenciar | M |
| Aumentar volume | Seta para cima |
| Diminuir volume | Seta para baixo |
| Alternar faixa de áudio | Ctrl + F |
| Alternar faixa de legenda | Ctrl + S |
| Alternar tela cheia | Enter ou atalho configurado |
| Reproduzir/pausar por botão de mídia | Botão Play/Pause do fone ou teclado multimídia |

As setas para cima e para baixo também podem controlar o volume enquanto o vídeo está em reprodução. O botão de silenciar localizado próximo à barra de volume alterna o estado de áudio sem interromper o vídeo.

## Atalhos do modo Explorer

O modo Explorer possui controles próprios para navegação e gerenciamento de arquivos:

| Ação | Controle |
|---|---|
| Voltar ao modo Play | Botão Play do Explorer |
| Voltar à pasta anterior | Botão Voltar |
| Ir para a pasta principal | Botão Início |
| Subir uma pasta | Botão Subir |
| Atualizar a pasta atual | Botão Atualizar |
| Pesquisar vídeos | Campo de pesquisa |
| Abrir vídeo | Botão Abrir ou duplo clique no vídeo |
| Remover pasta adicionada | Botão Remover pasta |
| Minimizar o Explorer | Botão Minimizar |
| Maximizar o Explorer | Botão Maximizar |
| Restaurar o Explorer | Botão Restaurar |
| Fechar o Explorer | Botão Fechar |
| Excluir vídeo | Ação Excluir, quando habilitada nas configurações |
| Copiar vídeos | Ctrl + C, quando habilitado |
| Colar vídeos | Ctrl + V, quando habilitado |
| Selecionar todos os vídeos | Ctrl + A, quando habilitado |

## Controles XInput e DInput

Quando habilitados nas configurações, os controles compatíveis podem ser usados para operar o player. O botão **L3** alterna entre os cinco formatos de vídeo disponíveis. O botão **R3** alterna entre tela cheia e modo janela.

## Plataformas

O Open Player possui versões para Windows e Linux. A versão Windows inclui executável portátil e pacote ZIP com arquivos soltos. O projeto utiliza Electron para a interface e libVLC para reprodução de mídia.

## Licença

Consulte o arquivo de licença incluído neste repositório para obter as condições de uso, modificação e distribuição do projeto.

---

## English

# Open Player

**Open Player** is a desktop media player built with Electron and libVLC, designed to provide a simple, fast, and customizable experience for video and audio playback.

The project supports a wide range of media formats, including MP4, MKV, WebM, MOV, AVI, MPEG, MPG, M4V, OGV, and other formats supported by libVLC. It allows users to select audio and subtitle tracks, play multilingual content, use embedded or external subtitles, and control volume, mute, playback speed, repeat mode, and video format.

## Main features

- Video and audio playback powered by the **libVLC** engine.
- Support for multiple media formats.
- Selection of embedded audio and subtitle tracks.
- Support for external subtitle files.
- Automatic activation of forced subtitles when configured.
- Volume, mute, playback speed, audio synchronization, and subtitle synchronization controls.
- Automatic resume from the point where playback was interrupted.
- Video repeat, playlist repeat, and shuffle playback.
- Frame capture and thumbnail generation.
- Video format options including fit, crop, stretch, and actual size.
- Fullscreen, maximize, restore, and window resizing support.
- XInput and DInput controller support.
- Brazilian Portuguese and English interface.

## Explorer mode

**Explorer mode** allows users to organize and browse videos directly inside the player without leaving the application. Users can add folders and subfolders, browse available videos, search files, refresh folder contents, and open videos directly from Explorer.

Explorer mode can also copy videos into added folders, display watched-video status, and delete videos with confirmation when the feature is enabled in Settings. When enabled, Open Player can automatically advance to the next video in the playlist after a video opened through Explorer finishes. This option can be turned on or off by the user.

The player can pause playback when entering Explorer and resume playback when returning to Play mode, depending on the selected setting.

## Player shortcuts

Shortcuts can be customized in Open Player Settings. The default shortcuts include:

| Action | Default shortcut |
|---|---|
| Play or pause | Space |
| Seek backward five seconds | Left Arrow |
| Seek forward five seconds | Right Arrow |
| Fullscreen | F11 or configured shortcut |
| Mute | M |
| Increase volume | Up Arrow |
| Decrease volume | Down Arrow |
| Switch audio track | Ctrl + F |
| Switch subtitle track | Ctrl + S |
| Toggle fullscreen | Enter or configured shortcut |
| Play/pause through media button | Headset or multimedia keyboard Play/Pause button |

The Up and Down Arrow keys can adjust the volume during playback. The mute button next to the volume bar toggles the audio state without stopping the video.

## Explorer mode controls

Explorer mode includes dedicated controls for file navigation and management:

| Action | Control |
|---|---|
| Return to Play mode | Explorer Play button |
| Go back to the previous folder | Back button |
| Go to the folder root | Home button |
| Move up one folder | Up button |
| Refresh the current folder | Refresh button |
| Search for videos | Search field |
| Open a video | Open button or double-click a video |
| Remove an added folder | Remove folder button |
| Minimize Explorer | Minimize button |
| Maximize Explorer | Maximize button |
| Restore Explorer | Restore button |
| Close Explorer | Close button |
| Delete a video | Delete action, when enabled in Settings |
| Copy videos | Ctrl + C, when enabled |
| Paste videos | Ctrl + V, when enabled |
| Select all videos | Ctrl + A, when enabled |

## XInput and DInput controls

When enabled in Settings, compatible controllers can be used to operate the player. Pressing **L3** cycles through the five available video formats. Pressing **R3** toggles between fullscreen and windowed mode.

## Platforms

Open Player provides Windows and Linux builds. The Windows release includes a portable executable and a ZIP package containing loose application files. The project uses Electron for the user interface and libVLC for media playback.

## License

Please refer to the license file included in this repository for the terms governing the use, modification, and distribution of the project.

---

## Suggested GitHub topics

`electron` `libvlc` `vlc` `media-player` `video-player` `audio-player` `subtitle-support` `mkv-player` `windows` `linux` `xinput` `dinput` `explorer-mode`
