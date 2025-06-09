# 🚀 GitHub Pages'e Proje Yükleme Rehberi

## Adım 1: Repository Hazırlığı
1. GitHub'da repository'nizi açın
2. **"Add file" > "Upload files"** butonuna tıklayın

## Adım 2: Ana Dosyaları Yükleyin
Aşağıdaki dosyaları **TEK TEK** yükleyin:

### 📄 Kök Dizin Dosyaları:
- `package.json`
- `index.html`
- `vite.config.ts`
- `tailwind.config.js`
- `postcss.config.js`
- `tsconfig.json`
- `tsconfig.app.json`
- `tsconfig.node.json`
- `eslint.config.js`
- `README.md`

### 📁 .github/workflows/ Klasörü:
1. **"Create new file"** tıklayın
2. Dosya adı: `.github/workflows/deploy.yml`
3. İçeriği kopyalayıp yapıştırın

### 📁 src/ Klasörü Dosyaları:
Her dosya için **"Create new file"** kullanın:

1. `src/main.tsx`
2. `src/App.tsx`
3. `src/index.css`
4. `src/vite-env.d.ts`
5. `src/components/Navigation.tsx`
6. `src/components/PhotoAnalysis.tsx`
7. `src/components/DrugAdvice.tsx`
8. `src/components/SmartIrrigation.tsx`
9. `src/components/About.tsx`
10. `src/components/Contact.tsx`
11. `src/components/Modal.tsx`
12. `src/components/AnimatedSection.tsx`

## Adım 3: GitHub Pages Ayarları
1. Repository **Settings** > **Pages** bölümüne gidin
2. **Source**: "GitHub Actions" seçin
3. Dosyalar yüklendikten sonra otomatik deploy başlayacak

## Adım 4: Site URL'i
Deploy tamamlandığında siteniz şu adreste yayında olacak:
`https://kullaniciadi.github.io/ai-tarim/`

## ⚠️ Önemli Notlar:
- Her dosyayı yükledikten sonra **"Commit changes"** yapın
- Dosya içeriklerini kopyalarken **TAM** içeriği aldığınızdan emin olun
- `.github/workflows/deploy.yml` dosyası çok önemli - bu olmadan otomatik deploy çalışmaz

## 🔧 Alternatif Yöntem - GitHub Desktop:
1. GitHub Desktop uygulamasını indirin
2. Repository'yi clone edin
3. Tüm dosyaları kopyalayıp yapıştırın
4. Commit ve push yapın

Bu yöntem daha hızlı ve hatasız olacaktır.