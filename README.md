# Merhaba, ben Kaan Gedikli! 👋

### Yazılım Geliştirici | Bilgi İşlem Uzmanı

Serdivan Belediyesi Bilgi İşlem Müdürlüğü bünyesinde, şehir hayatını kolaylaştıran dijital projeler geliştiriyorum. 

---

### 🛠️ Nelerle Uğraşıyorum?

- 📱 **Web:** React ve Strapi kullanarak modern, kullanıcı dostu arayüzler geliştiriyorum.
- 🗺️ **GIS / CBS:** Leaflet kütüphanesi ile interaktif harita sistemleri ve Saha Takip Sistemleri kurguluyorum.
- 🐍 **Backend:** Python ile veri yönetimi ve otomasyon süreçlerini yönetiyorum.

---

### 🚀 Teknik Yetkinlikler

| Alan | Teknolojiler |
| :--- | :--- |
| **Frontend** | React, JavaScript, HTML5, CSS3, Tailwind |
| **Backend & CMS** | Python, Strapi, Node.js |
| **Veritabanı & CBS** | PostgreSQL, SQLite |

### ✍️ Son Blog Yazılarım
name: Latest blog post workflow
on:
  schedule:
    - cron: '0 0 * * *'
  workflow_dispatch:

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v3
      - name: Pull in wordpress posts
        uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://kaangedikli.wordpress.com/feed/"
          max_post_count: 5


---

### 📊 GitHub İstatistiklerim

![Kaan's GitHub stats](https://github-readme-stats.vercel.app/api?username=bkaan7&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=bkaan7&layout=compact&theme=tokyonight)

---

### 📫 Bana Ulaşın

- **Blog:** kaangedikli.wordpress.com
- **Kurum:** Serdivan Belediyesi Bilgi İşlem Müdürlüğü

*"Don't Panic."* — 42.
