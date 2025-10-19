# Como Adicionar Sua Foto ao Currículo

## 📸 Instruções para Inserir Sua Foto

### Opção 1: Usando uma URL de Imagem Online
1. Faça upload da sua foto para um serviço como:
   - Google Drive (compartilhar como público)
   - Dropbox
   - Imgur
   - GitHub (criando um repositório para assets)

2. Substitua o placeholder atual no arquivo `index.html`:
```html
<!-- Linha 162-164 - Substitua este div -->
<div class="w-48 h-48 rounded-full border-4 border-[#00a0b0] shadow-lg hover:shadow-xl transition-shadow duration-300 profile-photo bg-gradient-to-br from-[#003f5c] to-[#4d8fac] flex items-center justify-center text-white text-6xl font-bold">
    RSM
</div>

<!-- Por sua imagem real -->
<img src="https://sua-url-aqui.com/sua-foto.jpg" alt="Ronaldo da Silva Melo" class="w-48 h-48 rounded-full border-4 border-[#00a0b0] shadow-lg hover:shadow-xl transition-shadow duration-300 profile-photo object-cover">
```

### Opção 2: Usando uma Imagem Local
1. Coloque sua foto na mesma pasta do `index.html`
2. Renomeie para `foto-perfil.jpg` (ou .png)
3. Substitua o div por:
```html
<img src="foto-perfil.jpg" alt="Ronaldo da Silva Melo" class="w-48 h-48 rounded-full border-4 border-[#00a0b0] shadow-lg hover:shadow-xl transition-shadow duration-300 profile-photo object-cover">
```

### Opção 3: Usando Base64 (Recomendado para garantir funcionamento)
1. Converta sua imagem para Base64 usando um conversor online
2. Substitua o div por:
```html
<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQ..." alt="Ronaldo da Silva Melo" class="w-48 h-48 rounded-full border-4 border-[#00a0b0] shadow-lg hover:shadow-xl transition-shadow duration-300 profile-photo object-cover">
```

## 📐 Especificações da Foto
- **Formato**: JPG ou PNG
- **Tamanho recomendado**: 400x400 pixels (mínimo)
- **Proporção**: Quadrada (1:1)
- **Qualidade**: Alta resolução para ficar nítida
- **Fundo**: Preferencialmente neutro ou transparente

## 🎨 Características da Foto no Currículo
- **Formato**: Circular com borda azul
- **Tamanho**: 192x192 pixels (12rem)
- **Efeitos**: Sombra e hover com escala
- **Responsivo**: Reduz para 150x150 em mobile

## 💡 Dicas
- Use uma foto profissional e recente
- Certifique-se de que o rosto está bem visível
- Evite fotos com fundos muito coloridos
- A foto será exibida em formato circular, então posicione o rosto no centro
