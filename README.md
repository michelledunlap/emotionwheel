# emotionwheel

This project is a web-based, interactive emotion wheel designed to help users identify, explore, and understand their feelings. It features a multi-layered wheel inspired by common psychological models of emotion, allowing for nuanced self-reflection.

## Features

* **Multi-Layered Visual Wheel:** Displays core emotions, secondary emotions, and more specific tertiary emotions in a clear, hierarchical structure.
* **Interactive Segments:** Each emotion segment on the wheel is interactive.
    * **Hover for Definitions:** Hovering over any emotion segment reveals its name and a brief definition.
    * **Select Tertiary Emotions:** Users can left-click on the outermost (tertiary) emotions to select the ones they are currently feeling.
    * **Gray Out Emotions:** Users can right-click on any emotion segment (core, secondary, or tertiary) to "gray out" emotions or entire branches they identify as *not* feeling.
        * Left-clicking a grayed-out tertiary emotion will make it active (first click) and then selectable (second click).
        * Left-clicking a grayed-out core or secondary emotion will make its entire branch active again.
* **Dynamic Highlighting:** Selected tertiary emotions are highlighted with a darker, desaturated version of their segment's color.
* **Emotion Counts:** Core and secondary emotion labels display a count of the active, selected tertiary emotions beneath them.
* **Summary & Reflection:**
    * A "Review Selected Feelings" button takes the user to a summary page.
    * Displays a list of all selected (active) tertiary emotions.
    * Provides a set of journal prompts to encourage further reflection on the selected feelings.
* **Reset Functionality:** A "Reset All Selections" text link allows users to clear all selections and grayed-out states.
* **Responsive Design:** The wheel and interface are designed to be usable on different screen sizes.


## Based On

The structure and concept are inspired by various emotion wheel models, including those derived from Plutchik's Wheel of Emotions. The specific emotion hierarchy and definitions in this version have been curated for this tool.


## Acknowledgments

This interactive emotion wheel was developed with the assistance of Google's AI model, Gemini. The core functionality, design iterations, and code were generated and refined through a collaborative process with the AI.


## Future Development (V2 Ideas)

* Enhanced accessibility (ARIA attributes, full keyboard navigation).
* Mobile-specific interaction improvements for "gray out" functionality.
* Undo/Redo functionality.
* User accounts and saving emotion logs (would require backend).
* Integration with journaling tools or APIs.
