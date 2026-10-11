# Mar & Rios — Central: instaladores e atualizações

Distribuição Windows da Central de cardápio e pedidos para retirada da Peixaria Mar & Rios, Xangri-lá / RS.

[**Baixar instalador**](https://github.com/susfghvyuj/mar-e-rios-central-atualizacoes/releases/latest/download/MarERiosCentral-Setup.exe) · [**Cardápio dos clientes**](https://mar-e-rios-retirada.mar-e-rios-xangri-la.workers.dev)

Execute MarERiosCentral-Setup.exe. Cria atalhos e preserva os dados. Requer Windows 10/11 e .NET Framework 4.8 ou compatível. É independente do aplicativo Caixa.

A versão **1.1.1** conecta o cardápio à Central pela hospedagem própria da loja na Cloudflare, recebe pedidos de retirada e atualiza o acompanhamento. Inclui **Em produção**, categorias, pratos, fotos, acompanhamentos, adicionais, comandas e pagamento na retirada. O catálogo começa vazio: a loja cadastra os pratos reais.

Acesse [Acesso da loja](https://mar-e-rios-retirada.mar-e-rios-xangri-la.workers.dev/conectar) com a senha da loja, gere a conexão e importe em **Configurações → Cardápio online**. Cadastre pratos e clique **Publicar cardápio** na primeira conexão. Depois, mudanças sincronizam automaticamente. Mantenha uma Central aberta com internet; após 90 segundos sem comunicação, o site pausa novos pedidos. Somente retirada e pagamento na loja.

Quem já tem a conexão do endereço anterior da Mar & Rios recebe a migração automática na primeira abertura após atualizar para **1.1.1**. O código protegido pelo Windows e a referência do último cardápio publicado são preservados, com backups dos arquivos de conexão na pasta de dados. Catálogo, clientes e pedidos locais são mantidos. Conexões com endereços personalizados continuam como estão. Consulte LEIA-ME.md se aparecer uma orientação de falha de gravação.

Atualizações automáticas neste repositório, sem login ou token GitHub. Verifica tamanho e SHA-256, aguarda não haver edição ou sincronização e preserva %LOCALAPPDATA%/MarERiosCentral. Consulte LEIA-ME.md para conexão, impressora e backup.

Releases contêm somente:

- MarERiosCentral-Setup.exe: instalador.
- MarERiosCentral-Windows.zip: versão portátil e instruções.
- update-manifest.json: versão e integridade.
- SHA256SUMS.txt: hashes.

Código da Central e do site permanece privado. Clientes, pedidos, credenciais, pratos cadastrados e backups não são publicados no GitHub. O site hospedado recebe os dados necessários aos pedidos. Os arquivos Source code gerados pelo GitHub contêm somente documentos deste repositório de distribuição.
