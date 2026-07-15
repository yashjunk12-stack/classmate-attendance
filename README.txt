CLASSMATE SHILLONG V5

Replace these six files in your current GitHub repository:
index.html
style.css
script.js
timetable.js
manifest.json
sw.js

V5 CHANGES
- Removed the old 75%-line advice logic from the Dashboard.
- Dashboard logic now follows absence allowance:
  4-credit subjects = 20 planned classes, maximum 3 absences.
  2-credit S&B = 10 planned classes, maximum 2 absences.
- Allowance colours:
  GREEN = 2 or more misses left.
  YELLOW = exactly 1 miss left.
  RED = no misses left or absence limit crossed.
- Attendance percentage colours:
  GREEN = 85% or above.
  YELLOW = 75% to 84.9%.
  RED = below 75%.
- Subject cards are much smaller and denser.
- Desktop shows up to 3 subject cards per row.
- Existing timetable, S1-S6 logic, Mark Past filters and attendance data keys are preserved.
- Cache bumped to classmate-v5.
