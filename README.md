# NYC High School Options

A categorized guide to NYC public high school options for Fall 2027 entry, built from official NYC Public Schools / MySchools data.

- 40 representative schools, grouped by admissions method: SHSAT Specialized, LaGuardia audition, screened / screened with assessment, audition arts, and large comprehensive / Ed. Opt. / open / zoned
- Per-school anonymized stats: applicants per seat (2024–25), waitlist offers (2023–24), strength tag (STEM, Arts, Humanities/Social Science, IB, Early College, CTE, Comprehensive), and a one-line "Who it suits" fit profile
- "How to read the numbers" — there is no published per-school RAN cutoff; RANs only break ties within a priority/screened group
- Commute calculator: enter a home address (geocoded in-browser via OpenStreetMap Nominatim) or use your location, pick Transit / Driving / Walking, and see estimated commute times, with Google Maps directions per school
- Fall 2027 timeline: applications opened 6 Oct 2026, SHSAT registration closed 30 Oct 2026, general + LaGuardia applications close 4 Dec 2026, offers 3 Mar 2027

## Structure

- `index.html` — the whole site, self-contained (single file)
- `data/` — (planned) school data as structured files, so the site can grow beyond a single file
- `research/` — (planned) source notes

## Hosting

This repo is a static site. Enable GitHub Pages (Settings → Pages → Deploy from a branch → `main`, `/ (root)`) and it will be live at `https://<username>.github.io/nyc-high-school-options/`.

## Sources

- NYC Public Schools high school admissions: https://www.schools.nyc.gov/enrollment/enroll-grade-by-grade/high-school
- MySchools: https://www.myschools.nyc/
- DOE random numbers in admissions: https://www.schools.nyc.gov/enrollment/enroll-grade-by-grade/how-students-get-offers-to-doe-public-schools/random-numbers-in-admissions
- DOE waitlists: https://www.schools.nyc.gov/enrollment/enroll-grade-by-grade/waitlists
- NYC SIFT: https://nycsift.com/

No Facebook group posts, quotes, or member names are included. Parent themes used to shape the site were anonymized aggregates only.
