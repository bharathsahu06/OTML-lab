# OTML Lab

OTML Lab is a static educational website for Optimization Techniques and Machine Learning laboratory experiments. The project is organized for easy browsing on the web and is now ready for deployment and hosting on Vercel.

## Overview

The website contains 19 experiment pages grouped into 5 course outcomes:

- CO1: Gradient Descent and optimization fundamentals
- CO2: Convex optimization and linear programming
- CO3: Sub-gradient and interior point methods
- CO4: Mini-batch and distributed gradient descent
- CO5: Regularization and advanced optimization methods

Each experiment page includes:

- Aim
- Description
- Algorithm
- Formula section
- Mathematical procedure
- Python program
- Expected output

## Included Pages

- `index.html` - landing page with all experiments
- `guide.html` - quick learning guide
- `reference.html` - glossary and concept reference
- `experiments/exp1.html` to `experiments/exp19.html` - individual experiment pages

## Tech Stack

- HTML5
- CSS3
- Static site hosting on Vercel
- Python code samples embedded in the content

No frontend framework or build pipeline is required for this project.

## Run Locally

You can use the project in either of these ways:

1. Open `index.html` directly in a browser.
2. Serve the folder locally with a simple static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Vercel Deployment

This project works as a zero-build static website on Vercel.

- Deployment status: ready and deployed on Vercel
- Build command: not required
- Output directory: not required for plain static hosting
- Entry page: `index.html`

If you redeploy later, Vercel can host the project directly without additional framework configuration.

## Python Libraries Used In Experiments

The website itself does not need Python to run. Python is only needed if you want to execute the sample programs shown in the experiment pages.

Install the common libraries with:

```bash
pip install numpy scipy scikit-learn cvxpy pulp matplotlib
```

## Project Structure

```text
.
|-- index.html
|-- guide.html
|-- reference.html
|-- README.md
|-- GETTING-STARTED.md
|-- WEBSITE-SUMMARY.md
|-- css/
|   `-- style.css
|-- experiments/
|   |-- exp1.html
|   |-- exp2.html
|   |-- ...
|   `-- exp19.html
`-- js/
```

## Learning Flow

Recommended order:

1. Start from `index.html`
2. Open `guide.html` for the study path
3. Work through experiments in order from CO1 to CO5
4. Use `reference.html` whenever you need quick definitions or concept refreshers

## Notes

- The site is fully static and lightweight.
- It can be opened offline or hosted online.
- The experiment code is designed for learning and demonstration.
- The layout is responsive for desktop and mobile browsing.

## Last Updated

March 27, 2026
