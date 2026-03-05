# Notion UI Shortcuts & Database Navigation Reference

> For use when operating Jason's Creator Accelerator CRM in Notion.
> Sources: [Notion Help Center](https://www.notion.com/help/keyboard-shortcuts), [Notion Tables](https://www.notion.com/help/tables), [Notion Boards](https://www.notion.com/help/boards)

---

## Quick Navigation

| Shortcut | Action |
|-|-|
| `Ctrl + P` or `Ctrl + K` | Open search / jump to recent page |
| `Ctrl + [` | Go back (previous page) |
| `Ctrl + ]` | Go forward |
| `Ctrl + \` | Toggle sidebar open/close |
| `Ctrl + Shift + U` | Navigate up one level in hierarchy |
| `Ctrl + N` | Create new page |
| `Ctrl + Shift + N` | Open new Notion window |
| `Ctrl + T` | New Notion tab |
| `Ctrl + L` | Copy current page URL |
| `Ctrl + Shift + L` | Toggle dark/light mode |

## Database: Table View

### Cell Navigation
| Shortcut | Action |
|-|-|
| `Enter` | Move to cell below |
| `Tab` | Move to next cell (right) |
| `Shift + Tab` | Move to previous cell (left) |
| Click cell directly | Edit inline (no need to open page) |
| `Esc` | Deselect / exit editing |

### Row Selection
- Hover over row → click checkbox that appears on the left
- Hover over `Name` column header → click checkbox to select ALL rows
- `Shift + click` to select a range of rows
- `Ctrl + click` to add/remove individual rows from selection

### Bulk Editing (CRITICAL FOR CRM WORK)
- Select multiple rows → `Ctrl + /` → edit properties for all selected rows at once
- Select multiple cells → `Ctrl + D` to fill down / `Ctrl + R` to fill right

### Column Management
- Click + hold column header → drag left/right to rearrange
- Hover over column edge → drag to resize
- Click `Properties` (top right) → use `⋮⋮` to drag property order

### Row Management
- Hover over row → click + hold `⋮⋮` on the left → drag up/down to reorder
- Click `+ New` at bottom to add new row

## Database: Board View (Our CRM Default)

### Card Operations
- **Drag cards between columns** to instantly change Lead Status (e.g., drag from "New Lead" to "In Conversation")
- Click + hold card → drag between columns = status change
- Cards can be dragged up/down within a column to reorder

### Multi-Select on Board
- Hover over cards → `Shift + click` or `Ctrl + click` to select multiple
- Selected cards → `Ctrl + /` to bulk edit properties

### Peek View (Opening Cards Without Leaving Board)
| Shortcut | Action |
|-|-|
| Click card | Opens in peek/side view |
| `Ctrl + K` | Previous database page in peek view |
| `Ctrl + J` | Next database page in peek view |

## Changing Status/Properties WITHOUT Opening the Page

1. **Table View**: Click the status cell directly → dropdown appears → select new value
2. **Board View**: Drag card to new column (each column = a Lead Status value)
3. **Bulk Edit**: Select multiple items → `Ctrl + /` → change property for all at once
4. **Database Buttons**: One-click property changes (if configured)

## Creating New Database Entries

- Table: Click `+ New` at bottom of table, or `Ctrl + N` within database
- Board: Click `+ New` at bottom of any column
- Then fill in properties inline

## Filters, Sorts & Groups

- Click `Filter` button at top of database view → add conditions
- Stack filters with AND logic, or create OR groups
- Click `Sort` → choose property + direction (ascending/descending)
- Multiple sort rules apply in listed order
- `Group` → group entries by property values into collapsible sections
- Each VIEW saves its own filter/sort/group settings

## Slash Commands (Inside Any Page/Cell)

| Command | Action |
|-|-|
| `/text` | Plain text block |
| `/h1`, `/h2`, `/h3` | Headings |
| `/todo` | Checkbox item |
| `/bullet` | Bulleted list |
| `/mention` | Mention a person or page |
| `/date` | Insert date/reminder |
| `/link` | Link to another page |
| `/duplicate` | Duplicate current block |
| `/delete` | Delete current block |

## Text Formatting

| Shortcut | Action |
|-|-|
| `Ctrl + B` | Bold |
| `Ctrl + I` | Italic |
| `Ctrl + U` | Underline |
| `Ctrl + Shift + S` | Strikethrough |
| `Ctrl + E` | Inline code |
| `Ctrl + K` | Add link |
| `Ctrl + Shift + M` | Create comment |

## Block Manipulation

| Shortcut | Action |
|-|-|
| `Ctrl + D` | Duplicate block |
| `Ctrl + /` | Edit/change block type |
| `Ctrl + Shift + Arrow` | Move block up/down |
| `Tab` | Indent/nest |
| `Shift + Tab` | Un-nest |
| `Backspace` / `Delete` | Delete selected blocks |

## CRM-Specific Workflow Tips

1. **Fastest status change**: In Board view, just drag the card. No clicks needed beyond grab-and-drop.
2. **Search for a lead**: `Ctrl + P` → type their name → jump directly to their entry.
3. **Edit without opening**: In Table view, click any cell to edit inline. For Select properties (like Lead Status), clicking shows the dropdown immediately.
4. **Bulk status updates**: After a session, select all leads that changed status → `Ctrl + /` → update Lead Status for all at once.
5. **Quick new lead entry**: Click `+ New` in the appropriate status column on Board view → the card is auto-assigned that status.
6. **Navigate between leads in peek**: Open one lead → use `Ctrl + J` / `Ctrl + K` to flip through leads without closing and reopening.
