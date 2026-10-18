# Pune Artisan Bakes – Production Static Website & SEO Hub

A complete, high-performance, multi-page website built for **Pune Artisan Bakes**, an artisan eggless home bakery based in Pune, Maharashtra.

This repository is ready for immediate deployment on **Vercel**, **GitHub Pages**, or any static web host.

---

## 📁 URL & File Structure

| Page | File Path | Primary Keyword |
| :--- | :--- | :--- |
| **Homepage** | `/index.html` | `eggless cakes Pune` |
| **Article 1: Cake Storage** | `/how-to-store-cake.html` | `how to store cake` |
| **Article 2: Eggless Recipe** | `/best-eggless-chocolate-cake-recipe.html` | `best eggless chocolate cake recipe` |
| **Article 3: Custom Cakes** | `/custom-birthday-cakes-pune.html` | `custom birthday cakes Pune` |

---

## 🚀 Deployment to Vercel

### Option 1: Direct Push via Git
1. Push this repository to GitHub, GitLab, or Bitbucket.
2. In Vercel, click **"Add New Project"** and import this repository.
3. Vercel automatically detects the static HTML and `vercel.json` clean URL routing configuration.
4. Click **Deploy**.

### Option 2: Build with Vite
- **Build Command**: `npm run build`
- **Output Directory**: `dist`

---

## 🔍 On-Page SEO & AEO Highlights

1. **Optimized Meta Tags:**
   - Every `<title>` tag is under 60 characters with the primary keyword positioned at the start.
   - Every `<meta name="description">` is strictly between 140 and 160 characters, with primary/secondary keywords and clear calls-to-action.
2. **Answer Engine Optimization (AEO):**
   - Every `<h2>` across all 3 long-form guides is written as a direct, searchable question.
   - The paragraph immediately beneath each `<h2>` provides a direct, factual answer for Google AI Overviews and featured snippets.
3. **Structured Data (Schema.org JSON-LD):**
   - Homepage: `Bakery` / `LocalBusiness` schema with Pune coordinates, opening hours, review rating (4.9/5), and neighborhood coverage.
   - Article 1: `Article` + `HowTo` + `FAQPage` schema.
   - Article 2: `Recipe` schema (with ingredients, instructions, yield, nutrition) + `FAQPage`.
   - Article 3: `Service` + `Bakery` + `FAQPage` schema.
4. **Natural Keyword Anchors:**
   - Internal links use descriptive keyword phrases (e.g. *"how to store cake to keep it moist and fresh"*, *"best eggless chocolate cake recipe"*).
5. **Interactive Enhancements:**
   - Pune cake weight and guest calculator.
   - Dynamic 1x / 1.5x / 2x recipe ingredient scaler.
   - WhatsApp quick ordering modal pre-filled with Pune delivery localities.
