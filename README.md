# ♟️ Custom CSS Chess Board

> A minimalist and elegant chessboard web application built from scratch using pure HTML5 and CSS3, featuring a custom color palette and Unicode chess pieces.
>
> <img width="1060" height="882" alt="image" src="https://github.com/user-attachments/assets/e51e74f3-52fb-4ac0-86fa-94dd3c9babd4" />


---

## 🎨 Design & Aesthetic

Moving away from the standard black-and-white board, this project introduces a refined, artistic color palette:
* **Background:** Soft warm neutral (`#EFEAE3`).
* **Dark Squares:** Charcoal tone (`#4E4B5C`).
* **Light Squares:** Taupe tone (`#A37871`).
* **Typography:** Elegant Georgia font styling for the main board heading.

---

## 🏛️ Layout Architecture & Implementation

* **Fixed Grid Structure:** The board is locked at an exact resolution of `640px` by `640px` and centered within the viewport.
* **Float-Based Layout:** Each square is precisely sized at `80px` by `80px` utilizing CSS `float: left` to arrange the 64 squares into an alternating grid layout.
* **Unicode Chess Pieces:** Pieces are rendered using native Unicode symbols (e.g., rooks, knights, pawns) scaled cleanly with `3.2rem` sizing and aligned using flex/text properties.

---

## ⚙️ Technical Specs

* **Markup Layer (`INDEX.HTML`):** Structured 8x8 grid mapped sequentially row-by-row with corresponding CSS classes.
* **Styling Layer (`STYLE.CSS`):** Handles precise block dimensions, float behaviors, unique color properties, and typography.

---

## 📂 Repository File Tree

```text
CHESS-BOARD/
│
├── INDEX.HTML          # Main HTML markup mapping out the 64-square layout
└── STYLE.CSS           # Custom stylesheet controlling grid dimensions and color themes
