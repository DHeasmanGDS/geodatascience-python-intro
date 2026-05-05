# Python for Geoscientists — Frank Arnott Tutorial Series

A beginner-friendly introduction to Python, computer science, and data science for geoscientists, made for Frank Arnott Award participants and anyone else who wants to bridge the gap between geology and code.

No prior coding experience required. If you can use Excel, you have everything you need to start.

## Who this is for

- Geoscientists curious about data science but unsure where to start
- Frank Arnott participants looking to skill up before the competition
- Anyone who's opened a Python tutorial, seen a wall of installation instructions, and closed the tab

## Who I am

I'm Drew, a geologist working at the intersection of data science and exploration geoscience. My team and I won the Frank Arnott competition in 2022, and I write about this stuff regularly at [botsontheground.com](https://botsontheground.com). I made these tutorials because the gap between geology and data science is mostly a confidence gap, not a skill gap.

## The series

| Video | Topic | Length |
|-------|-------|--------|
| 0 | Why data science matters for geoscientists | ~10 min |
| 1 | Getting Python running on your computer | ~30 min |
| 2 | Python basics for geoscientists | ~30 min |
| 3 | Core libraries: pandas, matplotlib, and a real workflow | ~30 min |

Links to videos will be added here as they're published.

## Video 1 — Getting Python running

**[▶ Watch Video 1](https://youtu.be/02YymGb9y_Y)**

In this video you'll go from "browser open" to "first piece of working Python code that reads a real drillhole dataset." We use Google Colab as the main path because it gets you coding in 60 seconds with no installation. Anaconda is covered briefly at the end for offline work.

### Follow along

The example dataset (`assays.csv`) contains 21 drillhole intervals from three fictional holes — one with a high-grade Au zone, one Cu-rich, one barren. Small enough to fit on screen, real enough to be interesting.

**Option A — Open directly in Colab:**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#)

*(Colab badge link to be added once the notebook is uploaded)*

**Option B — Download and run locally:**

1. Click `assays.csv` above, then "Download raw file"
2. Open the notebook of your choice (Colab, Jupyter, etc.)
3. Upload `assays.csv` to the same location as your notebook
4. Follow along with the video

### Files in `video1/`

- `assays.csv` — the example dataset (3 drillholes, 21 intervals)
- `my_first_notebook_completed.ipynb` — the finished notebook from the video
- `errors_cheatsheet.md` — common errors and what they mean

## Anaconda installation guide

If you'd rather work locally instead of in the cloud:

1. Go to [anaconda.com/download](https://www.anaconda.com/download)
2. Download the installer for your operating system
3. Run the installer. Click through the defaults — this is one of the rare cases where the defaults are correct.
4. Once installed, open Anaconda Navigator
5. Launch Jupyter Notebook from the Navigator home screen
6. You're ready to go

Total install time: about 10 minutes, mostly waiting.

## Coming up

Videos 2 and 3 will live in their own folders here once recorded. The plan:

- **Video 2** — variables, lists, dicts, loops, reading data, with geology examples throughout
- **Video 3** — pandas and matplotlib end-to-end on a real workflow

## Questions or feedback?

Open an issue on this repo, or reach out via [botsontheground.com](https://botsontheground.com).

## License

The code and example data in this repo are released under the MIT License. Use them however you like.
