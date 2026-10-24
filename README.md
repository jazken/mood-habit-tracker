# Daily Mood and Habit Tracker

A small practice page for [AI Newbie](https://www.ainewbie.org)'s Newbie to Tech track.

You tap today's mood. You tap two or three habits. That is the whole page.

You are on `step-2`. Check-ins are saved, and the last 7 days show as a chart.

## Open it

You do not need to install anything. There is no build step.

1. Get the files. Fork steps are below. Or click **Code**, then **Download ZIP**.
2. Unzip the folder if you downloaded a ZIP.
3. Double-click `index.html`.
4. It opens in your browser.

On this branch, the browser saves your check-in and draws the last 7 days. Refresh the page. Your taps should still be there. They stay on this computer only.

## Fork this repo

A fork is your own copy on GitHub. Do your practice there, not on this copy.

1. Sign in at [GitHub](https://github.com).
2. Open [github.com/jazken/mood-habit-tracker](https://github.com/jazken/mood-habit-tracker).
3. Click **Fork**.
4. Click **Create fork**.

Your copy lives at `https://github.com/YOUR-NAME/mood-habit-tracker`.

To put that copy on your computer:

```bash
git clone https://github.com/YOUR-NAME/mood-habit-tracker.git
cd mood-habit-tracker
```

Then double-click `index.html`.

## Switch to a step

Each stage is a branch. A branch is a separate line of the project. Each stage builds on the one before it. A tag with the same name marks that stage.

On GitHub's website:

1. Click the branch menu. It shows the current branch. It usually says `main`.
2. Choose a branch, such as `step-2`.
3. Read the files there. Or click **Code**, then **Download ZIP**, to get that branch.

On your computer, inside the project folder:

```bash
git switch step-2
```

Then double-click `index.html` again.

Older Git has no `git switch`. Use `git checkout step-2` instead.

Git may warn that the name is ambiguous. The branch and the tag share a name. The switch still opens the branch.

To send commits to GitHub, run `git push` with no branch name. `git push origin HEAD` also works. `git push origin step-2` does not, because that name is both a branch and a tag.

Use the branch in everyday practice. The tag is a fixed bookmark on the same save point.

## The stages

Lesson pages are not published yet.

**TODO:** each lesson link below is a placeholder. Use <https://www.ainewbie.org> until the real lesson URL is ready.

### `main` — starter

Tap today's mood and the habit buttons. Nothing is saved yet.

Lesson: **TODO** (not published yet) — <https://www.ainewbie.org>

### `step-1` — the day is saved

The page stores your check-in in this browser and shows it back. A refresh keeps it. It is not sent online.

Lesson: **TODO** (not published yet) — <https://www.ainewbie.org>

### `step-2` — a week chart

The last 7 days show as a simple chart. There is no chart library. The drawing is in `index.html`.

Lesson: **TODO** (not published yet) — <https://www.ainewbie.org>

### `step-3` — practice conflict

This branch adds a README line and a habits list that both partners edit. Two people then get a real merge conflict. You fix it on GitHub's website.

This setup is for the **Step 4 lesson**, "Git part 2: work together". It is not the Step 3 lesson.

The **Step 3 lesson**, "Git part 1: save points you control", is solo. You make a commit. You can try a branch. There is no partner and no conflict.

Lesson for the Step 3 solo exercise: **TODO** (not published yet) — <https://www.ainewbie.org>

Lesson for the Step 4 partner exercise: **TODO** (not published yet) — <https://www.ainewbie.org>

### `step-4` — GitHub Pages

This branch tells you how to publish the `main` branch from the repo root. You use GitHub Pages. There is no Actions build. The clicks are in that branch's README.

This is the track's "your first web page, online" lesson.

Lesson: **TODO** (not published yet) — <https://www.ainewbie.org>

### `step-5` — practice coach

An optional weekly note. It is a stub. There is no key and no network call. A real coach would need a key later. Never commit a key.

Lesson: **TODO** (not published yet) — <https://www.ainewbie.org>

## Which exercise is which

- **Step 3 lesson.** Save points you control. One commit, on your own. The lesson's check is a commit in `git log`.
- **Step 4 lesson.** Work together, with a partner, on GitHub's website. You both edit the same README line, then open pull requests. You fix the conflict with **Resolve conflicts**. The setup for that exercise is on the `step-3` branch. It also has a habits list you both edit.

## Licence

MIT. Copyright 2026 Kenneth Goh / AI Newbie. See the `LICENSE` file.
