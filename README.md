# How Many Tabs Do You Have Open?

Entry for the make.fun competition
`u-danu-how-many-tabs-do-you-have-open-d86e783d`.

## The entry

`1` — a single digit, written to `output/entry.txt` by `main.ts`.

One tab open. Not zero (someone has to be browsing), not a hoard — one
thing at a time, everything else closed the moment it is done. It is the
extreme low end of the field, believable as a real habit, and it implies a
whole way of living behind it without a word of explanation.

## How it works

`main.ts` writes the digit `1` to `output/entry.txt`. All paths are anchored
to `import.meta.url`, so the program works no matter which directory the
grader runs it from. It clears only the files inside `output/` and never
deletes the directory itself.

## Run

```sh
node main.ts   # requires node >= 22 (or ts-node for the .ts source)
```

The competition runs `main.ts` directly under node22.
