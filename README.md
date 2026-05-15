# Earicular

UC Irvine BME 180C Senior Design Capstone — tissue-engineered auricular reconstruction using 3D bioprinted constructs with Extearna® costal cartilage allograft.

## Structure

```
index.html                          # entire site (HTML, CSS, JS in one file)
website content/
  earicular-logo.png                # navbar + footer logo
  extearna.jpg                      # original product photo (unused)
  Website Content.pdf               # source reference material
  website-photos/
    extearna/                       # product and lab testing photos
    gelma/
      bioink.gif                    # animated bioink extrusion (converted from .mov)
      bioinkcured.MOV
      bioinktesting.mov
    printing/                       # G-code and bioprinter photos
```

## Sections

| Section | Anchor |
|---|---|
| Hero | `#home` |
| Product (Clinical Need, Extearna®, Solution) | `#product` |
| Research (GelMA, dECM, Surgery Problem, Approach) | `#research` |
| Competitor Analysis | `#competitors` |
| Market Strategy (overview + stakeholder tables) | `#market` |
| Team | `#team` |
| Contact | `#contact` |

## Editing

Open `index.html` in any code editor. All CSS lives in `<style>` and all JS lives in `<script>` at the bottom of the same file.

**To add team photos:** find the `.avatar` div for a team member, remove the `<span>` initials, and uncomment the `<img>` tag with the correct file path.

**To preview locally:** open `index.html` directly in a browser, or use the Live Server extension in VS Code.
