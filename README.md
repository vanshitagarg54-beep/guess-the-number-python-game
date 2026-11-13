# Guess the Number — Python Game

An interactive beginner-friendly Python number-guessing game for **Google Colab**.

## Features

- Easy (1–10, 5 attempts), Medium (1–50, 7 attempts), Hard (1–100, 10 attempts)
- Interactive interface built with `ipywidgets`
- Higher scores for solving in fewer attempts
- Live lives bar, high/low hints, and Play Again button
- Guess history, wins/losses, and high-score leaderboard
- Victory animation and an original generated sound effect
- Optional high-score persistence in Google Drive

## Play in Google Colab

1. Download `Guess_the_Number_Game_GitHub_Ready.ipynb` and open it in [Google Colab](https://colab.research.google.com/).
2. Run the Python cells **from top to bottom**.
3. Pick a difficulty, enter a number, and click **GUESS**.
4. Click **PLAY AGAIN** to start a new round.

### Save high scores (optional)

In the first Python cell, set:

```python
SAVE_SCORES_TO_DRIVE = True
```

When prompted, authorize your own Google Drive. High scores are saved to:

```
MyDrive/Guess_the_Number_Game/high_scores.json
```

The game loads any scores previously saved there. Don't commit your private Drive files or credentials to GitHub. Leave this setting at `False` if you want a demo that runs without asking for Drive permissions.

## Tech stack

- Python 3
- Google Colab / Jupyter
- `ipywidgets`
- NumPy
- HTML/CSS for lightweight styling
- JSON and optional Google Drive storage

## Project files

- `Guess_the_Number_Game_GitHub_Ready.ipynb` — runnable notebook
- `README.md` — project guide

## Limitations

The browser may block automatic audio playback. Guess history and previous games are not permanently saved; only high scores can be saved to Drive when opted in.

## License

You can add a license of your choice if you plan to distribute or invite contributions.
