# Mar & Rios — Central: instaladores e atualizações

Distribuição Windows da Central de cardápio e pedidos para retirada da Peixaria Mar & Rios, Xangri-lá / RS.

[**Baixar o instalador mais recente**](https://github.com/susfghvyuj/mar-e-rios-central-atualizacoes/releases/latest/download/MarERiosCentral-Setup.exe)

Execute `MarERiosCentral-Setup.exe`. O instalador cria os atalhos **Mar & Rios Central** e preserva os dados existentes. Requer Windows 10/11 com .NET Framework 4.8 ou compatível. A Central é independente do aplicativo Caixa: tem executável e pasta de dados próprios.

Esta primeira versão funciona localmente no PC da loja. Permite cadastrar categorias, pratos, fotos, acompanhamentos e adicionais; lançar pedidos manualmente; acompanhar o preparo; imprimir comandas e registrar pagamento somente na retirada. O catálogo e os pedidos começam vazios. O cardápio público para clientes, o recebimento online e o bot de WhatsApp ainda são etapas futuras.

Depois da instalação, o aplicativo busca atualizações automaticamente neste repositório, sem login ou token. Os instaladores são verificados por tamanho e SHA-256, e a atualização aguarda não haver pedido em edição. O programa usa `%LOCALAPPDATA%\MarERiosCentral` para os dados da loja. Configurações incluem exportação e importação de backup com fotos.

As Releases contêm somente:

- `MarERiosCentral-Setup.exe`: instalador Windows.
- `MarERiosCentral-Windows.zip`: versão portátil com instruções.
- `update-manifest.json`: versão e integridade usadas pelo atualizador.
- `SHA256SUMS.txt`: hashes SHA-256 dos arquivos.

O código-fonte permanece privado. Produtos, fotos cadastradas, clientes, pedidos e backups ficam no computador e não são publicados aqui. Os arquivos “Source code” gerados pelo GitHub contêm somente os documentos deste repositório de distribuição.
