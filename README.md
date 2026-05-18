# 📊 Carteira de Clientes

Dashboard de gestão da carteira de clientes para consultores.

## 🔗 Acesso

➡️ **[Acessar o Dashboard](https://raiiisopaoli.github.io/carteira-clientes)**

## 👤 Usuários

| Usuário | Perfil | Senha padrão |
|---|---|---|
| Raisa Oliveira | Consultora | `raisa123` |
| Elis Monteiro | Consultora | `elis123` |
| Criz Rodrigues | Gestora | `criz123` |

> ⚠️ Altere as senhas após o primeiro acesso diretamente na planilha Google (aba **Usuarios**).

## ✨ Funcionalidades

- **Dashboard** — KPIs, gráficos de status, suportes e T.PG
- **Lojas** — Cadastro e edição de lojas com status de risco
- **Financeiro** — Mensalidade e faturamento por loja
- **Relatório Mensal** — Snapshots mensais com histórico
- **Visão Gestora** — Visão consolidada de todos os consultores (apenas Criz)

## 🟢 Status de risco

| Status | Descrição |
|---|---|
| 🔴 Alto Risco | Total dependência. Não faz sozinho. |
| 🟠 Atenção | Baixa autonomia. Acompanhamento contínuo. |
| 🟡 Oportunidade | Autonomia em desenvolvimento. Apoio pontual. |
| 🔵 Monitorar | Autônoma. Acompanhamento estratégico. |

## 🛠️ Tecnologia

- HTML + CSS + JavaScript (sem dependências externas pagas)
- [Chart.js](https://chartjs.org) para gráficos
- Google Sheets como banco de dados (via Google Apps Script)
- Hospedagem gratuita via GitHub Pages

## 📋 Como atualizar senhas

1. Abra a planilha `Carteira Clientes DB` no Google Sheets
2. Vá na aba **Usuarios**
3. Edite a coluna **senha** da linha correspondente
4. Salve — a mudança é imediata

## 📥 Como importar lojas

1. Acesse com o perfil da **Criz**
2. Clique em **📥 Importar planilha**
3. Selecione um arquivo `.csv` com colunas `Loja` e `Consultor`
4. Confirme a importação

---

Desenvolvido para uso interno da equipe de consultores.
