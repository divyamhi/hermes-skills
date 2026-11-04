# hermes-skills (Divyamm05)

A Hermes Agent skill tap. Skill: **calendar-intel** — read-only iCal analysis (upcoming events, conflicts, free slots).

```
hermes skills tap add Divyamm05/hermes-skills
hermes skills search calendar-intel
hermes skills install calendar-intel
CAL_ICS_URL=skills/calendar-intel/sample.ics python3 <skill dir>/scripts/cal.py events --days 7
```
Needs `pip install icalendar recurring-ical-events`. Built for CSCI 599 A3.
