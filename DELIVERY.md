# Elspeth Campbell - delivery record

Built 28 to 29-08-2026. Portal client **1344**. Preview: https://trulyempoweredcode.github.io/elspethcampbell.com/

## State
Round 1 (portal round **327**) opened and she was invited on 29-08-2026 11:41. Client stage 4 Revisions, waiting on client. Round 1 feedback arrived 13 to 16-09-2026. Change request 203 (she wants the design format of ashleymeyer.co.uk) is with Rick, who spoke to her on 17-09-2026. Change request 204 (the homepage rebuilt as her five sections) was actioned on 17-09-2026: hero--half with her portrait, an invitation band, the list of what brings people here, a practice-statement band with the booking button, and a membership logo row. The service cards and homepage testimonials came off the homepage at her request. Open from that round: her chosen background images for the two bands, the Counselling Directory badge (their site blocks automated access), and a sharper APP logo.

## What she got
Nine pages: home, about, psychosynthesis, yoga, coaching, contact, privacy, cookies, plus `content-checklist.html` (noindex, addressed to her).

Every word is hers, from the six .docx page drafts she uploaded and from her live site. No invented claims, credentials or testimonials, and deliberately **no star ratings** on testimonials because she has no ratings.

## The one deliberate deviation from Style 8
Recorded in `build-spec.json` with its reason. Her hero photograph is a centred-sun composition, and the demo's `hero--image` dims the whole picture to protect centred text. Measured on the rendered page, deep enough for WCAG AA left the h1 at 1.25:1 over the sun and flattened the sunset to mud. `hero--showcase hero--showcase-dark` disables the overlay and carries the text in a frosted card, so her photograph ships at full vibrancy. Nav is solid rather than transparent for the same reason.

## Repositioning, which drove 20 page-level decisions
Her live site is **Campbell-Ozten Associates**, a leadership consultancy. Her 26-08 draft relaunches the same domain as her solo psychotherapy, yoga and coaching practice. All 29 of her old pages are either mapped or declared `DROPPED:` with a reason in `build-spec.json`. `verify_source_parity.py` passes on all six checks.

## Gates at delivery, all green
`validate_site.py` 0/0 - `verify_spec.py` 0/0 (slice_approved 2026-08-28) - `verify_source_parity.py` OK, every 40+ word passage of her copy survives - `verify-live.py` "SAFE TO TELL THE CLIENT" 0 errors 0 warnings on the plain URL - `check_defect_ledger.py` 0 errors.

## Open with her (all on the checklist page)
No logo. No Assagioli star diagram. No street address. Her Psychology Today and Counselling Directory URLs. Her mailboxes ("I think they are with 123-reg"), which **blocks go-live**. Two testimonials carried over from her live site need her confirmation. A testimonial headed Lianne is signed Liz. Assagioli's dates are a typo on her draft so they were left out.

## Not done
No competitor benchmarking. Stated plainly on her checklist page rather than implied.
