# 📸 COMO ADICIONAR SUA FOTO - GUIA SIMPLES

## 🚀 **MÉTODO MAIS FÁCIL**

### **Passo 1: Prepare sua foto**
- Salve sua foto no computador
- Renomeie para `foto-perfil.jpg` (ou .png)
- Coloque na mesma pasta do arquivo `index.html`

### **Passo 2: Edite o arquivo**
1. Abra o arquivo `index.html` no editor
2. Vá para a **linha 164** (procure por `<!-- <img src="foto-perfil.jpg"`)
3. **Remova os `<!--` e `-->`** da linha 164
4. **Remova o placeholder** (linhas 170-172)

### **Resultado final:**
```html
<img src="foto-perfil.jpg" alt="Ronaldo da Silva Melo" class="w-48 h-48 rounded-full border-4 border-[#00a0b0] shadow-lg hover:shadow-xl transition-shadow duration-300 profile-photo object-cover">
```

---

## 🌐 **MÉTODO COM URL ONLINE**

### **Passo 1: Faça upload da foto**
- Google Drive: Compartilhe como público
- Dropbox: Gere link público
- Imgur: Upload gratuito

### **Passo 2: Edite o arquivo**
1. Abra o arquivo `index.html`
2. Vá para a **linha 167** (procure por `<!-- <img src="SUA_URL_AQUI"`)
3. **Remova os `<!--` e `-->`**
4. **Substitua `SUA_URL_AQUI`** pela URL real
5. **Remova o placeholder** (linhas 170-172)

### **Exemplo:**
```html
<img src="https://drive.google.com/uc?id=SEU_ID_AQUI" alt="Ronaldo da Silva Melo" class="w-48 h-48 rounded-full border-4 border-[#00a0b0] shadow-lg hover:shadow-xl transition-shadow duration-300 profile-photo object-cover">
```

---

## ⚠️ **IMPORTANTE**
- **Remova sempre o placeholder** (div com "RSM") quando adicionar sua foto
- **Mantenha apenas uma opção** ativa (não deixe duas imagens)
- **Teste sempre** abrindo o arquivo no navegador

---

## 🆘 **PRECISA DE AJUDA?**
Me diga qual método você quer usar e eu te ajudo passo a passo!
