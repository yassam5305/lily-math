# Lily Math v10.12.0

November 11, 2026.

- Walter now considers edited fraction blocks together with typed answers when Lily presses Check or Help me across the Unit 5 workspaces. Tapping blocks still does not submit an answer, count as a miss, or record help by itself.
- Feedback responds to visible patterns: shading only the leftover fraction, shading only whole units, keeping the old piece count after making smaller pieces, or erasing a drawing. It gives a concrete next action and highlights the drawing that needs attention.
- For addition, keeps the drawing that already matches and directs attention to the other. Equal amounts shaded in different positions remain valid. The full-wholes step accepts a model of only those wholes.
- A correct typed answer with an unfinished drawing gets a separate review message, not a math miss. Lily can fix the drawing or choose Keep my checked answer. Changed typed answers are checked again; an unchanged unfinished drawing does not repeatedly stop later steps.
- When blocks match but the typed answer does not, Walter acknowledges the drawing and retains the specific answer clue. Fraction notation in a count-only box gets a clear format explanation.
- An untouched blank strip is not treated as an attempted zero. Edited drawings, drafts and bounded observation records survive supported lesson resume. Helped completion remains supported, and drawing observations do not establish mastery.

Tested with fictional beginner cases from local Qwen and real Chrome at phone and tablet sizes. No learner data was sent to Qwen. No progress-schema change. Prior releases and separate local v11 prototypes are preserved.
