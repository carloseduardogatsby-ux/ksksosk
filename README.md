# Gabarito Deck PDF

Leitor de PDF de provas com gabarito, pincel, marca-texto, borracha e resultado.

## Gerar o APK
1. Crie um repositório no GitHub e envie todos os arquivos desta pasta (branch `main`).
2. Abra a aba **Actions** > **Build APK** (roda sozinho a cada envio; ou clique em *Run workflow*).
3. Ao terminar, baixe o arquivo **Gabarito-Deck-PDF-APK-debug** em *Artifacts* e instale o `app-debug.apk`.

## Gabarito
Formato: `PROVA|NOME|TOTAL|GABARITO` — use `*` para questão nula (anulada).
Exemplo: `PROVA|URCA 2026.1|10|ABCDE*ABCD`

## Paralelo ao app antigo
Usa o ID `com.carlos.gabaritodeck.pdf`, então instala ao lado do Gabarito Deck original sem substituí-lo.

## Cor do PDF
Botão 🎨 no leitor alterna entre papel branco e magenta suave.
