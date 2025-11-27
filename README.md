# Monokochrome Theme for Btop

A sleek, monochrome theme for `btop` with a transparent background, featuring a palette of blacks, whites, and greys.

## Installation

1.  **Move the theme file:**
    Move the `monokochrome.theme` file to your `btop` themes directory.

    ```bash
    mv monokochrome.theme ~/.config/btop/themes/
    ```

2.  **Activate the theme:**
    You need to edit your `btop.conf` file to use the new theme.

    **Option A: Using the command line (Recommended)**
    Run this command to automatically update your configuration:

    ```bash
    sed -i 's/^color_theme =.*/color_theme = "monokochrome"/' ~/.config/btop/btop.conf
    ```

    **Option B: Manual Edit**
    Open `~/.config/btop/btop.conf` in your text editor and find the line starting with `color_theme`. Change it to:

    ```conf
    color_theme = "monokochrome"
    ```

3.  **Restart btop:**
    If `btop` is running, restart it to see the changes.
