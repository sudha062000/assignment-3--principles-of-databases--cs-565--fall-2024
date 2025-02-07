# Fall 2024 Principles of Databases (Graduate) — Assignment 3

* **Read these instructions repeatedly until you understand, then begin your project. If something is not clear, ask.**

## ❖ Before You Begin ❖

1. Log in to GitHub.
2. Fork this repo(sitory). See [this video](http://code-warrior.github.io/tutorials/git/github/forking-and-cloning-at-the-github-web-site/) on how to carry out this step and step `3`.
3. Clone your fork, using either the web site or the GitHub Desktop client.
4. Checkout your personalized branch, the one with your name and GitHub handle.

---

## ❖・Introduction・❖

For this assignment, you will complete update and delete routines in a web app using the MENN (Mongo, Express, Nunjucks, Node) stack. You will not need to add any files to this scaffold; all required files are already included in this repo. Routines, or routes, for the update and delete procedures must go in the included `server.js` file. When either route is carried out successfully, a message in the CLI should report the task carried out. For example, if a record was removed, your program should report which record was removed. Do the same for the “update” route. A starter database is included in this project (see below).

---

## ❖・Stand Up the MENN (Mongo, Express, Nunjucks, Node) Stack・❖

1. Start the Mongo server.
2. Open a CLI window and log in to Mongo: `mongosh`
3. Open another CLI window and navigate to the `models` folder.
4. Run `mongorestore`, which will restore the `project` database containing the `users` collection from the `dump` folder.
5. Navigate to the root folder of this repo.
6. Install the dependencies from the `package.json` file by running `npm i`.
7. Run `npm run dev`.
8. Visit `http://localhost:3000` in any browser.

---

## ❖・Grading・❖

| Item                                   | Points |
|----------------------------------------|:------:|
| Following directions                   |  `25`  |
| Syntax, style, and neatness            |  `25`  |
| Update router carried out successfully |  `25`  |
| Delete router carried out successfully |  `25`  |

---

## ❖・Due・❖

Wednesday, 11 December 2024, at 10:00 PM. ***Note*: Per the syllabus, NO late submissions will be accepted**

---

## ❖・Submission・❖

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may *only* be submitted via GitHub. **No other form of submission will be accepted**.
