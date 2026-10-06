# Git Collaboration Practice

## Pair Information

- Student A: Bryce Pfeilstifter
- GitHub username: Pfeilstifter22
- Student B:Joseph Salemi
- GitHub username:jsalemi-create

## Branch Work

- Feature branch created: new branch created named feature-about
- What changed on the branch: index.html about section changed
- Who merged it into `main`: Student B (Joe)

## Conflict Reflection

1. Why did the intentional conflict happen?

- The conflict happened because both students changed the exact same line (the Recommendation heading) to different text at the same time. Bryce changed it to the SaaS version and pushed it to GitHub, but Joe changed that same line to the Hybrid version locally without pulling Bryce's update first. When Joe tried to bring in the remote changes, Git saw two different versions of the same line and couldn't automatically decide which one was correct, so it flagged a merge conflict.

2. How did you resolve it?

- When Joe pulled in the remote changes, VSCode flagged the conflict in index.html and showed both versions of the heading with the conflict markers. Instead of just accepting one side or accepting both, we looked at the meaning of each version and replaced the whole conflicted block with the agreed final heading, "Team Recommendation: Evaluate SaaS and Hybrid Options." We made sure no conflict markers were left in the file, then staged, committed, and pushed the resolved version so both of us ended up with the same final result.

3. ## Give two practices that can reduce unnecessary Git conflicts on a real team.
   -Always pull the latest version before making any edits to ensure you have the most recent version of every file.
   - Section off work to avoid overlapping file when possible. Having each teammate working on seperate files will help avoid conflicts in the long run. When faced with overlapping files ensure constant communication outside of GitHub (text, email, vocal) messaging can help as well.
