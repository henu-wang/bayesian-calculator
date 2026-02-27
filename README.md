# Bayesian Probability Calculator & Visualizer

An interactive single-page application for understanding Bayes' theorem through hands-on calculation and visualization.

**Live Demo:** [https://henu-wang.github.io/bayesian-calculator/](https://henu-wang.github.io/bayesian-calculator/)

## Features

- **Interactive Calculator** - Adjust prior probability, sensitivity (true positive rate), and false positive rate with sliders and see results update in real time
- **Visual Probability Bars** - Side-by-side comparison of prior vs. posterior probability with colored bar charts
- **SVG Population Breakdown** - See true positives vs. false positives out of 10,000 people
- **Step-by-Step Math** - Full calculation breakdown showing each step of Bayes' theorem
- **Classic Examples** - Pre-loaded scenarios including:
  - Medical Test Paradox
  - Spam Filter (Naive Bayes)
  - Rare Event Detection (security screening)
  - Hiring Decision
- **Multi-Round Bayesian Update** - Add positive or negative evidence iteratively and watch beliefs evolve over time
- **Educational Content** - Explanation of why humans systematically fail at Bayesian reasoning (base rate neglect, confirmation bias, etc.)
- **Mobile Responsive** - Works on all screen sizes
- **Full SEO** - Open Graph, Twitter Card, and JSON-LD structured data

## How Bayes' Theorem Works

```
P(A|B) = P(B|A) × P(A) / P(B)
```

Where:
- **P(A)** = Prior probability (your belief before evidence)
- **P(B|A)** = Likelihood (probability of evidence given hypothesis is true)
- **P(B|¬A)** = False positive rate (probability of evidence given hypothesis is false)
- **P(B)** = Total probability of evidence = P(B|A)×P(A) + P(B|¬A)×P(¬A)
- **P(A|B)** = Posterior probability (updated belief after evidence)

## Technology

- Pure HTML/CSS/JavaScript (no build step)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- SVG visualizations
- Zero dependencies, zero backend

## About

Built by [KeepRule](https://keeprule.com) to promote better probabilistic thinking in investing and decision-making.

### Related Resources

- [Investment Principles](https://keeprule.com/en/principles) - Mental models from legendary investors
- [Decision Scenarios](https://keeprule.com/en/scenarios) - Practice applying frameworks to real situations
- [Masters of Investing](https://keeprule.com/en/masters) - Learn from Buffett, Munger, and more
- [Blog & Insights](https://keeprule.com/en/blog) - Articles on rational thinking and investing

## License

MIT License. Free to use, modify, and distribute.
