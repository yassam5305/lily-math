# Lily Math v10.16.0 verification

November 11, 2026. Publication authorized by the user after implementation and verification.

## Frozen artifact

`index-v10.16.0.html` SHA-256: `929c1162450402a1e80abbe4ba9d0e73525f234183e4bbf5c952700d4b451bf9`.
The generated `index.html` matches the candidate and source-build parity passes. The prior v10.14.0 published artifact, v10.15.0 local candidate, and separate v11 prototypes are preserved.

## Acceptance scope

The release gate contains 117 suites: the 110 inherited release checks plus seven new checks for decimal-container arithmetic and recovery, fraction strategy revision and recovery, open-problem practice and evidence, and visible Unit 5 navigation. New Chrome journeys run at 320 and 820 CSS pixels with disposable synthetic profiles. They cover real entry, help delivery, cold reload, keyboard controls, original-problem preservation, supported/answer-only versus method evidence, and next-day practiced-difficulty scheduling.

The decimal-container oracle computes expected filled versus required container counts independently from integer tenths. Correct products for oversized trials and correct subtractions for undersized trials remain accepted exploration. Format issues are separate from misses. Generation v6 selects the new U4L9 problems; old-generation saves reconstruct their earlier exact-division stories.

Fraction revision tests include area, number-line, and algorithm routes; addition and subtraction; nested accepted stories; exact fraction homework; invalid/same/cancel behavior; failed-save rollback; 180 consecutive revisions with bounded history; and hidden-solution getter traps. Replaced dependent checks are historical rather than counted as current accepted work.

Open-problem tests cover contextual preference, draft/help recovery, deduplicated support, complete question rendering, checked-step fallback, preserved pending date/load, and no false lesson completion or readiness advancement. Whole-answer checks remain answer evidence even when no help was used.

The pre-freeze audit found and corrected decimal-tolerance acceptance, fractional-count error classification, and stale due-difficulty after a later ordinary practice session. Regression assertions cover those cases. An older story-set test was updated from generation v5 to v6 while retaining its recovery checks. The superseded partial gate is retained under `before-final-audit` and is not final-byte evidence.

Actual session-generation inventory sampled all 106 authored routes at difficulties 1–3: 59 eligible routes for initial open-problem practice and 59 task-capable delayed routes (subject to the prior-evidence gate), with 47 retaining checked flow. No generation errors occurred. See `output/v10.16.0-verification/open-problem-coverage.json`.

A second gate identified the container route’s use of an unrelated decimal-expression help context. It now uses its own authored container guidance through the shared menu, with menu browsing uncounted and checked story intent recorded separately. The old fixtures for optional whole-problem offers and explicitly requested check difficulties were updated without removing their original behavior assertions. Targeted reruns passed all 106 Walter lesson routes, all repairs, 134,603 curriculum checks, strategy alignment, cold focus recovery, and 321 adaptation checks. The superseded gate is retained under `before-shared-help-fix`.

Final gate: **117 passed, zero failed, zero skipped**, all on the frozen SHA-256 above. All six final batches completed successfully. Build parity and equality of the main/versioned app were rechecked. Public verification records accompany this release under `verification/v10.16.0/`; detailed raw logs are retained locally under `output/v10.16.0-verification/`. Publication byte parity and live browser checks are recorded separately after deployment.

## Limits

Saved workspace expansion in this release covers U4L9 and the ten authored Unit 5 lessons. The open-problem feature requires complete supported task metadata or a self-contained arithmetic prompt. Fraction reconsideration covers dynamic shared fraction-combination methods; ordinary static cards retain their existing flow. There are still 27 mapped calendar entries without authored lesson routes. No spoken-reasoning assessment, generic sketch interpretation, physical iPad/Safari/Pencil verification, or measured learning benefit is claimed.

No real learner records were used in verification or included in the publication package.
