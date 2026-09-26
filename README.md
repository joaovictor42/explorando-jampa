# Explorando Jampa

Diretório de 947 atividades, escolas, clubes e eventos de João Pessoa e região
metropolitana, com contato, horário, preço e link direto para o Google Maps.

Site estático. `index.html` carrega `dados.json` — nenhuma dependência de servidor.

## Curadoria

Nada é removido de `dados.json`. Ocultar marca `del: true` e arquivar marca
`arq: true`; a linha continua no arquivo com todos os campos. O histórico
completo de alterações fica no próprio git.

Para curar: abra o site com `#admin` no fim da URL (ou Ctrl+Shift+A), faça as
alterações e use **Exportar** — o bloco JSON gerado é aplicado ao `dados.json`
num commit.
