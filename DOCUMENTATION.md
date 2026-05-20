# Deck of Nodes API Reference
Generated: 2026-05-20

An addon for managing a list of nodes. Useful for card games

## Class: DeckOfNodes
**Inherits:** [Resource](https://docs.godotengine.org/en/stable/classes/class_resource.html)

This class is used to store a list of packed scenes, (for example for a deck of cards, or an inventory), and spawn them into the tree when needed

### ⚙️ Inspector Variables (Exported)
| Property | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| **deck_of_scenes** | `Array[PackedScene]` | `-` | The ordered list of PackedScenes that make up this deck |

### 🛠️ Methods
| Method | Arguments | Returns | Description |
| :--- | :--- | :--- | :--- |
| **append_packed_scene()** | `packed_scene : PackedScene` | `void` |  Adds a PackedScene to the back of the deck |
| **insert_packed_scene()** | `position : int`<br>`packed_scene : PackedScene` | `void` |  Inserts a PackedScene at the given index, shifting later entries back |

---

