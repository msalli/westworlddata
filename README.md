# westworlddata
Westworld + Fun Data Viz

### How to push to GitHub: 
We need a better system for this, right now it works well when one person is working at a time. 

Do all work on `master` branch in the main directory. The `master` branch is not connected to GitHub, just a local git repo.

When you are ready to push up your changes, run `hugo` in the main directory. This will compile the files and update the files in the /public directory to reflect your latest changes.

Move into the /public directory: `cd public`

❗️ FYI: This next step will update the live site. ❗️

Run `git add .`, `git commit -m "Your message"`, `git push -f origin gh-pages`





