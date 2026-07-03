<div align="center">

# pluttaneON

**3D-printed illuminated "pluttan" sign**


</div>

A large DIY glowing sign spelling "pluttan", designed for 3D printing. Each letter is split into numbered printable segments so the oversized glyphs fit on a standard FDM bed, plus a shared body part for assembly and LED backlighting.

## ■ Features

- ❖ **Letter parts** — STL files for the letters P, l, u, t, a, split into segments (P1/P2, l1/l2, u1/u2/u3, t1/t2, a1/a2)
- ❖ **Shared body** — a single `Body1.stl` base part used across the build
- ❖ **3MF print plates** — four `.3mf` projects (1–4) that arrange the segments into ready-to-slice plates
- ❖ **Illumination ready** — assembled letters are meant to glow with a user-supplied LED strip

## ■ Stack

<div align="center">

| Component | Technology |
|-----------|------------|
| Models | STL, 3MF |
| Printing | FDM 3D printer |
| Lighting | LED strip (user-supplied) |

</div>

## ■ How It Works

```
1. Open one of the four .3mf plate files (or individual .stl parts) in your slicer.
2. Print the letter segments in opaque filament for the body and translucent filament for the letter fronts.
3. Assemble the numbered segments into full letters using the shared Body1.stl base.
4. Mount a user-supplied LED strip behind the assembled letters and power it to achieve the glow effect.
```

## ■ Usage

Open the `1.3mf`–`4.3mf` files in your slicer (Cura, PrusaSlicer, etc.) for ready-made plates, or import the individual `.stl` parts. Print in an opaque filament for the body and a translucent material for the letter fronts to get the glow effect, then add an LED strip behind the assembled letters.

## ■ License

MIT © [pluttan](https://github.com/pluttan)
