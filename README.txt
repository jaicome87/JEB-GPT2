
JEB 'Fresh' Package (v1.1 - drop-in)

What’s inside:
- jeb_logic_pack_v1_1.json  → Patched logic (v1) with missing variables defined, access/hoisting fix, ceilings AF, doors 'op', ceiling spec drivers, and safer QA flags.
- JEB_Coding_Guide_all_sheets_v1_1.json → Same as your supplied Coding Guide but with strict JSON fixes: NaN→null and explicit { type: "heading" } markers in RATES.
- jeb.enums.json → Optional externalized enums/synonyms you can load into your runtime.
- jeb.schema.json → Starter canonical schema + alias map (for a v2 migration).

Notes:
- This is a conservative, drop-in patch for your current engine. It keeps your v1 structure but closes key gaps causing evaluation errors.
- You can continue to use your existing rates. If you want structured per-category rates, ask for the “rates structuring” add-on and I’ll generate a normalized rates bundle.
- Safe defaults: DeflectionType is introduced as a new (optional) input; leave as "Track" when unknown.
