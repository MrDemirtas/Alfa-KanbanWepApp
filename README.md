# Alfa Kanban Web App

Bu proje, Acunmedya Akademi'de ekip çalışması ile geliştirilmiş modern bir Kanban görev yönetim uygulamasıdır.

## 🌐 Demo

Projenin canlı demosuna [buradan](https://alfa-kanban-wep-app.vercel.app/) ulaşabilirsiniz.

## 🚀 Özellikler

- Yerel depolama ile veri kalıcılığı (LocalStorage)
- Responsive tasarım ile tüm ekran boyutlarına uyum
- Board oluşturma ve yönetme
- Görev kartları oluşturma ve düzenleme
- Görevleri farklı kolonlar arasında organize etme
- Bildirim sistemi ile kullanıcı geri bildirimi
- Yan menü ile kolay gezinme
- Karanlık/Aydınlık tema desteği

## 💻 Kullanılan Teknolojiler

- **Frontend Framework:** React.js
- **State Yönetimi:** React Context API
- **Veri Saklama:** LocalStorage
- **Build Tool:** Vite.js
- **Bildirim Sistemi:** React Hot Toast
- **Stil:** CSS Modules

## 🏗️ Proje Yapısı

```
src/
├── components/
│   ├── Header.jsx
│   ├── Main.jsx
│   └── Sidebar.jsx
├── css/
├── App.jsx
├── main.jsx
└── reset.css
```

## 🛠️ Kurulum

1. Projeyi klonlayın:

```bash
git clone github.com/MrDemirtas/Alfa-KanbanWepApp
```

2. Proje dizinine gidin:

```bash
cd alfa-kanban-wep-app
```

3. Bağımlılıkları yükleyin:

```bash
npm install
```

4. Geliştirme sunucusunu başlatın:

```bash
npm run dev
```

## 📦 Scripts

- `npm run dev`: Geliştirme sunucusunu başlatır
- `npm run build`: Projeyi production için derler
- `npm run lint`: ESLint ile kod kontrolü yapar
- `npm run preview`: Production build'i local'de önizleme
