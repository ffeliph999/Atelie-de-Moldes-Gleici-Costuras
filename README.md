<p align="center">
  <img src="imagens/art.webp" alt="Ateliê Gleici Costuras: vestido vermelho no manequim com agulha e linha dourada" width="600">
</p>

# Atelie de Moldes Gleici Costuras

Editor de modelagem de roupas que roda direto no navegador, sem instalar nada. Com ele você:

- desenha moldes e transforma os desenhos em peças;
- adiciona margem de costura, margem de segurança, bainha, piques e pences;
- faz a gradação de tamanhos e planeja o encaixe no tecido;
- imprime o molde em tamanho real, dividido em folhas para colar e montar;
- exporta em DXF para plotter e máquina de corte.

Funciona no computador e no celular (em pé ou deitado).

📖 **Manual com fotos:** https://ffeliph999.github.io/Atelie-de-Moldes-Gleici-Costuras/manual.html (também abre pelo link "Precisa de ajuda? Abrir o manual" no painel da direita).

---

## Como usar

- **Online:** abra o endereço do site publicado https://ffeliph999.github.io/Atelie-de-Moldes-Gleici-Costuras/
- **No computador, sem internet de hospedagem:** dê dois cliques no arquivo `index.html` para abrir no Chrome, Edge ou Firefox.

Na primeira vez o editor abre com um molde de exemplo (camiseta básica: frente, costas e manga, com gradação P/M/G/GG), para você explorar as ferramentas. Para começar um molde seu, clique na pasta (canto superior esquerdo) → **Novo molde**.

### Fluxo típico

1. **Novo molde:** informe nome/referência, tecido, observação e o tamanho da área de impressão. Você pode anexar a ficha técnica ou uma foto da peça.
2. **Desenhe as linhas de construção** com Retângulo, Elipse, Linha, Curva ou Mão livre. Também dá para digitalizar um molde de papel por foto ou importar um DXF/PLT. Com o **ímã** ligado, as linhas se prendem umas nas outras.
3. **Gerar molde:** clique nas linhas que formam o contorno (ou dentro da área fechada) e depois em **Gerar molde**.
4. **Acabamento:** margem de costura, bainha, piques e pences.
5. **Gradação:** crie os tamanhos e defina quanto cada ponto anda em cada um, ou use a gradação automática.
6. **Encaixe:** planeje o corte no tecido (aberto, par ou tubular) e veja quanto tecido vai.
7. **Imprimir ou exportar:** PDF em escala real, dividido em folhas numeradas, ou DXF para plotter e corte.

---

## Ferramentas

### Barra lateral

| Ferramenta | O que faz |
|---|---|
| **Selecionar** (V) | Seleciona, move e edita pontos (Shift seleciona vários pontos, que podem andar juntos por X/Y). Duplo clique numa linha cria um ponto; duplo clique num ponto liga ou desliga o **ponto de controle**. Os pontos de controle dividem o molde em linhas: margem, fita métrica, redefinir perímetro e redistribuir piques agem de um ponto de controle até o outro. Alças de Bézier opcionais nos pontos de curva. |
| **Retângulo** (R) / **Elipse** (O) | Desenha arrastando; mostra a largura em cima e a altura do lado. A elipse tem só 4 pontos, como no molde.me. |
| **Linha** (L) | Uma linha por traço. O cursor gruda nas pontas e em qualquer ponto das linhas existentes. Shift trava em 0°, 45° e 90°. |
| **Curva** (C) | Cada clique adiciona um ponto de curva; clique no primeiro ponto para fechar. |
| **Estender linha** (E) | Arrasta a ponta de uma linha aberta para estender ou encurtar na mesma direção; um clique estende até a linha mais próxima. |
| **Mão livre** (F) | Desenho livre que vira curva com pontos editáveis; mostra o comprimento total. |
| **Marcar pontos** (P) | O 1º clique pega o ponto mais próximo como referência e uma régua tracejada mede até o mouse; o 2º clique marca o ponto. Numa linha ou curva ele vira ponto de controle dela; fora, fica um ponto solto. L, A, C e P fixam a medida; Shift trava em 45°; D apaga os pontos soltos. |
| **Texto** (T) | Textos no desenho, que também podem ser girados. |
| **Digitalização de moldes** | Foto do molde de papel: calibra a escala com uma medida conhecida e detecta o contorno. |
| **Redefinir perímetros** (X) | Muda o comprimento de uma linha (bidirecional, unidirecional ou mantendo as pontas). |
| **Gerar molde** (M) | Transforma a área fechada em molde, com nome, tamanho do texto, sentido do fio e rotação permitida. |
| **Fita métrica** (N) | Passe o mouse sobre linhas e margens para ver a medida. Cada clique cria uma régua emendada, com o total. |
| **Margem de costura** (1) | Margem inicial e final em cada linha, para fora ou para dentro (para dentro, o molde recua e a linha de corte fica no contorno de antes). Acabamento reto, chanfrado, sem acabamento ou redondo. Clicar na margem de um lado a remove. |
| **Margem de segurança** (S) | Espaço livre em volta da linha de corte, para separar as peças no encaixe e no corte. |
| **Bainha** | Largura, número de dobras e piques nas dobras. |
| **Desdobrar / Dobrar molde** | Espelha a peça sobre uma linha reta ou dobra uma peça simétrica ao meio. |
| **Marcar pique** (4) | Piques no contorno (traço, T, V, contínuo, seta, texto ou tamanho), a uma medida exata (P, L, A ou C), redistribuídos numa linha, e marcações internas. |
| **Pence** (D) | Abertura e profundidade; pode abrir no contorno ou só marcar as pernas. |
| **Agrupar moldes** | Junta dois moldes por uma costura (por exemplo, frente e costas), para encaixar e cortar juntos. |
| **Alinhar pontos** (9) | Alinha pontos na horizontal ou na vertical. |
| **Linhas paralelas** | Cria uma linha paralela a uma distância definida. |
| **Conferência por aproximação** | Encosta a linha de uma peça na de outra e compara os comprimentos. |
| **Tabela de medidas** | Tabela de medidas por tamanho, que pode ficar fixa na tela. |
| **Gradação** (5) | Lista de tamanhos com cor; define o deslocamento X/Y de cada ponto por tamanho. |
| **Gradação automática** (A) | Calcula a gradação a partir de quanto a peça cresce em largura e altura. |
| **Copiar gradação** | Copia a gradação (X, Y ou os dois) de um ponto para outros. |

### Barra de cima

Mais zoom, menos zoom, desfazer, refazer, ímã, guias, grade, mostrar medidas, esconder pontos, suavizar curvas, redimensionar, rotacionar, inverter na vertical, inverter na horizontal, reorganizar painéis, travar, fotografar moldes na tela, encaixe, imprimir, remover, modo celular/computador e tema claro/escuro.

- **Redimensionar** e **Rotacionar** ligam alças em volta da seleção. Na rotação, arraste os arcos dos cantos para girar em volta do eixo (a cruz do centro, que também pode ser arrastada); Shift gira de 15 em 15°.
- **Encaixe** distribui as peças de todos os tamanhos no tecido (aberto, par ou tubular) e mostra o comprimento de tecido, o aproveitamento e o tempo de corte. O resultado vira um molde novo para imprimir em plotter ou exportar.
- Com o botão direito, um duplo clique num ponto de um molde começa a **sobrepor moldes**.

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
- **Papel:** A0 a A5, Carta, Ofício, Tabloide, Plotter (largura do rolo), tamanho customizado ou Dimensões totais (uma página só, do tamanho de todos os moldes).
- **Margens:** padrão de 0,5 cm ou customizadas, lado a lado.
- **Orientação:** retrato ou paisagem.

O PDF sai em **escala real**, igual ao do molde.me:
- **Folhas:** a grade começa no canto do projeto. A quantidade depende de onde estão os moldes, do papel, da orientação e das margens, e as páginas em branco são puladas.
- **Numeração:** cada folha é numerada no canto superior esquerdo como **linha-coluna**. `1-1, 2-1, 3-1…` descem pela primeira coluna e `1-2, 2-2…` pela segunda.
- **Linhas:** a linha de corte sai contínua e a de costura tracejada. O sentido do fio e o nome do molde saem em roxo, com o nome escrito ao longo do fio.

> Na impressora, escolha **tamanho real (100%)** e desligue "ajustar à página". Confira uma medida com a régua depois de imprimir.

## Exportar

Pela pasta → **Exportar**:

- **SVG:** em centímetros reais.
- **DXF (R12, em mm):** para plotter e máquina de corte, com camadas separadas para contorno, costura, piques, fio, texto e cada tamanho. O pique contínuo sai recortado no próprio contorno.
- **Projeto (.json):** para abrir de novo em **Importar projeto**.

Na janela de exportar você escolhe o que vai no arquivo (nome, textos, margem de costura, linhas tracejadas e bordas da área de impressão) e quais tamanhos entram. **Exportar individualmente** gera um arquivo por tamanho.

## Importar

Pela pasta → **Importar moldes**, abra um molde de outro programa como um molde novo:
- **DXF** (R12 ou AAMA);
- **DXF + RUL** (escolha os dois arquivos juntos para trazer a gradação);
- **PLT/HPGL**.

Contornos fechados viram moldes, e o resto vira linhas de construção.

---

## Atalhos

| Tecla | Ação |
|---|---|
| `V` `R` `O` `L` `C` `E` `F` `P` `T` | Selecionar, Retângulo, Elipse, Linha, Curva, Estender linha, Mão livre, Marcar pontos, Texto |
| `X` `M` `N` | Redefinir perímetros, Gerar molde, Fita métrica |
| `1` `S` `4` `D` | Margem de costura, Margem de segurança, Marcar pique, Pence |
| `9` `5` `A` | Alinhar pontos, Gradação, Gradação automática |
| `I` / `G` | Ímã / guias |
| `Enter` | Termina curva ou sequência de réguas |
| `Esc` | Cancela e volta para Selecionar |
| `Delete` | Remove o ponto ou elemento selecionado |
| `Setas` | Move 1 mm (com Shift, 1 cm) |
| `Ctrl+Z` / `Ctrl+Y` | Desfazer / refazer |
| `Ctrl+D` | Duplicar |
| `Ctrl+K` / `Ctrl+L` | Inverter na vertical / na horizontal |
| `+` `-` `0` | Mais zoom, menos zoom, ajustar à tela |
| `?` | Ajuda |
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
2. Envie o `index.html`, o `manual.html`, as pastas `manual/` e `imagens/` e este `README.md` (**Add file → Upload files → Commit changes**).
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/(root)`, e clique em **Save**.
4. Em 1 ou 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/atelie-moldes/`.

Para atualizar, envie os arquivos novos por cima dos antigos.

## Estrutura

| Arquivo | O que é |
|---|---|
| `index.html` | O app inteiro, num único arquivo (HTML, CSS e JavaScript puros, sem etapa de build). O desenho usa SVG, as medidas internas são em centímetros e o PDF é gerado com jsPDF. As artes do app vão embutidas nele. |
| `manual.html` | Manual com o passo a passo de cada ferramenta, no computador e no celular. |
| `manual/` | Fotos do manual (WebP). |
| `imagens/` | Artes do ateliê (a capa deste README é `art.webp`). |

---

Feito para a **Gleici Costuras**.
