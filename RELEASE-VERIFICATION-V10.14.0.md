# Lily Math v10.14.0 verification

November 11, 2026. Mainline integration of the local Walter v11 prototype's workspace and revisit features onto v10.13.0.

Exact frozen artifact: `index-v10.14.0.html`. SHA-256: `c7b80bf2141a5ba90b9a84aab3f61c252548c2ee0531c2b08255145f85ccebae`. Git blob: `ddb0ac74bff5f943f9b46d63ea33298706e06104`.

## Checks on these exact bytes

- Build parity passed; frozen artifact and generated `index.html` match.
- Full release gate: **102 PASS, 0 FAIL, 0 SKIPPED**, across six shards with three workers. This includes inherited arithmetic/generator, language, privacy, shared-engine, adaptation, recovery and authored-route checks, rerun on this candidate.
- Four Unit 5 Home-to-completion-to-next-day Chrome journeys: L1 and L3 clean, L2 and L4 supported, at 320/820 pixels. Checks include different-number model delivery, deduplicated support, independent versus supported evidence, notes/ink/draft recovery, fresh questions and practiced difficulty after practice advances.
- Fill browser tests at 320/820: mouse and touch toggles, drag as one undo, keyboard arrows/Space, mixed ink and fill, typed notes, pause/reload, resize, help preservation, Clear/Undo and no automatic math/help credit. Workspace and overflow coverage reaches all ten authored Unit 5 lessons.
- Migration tests across all ten lessons: old pending loads, teacher-focus isolation, exclusion of model and later unfinished records, bounded restoration and failed-save rollback. A draft produced by the preserved 10.13.0 artifact resumes with its accepted divisor and partial field intact.
- Four additional real-Chrome suites rerun: fraction division layout, Unit 5 block workspace, block-aware tutor and shared diagram coach. They cover narrow/tablet drawing review, equivalent arrangements, current-draft feedback, chosen methods, recovery and retained practice interfaces.
- Screenshots inspected for working-area layout. Test profiles were disposable and synthetic; real learner storage was not used.

Development testing found a direct-model exception, which was fixed before freezing. Earlier broad-run logs are retained under `pre-final`; they record a 3.2 GB jsdom language-scan heap exhaustion and a source-parity failure while the source and an earlier candidate differed. The final gate used a 6 GB test-process ceiling and passed on the exact bytes above. A mistyped browser test filename was corrected and the real existing layout harness passed; it was not an app defect.

## Scope and limits

The ten authored Unit 5 lessons inherit the saved workspace and practiced-load scheduling. Unit 5 Lesson 11 remains mapped review. The first four have new complete next-day browser journeys; later lessons have workspace, migration and inherited authored-method coverage. Other units retain their existing engines and schedules.

Qwen ran locally using fictional classroom attacks. Its invented block-drag controls and claim that viewing a model changes practiced difficulty were rejected. Scratch grading, reload, retained difficulty and undo scenarios were independently reproduced. Clear can be undone while the current work page remains open; its undo buffer does not survive leaving/reload. Current ink/fill/notes do persist with the active problem.

Tests establish implemented behavior and arithmetic consistency, not learning gains or actual child mastery. Physical Safari/iPad/Pencil behavior was not tested. Walter does not recognize freehand or generic scratch patterns; mathematical feedback uses the existing structured fraction blocks and answer fields. Existing resume expiry and browser storage limits remain.

The prior `index-v10.13.0.html`, local prototypes and learner-data format are preserved. Publication is recorded separately after branch and live-byte verification.
