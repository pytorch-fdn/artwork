# PyTorch Foundation Logos

This repository contains official artwork in standard formats for the **PyTorch Foundation**, its foundation-hosted projects, ecosystem projects, and working groups. Artwork is provided in commonly used formats such as **SVG** and **PNG**, and in multiple variants (for example: color, black, and white) where applicable.

With most modern browsers, you can right-click and copy the logo of your choice directly from the site. While PNG is widely used, **SVG files are recommended** whenever possible, as they are smaller in size, scale cleanly at any resolution, and are suitable for both print and high-resolution displays.

Use of the PyTorch Foundation name, logos, and related marks is subject to the trademark terms and usage guidelines described in [LICENSE.md](LICENSE.md). Unauthorized or improper use of these marks is prohibited.

For visual identity guidance, refer to the [PyTorch Brand Book (PDF)](https://github.com/pytorch-fdn/artwork/blob/main/pytorch_brand__book_web.pdf).

Visit the GitHub Pages artwork site:

https://pytorch-fdn.github.io/artwork/

---

## Updating Artwork & Submitting Pull Requests

Artwork updates and additions are managed through pull requests to this repository.

### PyTorch Foundation Logo Assets

PyTorch Foundation logo assets should be added under:

```txt
/assets/img/pytorch_foundation_logo
```

This includes:
- stacked logos
- horizontal logos
- SVG and PNG variants
- approved branding assets and variations

### Foundation-Hosted Projects

Foundation-hosted project artwork should be added under:

```txt
/projects/<ProjectName>
```

Example:

```txt
/projects/PyTorch
/projects/vLLM
/projects/DeepSpeed
```

Each foundation-hosted project should have its own dedicated directory containing:
- official logo assets
- SVG and/or PNG variants
- approved branding variations

---

## Pull Request Workflow

```txt
Add logo assets
        ↓
Update index.html project card
        ↓
Verify preview logo and links
        ↓
Submit pull request
        ↓
Review and approval
```

### Website Directory Updates

The GitHub Pages website directory is managed through:

```txt
/index.html
```

When adding a new foundation-hosted project:

- create the project directory under `/projects`
- add the approved logo assets
- add a new project card entry to `index.html`
- include a preview logo/icon for the website card display
- verify that all links and preview assets render correctly

Project cards should only be added or updated within the relevant section of `index.html`.

### Preview Logo Recommendations

Preview logos used for website cards should:
- preferably use SVG format
- use icon variants when available
- maintain transparent backgrounds where possible

For questions regarding artwork updates or branding usage, contact:

**[ops@pytorch.org](mailto:ops@pytorch.org)**

