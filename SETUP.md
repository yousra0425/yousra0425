# Setup — Your navy & baby-pink GitHub profile

This folder is a complete, ready-to-upload GitHub profile README. **No build step is required.**

## Publish through the GitHub website

1. Sign in as **yousra0425** and visit https://github.com/new.
2. Name the repository **yousra0425** (exact match to your account username).
3. Set visibility to **Public**. The repository can be empty; creating it with the default README is also fine.
4. Upload **README.md** and the entire **assets/** folder, preserving all filenames and the folder structure. In the new repository, select **Add file → Upload files**, then drag in the files and folder together. Commit to the default branch (`main`).
5. Open https://github.com/yousra0425 to see the finished profile.

**Important:** Upload the contents of this folder to the *root* of the GitHub repository — not a single extra parent folder. For example, `README.md` must be at the repository root, and `assets/banner.svg` must exist.

### Alternative: command line

```bash
cd yousra-github-profile # replace this with the extracted folder location
git init
git add README.md assets/
git commit -m "Add midnight-blush GitHub profile"
git branch -M main
git remote add origin https://github.com/yousra0425/yousra0425.git
git push -u origin main
```

If the repository already contains an initialized README, do not blindly run `git push` from a separate history; use the website upload flow or clone the existing repository first.

## Make it your own

- Profile introduction, project descriptions, tech stack, links: edit `README.md`.
- Main colors: find and replace the dark navy `#0A1028` and baby pink `#FFC3DC` in `assets/*.svg`; some secondary shades are also used.
- Hero text: `assets/banner.svg` has customizable name, tagline, and right-side code snippet.
- Original coding cat: `assets/pixel-kitty.svg`.
- Additional decoration: `assets/divider.svg`, `assets/terminal.svg`, `assets/loading.svg`, `assets/buttons.svg`, and `assets/footer.svg`.
- Typing animation uses https://github.com/DenverCoder1/readme-typing-svg. Modify the `lines=` query parameter in the image URL inside `README.md` (words separated with `+`, different sentences separated with `;`).
- Badges use https://shields.io/ and are external dynamic images.

## Notes

- SVG files use lightweight CSS animation; support can vary by platform and reduced-motion settings.
- Header and local assets do not require an external image-hosting service.
- `README.md` deliberately does not invent project repository links. Add links to your published repositories when you are ready.
- The `previews/` folder is optional; it is not referenced by the README.
