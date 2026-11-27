# study-notes

Text corpus for local experiments. Plain UTF-8, no markup.

War and Peace by Leo Tolstoy (trans. Louise and Aylmer Maude), Project Gutenberg edition. Long-form
Russian literature is a good stress test: the sentence structure is nothing
like English technical writing, so anything tuned only on documentation breaks
immediately.

## Files

- `section-i.txt` — 140 KB
- `section-ii.txt` — 143 KB
- `section-iii.txt` — 143 KB
- `section-iiii.txt` — 132 KB
- `section-iiiii.txt` — 115 KB
- `section-iiiiii.txt` — 101 KB
- `section-7.txt` — 150 KB
- `section-8.txt` — 70 KB

## Notes

- one file per section, split at paragraph boundaries
- original punctuation kept, including the em dashes and the odd spacing
- 8 files, roughly 999 KB in total
- public domain, so safe to keep in a public repo

## Usage

```bash
cat part-*.txt | wc -l
```

Nothing to install. There is no code here yet.
