# Como funciona

1. **Base** — uma planilha em Excel guarda os destinatários e os dados de cada envio.
2. **Gatilho** — o fluxo é iniciado no Power Automate.
3. **Loop** — para cada linha da planilha, o fluxo monta o e-mail com os dados daquela pessoa.
4. **Anexo** — o arquivo correspondente é anexado à mensagem.
5. **Envio** — o e-mail personalizado é enviado, e o fluxo segue para a próxima linha.

## Cuidados

- Validar a base antes de disparar o fluxo (e-mails e anexos corretos).
- Testar com um pequeno grupo antes do envio completo.

[← Voltar ao README](../README.md)
