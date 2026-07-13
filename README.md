# 🔱 Explore Banaras – Mahadev ki Nagri

A beautiful, animated Flask website showcasing Varanasi (Banaras/Kashi) — its ghats, temples, Sarnath, famous food, Banarasi sarees, and the narrow galis of the old city.

## Features

- 🏠 Hero section with Ganga Aarti background
- 📖 About Banaras
- 🌊 Ghats of Varanasi (84 ghats, Panch-Tirtha, and more)
- 🕉️ Famous Places & Sacred Temples (Kashi Vishwanath, Sankat Mochan, New Vishwanath Temple at BHU, Mansa Devi Mandir, Tridev Mandir)
- ☸️ Sarnath (Dhamek Stupa, Chaukhandi Stupa, Ashoka Pillar, Sarnath Museum)
- 🎓 Banaras Hindu University (BHU)
- 🍛 Famous Food (Kachori Sabzi, Tamatar Chaat, Lassi, Thandai, Jalebi, Paan)
- 🥻 Famous Dress (Banarasi Saree)
- 🛣️ Famous Galis (Godowlia, Vishwanath Gali, Thatheri Bazaar)
- 🖼️ Photo Gallery
- 📱 Fully responsive, with scroll fade-in animations

## Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML5, CSS3 (no external JS frameworks)
- **Images:** Hotlinked from Wikimedia Commons

## Folder Structure

```
banaras_project/
│
├── app.py
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## Setup & Run

```bash
# Clone the repository
git clone https://github.com/your-username/explore-banaras.git
cd explore-banaras

# Install Flask
pip install flask

# Run the app
python app.py
```

Then open **http://127.0.0.1:5000/** in your browser.

## Deploy on Render (Free Hosting)

1. Push this project to a GitHub repository (see steps above).
2. Go to [render.com](https://render.com) and sign up / log in (you can sign in with GitHub).
3. Click **New +** → **Web Service**.
4. Connect your GitHub account and select your `explore-banaras` repository.
5. Fill in the settings:
   - **Name:** `explore-banaras` (or anything you like)
   - **Runtime:** Python 3
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
6. Click **Create Web Service**.
7. Wait a couple of minutes for the build to finish — Render will give you a live URL like `https://explore-banaras.onrender.com`.

That's it — your site is now live on the internet, not just localhost!

## License

Free to use for learning and personal projects.
