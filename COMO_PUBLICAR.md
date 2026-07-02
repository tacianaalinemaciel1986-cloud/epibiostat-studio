# Guia rápido para publicar

## Pelo site do GitHub

1. Entre no GitHub.
2. Clique em **New repository**.
3. Nomeie como `epibiostat-studio`.
4. Escolha **Public**.
5. Clique em **Create repository**.
6. Clique em **uploading an existing file**.
7. Arraste todos os arquivos desta pasta.
8. Clique em **Commit changes**.
9. Vá em **Settings > Pages**.
10. Selecione **Deploy from a branch**, branch **main**, pasta **/(root)**.
11. Clique em **Save**.

## Pelo Git

```bash
git clone https://github.com/SEU-USUARIO/epibiostat-studio.git
cd epibiostat-studio
# copie os arquivos desta pasta para dentro do repositório
git add .
git commit -m "Publica EpiBioStat Studio"
git push origin main
```

Depois ative o GitHub Pages em **Settings > Pages**.
