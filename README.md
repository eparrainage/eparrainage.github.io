# Ensamien Parrainage

Landing page of Ensamien Parrainage, served at <https://eparrainage.github.io>.

It presents the program and its apps:

- [Vault](https://vault.hclap.tech): course resources ([source](https://github.com/H0ussamCl4p/ENSAMC))
- [Flow](https://flow.hclap.tech): class timetables

It also links the opportunity pages, each generated twice a day by the finders in [ai-radar](https://github.com/Salwa08/ai-radar) and served from its own repo:

- [/internships/](https://eparrainage.github.io/internships/): internships, from `eparrainage/internships`
- [/phd/](https://eparrainage.github.io/phd/): PhD positions, from `eparrainage/phd`
- [/jobs/](https://eparrainage.github.io/jobs/): cybersecurity and cloud jobs, public and private sector, from `eparrainage/jobs`

The home page reads each page's `stats.json` for its live counts.

One static `index.html` with inline CSS; a small script fills in the live counts and the phone menu. The Inter font is self-hosted (`assets/fonts`, SIL Open Font License). GitHub Pages serves the `main` branch.
