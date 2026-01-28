# guesstopass

Small web application to demonstrate chance guessing in multiple-choice questions.

## Usage

Open `index.html` in a browser, or serve the folder with:

```bash
python -m http.server 8000 --directory .
```

Then visit `http://localhost:8000/` (or `http://localhost:8000/index.html`) and enter the pass score, number of items, and number of options per item to see the probability of passing by random guessing.
