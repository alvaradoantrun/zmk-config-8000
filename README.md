# MySplit ZMK Config (nice!nano v2)

If your previous build failed with `https://github.com/zmk not found`, it was due to a short `url-base`.
This repo sets `url-base: https://github.com/zmkfirmware` so West fetches `zmkfirmware/zmk` correctly.

Steps:
1. New empty repo → upload all files preserving folders (or create `.github/workflows/build.yml` via web).
2. Push and open **Actions** → **Build ZMK firmware**.
3. Artifacts: `mysplit_right-nice_nano_v2.uf2` and `mysplit_left-nice_nano_v2.uf2`.
4. Edit `boards/shields/mysplit/mysplit_left.overlay` with your left pins, then push again.
