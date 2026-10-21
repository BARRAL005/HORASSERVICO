# HoraCerta Black — Controle de horas trabalhadas

Aplicativo web responsivo, com visual preto e dourado, pensado para uso no celular. Não precisa instalar dependências.

## Funcionalidades
- Calendário mensal com navegação entre meses e seleção de dia.
- Registro de trabalho, folga, festa/evento, feriado e outro.
- Lembretes e observações exibidos no calendário e em uma lista de próximos lembretes.
- Cálculo automático entre entrada e saída, intervalo descontado e turno que cruza a meia-noite.
- Campo de horas manual, quando necessário.
- Valor padrão por hora editável e valor individual por dia.
- Relatório por período com data, status, entrada, saída, horas, valor/hora, valor diário, observações e total.
- Exportação CSV compatível com Excel, impressão/salvar em PDF, resumo copiável e backup/restauração JSON.
- Layout adaptável a telas pequenas, campos acessíveis e ações com áreas de toque maiores.
- Dados armazenados localmente no navegador; nada é enviado a um servidor.

## Executar localmente
Abra `index.html` em um navegador moderno.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie `index.html`, `README.md` e `.gitignore` para a raiz.
3. Abra **Settings → Pages**.
4. Em Build and deployment, selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`.
5. Salve e aguarde a URL que o GitHub Pages fornecer.

## Adicionar à tela inicial do celular
- **iPhone:** abra a URL publicada no Safari, toque em Compartilhar e escolha **Adicionar à Tela de Início**.
- **Android:** abra a URL no Chrome, abra o menu e escolha **Adicionar à tela inicial**.

## Dados e limites
Os dados ficam no armazenamento local do navegador e não sincronizam entre dispositivos. Exporte backups com frequência. O relatório é uma estimativa (horas × valor por hora); adicionais, regras trabalhistas, impostos e descontos não são calculados automaticamente.
