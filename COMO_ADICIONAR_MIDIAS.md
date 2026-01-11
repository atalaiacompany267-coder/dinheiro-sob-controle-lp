# 📹 Como Adicionar Vídeos e Imagens

## 📁 Estrutura de Pastas

Crie esta estrutura na pasta `vendas_lp`:

```
vendas_lp/
  ├── index.html
  ├── style.css
  ├── imagens/          ← CRIE ESTA PASTA
  │   ├── hero-demo.mp4 ou hero-demo.jpg
  │   ├── video-completo.mp4
  │   ├── lancamentos-automaticos.png
  │   ├── dashboard-graficos.png
  │   ├── metas-financeiras.png
  │   ├── controle-dividas.png
  │   ├── foto-perfil.jpg
  │   ├── depoimento-1.mp4
  │   ├── depoimento-2.mp4
  │   └── depoimento-3.mp4
```

---

## 🎬 VÍDEOS

### 1️⃣ Hero Section (Linha ~75 no HTML)

**OPÇÃO A - YouTube:**
```html
<!-- Encontre este código -->
<div class="demo-video-container">
    <div class="placeholder-box">
        <i class="fas fa-play-circle fa-6x mb-4"></i>
        ...
    </div>
</div>

<!-- SUBSTITUA por -->
<div class="demo-video-container">
    <div class="ratio ratio-16x9" style="border-radius: 20px; overflow: hidden;">
        <iframe src="https://www.youtube.com/embed/SEU_VIDEO_ID" 
                allowfullscreen
                style="border: none;"></iframe>
    </div>
</div>
```

**OPÇÃO B - Vídeo Local:**
```html
<div class="demo-video-container">
    <video controls class="w-100" style="border-radius: 20px;">
        <source src="imagens/hero-demo.mp4" type="video/mp4">
        Seu navegador não suporta vídeo.
    </video>
</div>
```

**OPÇÃO C - Imagem com Play Button:**
```html
<div class="demo-video-container">
    <img src="imagens/hero-demo.jpg" 
         alt="Demonstração do Sistema" 
         class="w-100" 
         style="border-radius: 20px; box-shadow: 0 20px 40px rgba(0,0,0,0.5);">
</div>
```

---

### 2️⃣ Vídeo Demo Completo (Linha ~90)

```html
<!-- Encontre -->
<div class="video-demo-box" data-aos="zoom-in">
    <div class="placeholder-box large">
        ...
    </div>
</div>

<!-- SUBSTITUA por -->
<div class="video-demo-box" data-aos="zoom-in">
    <div class="ratio ratio-16x9">
        <iframe src="https://www.youtube.com/embed/SEU_VIDEO_ID" 
                allowfullscreen></iframe>
    </div>
</div>
```

---

### 3️⃣ Depoimentos (Linha ~380)

```html
<!-- Encontre cada depoimento -->
<div class="testimonial-video-box">
    <div class="placeholder-box">
        ...
    </div>
</div>

<!-- SUBSTITUA por -->
<div class="testimonial-video-box">
    <div class="ratio ratio-16x9">
        <iframe src="https://www.youtube.com/embed/VIDEO_DEPOIMENTO_1" 
                allowfullscreen></iframe>
    </div>
</div>
```

**OU com vídeo local:**
```html
<div class="testimonial-video-box">
    <video controls class="w-100" style="border-radius: 20px;">
        <source src="imagens/depoimento-1.mp4" type="video/mp4">
    </video>
</div>
```

---

## 🖼️ IMAGENS

### 4️⃣ Funcionalidade 1 - Lançamentos Automáticos (Linha ~230)

```html
<!-- Encontre -->
<div class="feature-image-box">
    <div class="placeholder-box">
        <i class="fas fa-magic fa-5x mb-3"></i>
        ...
    </div>
</div>

<!-- SUBSTITUA por -->
<div class="feature-image-box">
    <img src="imagens/lancamentos-automaticos.png" 
         alt="Lançamentos Automáticos" 
         class="w-100" 
         style="border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
</div>
```

---

### 5️⃣ Funcionalidade 2 - Gráficos (Linha ~255)

```html
<div class="feature-image-box">
    <img src="imagens/dashboard-graficos.png" 
         alt="Dashboard com Gráficos" 
         class="w-100" 
         style="border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
</div>
```

---

### 6️⃣ Funcionalidade 3 - Metas (Linha ~280)

```html
<div class="feature-image-box">
    <img src="imagens/metas-financeiras.png" 
         alt="Gestão de Metas" 
         class="w-100" 
         style="border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
</div>
```

---

### 7️⃣ Funcionalidade 4 - Dívidas (Linha ~305)

```html
<div class="feature-image-box">
    <img src="imagens/controle-dividas.png" 
         alt="Controle de Dívidas" 
         class="w-100" 
         style="border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
</div>
```

---

### 8️⃣ Sua Foto - Quem Somos (Linha ~420)

```html
<!-- Encontre -->
<div class="about-image-placeholder mb-4">
    <i class="fas fa-user-circle fa-8x"></i>
    ...
</div>

<!-- SUBSTITUA por -->
<div class="about-image mb-4">
    <img src="imagens/foto-perfil.jpg" 
         alt="Seu Nome" 
         class="rounded-circle" 
         style="width: 200px; height: 200px; object-fit: cover; border: 4px solid #10b981; box-shadow: 0 10px 30px rgba(16,185,129,0.3);">
</div>
```

---

## 📸 Dicas para Tirar Screenshots do Sistema

### Método 1: Navegador (Chrome/Edge)
1. Abra o sistema: https://seu-sistema.herokuapp.com
2. Pressione `F12` (Ferramentas de Desenvolvedor)
3. Clique no ícone de celular/tablet (Modo Responsivo)
4. Pressione `Ctrl + Shift + P`
5. Digite "screenshot" e escolha "Capture full size screenshot"

### Método 2: Windows
1. Pressione `Windows + Shift + S`
2. Selecione a área
3. Cole no Paint e salve

### Método 3: Extensão Awesome Screenshot
- Instale: https://chrome.google.com/webstore/detail/awesome-screenshot
- Capture tela inteira ou área específica

---

## 🎥 Como Fazer Vídeos

### Para Vídeo de Demonstração:
1. **OBS Studio** (Grátis): https://obsproject.com/
2. **Loom** (Fácil): https://www.loom.com/
3. **Windows Game Bar**: Pressione `Windows + G`

### Roteiro Sugerido (2-3 minutos):
1. Mostrar tela de login
2. Dashboard principal com gráficos
3. Criar um lançamento automático
4. Criar uma meta financeira
5. Mostrar relatório mensal

---

## 🚀 Como Atualizar no GitHub

Após adicionar suas mídias:

```powershell
cd "c:\Users\jhenn\OneDrive\Documentos\PROJETO- DINHEIRO SOB CONTROLE\vendas_lp"

git add .
git commit -m "📸 Adicionadas imagens e vídeos na landing page"
git push origin main
```

O Render vai atualizar automaticamente em 1-2 minutos!

---

## 💡 Dicas Importantes

### Otimização de Imagens:
- Use **TinyPNG**: https://tinypng.com/
- Ou **Squoosh**: https://squoosh.app/
- Reduz até 70% do tamanho sem perder qualidade

### Tamanhos Recomendados:
- Screenshots: 1920x1080 (Full HD)
- Foto perfil: 500x500 (quadrada)
- Hero images: 1920x1080 ou maior

### Formatos:
- **PNG**: Para screenshots com texto
- **JPG**: Para fotos
- **WebP**: Melhor compressão (mais moderno)
- **MP4**: Para vídeos (H.264 codec)

---

## ❓ Resolução de Problemas

### Imagem não aparece?
```html
<!-- Verifique se o caminho está correto -->
<img src="imagens/nome-do-arquivo.png" alt="Descrição">

<!-- Use barra normal /, não \ -->
<!-- Verifique se o nome do arquivo está exato (case-sensitive no servidor) -->
```

### Vídeo não carrega?
- Confirme que o vídeo do YouTube é **público** ou **não listado**
- Para vídeos locais, o arquivo precisa estar na pasta `imagens/`

---

## 🎯 Exemplo Completo - Hero Section

```html
<div class="col-lg-6 text-center" data-aos="fade-left">
    <!-- YouTube -->
    <div class="demo-video-container">
        <div class="ratio ratio-16x9" style="border-radius: 20px; overflow: hidden; box-shadow: 0 20px 40px rgba(0,0,0,0.5);">
            <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
                    allowfullscreen
                    style="border: none;"></iframe>
        </div>
    </div>
</div>
```

---

**Precisa de ajuda?** Me mande o tipo de mídia que quer adicionar e eu te mostro o código exato! 🚀
