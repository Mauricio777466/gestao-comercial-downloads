# Gestão Comercial — downloads

Instaladores do sistema **Gestão Comercial** (vendas, caixa/PDV, estoque e financeiro para lojas).
O código do sistema não fica aqui: este repositório só guarda os arquivos para baixar.

**Baixe sempre pela página de versões:** [Releases → última versão](../../releases/latest)

| Arquivo | Para quê |
|---|---|
| `GestaoComercial-Atualizacao-X.Y.Z.exe` | **Atualizar** um servidor que já tem o sistema. Não mexe no banco, na senha nem nos backups. |
| `GestaoComercial-Servidor-Setup.exe` | **Primeira instalação** no computador servidor da loja (inclui o PostgreSQL). |
| `GestaoComercial-Caixa-Setup.exe` | Programa do caixa, em cada computador de caixa (pode instalar por cima para atualizar). |

## Como atualizar

1. No computador servidor, baixe o `GestaoComercial-Atualizacao-X.Y.Z.exe` da última versão.
2. Rode e clique em Avançar. O sistema fica parado por alguns segundos e liga sozinho de novo.
3. Nos caixas, baixe e instale o `GestaoComercial-Caixa-Setup.exe` por cima, se a versão pedir.

O próprio sistema avisa quando sai versão nova (Agenda do dia e tela Suporte, para administradores).

Requisitos: Windows 10 ou 11 de 64 bits, usuário administrador do Windows.

© 2026 Mauricio
