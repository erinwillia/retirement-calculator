# Retirement Savings Comparison Calculator

An interactive Monte Carlo simulation tool that compares retirement outcomes for 15%, 18%, and 20% savings rates.

## Features
- **Monte Carlo Simulation**: Runs 1,000 market scenarios to show range of possible outcomes
- **Visual Projections**: Interactive charts showing growth trajectories
- **Detailed Comparisons**: Side-by-side analysis of contribution rates
- **Customizable Inputs**: Adjust age, salary, returns, volatility, and more
- **Roth 403(b) Focus**: Designed for workplace Roth contribution planning

## How to Use

### Option 1: Open Locally
1. Download `retirement_comparison.html`
2. Open it in any web browser (Chrome, Firefox, Safari, Edge)
3. No installation required - works completely offline!

### Option 2: Host on GitHub Pages (Free)
1. Create a GitHub account at https://github.com
2. Create a new repository (name it something like `retirement-calculator`)
3. Upload `retirement_comparison.html` and rename it to `index.html`
4. Go to repository Settings → Pages
5. Select "main" branch as source
6. Your app will be live at: `https://[your-username].github.io/retirement-calculator`

### Option 3: Deploy to Netlify (Free, Easy)
1. Go to https://app.netlify.com/drop
2. Drag and drop `retirement_comparison.html` onto the page
3. Get instant live URL (e.g., `https://random-name-123.netlify.app`)
4. Optional: Claim the site and customize the URL

### Option 4: Deploy to Vercel (Free)
1. Sign up at https://vercel.com
2. Click "New Project"
3. Upload `retirement_comparison.html`
4. Deploy - get instant live URL

## Technical Details
- Pure HTML/CSS/JavaScript - no backend required
- Uses Chart.js for visualizations
- Responsive design works on mobile and desktop
- No data collection or tracking
- All calculations happen in your browser

## Customization
You can modify the defaults in the HTML file:
- Line 180: Change default current age
- Line 184: Change default retirement age
- Line 188: Change default salary
- Line 192: Change default current balance
- Line 196: Change default return rate
- Line 200: Change default volatility

## About the Calculation
The Monte Carlo simulation:
1. Generates 1,000 random market scenarios
2. Each scenario uses a normal distribution with your specified return and volatility
3. Compounds contributions and returns annually
4. Accounts for salary increases over time
5. Shows median (50th percentile) along with 10th and 90th percentiles

The 4% safe withdrawal rate is a common retirement planning guideline suggesting you can withdraw 4% of your portfolio annually with low risk of running out of money.

## License
Free to use, modify, and share. No attribution required.

---
Created for retirement planning comparison - not financial advice. Consult with a financial advisor for personalized guidance.
