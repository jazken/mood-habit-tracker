# Daily Mood and Habit Tracker

> **Partner exercise:** both of you change the title on the line above, in different ways. The steps are under "Work with a partner".

A small practice page for [AI Newbie](https://www.ainewbie.org)'s Newbie to Tech track.

You tap today's mood. You tap two or three habits. That is the whole page.

You are on `step-4`. The README lists the GitHub Pages clicks. There is no build.

## Work with a partner

This is the partner exercise from the Step 4 lesson, "Git part 2: work together". You do it on GitHub's website.

This is not the Step 3 lesson. The Step 3 lesson, "Git part 1: save points you control", is solo. You make a commit. You can try a branch. Do that lesson first if you have not.

Lesson for the Step 3 solo exercise: **TODO** (not published yet) — <https://www.ainewbie.org>

Lesson for the Step 4 partner exercise: **TODO** (not published yet) — <https://www.ainewbie.org>

You need a partner, and a free GitHub account each: <https://github.com>

1. **Partner A** forks this repo. That fork is the one shared copy. Then Partner A invites Partner B: **Settings → Collaborators**. Partner B works in that same fork, not a second fork.
2. Switch the branch menu to `step-3`. **Each of you** makes your own branch from `step-3`. Call them `a-title` and `b-title`.
3. **Each of you** edits the **same first line** of this README on your own branch, in different ways. Commit.
4. **Each of you** edits the habits list in `index.html`. The habits list is the three buttons under **Habits**: `Drink water`, `Take a walk`, and `Read a page`. Change those names in different ways. Leave the tags in place. Commit.
5. **Each of you** opens a **pull request** (PR) from your branch into `main`.
6. **Merge Partner A's PR.**
7. Partner B's PR now says it has a **conflict**. Click **Resolve conflicts** and fix it **together**: pick one line, or combine them. Do that for the title and for the habits list. Then merge.

**Check you did it:** `main` has one first line that you both agreed on. Both PRs say *Merged*. The habits list is one agreed list.

The pull request into `main` also contains the earlier steps. That is expected. On the conflict screen, keep the words you want. Delete the marker lines (`<<<<<<<`, `=======`, `>>>>>>>`).

### Clicks on GitHub's website

Make a branch:

1. Open the fork. Set the branch menu to `step-3`.
2. Click the branch menu again. Type `a-title` or `b-title`.
3. Click **Create branch** from `step-3`.

Edit a file:

1. Open the file on your branch.
2. Click the pencil (**Edit this file**).
3. Change your lines. Click **Commit changes**.

Open a pull request:

1. Click **Compare & pull request** if GitHub offers it. Or click **Pull requests**, then **New pull request**.
2. Set the base to `main` and the compare branch to yours.
3. Click **Create pull request**.

Merge, then fix the conflict:

1. On Partner A's pull request, click **Merge pull request**, then **Confirm merge**.
2. Open Partner B's pull request. Click **Resolve conflicts**.
3. Fix the title and the habits list together. Click **Mark as resolved**, then **Commit merge**.
4. Click **Merge pull request**.

## Put your page on the internet

This publishes the page with GitHub Pages. The source is the **main** branch and the folder **/ (root)**. There is no Actions build. Do not add a workflow file.

The live page shows whatever is on `main`. On the class repo, `main` is the starter. On your fork, `main` changes after you merge a pull request.

You need to own the repo. On your fork, you do.

1. On GitHub, open your fork.
2. Click **Settings**. If you cannot see **Settings**, open the menu, then click **Settings**.
3. In the left sidebar, under "Code, planning, and automation", click **Pages**.
4. Under "Build and deployment", next to "Source", choose **Deploy from a branch**. Do not choose **GitHub Actions**.
5. If a button says **Configure** and opens a workflow file, close that file. Come back here. Choose **Deploy from a branch**.
6. Still under "Build and deployment", choose branch **main** and folder **/ (root)**.
7. Click **Save**.
8. Wait a minute. Refresh this page. GitHub shows a link.

Your link looks like `https://YOUR-NAME.github.io/mood-habit-tracker/`.

The class repo's link is <https://jazken.github.io/mood-habit-tracker/>.

Lesson: **TODO** (not published yet) — <https://www.ainewbie.org>

Go deeper: <https://pages.github.com/>

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
