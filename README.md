You will need Git for this project, you might have to [install it](https://alx-intranet.hbtn.io/rltoken/qhCES0BhU0FQc8kbWfD8Ug) on your computer if it’s not done yet.

- Configure your basic info (name, email) on your local machine – they will be part of your commits. [Tips](https://alx-intranet.hbtn.io/rltoken/V2JYYogSxXcS8T9YMuahZQ)

On [GitHub.com](https://alx-intranet.hbtn.io/rltoken/1vpH3ScWYjfgZD0J59jusA):

- Using the graphic interface on the website, create the repository (if it’s not done yet)
  - Name: `alx-zero_day`
  - Description: `I'm now a ALX Student, this is my first repository as a full-stack engineer`
  - Public repo
  - No `README`, `.gitignore`, or license

Update your Intranet profile by adding your Github username [here](https://alx-intranet.hbtn.io/rltoken/9dthiwx9AyxxUzV_QPIRWQ) - if it’s not done, **the Checker won’t be able to correct your work**

On your computer, open a terminal and do the following:

- Navigate to your home directory. [Tips](https://alx-intranet.hbtn.io/rltoken/Fj3VK7ueG1JR35QPw0b8Gg)
- Create a directory `alx-zero_day`. [Tips](https://alx-intranet.hbtn.io/rltoken/wgoyDWhg_ay1SGI9nrWjGw)
- Navigate to this new directory. [Tips](https://alx-intranet.hbtn.io/rltoken/qSP5HcBSSIL0U23PdIGKLw)
- Initialize git and add the remote origin
- Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://alx-intranet.hbtn.io/rltoken/cS_mrgo3M5QtDRgRB21kBw) text to present this project. **This file is mandatory in all ALX School projects**
- Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your **first repository** of the **first task** of your **first ALX School project**.

Create a new directory called `0x03-git` in your `alx-zero_day` repo.

Make sure you include a not empty `README.md` in your directory:

- at the root of your repository `alx-zero_day`
- AND in the directory `0x03-git`

And important part: **Make sure your commit and push your code to Github - otherwise the Checker will always fail.**

**Repo:**

- GitHub repository: `alx-zero_day`

For the moment we have an empty project directory containing only a `README.md`. It’s time to code!

- Create these directories at the root of your project: `bash`, `c`, `js`
- Create these empty files:
  - `c/c_is_fun.c`
  - `js/main.js`
  - `js/index.js`
- Create a file `bash/alx` with these two lines inside: `#!/bin/bash` and `echo "ALX"`
- Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"`
- Add all these new files to git
- Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

**Repo:**

- GitHub repository: `alx-zero_day`
- Directory: `0x03-git`
- File: `bash/alx, bash/school, c/c_is_fun.c, js/main.js, js/index.js`

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

- Change branch to `main`
- Update the file `bash/alx` by replacing `echo "ALX"` with `echo "ALX School is so cool!"`
- Delete the directory `js`
- Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

**Repo:**

- GitHub repository: `alx-zero_day`
- Directory: `0x03-git`
- File: `bash/alx, bash/school, bash/98`

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task – **and only for this task** – please update your file `README.md` in the main branch from GitHub.com. It’s the **only time** you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

- Get all changes of the main branch locally (i.e. your `README.md` file will be updated)
- Create a new file `up_to_date` at the root of your directory and in it, write the git command line used
- Add `up_to_date` to git, commit (message: “How to be up to date in git”), and push to the origin

**Repo:**

- GitHub repository: `alx-zero_day`
- Directory: `0x03-git`
- File: `README.md, up_to_date`