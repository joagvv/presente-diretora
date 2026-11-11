# O presente da diretora

Player de apresentação para o vídeo "O presente da diretora virou assunto na sala":
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

O vídeo original (28,46 s) foi dividido em 15 partes, uma por fala. Cada corte
fica no meio da pausa entre uma fala e a seguinte, então nenhuma palavra é
cortada. Cada parte termina parada no último quadro até o próximo espaço.

| Arquivo | Fala | Trecho do original |
|---|---|---|
| `00.mp4` | Tudo certinho? | 0:00.00 → 0:01.12 |
| `01.mp4` | Toma seu cafezinho, depois passa na minha sala. | 0:01.12 → 0:03.60 |
| `02.mp4` | E aí, qual as novidades? | 0:03.60 → 0:05.20 |
| `03.mp4` | Vocês acham que eu não sei das coisas, mas sei de tudo! | 0:05.20 → 0:08.52 |
| `04.mp4` | Ai, não acredito! | 0:08.52 → 0:09.88 |
| `05.mp4` | Eu me recuso! | 0:09.88 → 0:11.12 |
| `06.mp4` | Tudo certo e nada resolvido! | 0:11.12 → 0:13.08 |
| `07.mp4` | Veja na tua IA! | 0:13.08 → 0:14.08 |
| `08.mp4` | Me surpreendam! | 0:14.08 → 0:14.96 |
| `09.mp4` | Vai ser top! | 0:14.96 → 0:15.96 |
| `10.mp4` | Tu vai, né? Se não, a diretora vai ficar brava! | 0:15.96 → 0:19.04 |
| `11.mp4` | O que vocês vão dar para a diretora se eu adiantar o salário? | 0:19.04 → 0:21.76 |
| `12.mp4` | Sugestões de presentes. | 0:21.76 → 0:23.24 |
| `13.mp4` | Fizeram o bolão para saber o presente? | 0:23.24 → 0:25.44 |
| `14.mp4` | Tem pessoas aqui que eu nunca esperaria na minha sala. | 0:25.44 → 0:28.46 |

Os vídeos estão em H.264 + AAC (MP4), 1080p a 25 quadros por segundo, que tocam
em qualquer navegador e sistema.

## Estrutura

```
ABRIR APRESENTACAO.html   o player (HTML, CSS e JavaScript num arquivo só)
index.html                abre o player (para o GitHub Pages)
icone.svg                 ícone da aba (um presente)
videos/00.mp4 … 14.mp4    as 15 falas
```
