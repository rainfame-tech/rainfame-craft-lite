# Standard template (ten parts)

Fill each part for the product. Defaults are starting values; change them only with a reason written next to the rule.

## 1. Who we design for
One paragraph: the person, their place, their hands, their time, the question they must answer at a glance, and what they hate in other products.

## 2. Names in the user's own words
Table: current label, new label, why. Use the trade's vocabulary, never the data model or sales jargon. One name per feature everywhere. Where a name alone could be misread, add one plain purpose line under it.

Copy rules: sentence case, local spelling, active verbs on buttons, no em dashes, en dash only in ranges, curly quotes, the real ellipsis character, no hype words.

## 3. Organisation
- Three to five labelled bottom tabs on mobile, never hidden behind a menu.
- Order by frequency, then by consequence: daily jobs on the first tab, weekly jobs one tab away, settings in More.
- Group by the user's job, not by the database. Confirm groups with a card sort or tree test when possible.
- Recognition over recall: show counts and next steps; each count opens a filtered list and drops as work is done.
- Progressive disclosure: a row shows the one fact needed to act; detail is one tap down.
- One name, one place. A shortcut keeps the same name.
- Creating things is one persistent action, not a tab. The screen title appears once.

## 4. Typography
One legible family, plus a tabular or mono style for figures. Default scale:

| Role | Size / line | Use |
| --- | --- | --- |
| Display | 28 / 32 | One per screen at most |
| Title | 22 / 28 | Screen title |
| Heading | 18 / 24 | Section headings |
| Body | 16 / 24 | All reading text |
| Label | 15 / 20 | Buttons, row primary line, form labels |
| Caption | 13 / 18 | Secondary lines, hints |
| Figure | inherits | Every time, date numeral, amount, count; tabular |

Rules: nothing under 13px; inputs 16px or more; weight before size, colour before weight; no italics in UI; no uppercase letter-spaced eyebrows; at most three type roles per region; balanced wrapping on headings.

## 5. Colour with meaning
- Roles, not raw colours: primary (go, done), caution (owed, unconfirmed), stop (failed, destructive), information, neutrals.
- Build light and dark from the same scales (OKLCH works well), never by inverting.
- Status never relies on colour alone: colour plus shape plus word.
- Contrast: 4.5:1 body text, 3:1 large text and control edges, in both themes. Hairlines below 3:1 are decorative only; anything whose edge must be seen to be used needs 3:1.
- Simulate protanopia, deuteranopia and tritanopia. Amber against red and red against green usually collapse; separate them with fill, outline and glyph.

## 6. Space and shape
- 4px grid; spacing only from 4, 8, 12, 16, 24, 32, 48.
- One shared Section component owns section headings: title, optional purpose line, optional action.
- Rows at least 56px; targets at least 44px; primary actions in the lower 40% of the screen at 375px.
- Fewer cards: divided lists and grouped sections, one surface per section, never a card inside a card, no dashed empty boxes.
- More space between groups than within them. The page stack owns the gaps; do not add a second margin.

## 7. Icons
One set, sized and stroked to match the text (for example 20px at 1.75px stroke beside 15 to 16px text). Labelled on mobile.

## 8. Motion
Under 250ms, ease-out, transform and opacity only, never on frequent actions, always interruptible, reduced motion respected. At most two signature moments in the product.

## 9. States
Design empty, sparse, loading, error, offline and success for every screen. Empty states say what the place is, why it is empty, and offer one action inline. Loading uses skeletons shaped like the final layout. Offline is calm and specific.

## 10. Review gate (every screen)
1. Labels match part 2; purpose lines present; no banned words; sentence case; no em dashes.
2. Only the type roles in part 4; nothing under 13px; inputs 16px or more.
3. Every number tabular.
4. Colour carries meaning only; status has shape and word; control edges 3:1.
5. No card in card; no dashed empty box; spacing varies by grouping.
6. 44px targets; primary action in the thumb zone at 375px.
7. Empty, loading, error and offline states designed and seen.
8. Contrast AA in light and dark; automated accessibility scan clean.
9. Motion under 250ms, none on frequent actions, reduced motion honoured.
10. Walked at 375px on production before it is called done.
