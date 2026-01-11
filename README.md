# 💰 Dinheiro Sob Controle - Landing Page

> Landing page de vendas profissional do sistema **Dinheiro Sob Controle**

[![Deploy no Render](https://img.shields.io/badge/Deploy-Render-46E3B7?style=for-the-badge&logo=render)](https://render.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)

## 📋 Sobre

Static site otimizado para conversão de vendas do sistema de gestão financeira **Dinheiro Sob Controle**. 

Design premium inspirado em landing pages modernas, com foco em UX/UI e alta taxa de conversão.

## 📁 Estrutura do Projeto

```
dinheiro-sob-controle-lp/
├── index.html       # Página principal (HTML5 semântico)
├── style.css        # Estilos customizados (CSS3)
├── README.md        # Documentação (este arquivo)
└── .gitignore       # Arquivos ignorados pelo Git
```

## 🎨 Características

- ✅ **Design Premium** - Gradientes modernos (azul marinho + verde)
- ✅ **100% Responsivo** - Funciona perfeitamente em mobile, tablet e desktop
- ✅ **Performance Otimizada** - Carregamento ultra-rápido
- ✅ **SEO Friendly** - Meta tags otimizadas
- ✅ **Pronto para Render** - Deploy em 1 clique

## 🚀 Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|------------|--------|-----|
| HTML5 | Latest | Estrutura semântica |
| CSS3 | Latest | Estilização avançada |
| Bootstrap | 5.3.2 | Framework responsivo |
| Font Awesome | 6.4.0 | Ícones profissionais |
| Google Fonts | Inter | Tipografia moderna |

## 📦 Como Subir para o GitHub

### 1️⃣ Criar Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login
2. Clique em **"New Repository"** (botão verde)
3. Configure:
   - **Repository name**: `dinheiro-sob-controle-lp`
   - **Description**: `Landing page de vendas - Dinheiro Sob Controle`
   - **Visibility**: Public ou Private (sua escolha)
   - ❌ **NÃO marque** "Add a README file" (já temos um)
   - ❌ **NÃO adicione** .gitignore nem license
4. Clique em **"Create repository"**
5. **Copie a URL** que aparece (ex: `https://github.com/seu-usuario/dinheiro-sob-controle-lp.git`)

### 2️⃣ Executar Comandos no Terminal

Abra o **PowerShell** na pasta da landing page e execute:

```powershell
# Navegar até a pasta da landing page
cd "C:\Users\jhenn\OneDrive\Documentos\PROJETO- DINHEIRO SOB CONTROLE\vendas_lp"

# Inicializar repositório Git
git init

# Adicionar todos os arquivos
git add .

# Fazer o primeiro commit
git commit -m "🚀 Landing page inicial - Dinheiro Sob Controle"

# Definir branch principal como 'main'
git branch -M main

# Conectar ao repositório remoto (SUBSTITUA pela sua URL)
git remote add origin https://github.com/SEU-USUARIO/dinheiro-sob-controle-lp.git

# Enviar para o GitHub
git push -u origin main
```

> ⚠️ **IMPORTANTE**: Substitua `SEU-USUARIO` pela URL real que você copiou do GitHub!

### 3️⃣ Verificar se Funcionou

1. Atualize a página do seu repositório no GitHub
2. Você deve ver os arquivos: `index.html`, `style.css`, `README.md`
3. Se aparecer tudo, está pronto para o Render! ✅

## 🌐 Deploy no Render (Static Site)

### Passo a Passo:

1. **Acessar Render**
   - Vá para [render.com](https://render.com)
   - Faça login (pode usar conta do GitHub)

2. **Criar Static Site**
   - Clique em **"New +"** → **"Static Site"**
   - Autorize o Render a acessar seus repositórios GitHub
   - Selecione o repo `dinheiro-sob-controle-lp`

3. **Configurações do Deploy**
   ```
   Name: dinheiro-sob-controle-lp
   Branch: main
   Build Command: (deixe vazio)
   Publish Directory: . (apenas um ponto)
   ```

4. **Deploy**
   - Clique em **"Create Static Site"**
   - Aguarde 1-2 minutos
   - Sua URL será: `https://dinheiro-sob-controle-lp.onrender.com`

### Auto-Deploy Ativo ✅

Sempre que você fizer push no GitHub, o Render atualiza automaticamente!

```bash
# Fazer mudanças e atualizar
git add .
git commit -m "Descrição da mudança"
git push origin main
# Render deploya automaticamente!
```

## 🔗 Configurações Importantes

### Link de Pagamento

Atualmente: `https://pay.cakto.com.br/3ah8tei_701038`

Para alterar, edite todos os botões CTA no `index.html`:
```html
<a href="SEU_NOVO_LINK_AQUI" class="btn btn-success">
```

### Domínio Customizado (Opcional)

No painel do Render:
1. **Settings** → **Custom Domain**
2. Adicione: `vendas.seudominio.com.br`
3. Configure DNS conforme instruções

## 📱 Preview Local

Para testar localmente antes de subir:

**Opção 1 - Duplo Clique:**
```
Abrir index.html direto no navegador
```

**Opção 2 - Live Server (VS Code):**
```
1. Instalar extensão "Live Server"
2. Clicar com botão direito em index.html
3. Selecionar "Open with Live Server"
```

## 🛠️ Comandos Git Úteis

```bash
# Ver status dos arquivos
git status

# Ver histórico de commits
git log --oneline

# Desfazer mudanças não commitadas
git checkout .

# Ver repositório remoto
git remote -v

# Atualizar do GitHub
git pull origin main
```

## 📞 Suporte

- 📚 [Documentação Render](https://render.com/docs/static-sites)
- 💻 [Bootstrap Docs](https://getbootstrap.com/docs/5.3)
- 🎨 [Font Awesome Icons](https://fontawesome.com/icons)

## 📄 Licença

© 2026 Dinheiro Sob Controle. Todos os direitos reservados.

---

**Desenvolvido com 💚 para conversão de vendas**
