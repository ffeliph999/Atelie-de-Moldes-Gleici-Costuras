# Atelie de Moldes Gleici Costuras

Editor de modelagem de roupas que roda direto no navegador, sem instalar nada. Serve para desenhar moldes, transformar desenhos em peças, adicionar margem de costura, bainha, piques e pences, fazer a gradação de tamanhos e imprimir o molde em tamanho real, dividido em folhas A4 para colar e montar.

Funciona no computador e no celular (em pé ou deitado).

---

## Como usar

- **Online:** abra o endereço do site publicado (veja [Publicar no GitHub Pages](#publicar-no-github-pages)).
- **No computador, sem internet de hospedagem:** dê dois cliques no arquivo `index.html` para abrir no Chrome, Edge ou Firefox.

Na primeira vez o editor abre com um molde de exemplo (camiseta básica: frente, costas e manga, com gradação P/M/G/GG), para você explorar as ferramentas. Para começar um molde seu, clique na pasta (canto superior esquerdo) → **Novo molde**.

### Fluxo típico

1. **Novo molde:** informe nome/referência, tecido, observação e o tamanho da área de impressão. Você pode anexar a ficha técnica ou uma foto da peça.
2. **Desenhe as linhas de construção** com Retângulo, Linha, Curva ou Mão livre. Com o **ímã** ligado, as linhas se prendem umas nas outras.
3. **Gerar molde:** clique nas linhas que formam o contorno (ou dentro da área fechada) e depois em **Gerar molde**.
4. **Acabamento:** margem de costura, bainha, piques e pences.
5. **Gradação:** crie os tamanhos e defina quanto cada ponto anda em cada um, ou use a gradação automática.
6. **Imprimir:** gera um PDF em escala real, dividido em folhas numeradas.

---

## Ferramentas

### Barra lateral

| Ferramenta | O que faz |
|---|---|
| **Selecionar** (V) | Seleciona, move e edita pontos. Duplo clique numa linha cria um ponto; duplo clique num ponto alterna entre canto e curva. Soltar um ponto em cima de outro da mesma linha une os dois. |
| **Retângulo** (R) / **Elipse** (E) | Desenha arrastando; mostra a largura em cima e a altura do lado. |
| **Linha** (L) | Uma linha por traço. O cursor gruda nas pontas e em qualquer ponto das linhas existentes. Shift trava em 0°, 45° e 90°. |
| **Curva** (C) | Cada clique adiciona um ponto de curva; clique no primeiro ponto para fechar. |
| **Estender linha** (X) | Arrasta a ponta de uma linha aberta para estender ou encurtar na mesma direção. |
| **Mão livre** (P) | Desenho livre que vira curva com pontos de controle editáveis; mostra o comprimento total. |
| **Marcar pontos** (.) / **Texto** (T) | Pontos de referência e textos. |
| **Digitalização de moldes** (I) | Foto do molde de papel: calibra a escala com uma medida conhecida e detecta o contorno. |
| **Redefinir perímetros** | Muda o comprimento de uma linha (bidirecional, unidirecional ou mantendo as pontas). |
| **Gerar molde** | Transforma a área fechada em molde, com nome, tamanho do texto, sentido do fio e rotação permitida. |
| **Fita métrica** (M) | Passe o mouse sobre linhas e margens para ver a medida. Cada clique cria uma régua emendada, com o total. |
| **Margem de costura** | Margem inicial e final (pode variar ao longo da linha), com acabamento reto ou chanfrado. |
| **Bainha** | Largura, número de dobras e piques nas dobras. |
| **Desdobrar / Dobrar molde** | Espelha a peça sobre uma linha reta ou dobra uma peça simétrica ao meio. |
| **Marcar pique** (N) | Piques no contorno (traço, V ou T) e marcações internas (cruz, círculo ou ponto). |
| **Pence** (D) | Abertura e profundidade; pode abrir no contorno ou só marcar as pernas. |
| **Alinhar pontos** | Alinha pontos na horizontal ou na vertical. |
| **Linhas paralelas** | Cria uma linha paralela a uma distância definida. |
| **Conferência por aproximação** | Encosta a linha de uma peça na de outra e compara os comprimentos. |
| **Tabela de medidas** | Tabela de medidas por tamanho, que pode ficar fixa na tela. |
| **Gradação** | Lista de tamanhos com cor; define o deslocamento X/Y de cada ponto por tamanho. |
| **Gradação automática** | Calcula a gradação a partir de quanto a peça cresce em largura e altura. |
| **Copiar gradação** | Copia a gradação (X, Y ou os dois) de um ponto para outros. |

### Barra de cima

Mais zoom, menos zoom, desfazer, refazer, ímã, guias, mostrar medidas, esconder pontos, suavizar curvas, redimensionar, rotacionar, inverter na vertical, inverter na horizontal, reorganizar painéis, travar, fotografar moldes na tela, imprimir, remover, modo celular/computador e tema claro/escuro.

### Painel da direita

Mostra as opções da ferramenta ativa. Com um molde selecionado, mostra as propriedades da peça:
- posição, tamanho e rotação;
- nome, tamanho do texto, sentido do fio e rotação permitida;
- par, cortar na dobra, tecido tubular, quantidade e tecido;
- margem geral e encolhimento.

Sem nada selecionado, mostra os dados do molde e a lista de peças com miniaturas (mostrar/esconder, travar, duplicar e excluir).

---

## Impressão

Em **Imprimir** você escolhe:

- **Propriedades:** nome do molde, textos, margem de costura, páginas em branco, linhas tracejadas e mostrar só o tamanho base.
- **Papel:** A4, A3 ou Carta.
- **Margens:** padrão de 0,5 cm ou customizadas, lado a lado.
- **Orientação:** retrato ou paisagem.

O PDF sai em **escala real**, dividido em quantas folhas forem necessárias. A quantidade de folhas depende do tamanho dos moldes, do papel, da orientação e das margens. Cada folha é numerada no canto inferior direito como **coluna-linha**: `1-1, 1-2, 1-3…` descem pela primeira coluna e `2-1, 2-2…` pela segunda.

> Na impressora, escolha **tamanho real (100%)** e desligue "ajustar à página". Confira uma medida com a régua depois de imprimir.

## Exportar

Pela pasta → **Exportar**:

- **SVG:** em centímetros reais.
- **DXF (R12, em mm):** para plotter e máquina de corte, com camadas separadas para contorno, costura, piques, fio, texto e cada tamanho.
- **Projeto (.json):** para abrir de novo em **Importar projeto**.

---

## Atalhos

| Tecla | Ação |
|---|---|
| `V R E L C X P . T I M N D` | Trocar de ferramenta |
| `Enter` | Termina curva ou sequência de réguas |
| `Esc` | Cancela e volta para Selecionar |
| `Delete` | Remove o ponto ou elemento selecionado |
| `Setas` | Move 1 mm (com Shift, 1 cm) |
| `Ctrl+Z` / `Ctrl+Y` | Desfazer / refazer |
| `Ctrl+D` | Duplicar |
| `S` / `G` | Ímã / guias |
| `+` `-` `0` `1` | Zoom, ajustar à tela, tamanho real |
| `Espaço` + arrastar | Mover a tela (ou botão do meio/direito do mouse) |

## Modo celular

O modo celular liga sozinho em telas de celular. Para trocar manualmente, use o botão de celular/computador na barra de cima ou **pasta → Modo da tela** (Automático, Computador ou Celular).

- **Em pé:** as ferramentas ficam numa faixa embaixo e as opções abrem numa gaveta que sobe de baixo.
- **Deitado:** as ferramentas ficam numa coluna à esquerda e as opções abrem pela direita.
- **Toque:** um dedo move a tela (no Selecionar); dois dedos dão zoom.

---

## Onde os dados ficam

Os moldes são salvos **no próprio navegador** (localStorage), sem servidor e sem login. Por isso:

- cada navegador e cada aparelho tem os seus próprios moldes;
- limpar os dados do navegador apaga os moldes.

Para guardar uma cópia ou levar para outro aparelho, use **Exportar → Projeto (.json)** e depois **Importar projeto**.

## Requisitos

- Navegador atual: Chrome, Edge, Firefox ou Safari.
- Internet para gerar o PDF, porque a biblioteca [jsPDF](https://github.com/parallax/jsPDF) vem do cdnjs. As fontes vêm do Google Fonts; sem internet, o editor usa uma fonte padrão.

---

## Publicar no GitHub Pages

1. Crie um repositório **público** no GitHub (por exemplo, `atelie-moldes`).
2. Envie o `index.html` e este `README.md` (**Add file → Upload files → Commit changes**).
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/(root)`, e clique em **Save**.
4. Em 1 ou 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/atelie-moldes/`.

Para atualizar, envie o novo `index.html` por cima do antigo.

## Estrutura

O app inteiro é um único arquivo `index.html` (HTML, CSS e JavaScript puros, sem etapa de build). O desenho usa SVG, as medidas internas são em centímetros e o PDF é gerado com jsPDF.

---

Feito para a **Gleici Costuras**.
