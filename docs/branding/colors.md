# Brand Colors
---

## Color Palette

### Primary Color – Orange  
The **core** of the brand. Conveys **energy, visibility, and unity**.

| Shade | RGB | CMYK | HEX | Pantone | Preview |
|-------|-----|------|-----|---------|--------|
| **Light Orange** | `241/110/34` | `0/66/99/0` | `#F16E22` | **1585 C** | <span style="background:#F16E22;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Dark Orange**  | `87/23/20`   | `10/82/81/63` | `#571714` | **483 C**  | <span style="background:#571714;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |

---

### Neutral Support Colors  
Clean, professional base for **contrast and readability**.

| Shade | RGB | CMYK | HEX | Pantone | Preview |
|-------|-----|------|-----|---------|--------|
| **Light White** | `255/255/255` | `0/0/0/0` | `#FFFFFF` | — | <span style="background:#FFFFFF;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Dark White**  | `242/240/235` | `6/5/9/0` | `#F2F0EB` | — | <span style="background:#F2F0EB;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Light Black** | `204/206/221` | `18/13/10/0` | `#CCCEED` | **Cool Gray 3C** | <span style="background:#CCCEED;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Dark Black**  | `42/44/55`    | `77/66/50/56` | `#2A2C37` | — | <span style="background:#2A2C37;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |

---

### Accent Colors  
Bright, diverse tones inspired by **academic vibrancy** and **youthful energy**.

| Color | Shade | RGB | CMYK | HEX | Pantone | Preview |
|-------|-------|-----|------|-----|---------|--------|
| **Pink** | Light | `250/228/241` | `1/15/0/0` | `#FAE4F1` | **670 C** | <span style="background:#FAE4F1;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| | Dark | `251/191/236` | `5/42/0/0` | `#FBBFEC` | **672 C** | <span style="background:#FBBFEC;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Purple** | Light | `217/165/235` | `14/35/0/0` | `#D0A5EB` | **2562 C** | <span style="background:#D0A5EB;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| | Dark | `98/23/130` | `68/100/0/0` | `#621782` | **2613 C** | <span style="background:#621782;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Yellow** | Light | `250/238/176` | `1/1/29/0` | `#FAEEB0` | **7449 C** | <span style="background:#FAEEB0;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| | Dark | `251/216/61` | `0/9/80/0` | `#FBD83D` | **122 C** | <span style="background:#FBD83D;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Green** | Light | `166/195/163` | `34/11/37/2` | `#A6C3A3` | **2404 C** | <span style="background:#A6C3A3;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| | Dark | `1/98/32` | `81/0/100/54` | `#016220` | **2427 C** | <span style="background:#016220;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Blue** | Light | `186/212/255` | `19/7/0/0` | `#BAD4FF` | **657 C** | <span style="background:#BAD4FF;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| | Dark | `86/146/255` | `63/37/0/0` | `#5692FF` | **2129 C** | <span style="background:#5692FF;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| **Navy Blue** | Light | `183/201/237` | `24/12/1/0` | `#B7C9ED` | **537 C** | <span style="background:#B7C9ED;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |
| | Dark | `25/61/105` | `100/81/0/13` | `#193D69` | **661 C** | <span style="background:#193D69;width:40px;height:40px;border-radius:50%;display:inline-block;border:2px solid #ccc;"></span> |

---

## CSS Variables

```css
:root {
  /* Primary */
  --orange-light: #F16E22;
  --orange-dark:  #571714;

  /* Neutrals */
  --white:        #FFFFFF;
  --off-white:    #F2F0EB;
  --gray-light:   #CCCEED;
  --gray-dark:    #2A2C37;

  /* Accents */
  --pink-light:   #FAE4F1;
  --pink-dark:    #FBBFEC;
  --purple-light: #D0A5EB;
  --purple-dark:  #621782;
  --yellow-light: #FAEEB0;
  --yellow-dark:  #FBD83D;
  --green-light:  #A6C3A3;
  --green-dark:   #016220;
  --blue-light:   #BAD4FF;
  --blue-dark:    #5692FF;
  --navy-light:   #B7C9ED;
  --navy-dark:    #193D69;
}
```