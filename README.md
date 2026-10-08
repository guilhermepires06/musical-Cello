# 🎻 Editor e Leitor de Partituras para Violoncelo

Um editor de partituras interativo baseado em Web Technologies (SVG + Web Audio API) projetado para auxiliar estudantes de violoncelo a relacionar notas na **Clave de Fá** com as posições de digitação no braço do instrumento.

## 🚀 Funcionalidades

- **Mapeamento do Braço**: Exibição da corda (Dó, Sol, Ré, Lá) e dedo correspondente (0 a 4 na 1.ª posição, cobrindo do Dó2 ao Sol4).
- **Interatividade na Pauta**:
  - Arraste de notas com alinhamento magnético (*snapping*).
  - Linha guia dinâmica durante o movimento.
  - Ajuste por clique na pauta ou seleção via barra de escala.
- **Áudio Realista de Cello**:
  - Motor de áudio construído com `AudioContext` sem bibliotecas externas.
  - Simulação de timbre com múltiplos harmónicos e efeito de vibrato.
- **Controlo de Compasso & Ritmo**:
  - Suporte para compassos 4/4, 3/4 e 2/4.
  - Suporte para figuras rítmicas (Semibreve, Mínima, Semínima, Colcheia) e pausas.
  - Notas e pausas pontuadas.
  - Modo de reprodução contínua com acompanhamento (*scroll* automático).

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** (Interface moderna e responsiva em modo escuro)
- **JavaScript (Vanilla)**
- **SVG estático e dinâmico** (Para renderização da pauta, braço e notas)
- **Web Audio API** (Para síntese sonora)

## 📦 Como Executar

Por ser uma aplicação web frontend sem dependências pesadas, podes executá-la de duas formas:

1. **Localmente**:
   - Clona este repositório:
     ```bash
     git clone [https://github.com/teu-usuario/editor-partitura-violoncelo.git](https://github.com/teu-usuario/editor-partitura-violoncelo.git)
     ```
   - Abre o ficheiro `index.html` em qualquer navegador web moderno.

2. **Servidor Flask / Python**:
   - Executa `python app.py` para rodar num servidor local ou num serviço de alojamento cloud.
