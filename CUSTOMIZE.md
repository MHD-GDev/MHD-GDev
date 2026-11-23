# Publishing your GitHub profile

This folder contains the profile README and its custom SVG artwork.

## Publish it

1. Open https://github.com/new.
2. Create a **Public** repository named exactly **MHD-GDev**.
3. Leave the repository empty: do not initialize it with a README, license, or .gitignore.
4. In a terminal, run:

    cd ~/Projects/GitHub-Profile
    git remote add origin git@github.com:MHD-GDev/MHD-GDev.git
    git push -u origin main

5. Refresh https://github.com/MHD-GDev.

## Included

- README.md — the profile page itself.
- assets/header.svg — custom animated graphite/aurora banner.
- assets/footer.svg — matching animated footer accent.

## Notes

- The profile README appears only when the repository is public, its name matches the account username, and README.md is at the repository root.
- Stats, typing, streak, and repository-card images are served by third-party services. If one is unavailable, the rest of the profile still works.
- The SVG banner is self-hosted in this repository, so it does not depend on an external banner generator.
- Update featured project links as your public repositories change.
