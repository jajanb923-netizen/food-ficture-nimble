# Food Picture — Seared Salmon

A gourmet photograph of a seared salmon dish, 1024x1024 JPEG.

`main.py` copies `entry.png` from the repository root into the output
directory (`MAKEFUN_OUTPUT_DIR` if set, otherwise `/output/`), writing it
as `entry.png`. The copy is byte-identical and only happens after the
file's magic bytes are verified as JPEG (or PNG).
