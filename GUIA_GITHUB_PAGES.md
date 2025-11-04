# 📤 Guia para Publicar no GitHub Pages

## Passo 1: Inicializar o repositório Git (se ainda não fez)

Abra o PowerShell ou CMD na pasta do projeto e execute:

```bash
cd "C:\Users\carme\OneDrive\Documentos\ambiental_pro\f2w\live"
git init
```

## Passo 2: Adicionar o repositório remoto

```bash
git remote add origin https://github.com/CarmenLMTavares/f2w-aula1_piloto_f2w_tavares.git
```

## Passo 3: Adicionar todos os arquivos necessários

```bash
git add index.html
git add README.md
git add .gitignore
git add .nojekyll
git add data/tavares.geojson
git add data/imoveis_rurais_tavares.geojson
```

## Passo 4: Fazer o commit

```bash
git commit -m "Inicial: WebGIS com Leaflet - Tavares, RS"
```

## Passo 5: Fazer push para o GitHub

```bash
git branch -M main
git push -u origin main
```

Se pedir autenticação, você pode precisar usar um token de acesso pessoal.

## Passo 6: Habilitar GitHub Pages

1. Vá para: https://github.com/CarmenLMTavares/f2w-aula1_piloto_f2w_tavares
2. Clique em **Settings** (Configurações)
3. No menu lateral, clique em **Pages**
4. Em **Source** (Origem), selecione:
   - Branch: **main**
   - Folder: **/ (root)**
5. Clique em **Save** (Salvar)

## Passo 7: Aguardar publicação

- Aguarde alguns minutos (geralmente 1-3 minutos)
- A URL será: `https://carmenlmtavares.github.io/f2w-aula1_piloto_f2w_tavares/`

## 🔄 Para atualizar no futuro

Quando fizer alterações no código:

```bash
git add .
git commit -m "Descrição das alterações"
git push
```

O GitHub Pages atualiza automaticamente após alguns minutos.

## ⚠️ Importante

- Certifique-se de que o arquivo `index.html` está na raiz do repositório
- As pastas `data/` devem estar no mesmo nível do `index.html`
- O arquivo `.nojekyll` garante que o GitHub Pages funcione corretamente


