# Laboratory Equipment Register

College of Pharmacy, Al-Maaqal University — كلية الصيدلة، جامعة المعقل

A static register of the teaching-laboratory instruments. Each instrument carries a
QR label; scanning it opens that instrument's record on this page.

**Live page:** https://hamada0106648249.github.io/lab-equipment/

| | |
|---|---|
| Records | 14 instruments |
| Direct link | `…/lab-equipment/#eq-008` opens record EQ-008 |
| Form | COP-EQ-01 Rev. 1 |

Each record holds the equipment name, manufacturer and model, serial number,
asset number, installation and warranty dates, status, working principle,
intended use, key specifications, hazards and required PPE.

## Files

- `index.html` — the whole register; no server, database or build step
- `img/` — equipment photographs and the college logo

## Updating a record

Edit the `DATA` list near the bottom of `index.html` and commit. The web address
never changes, so QR labels already fixed to the instruments keep working.
