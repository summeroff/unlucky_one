# Ему просто не повезло (He Was Just Unlucky)

This repository contains the source files for the completed fictional story, "Ему просто не повезло" (He Was Just Unlucky), a cosmic adventure narrative infused with dark humor, existential dread, and the relentless misfortune of its protagonist, Ivan. Spanning the forsaken outskirts of the universe to its mysterious core, the tale explores themes of luck, sacrifice, and the steep cost of chasing destiny.

## Content Warning
The story contains potentially triggering or distressing content, including:
- Graphic depictions of violence and death
- Themes of despair, betrayal, and moral ambiguity
- Dark humor and ironic twists
- Scenes of emotional and physical loss
- Cosmic and existential horror elements

These elements are fictional and do not reflect the author’s personal views. **Reader discretion is advised**.

## Story Summary (Lore) - Spoiler Alert!
For a detailed lore summary, see [lore_summary.md](lore_summary.md).

### Brief Overview:
Ivan, born in the desolate village of Krayukha on the universe's edge, is a magnet for misfortune. From a meteor destroying his family’s barn at birth to a lifetime of calamities, his bad luck is his curse. When a waterlogged map reveals the path to the "Treasure of Golden Light"—an artifact said to rewrite fate—Ivan embarks on a journey aboard the ramshackle spaceship *Old Fox*. His quest takes him through cosmic perils: asteroid collapses, pirate ambushes, and the treacherous Temple of Zariya. Each triumph costs him dearly—friends, humanity, and pieces of his soul—culminating in a harrowing choice: claim the treasure’s power or succumb to the void it demands.

## Project Status
The story is **complete**, with all chapters included across two parts, as reflected in the LaTeX source:

- **Part 1:**
  - Chapter 1: Начало неудач (The Beginning of Misfortune)
  - Chapter 2: Потерянный в Шепчущих Лесах (Lost in the Whispering Woods)
  - Chapter 3: Побег на звездолёте (Escape on a Starship)
  - Chapter 4: Ловушка на астероиде (Trap on the Asteroid)
  - Chapter 5: Тайна кристалла (The Mystery of the Crystal)
  - Chapter 6: Передышка на станции (Respite at the Station)
  - Chapter 7: Предательство и спасение (Betrayal and Salvation)

- **Part 2:**
  - Chapter 8: Цена сострадания (The Price of Compassion)
  - Chapter 9: Притяжение силы (The Pull of Power)
  - Chapter 10: Правосудие или месть (Justice or Revenge)
  - Chapter 11: Темная сделка (The Dark Deal)
  - Chapter 12: Тени «Омеги» (Shadows of Omega)
  - Chapter 13: Эхо пустоты (Echo of the Void)
  - Chapter 14: Цена выживания (The Cost of Survival)

*Note:* The chapter numbering and titles are now synchronized with the LaTeX document `book_unlucky_one.tex`. "Потерянный в Шепчущих Лесах" is positioned as Chapter 2, reflecting its placement in the narrative flow before Ivan’s cosmic journey begins in earnest.

## Repository Structure
- **LaTeX Sources**:
  - `book_unlucky_one.tex`: The complete story in Russian, now fully edited and structured.
- **Lore Summary**:
  - `lore_summary.md`: Updated overview of the story’s characters, events, and themes, reflecting the final narrative.
- **Release Scripts**:
  - GitHub Actions script to automate generation of reader formats (PDF, EPUB, etc.).

## License
This project is licensed under the MIT License—see the [LICENSE](LICENSE) file for details. You are free to use, modify, and distribute the code and story, even commercially, provided you include the original copyright notice and disclaimer.

## Updates and Changes
- **Narrative Completion**: The story now spans 14 chapters across two parts, fully detailing Ivan’s transformation from a hapless villager to a cold, powerful figure shaped by the Temple of Zariya’s dark energy.
- **Chapter Adjustments**: 
  - "Потерянный в Шепчущих Лесах" is now Chapter 2, serving as Ivan’s initial terrestrial adventure before his cosmic journey.
  - Chapter numbering has been updated to match the LaTeX document exactly, with titles like "Притяжение силы" (Chapter 9) and "Правосудие или месть" (Chapter 10) reflecting their current positions.
  - The sequence now flows logically from the LaTeX source, correcting prior inconsistencies.
- **Thematic Depth**: The story emphasizes Ivan’s internal struggle with the cost of power, culminating in the loss of Lena and his humanity in "Цена выживания".
- **Character Development**: New characters like Lari, Kairen, and Boris enrich the narrative, while the fates of Andrei, Pavel, and Lena underscore the stakes of Ivan’s choices.

## Future Plans
- **Refinement and Editing**: Final polish of the LaTeX formatting and minor grammatical tweaks in progress.
- **Automated Builds**: GitHub Actions now fully operational to generate PDF, EPUB, and MOBI formats for distribution.
- **Supplementary Materials**: Plans for a map of Ivan’s journey and character sketches are underway.

## Contributing
While this remains a solo project, feedback is welcome! Open an issue to report errors, inconsistencies, or share ideas for enhancement. Pull requests may be considered for supplementary materials or build improvements.

## Author
SummerOfF

## Getting Started (for building the LaTeX files)
To compile the LaTeX files into a PDF, ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX, MacTeX). Compile the full book using:

```bash
xelatex book_unlucky_one.tex