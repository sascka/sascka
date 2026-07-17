# Setup guide for the `mondmann` GitHub profile

## 1. Create the special profile repository

Create a new **public** GitHub repository named exactly:

```text
mondmann
```

The repository name must match your GitHub username.

## 2. Upload this starter pack

Upload these items to the root of the repository:

```text
README.md
assets/
.github/
```

Do not put everything inside an extra `mondmann-profile` folder.

## 3. Add your GIF

1. Choose one wide GIF with a winter night, Japan, and moon atmosphere.
2. Rename it to:

```text
winter-night.gif
```

3. Upload it into:

```text
assets/winter-night.gif
```

4. Open `README.md`.
5. Find the section beginning with `ADD YOUR GIF`.
6. Remove the surrounding `<!--` and `-->` comment markers.

Recommended:
- Landscape format
- Width of roughly 800–1200 px
- Dark blue / grey palette
- Calm motion
- Avoid large subtitles, logos, watermarks, or bright colours
- Compress the file before uploading if it is very large

## 4. Generate the contribution animation

1. Open the repository's **Actions** tab.
2. Select **Generate winter contribution snake**.
3. Click **Run workflow**.
4. Wait for the workflow to commit the generated SVG files.

The workflow will then refresh the animation once per day.

## 5. Personalise the text

Edit these parts in `README.md` when your projects develop:

- Lantern status
- Toolkit
- Current direction
- Project links
- Contact links, only if you want them public

## 6. Improve the rest of the GitHub profile

For a professional-looking profile:

- Use a simple avatar that remains readable at small size
- Keep your bio to one line
- Pin 3–6 of your strongest repositories
- Give every serious repository a clear README, screenshots, licence, and roadmap
- Use consistent repository descriptions
- Avoid filling the profile with dozens of badges or unrelated widgets

Suggested bio:

```text
Systems & network programming · Rust/C++ · Building resilient, privacy-respecting software
```

Suggested profile name:

```text
mondmann
```
