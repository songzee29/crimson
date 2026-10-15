# Crimson Legacy Deep Dive — Phase 06
## Source-Message Grouping and Chapter-Level Collisions

**Classification:** Archival findings; no canon changes.  
**Primary source:** Original exported conversation *Crimson Legacy Reimagined*, with repository chapter extractions used as a comparison index.

## 1. Chapter 13 is not one chapter draft

The source has at least three distinct Chapter 13 identities, which must not be collapsed:

1. **“The Thing Between Shelves” — source message `188786b7-fef4-4263-8988-451752328524`, June 12, 07:26 UTC, 3,882 characters.**  
   This response includes a long editorial bridge about the intended dark-mystery tone, a recap of the archive and Lyra's folder, and a full Chapter 13 opening. It explicitly states Rez is still asleep and that the archive contains something physical and hunting Aidan.

2. **“The Thing Between Shelves” — source message `6b382726-5381-4351-9e97-0c9542185b8e`, June 12, 07:40 UTC, 5,670 characters.**  
   This is not merely a second copy of Chapter 13. The same response contains a five-chapter sequence: Chapter 13 “The Thing Between Shelves,” Chapter 14 “The Girl in the Crack,” Chapter 15 “The Church Beneath the Church,” Chapter 16 “Lyra,” and Chapter 17 “The Truth About Erasure.” The Chapter 13 extract alone is therefore not a complete archive of this source response.

3. **“The Invitation” — source message `98112a92-5941-4c36-a482-ff87413ba037`, June 27, 16:29 UTC, 6,508 characters.**  
   This is a separate Chapter 13 in a later high-numbering/alternate story track. It is not a continuation of the June 12 archive encounter simply because the number matches.

**Repository implication:** `re-ch013-the-thing-between-shelves.md`, `re-ch013-the-thing-between-shelves-v2.md`, and `re-ch013-the-invitation.md` are distinct archive entries. The response-level source text must remain available in the raw conversation archive; chapter-only extractions should be labeled as excerpts when they do not preserve the entire source response.

## 2. Chapter 13's story context differs by version

- In the June 12 first version, Aidan is isolated in the dark archive, detects a hostile entity, and uses Witch Sight. The surrounding editorial text says the current arc is a mystery/curse fantasy and that Rez remains asleep.
- In the June 12 five-chapter version, the Archive Keeper attacks, Aidan escapes with Lyra's folder, and the story proceeds into the erased-person mystery through Chapters 14–17.
- The June 27 “Invitation” chapter belongs to a different later run and cannot be merged into the archive encounter without a source-backed continuity bridge.

## 3. Chapter numbers 94–101 also collide across tracks

The June 27 *Crimson Legacy Reimagined* source has one message containing **Chapter 94 “The Hunter Returns”** and **Chapter 95 “The First Team Mission”** (message `4fc3d911-327f-4edf-8ad7-dc94b8fb2157`). Another message has **Chapter 98 “The Bone Collector,” Chapter 99 “The First Boss,” Chapter 100 “A Lesson Paid in Blood,” and Chapter 101 “The Child Who Never Left”** (message `f14e9a6a-dd0f-4b88-be8c-4453096a566a`).

Those titles differ from the Book Two Blood Trials set preserved elsewhere:
- Ch 94/95 “The Crimson Offering” appears in a separate Book Two source track.
- Ch 98 “Blood Trial IV — The Crimson Throne,” Ch 99 “The King's Walk,” and Ch 100 “The Final Seal” are another sequence.
- Another Ch 98–100 version has Aidan meeting the Crimson Witch, receiving her power, and undergoing Final Judgment.

The numbers alone do not establish which track is current. The October 12 ruling places the Witch Arc endpoint at Ch 101 “Two Years Later,” while the Chapter 101 titles above belong to earlier alternative runs. Preserve all titles and source IDs; do not rename them to match the current endpoint.

## 4. Chapter 177–178 collisions are wider than a single repeated title

The repository has multiple Chapter 177 files (“The Boy Who Was Hidden,” “The First Demon Hexborn,” “Bound by Blood,” and “Too Fast”) and multiple Chapter 178 files (“Brothers,” “No Mercy,” and “The Crimson Demon”). They represent separate scene proposals, chapter variants, or tracks. A chapter title and number cannot be used as a unique identifier. The archive key must include at least:
- conversation title,
- original message ID,
- source timestamp,
- chapter number and title,
- whether the entry is a full response, chapter-only extraction, outline, or excerpt,
- current status: locked, alternate, superseded, or unresolved.

## 5. Verified source-level conclusions

- There are multiple full Chapter 13 versions, not one authoritative Chapter 13.
- The June 12 second Chapter 13 response contains Chapters 13–17 in one message; saving only Chapter 13 loses the original response grouping.
- Later Chapter 13 “The Invitation” belongs to a different track.
- Chapters 94–101 have multiple title and plot sequences across conversations.
- Chapters 177–178 have multiple variants and must be cross-referenced by source message, not filename alone.
- The latest locked story map remains the governing present-tense anchor: Dynasty first; Legacy paused; Witch Arc ends at Chapter 101; high-numbered Witch-finale material remains alternate until explicitly mapped.

## Next pass

The next comparison target is the exact prose and response grouping for Chapters 94–101, followed by Chapters 177–178. Preserve every distinct full response, and mark a chapter-only file as an extraction rather than pretending it is the complete original source message.
