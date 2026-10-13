# Crimson Dynasty Writers' Room → GitHub Reconciliation Ledger

**Date:** 2026-10-13  
**Working branch:** `reconcile/dynasty-writers-room-2026-10-13`  
**Status:** Initial audit ledger; not a declaration that the full reconciliation is complete.

## Purpose and handling rules

This ledger records the reconciliation process between Zee's Crimson Dynasty Writers' Room decisions and the GitHub project. It does not replace locked canon or manuscript files.

- **Locked canon wins:** the newest explicitly locked decision overrides older canon.
- **Separate status from content:** locked canon, confirmed current direction, brainstorm/proposal, manuscript draft, and unresolved continuity issue must remain distinguishable.
- **No silent rewrites:** preserve existing prose and archive drafts. Do not treat archived proposals as approved chapters unless Zee explicitly approved them.
- **Dynasty first:** Crimson Dynasty is the active priority. Crimson Legacy remains paused except where a confirmed cross-book rule is needed for continuity.
- **Writers' Room is not the novel manuscript:** use it for planning, worldbuilding, continuity, critique, and development. Novel chapter drafting belongs in the book-drafting workflow.
- **Use a review branch:** changes are being prepared on this branch, not directly on `main`.

## Confirmed current Dynasty direction

- Current locked manuscript progress is through **Chapter 146**; the next chapter counter is **Chapter 147**.
- Chapter 146: **Brannic Dor dies**. Selk Varren is already dead.
- Retaliation order after Selk Varren: Brannic Dor → Vaeren Thoss → Kaldrek Vane → Sera Quill → Jorren Vale → Neris Pell → Drovak Senn.
- Zee's darker phase is deliberate and merciless toward responsible threats, not indiscriminate; civilians and Zee's people are not targets.
- The original commissioner of the Chapter 128 attack remains **unknown**.
- Victor's thread continues alongside the revenge arc: he tests Zee through the Zerlin scenario and gradually earns a place with Zayrlen. Any return from apparent death must be handled as a plot development, not assumed fact without the relevant locked decision.
- Keep the Devouring Choir separate; it is not the explanation for Victor or the Chapter 128 attack.
- Aidan remains hidden in Vesper and offstage for new Dynasty retaliation scenes. Do not add a new Aidan brother-attack plot.
- Rez is Zee's best friend and Aidan's uncle, not Zee's son. Ner Azrion is Zee's male partner and the father/gestational parent of Zayrlen and Azren, not Zee's son.
- Zee is the only character who creates hybrids. Do not add a demon hybrid to Zee's team.
- The Order of the Hollow Crown is the paper/legal-war Order. The League of the Black Order is a separate assassin organization.
- Phoenix-related fire/wings imagery may appear where already supported, but do not prematurely reveal or lock a Phoenix form/name.
- Drafts in the archive are proposals unless explicitly approved.

## Canon guardrails to preserve during reconciliation

- Zee Darkheart's title is **First Natural Tribrid**, not Quadbrid. Witch, Vampire, and Wolf natures are awake from birth; dormant Dragon blood is inherited from Aurelia.
- The Convergence Vault says **“Four”** and **“Three awake”** without turning this into a destiny/prophecy framing.
- Victor's single newborn kill attempt already occurred; Zee returned. Do not add repeated kill attempts or a recurring death/resurrection cycle.
- Zee's Crimson magic belongs to Zee, not House Darkheart. Zee absorbs/evolves into Crimson Evolutions; he does not copy other people's powers.
- Zee's time/age power can alter a living person's biological age only. It cannot rewrite history, undo events, reverse death, or prevent Aurelia's eventual death.
- At age ten, Zee's Dragon signs include crimson-black horns, permanent Crimson scales that spread with emotion/danger/combat, and Dragon energy. No full Dragon transformation or adult wings at that stage.
- Zareth Drakonis is the true Dragon Prince of House Drakonis, born on Zee's birthday; Teal-and-Gold Mana/Dragon Link catalyzes Zee's dormant Dragon blood but does not supply it.
- Ner Azrion uses he/him, has Pure Gold Mana, and is Zee's lover; no Nymeris romance or jealousy triangle.
- Zee has exactly three sons: Aidan Seyrion Darkheart (mother Queen Nymeris Thalryn), Zayrlen Keal Darkheart, and Azren Neyron Darkheart (both sons of Zee and Ner, carried/born by Ner).
- Nymeris and Zee are chosen family, not romantic partners. Aidan's maternal Ocean/Abyss/Siren blood is not assumed sealed or known; Zee sealed only Witch/Vampire/Wolf when hiding Aidan.
- Inner-circle no-target boundaries include Ner, Rez, Zareth, Kael, Tessa, Amara, family, and close friends.
- Veyrath and Drakonis are separate houses. Aurelia Veyrath is a true Dragon–Witch hybrid with a true Dragon form; Lucien did not know. Do not substitute Vaelorian for Veyrath.
- Khandra Parbat replaces Nanda Parbat. Cassel Rhune is the first true Godslayer encounter; Godslayer era begins in Chapter 94. Zee's formal term is Black Divinity.

## Repository items requiring careful comparison

- `dynasty/canon.md`, `dynasty/characters.md`, and `dynasty/chapters.md` are existing core references.
- Root `chapter_map.md` also exists. Compare it with `dynasty/chapters.md` before deciding which is authoritative; do not merge blindly.
- `drafts/current-direction.md` contains the current Chapter 146/147+ direction and must be compared with the locked references.
- `drafts/archive-pre-restart-2026-10-12/` contains many chapter draft proposals, including a numbering gap at Chapter 225. Their presence does not mean they are approved or canon.
- `drafts/brainstorm.md` is empty at the time of this audit.
- `drafts/incoming/` is referenced in shift-report workflow but was not present during the initial repository inspection.
- `legacy/chapter_map.md` and a root-level `shared/` directory were not found during initial inspection. Verify whether they are truly required before creating replacements.

## Known reconciliation flags

1. **Chapter 142 Aidan material:** conflicts with the later lock that Chapter 104 “Uncle Rez” leaves Aidan hidden in Vesper and that no further Aidan childhood chapters should be added. Preserve the material for review; do not silently treat it as canon.
2. **Chapter maps:** root `chapter_map.md` and `dynasty/chapters.md` need a side-by-side comparison and an explicit authority decision.
3. **Archived drafts:** Chapters 147 onward in the archive are not automatically approved manuscript chapters. Confirm status before promoting any text.
4. **Chapter 225:** missing from the observed archive sequence; determine whether intentionally absent, stored elsewhere, or never drafted.
5. **Unresolved names/continuity:** Darkheart is the current continuity; Drakhar is alternate/unresolved and should not be silently substituted.
6. **Chapter 128 attack commissioner:** remains unknown; don't invent or infer the identity.
7. **Legacy gating:** Legacy must remain paused while Dynasty is reconciled. The Wolf Arc remains gated until Lyra's death; don't draft it early.

## Work sequence

1. Compare root and Dynasty chapter maps.
2. Compare current direction, canon, character reference, chapter reports, and locked Writers' Room decisions.
3. Build a source/status matrix for each discovered conflict or gap.
4. Update the appropriate reference files only when the authoritative decision is clear; preserve conflicting source material and record unresolved items.
5. Reconcile the chapter archive and reports without promoting unapproved drafts.
6. Validate cross-book references and retain Dynasty-first sequencing.
7. Summarize changed files and unresolved decisions for Zee.

## Completion note

This ledger is the first tracked reconciliation artifact. It does **not** claim that every Writers' Room message or every repository file has been reconciled yet.
