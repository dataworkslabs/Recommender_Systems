# Letterboxd Recommender System Analysis

## About This Project
This project takes a close look at how Letterboxd handles movie recommendations.
Letterboxd is a social film platform with over 17 million users, but its approach
to recommendations is surprisingly different from what you'd expect — there's no
personalized "recommended for you" page at all. Instead, discovery happens through
a mix of NLP-powered similar film suggestions, a social activity feed, user-created
lists, and editorial picks.

The analysis covers three main areas:
- **Scenario Design** — looking at the goals of both Letterboxd as a business and
  its users, and where those goals overlap or conflict
- **Reverse Engineering** — digging into how the platform's recommendation features
  actually work under the hood, including the Nanocrowd partnership and the weighted
  rating system
- **Improvement Recommendations** — three concrete suggestions for how Letterboxd
  could make its recommendations better

## Files
- `Recommender(Letterboxd).qmd` — Main analysis in Quarto format
- `Recommender(Letterboxd).html` — Rendered HTML output

## How to Render
If you have Quarto installed you can render the .qmd file with:
```bash
quarto render Recommender(Letterboxd).qmd
```

## Author
Mark Hamer
