# ORIOM — Landing Page de Vendas

## Como publicar na Vercel (passo a passo)

### 1. Criar repositório no GitHub
1. Acessa github.com e faz login
2. Clica em "+" no canto superior direito → "New repository"
3. Nome: `oriom-landing`
4. Deixa como "Public" ou "Private" (tanto faz)
5. Clica em "Create repository"
6. Vai aparecer instruções — guarda a URL do repo (algo como `https://github.com/seu-usuario/oriom-landing.git`)

### 2. Subir os arquivos pro GitHub
No terminal (Prompt de Comando):

```
cd CAMINHO\DA\PASTA\oriom-landing
git init
git add .
git commit -m "landing page oriom"
git branch -M main
git remote add origin https://github.com/seu-usuario/oriom-landing.git
git push -u origin main
```

### 3. Importar na Vercel
1. Acessa vercel.com e faz login
2. Clica em "Add New" → "Project"
3. Importa o repositório `oriom-landing` do GitHub
4. Framework: seleciona "Other" (é HTML estático)
5. Clica em "Deploy"

### 4. Conectar o domínio oriom.online
1. No projeto na Vercel → Settings → Domains
2. Adiciona `oriom.online`
3. A Vercel vai dar instruções de DNS
4. Na Hostinger, adiciona os registros DNS que a Vercel pedir

Pronto! A landing page vai estar em oriom.online
