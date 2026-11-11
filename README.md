# Vídeo da diretora: versão completa

Player de apresentação do vídeo da diretora (versão completa, 36 falas):
cada fala toca uma de cada vez, e o vídeo só segue quando você aperta **espaço**.
Na tela aparece só o vídeo.

## Como rodar no computador (sem internet)

1. Baixe o projeto:
   - pelo GitHub: botão verde **Code → Download ZIP**, ou
   - pelo terminal: `git clone <endereço deste repositório>`
2. Se baixou o ZIP, **extraia** (no Mac, dois cliques no ZIP; no Windows, botão direito → *Extrair tudo*).
   Não abra a apresentação de dentro do ZIP sem extrair: os vídeos não carregam.
3. Dentro da pasta, dê dois cliques em **`ABRIR APRESENTACAO.html`**.
   Ele abre no seu navegador padrão (Chrome, Edge, Safari ou Firefox).
4. Aperte **espaço** para começar. Na primeira vez a página entra em tela cheia.

Não precisa instalar nada nem ter internet. O arquivo `.html`, o `icone.svg`
e a pasta `videos/` precisam ficar juntos, na mesma estrutura.

> Se o navegador não abrir com dois cliques, arraste o `ABRIR APRESENTACAO.html`
> para uma janela do navegador.

## Online (GitHub Pages)

No repositório, vá em **Settings → Pages**, escolha a branch `main` e a pasta
`/ (root)` e clique em **Save**. Em um ou dois minutos fica no ar em
`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/` (o `index.html` abre a
apresentação).

## Controles

| Tecla | O que faz |
|---|---|
| **Espaço** | Solta a próxima fala |
| **←** | Volta uma fala inteira (com fade) |
| **→** | Avança uma fala (com fade) |
| **R** | Reinicia. Enquanto o vídeo não acabou, pergunta antes (**Enter** confirma, **Esc** cancela) |
| **F** | Liga/desliga tela cheia |

No celular ou tablet: tocar na tela avança e deslizar para o lado volta ou avança.

## Como funciona

No vídeo original (2:59), cada troca de fala era marcada por 1 segundo de tela
preta. Essas telas pretas foram removidas e o vídeo foi dividido nos 36 trechos
entre elas. Cada trecho termina parado no último quadro da fala, sem tela
preta, até o próximo espaço.

| Arquivo | Trecho do original | Duração |
|---|---|---|
| `00.mp4` | 0:00.00 → 0:19.80 | 19.8 s |
| `01.mp4` | 0:20.80 → 0:21.77 | 1.0 s |
| `02.mp4` | 0:22.77 → 0:26.40 | 3.6 s |
| `03.mp4` | 0:27.40 → 0:35.27 | 7.9 s |
| `04.mp4` | 0:36.27 → 0:38.67 | 2.4 s |
| `05.mp4` | 0:39.70 → 0:45.20 | 5.5 s |
| `06.mp4` | 0:46.23 → 0:50.50 | 4.3 s |
| `07.mp4` | 0:51.53 → 0:53.10 | 1.6 s |
| `08.mp4` | 0:54.13 → 0:57.30 | 3.2 s |
| `09.mp4` | 0:58.33 → 1:01.57 | 3.2 s |
| `10.mp4` | 1:02.60 → 1:06.47 | 3.9 s |
| `11.mp4` | 1:07.50 → 1:13.70 | 6.2 s |
| `12.mp4` | 1:14.73 → 1:17.30 | 2.6 s |
| `13.mp4` | 1:18.30 → 1:23.30 | 5.0 s |
| `14.mp4` | 1:24.33 → 1:26.33 | 2.0 s |
| `15.mp4` | 1:27.37 → 1:30.40 | 3.0 s |
| `16.mp4` | 1:31.43 → 1:35.37 | 3.9 s |
| `17.mp4` | 1:36.40 → 1:37.50 | 1.1 s |
| `18.mp4` | 1:38.50 → 1:42.43 | 3.9 s |
| `19.mp4` | 1:43.43 → 1:49.87 | 6.4 s |
| `20.mp4` | 1:50.90 → 1:51.87 | 1.0 s |
| `21.mp4` | 1:52.90 → 1:55.37 | 2.5 s |
| `22.mp4` | 1:56.37 → 1:57.27 | 0.9 s |
| `23.mp4` | 1:58.30 → 2:01.30 | 3.0 s |
| `24.mp4` | 2:02.33 → 2:05.37 | 3.0 s |
| `25.mp4` | 2:06.40 → 2:09.70 | 3.3 s |
| `26.mp4` | 2:10.73 → 2:17.40 | 6.7 s |
| `27.mp4` | 2:18.43 → 2:21.33 | 2.9 s |
| `28.mp4` | 2:22.37 → 2:24.63 | 2.3 s |
| `29.mp4` | 2:25.67 → 2:27.17 | 1.5 s |
| `30.mp4` | 2:28.20 → 2:30.80 | 2.6 s |
| `31.mp4` | 2:31.83 → 2:33.87 | 2.0 s |
| `32.mp4` | 2:34.90 → 2:38.73 | 3.8 s |
| `33.mp4` | 2:39.77 → 2:46.97 | 7.2 s |
| `34.mp4` | 2:48.00 → 2:51.07 | 3.1 s |
| `35.mp4` | 2:52.10 → 2:59.17 | 7.1 s |

Os vídeos estão em H.264 + AAC (MP4), 1280×720 a 30 quadros por segundo, que
tocam em qualquer navegador e sistema.

## Estrutura

```
ABRIR APRESENTACAO.html   o player (HTML, CSS e JavaScript num arquivo só)
index.html                abre o player (para o GitHub Pages)
icone.svg                 ícone da aba
videos/00.mp4 … 35.mp4    os 36 trechos
```
