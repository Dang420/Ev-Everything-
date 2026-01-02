# EV Charge Finder ⚡

A beautiful, fast, and free web app to find **electric vehicle charging stations** worldwide — works for **ALL EVs** (Tesla, Hyundai, Ford, Chevy, Nissan, Rivian, BMW, Kia, Volkswagen, and more).

Live Demo: [https://yourusername.github.io/your-repo-name](https://yourusername.github.io/your-repo-name)  
*(Replace with your actual GitHub Pages link once deployed)*

## Features
- Interactive map with real charging stations
- Search by city, address, or zip code
- Shows connector types (CCS, CHAdeMO, J1772, Type 2, NACS/Tesla, etc.)
- Highlights **fast chargers** (>50 kW) with ⚡ badge
- Real-time status when available
- Mobile-friendly design
- 100% free • No login required • No tracking

## How It Works
Powered by:
- **Leaflet.js** + OpenStreetMap (beautiful free maps)
- **Open Charge Map** (world's largest open EV charging database)
- Pure HTML, CSS, and JavaScript (no backend needed)

## How to Use
1. Open the website
2. Allow location access (or search manually)
3. Browse stations on the map or list below
4. Click markers or cards for details

## Setup (For Developers)
This is a static site — just one file!

1. Fork or download this repo
2. Open `index.html` in your browser to test locally
3. Deploy instantly for free:

### Deploy on GitHub Pages (Recommended)
1. Push to a public GitHub repo
2. Go to **Settings** → **Pages**
3. Set source to `main` branch → `/ (root)`
4. Your site will be live at: `https://yourusername.github.io/repo-name`

### Other Free Hosting Options
- Vercel
- Netlify
- Cloudflare Pages

## Improve Data Quality (Optional but Recommended)
Sign up for a **free API key** at [openchargemap.org](https://openchargemap.org/site/register)  
Then replace this line in `index.html`:
```js
const OCM_API_KEY = 'YOUR_API_KEY_HERE';
```
