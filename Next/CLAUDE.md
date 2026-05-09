# CLAUDE.md

Project notes for writing theology Q&A documents in this directory.

## Audience and tone

- Write so a middle school student can read and understand it. Use
  short sentences and simple words. Explain hard ideas with everyday
  examples.
- Keep the tone friendly and loving, like a caring older sibling or
  Sunday school teacher. Encourage the reader and remind them that God
  loves them.
- Avoid scary or shaming language. When a topic is hard, be gentle and
  honest.

## Doctrinal anchor

- Anchor every answer in Reformed theology. When a question touches on
  doctrine, line up the answer with historic Reformed teaching.
- Use the Westminster Confession of Faith (WCF) as the primary
  doctrinal reference. Link to the OPC version at
  <https://www.opc.org/wcf.html>.
- When citing Scripture, use the English Standard Version (ESV) and
  link each reference to its page on <https://www.esv.org/>.

## Reference link style

Use reference-style markdown links so prose lines stay short and easy
to read. Put all link definitions together at the bottom of the file.

- Scripture link IDs follow the pattern `book-chapter-verse`, e.g.
  `[gen-2-7]`, `[2tim-3-16]`. For verse ranges, include both ends,
  e.g. `[2pet-3-15-16]`.
- WCF links can share a single ID per chapter (e.g. `[wcf]` for chapter
  1) or use `[wcf-1-2]` style if multiple chapters appear in one file.
- ESV URL format: `https://www.esv.org/<Book+Chapter:Verse>/` with `+`
  for spaces and `-` for verse ranges.
- WCF URL format: `https://www.opc.org/wcf.html#Chapter_NN` where `NN`
  is the two-digit chapter number (e.g. `#Chapter_01`).

## Document format

Keep every Q&A document consistent so the collection feels like one
book. Follow this shape:

1. `# Short Title` — an H1 that fits within 80 columns. Do not put the
   full question in the H1.
2. A blockquote with the full question, prefixed by `**Q:**`.
3. `## Doctrine Answer` — a few short paragraphs of WCF-anchored
   teaching, with WCF citations linked.
4. `## The Explanation` — a longer, plain-language walkthrough with
   Scripture citations linked to ESV.
5. `### Subsection headings` for follow-up questions inside the
   explanation (e.g. "Why No Errors?").
6. A closing line of encouragement.
7. Reference link definitions grouped at the bottom of the file.

## Formatting rules

- Wrap every line at 80 columns or fewer. Headings and link
  definitions are the only exceptions, and only when they cannot be
  broken.
- Use Title Case for headings (e.g. "How Do We Know We Have the Right
  Books?"). Capitalize major words; keep short articles, conjunctions,
  and prepositions lowercase unless they are the first or last word.
- Use bullet lists for parallel ideas (definitions, examples, short
  pairs of point + explanation).
- Bold inline labels with `**Label:**` when a bullet starts with a
  named idea.
- Use straight quotes (`"`) and straight apostrophes (`'`), not curly
  quotes, so the files stay easy to edit.

## Things to avoid

- Don't add emojis unless asked.
- Don't paste long Scripture quotes; link to ESV instead and quote
  only the short phrase the answer needs.
- Don't promise things Scripture doesn't promise. If a question is
  open-handed in Reformed theology, say so kindly.
- Don't use scary language about hell, judgment, or sin to pressure
  the reader. Speak truth, but lead with God's love and grace.
