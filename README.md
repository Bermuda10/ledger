# Bermuda 10 · The open ledger

Bermuda 10 asks one question: what would have to be true for Bermuda to be the best place to live on Earth by 2050? The answers live here, as an open, append-only ledger. Organisations table their answers, copied or changed, and co-sign one another's from the second entry on. Residents sign the answer they stand behind. At every month-end the ledger is read and records who backs what. It declares no winner. Bermuda 10 keeps the record and counts. It never tables an answer, never co-signs one and never chooses one.

This repository is the canonical record. The website at bermuda10.com reads from it. If the website and this repository ever differ, this repository is right.

## Layout

```
index.json                  index of everything below, what the website reads first
entries/001-genesis.md      one entry per answer, human readable
entries/001-genesis.json    the same entry, machine readable
readings/                   one record per month-end reading
brake/                      every use of the brake, with its reason
settings/                   rules in force, one file per change, with effective date
not-admitted.json           running count of submissions not admitted, by reason
tools/source.json           the single source every file above is built from
tools/build.py              the builder
```

## Rules in brief

- Genesis (001) is the founder's draft, entered as a resident, frozen, and can never be signed or co-signed by anyone. An organisation that agrees with it tables its own copy and keeps all ten.
- Only organisations table. Political parties may not table for now. From the second entry on, organisations co-sign tabled answers and residents sign them, one signature each, theirs to move.
- An answer builds on an earlier one or starts its own line. Nothing published is edited or deleted. A revision is a new numbered entry.
- Read at 23:59 Atlantic/Bermuda on the last day of every month. A reading records backing and declares nothing. There is no leading version until a convergence rule is written with the participants and published before it applies.
- The brake slows and never steers. Every use is recorded here with a written reason.
- No individual signer, named or unnamed, ever appears in this repository. Counts and spread by walk only. Organisations that co-sign appear by name, as they agreed.
- Text is licensed CC BY 4.0.

## Who holds this

Bermuda 10 is an independent nonprofit, in formation. Until incorporation completes, this GitHub organisation is held by the founder, Hannes Heyns, personally. It transfers to the nonprofit on incorporation. The history does not change with it.

The full rules are the Governance Thesis at bermuda10.com/governance. A test copy of this ledger with invented data, used to rehearse the process, is `bermuda10/ledger-test`.
