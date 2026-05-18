# 📊 Dashboard ROI por Placement — Gás do Povo

Dashboard interativo para análise de ROI cruzando dados do **Meta Ads** (custo) com **Google Ad Manager** (receita).

## 🚀 Como publicar no GitHub Pages (5 minutos)

### Passo 1: Criar repositório
1. Acesse [github.com/new](https://github.com/new)
2. Nome do repositório: `dashboard-roi` (ou o que preferir)
3. Marque **Public**
4. Clique em **Create repository**

### Passo 2: Subir os arquivos
1. Na página do repositório, clique em **"uploading an existing file"**
2. Arraste o arquivo `index.html` para a página
3. Clique em **Commit changes**

### Passo 3: Ativar GitHub Pages
1. Vá em **Settings** (engrenagem) do repositório
2. No menu lateral, clique em **Pages**
3. Em "Source", selecione **Deploy from a branch**
4. Em "Branch", selecione **main** e pasta **/ (root)**
5. Clique em **Save**
6. Aguarde 1-2 minutos

### Passo 4: Acessar o dashboard
Seu dashboard estará disponível em:
```
https://SEU-USUARIO.github.io/dashboard-roi/
```

## 📥 Como atualizar dados

### Via Google Sheets (automático)
1. Publique suas planilhas: **Arquivo → Compartilhar → Publicar na Web**
2. No dashboard, aba "Importar / Sync", cole as URLs
3. Clique em "Sincronizar agora"
4. Os dados são atualizados para todos que acessarem o link

### Via arquivo Excel (manual)
1. Na aba "Importar / Sync", arraste o Excel do Meta e/ou GAM
2. Os dados ficam salvos no navegador

## 📋 Formato das planilhas

### Meta Ads
Cada campanha em uma aba separada (ex: "CAMPANHA 15"). Colunas:
- Dia, Nome da campanha, Posicionamento, Plataforma, Impressões, Cliques no link, CTR, CPC, CPM, Valor usado (USD)

### GAM
Cada campanha em uma aba separada. Colunas:
- Data, Chaves-valor, Receita, Impressões, Cliques, CTR, Receita total de CPM e de CPC, eCPM

## 🔗 Compartilhamento
Basta enviar o link do GitHub Pages para o time. Qualquer pessoa com o link pode acessar.
