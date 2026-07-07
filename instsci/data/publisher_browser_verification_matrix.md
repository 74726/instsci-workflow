# Publisher Browser Verification Matrix (Public Preview)

This public file is intentionally a compact planning matrix. Detailed local browser evidence, sample DOI runs, screenshots, downloaded paths, and institution-specific traces are not shipped in the public repository.

Final closed-access verdicts still require a fresh visible browser-backed InstSci run for the current DOI and the user's own legitimate institutional access.

| Publisher | Status | Route Kind | Batch Policy | Known Blocker |
| --- | --- | --- | --- | --- |
| ACS | guarded | publisher_pdf_route | single DOI prewarm, then batch | publisher challenge or entitlement may require visible browser handling |
| Elsevier / ScienceDirect | guarded | publisher_pdf_route | OA-first, then visible browser for remaining rows | signed asset and bot challenge behavior varies by network/session |
| IEEE Xplore | guarded | institutional_sign_in_to_stamp_pdf | single DOI prewarm, then batch | institutional sign-in and browser session persistence required |
| IOPscience | ready | article_pdf_deeplink | OA-first, then grouped browser batch | entitlement required for closed-access articles |
| Springer Nature | ready | direct_pdf_or_article_pdf | OA-first, then grouped browser batch | route differs between SpringerLink and Nature families |
| Wiley Online Library | ready | doi_pdfdirect | OA-first, then grouped browser batch | entitlement and session state required for closed access |
| Science / AAAS | ready | doi_epdf | OA-first, then grouped browser batch | some journal families require visible browser verification |
| APS | unsupported | article_pdf_route | avoid closed-access batch | reusable institutional-login route is not published in this preview |
