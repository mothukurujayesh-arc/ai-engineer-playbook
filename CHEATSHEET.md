# JUPYTER NOTEBOOK CHEAT CODE (VS CODE)
*Your 1-Page Reference for Clean, Fast AI Engineering Notes*

---

## 1. KEYBOARD SHORTCUTS (WINDOWS)
Jupyter has two modes:
- **Edit Mode (Green/Cursor blinking):** You are typing inside a cell. Press `Esc` to exit.
- **Command Mode (Blue/No cursor):** You are organizing cells. Press `Enter` to type inside a cell.

### Essential Shortcuts (Use These Every Day)
| Shortcut | Mode | What It Does |
| :--- | :--- | :--- |
| **`Shift + Enter`** | Any | **Run / Render cell** and move to the next cell |
| **`Ctrl + Enter`** | Any | **Run / Render cell** and stay on the same cell |
| **`Ctrl + S`** | Any | **Save** your notebook |
| **`Esc`** | Edit | Switch to **Command Mode** (to use single-letter shortcuts) |
| **`Enter`** | Command | Switch to **Edit Mode** (to start typing) |
| **`A`** | Command | Insert a new cell **Above** |
| **`B`** | Command | Insert a new cell **Below** |
| **`M`** | Command | Convert cell to **Markdown (Notes)** |
| **`Y`** | Command | Convert cell to **Code (Python)** |
| **`D` `D`** *(press D twice)* | Command | **Delete** the selected cell |
| **`Z`** | Command | **Undo** deleting a cell |
| **`Alt + Up / Down`** | Any | **Move** the current cell up or down |
| **`Ctrl + /`** | Edit | **Comment / Uncomment** lines of Python code |

---

## 2. MARKDOWN KEYWORDS & FORMATTING (FOR NOTES CELLS)
Type these symbols inside a **Markdown cell** (`Esc` + `M`), then press **`Shift + Enter`** to render.

### Headings (Always put a space after `#`)
- `# Course Name` $\rightarrow$ **Title** (Use once at the very top)
- `## Chapter 1: Topic` $\rightarrow$ **Major Section** (Use for each chapter)
- `### Function Name` $\rightarrow$ **Sub-section** (Use for specific methods)

### Text Styling & Highlights
- `**Important Term**` $\rightarrow$ **Important Term** (Bold)
- `*Subtle note*` $\rightarrow$ *Subtle note* (Italic)
- `` `temperature=0.2` `` $\rightarrow$ `temperature=0.2` (Inline code / parameter highlight)
- `> **Exam Tip:** Remember this rule!` $\rightarrow$ Indented callout box for exam warnings
- `---` $\rightarrow$ Draws a horizontal divider line between lessons

### Lists & Tables
- `- Bullet point` or `* Bullet point` $\rightarrow$ Unordered list
- `1. First step` $\rightarrow$ Numbered list
- `| Col 1 | Col 2 |` $\rightarrow$ Creates a clean comparison table

### Code Block Inside Markdown (For reference syntax you don't want to run)
````markdown
```python
client = OpenAI(api_key="YOUR_API_KEY")