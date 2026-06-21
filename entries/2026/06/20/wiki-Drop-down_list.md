---
source: sources/wiki-Drop-down_list.md
source_url: https://en.wikipedia.org/wiki/Drop-down_list
---

## Drop-Down Lists: Definition, Terminology, and Implementation

A drop-down list (DDL) is a GUI control element that displays a single value when inactive and expands to reveal a selectable list of values when activated. Upon selection, it collapses back to show the chosen value. It is a fundamental form input widget used across desktop and web interfaces.

## Key Concepts

- **Core behavior**: Inactive state shows one value; activated state "drops down" to reveal all options; selecting a value returns the control to its inactive state
- **Single-selection model**: The standard drop-down allows the user to choose exactly one value from a list
- **Activation methods**: Can be triggered by clicking or hovering, depending on implementation
- **Platform terminology varies**:
  - macOS calls this a "pop-up menu" (distinct from "pull-down menu")
  - Other platforms use "context menu" for what Mac calls "pop-up menu"
- **Pop-up vs. pull-down (macOS distinction)**: A pop-up menu's closed title shows the last-selected item; a pull-down menu shows a static title. Pop-ups are for selecting options; pull-downs are for issuing commands or multi-select scenarios
- **Related but distinct controls**: Combo box (allows typed input + list), List box (always-visible multi-item list)

## Commands and Syntax

**HTML implementation** using `<select>` and `<option>` elements:
```html
<select>
  <option>option1</option>
  <option>option2</option>
  <option>option3</option>
</select>
```

**GTK 4 implementation**: Uses the `Gtk.DropDown` widget class.

## Relationships

- **List box**: Similar control but displays multiple items simultaneously without collapsing; drop-down is the space-efficient alternative
- **Combo box**: Extends drop-down by adding a text input field, allowing users to type values not in the list
- **Context menu**: Shares "pop-up" terminology on some platforms, causing confusion; functionally distinct (context menus are action-oriented, drop-downs are selection-oriented)
- **Web forms**: Drop-downs are a standard form input alongside checkboxes, radio buttons, and text fields
- **Widget taxonomy**: Classified as a "command input" control alongside buttons, context menus, and hamburger menus

## Exam-Relevant Points

- A drop-down list allows selection of **one** value from a predefined list — distinguish from multi-select list boxes
- The HTML elements for drop-downs are `<select>` (container) and `<option>` (individual choices) — not `<dropdown>` or `<list>`
- On macOS, "pop-up menu" refers to what other platforms call a drop-down list; on other platforms, "pop-up menu" means context menu — terminology is platform-dependent
- The key UX distinction between pop-up and pull-down menus is what the closed state displays: last-selected item vs. static label
- Drop-downs are space-efficient alternatives to list boxes — they consume only one line of screen space when inactive
- GTK 4 uses `Gtk.DropDown` as the widget class name
