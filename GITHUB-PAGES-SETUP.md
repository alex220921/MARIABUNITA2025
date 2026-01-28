# Setup GitHub Pages - Maria Bunita

## ⚡ Setup Rápido (3 passos)

### 1. Criar Repositório no GitHub

1. Acesse https://github.com/new
2. Nome do repositório: `seu-usuario.github.io`
   - Substitua `seu-usuario` pelo seu username do GitHub
3. Clique em "Create repository"

### 2. Fazer Upload dos Arquivos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/seu-usuario.github.io.git
cd seu-usuario.github.io

# Copie todos os arquivos deste pacote para a pasta
# (index.html, assets/, images/, etc)

# Faça commit e push
git add .
git commit -m "Deploy Maria Bunita Website"
git push origin main
```

### 3. Acessar o Site

Seu site estará disponível em:
- **https://seu-usuario.github.io**

## 🌐 Usar Domínio Customizado (Opcional)

### Se você tem um domínio próprio:

1. **Edite o arquivo CNAME:**
   - Abra `CNAME`
   - Substitua `seu-dominio.com` pelo seu domínio
   - Salve e faça push

2. **Configure DNS no seu registrador:**
   - Adicione um registro CNAME apontando para: `seu-usuario.github.io`
   - Ou adicione um registro A apontando para: `185.199.108.153`

3. **Ative HTTPS no GitHub:**
   - Vá para Settings → Pages
   - Marque "Enforce HTTPS"

## 📋 Arquivos Inclusos

- `index.html` - Página principal compilada
- `assets/` - CSS e JavaScript minificados
- `images/` - Todas as imagens do site
- `.nojekyll` - Arquivo para desabilitar Jekyll
- `CNAME` - Configuração de domínio customizado
- `GITHUB-PAGES-SETUP.md` - Este arquivo

## ✅ Verificar Deploy

1. Acesse https://seu-usuario.github.io
2. Verifique se o site carregou corretamente
3. Teste responsividade em mobile
4. Teste links e botões WhatsApp

## 🔧 Atualizar o Site

Para fazer alterações:

1. Edite os arquivos localmente
2. Faça commit: `git add . && git commit -m "Atualização"`
3. Faça push: `git push origin main`
4. GitHub Pages atualiza automaticamente em ~1 minuto

## ⚙️ Configurações GitHub Pages

1. Acesse seu repositório
2. Vá para Settings → Pages
3. Verifique:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - HTTPS: Ativado

## 🆘 Troubleshooting

### Site não carrega
- Aguarde 1-2 minutos após push
- Limpe cache do navegador (Ctrl+Shift+Del)
- Verifique se o arquivo index.html está na raiz

### Imagens não aparecem
- Verifique se a pasta `images/` foi enviada
- Verifique permissões dos arquivos

### Domínio customizado não funciona
- Aguarde 24-48 horas para propagação DNS
- Verifique registros DNS no seu registrador
- Certifique-se que HTTPS está ativado

## 📊 Estatísticas

- Tamanho total: ~22 MB (compactado)
- Tempo de carregamento: < 2 segundos
- Compatibilidade: Todos os navegadores modernos
- Responsividade: Mobile, Tablet, Desktop

## 🎯 Próximos Passos

Após hospedar no GitHub Pages, você pode:

1. **Adicionar domínio customizado**
   - Configure CNAME e DNS

2. **Ativar Google Analytics**
   - Adicione código de tracking no `index.html`

3. **Fazer alterações**
   - Edite `index.html` ou `assets/` conforme necessário

4. **Versionar mudanças**
   - Use Git para manter histórico de alterações

## 📞 Suporte

- **GitHub Pages Docs**: https://pages.github.com
- **GitHub Help**: https://help.github.com
- **Manus Help**: https://help.manus.im

---

**Versão**: 1.0.0
**Data**: 28/01/2026
**Site**: Maria Bunita Unhas Recife
