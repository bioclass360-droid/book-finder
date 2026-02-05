# 📚 Next Read AI (The Book Matchmaker)

"What should I read next?" is a question millions of people ask every day. **Next Read AI** solves this decision paralysis. It is a minimalist recommendation engine that matches readers with their perfect book based on **Genre** and **Current Mood**.

## 🚀 Live Demo
**[Insert your live link here, e.g., https://yourusername.github.io/book-finder/]**

## ✨ Key Features
- **Mood-Based Filtering:** Unlike Amazon (which filters by category), this tool filters by *vibe* (e.g., "Easy & Quick" vs. "Deep & Serious").
- **Curated Database:** Features only high-rated, evergreen bestsellers to ensure user satisfaction.
- **Zero-Friction UI:** No sign-up required. Users get a recommendation in just 2 clicks.
- **Affiliate Optimized:** The final "Get it on Amazon" button is designed to maximize click-through rates (CTR).

## ⚙️ How It Works
The tool uses a lightweight decision tree algorithm:
1.  **Input 1 (Genre):** Wealth, Psychology, Thriller, or Romance.
2.  **Input 2 (Vibe):** User selects if they want a light read or a heavy, intellectual challenge.
3.  **Matching:** The JavaScript logic queries the internal `books` array to find the specific object that matches both criteria.
4.  **Output:** Instantly renders the book cover, description, and purchase link without reloading the page.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Clean, distraction-free typography).
- **Logic:** Vanilla JavaScript (ES6).
- **Hosting:** GitHub Pages.
- **Performance:** 100/100 Lighthouse Score (No heavy frameworks).

## 💰 Monetization Strategy
This tool is built for **High-Volume Affiliate Marketing**:
- **Impulse Friendly:** Books are low-ticket items (₹200-₹500), leading to higher conversion rates than expensive tech.
- **Evergreen Content:** The database focuses on "Timeless Classics" (e.g., *Atomic Habits*, *The Alchemist*), meaning the recommendations never go out of style.
- **Cookie Duration:** Even if the user doesn't buy the specific book, the Amazon cookie tracks *anything* they buy for the next 24 hours.

## 📝 Usage for Developers
1. Clone the repository.
2. Open `index.html`.
3. Locate the `books` array in the `<script>` section.
4. Replace the `link` properties with your own **Amazon Associate** affiliate links.
