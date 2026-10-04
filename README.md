# Priyank Modi's Responsive Portfolio Website
## Website URL: priyankmodipm.github.io

- The design is based on [Bedimcode](https://github.com/bedimcode)
- The resume is created on [FlowCV](https://flowcv.com/)
- The email service provider is [EmailJs](https://www.emailjs.com/)
- Contact form validations are added using [JavaScript](https://www.youtube.com/watch?v=fz8bwvn9lA4) 
- Normal alerts are replaced with Sweet Alert [SweetAlert](https://sweetalert.js.org)
- The favicon generator is [favicon.io](https://favicon.io/favicon-generator/)
- The Open Graph Meta Tags are added [Open Graph](https://ogp.me/)
- Videos are embedded from [YouTube](https://www.youtube.com)
- Presentations are  embedded from [Beautiful.ai](https://www.beautiful.ai)
- Added Google Tag script for [Google Analytics](https://analytics.google.com)

## Image-reading experiment

The experiment is isolated under `/image-reading/`, with nine independent
catalogue pages at `/image-reading/x/<instance-token>/`. Images and PDFs use
absolute AEM Dynamic Media original delivery URLs (`/original/as/`); no local
asset copies are required. Original renditions preserve the uploaded image
bytes and embedded XMP/IPTC/EXIF metadata. Do not replace them with resized
`/as/` renditions, which strip the metadata canaries used by the experiment.
The existing homepage, `assets-brand-visibility`, `channel-test`, and
`channel-test2` routes are unchanged.

Pages are generated from `experiments/image-reading/site/` in the AEM-LLMO
experiment worktree. When refreshing this route, copy only the generated
`index.html` and `x/` into `image-reading/`; do not replace the portfolio root,
its sitemap, or its robots policy. Prompt sheets must use
`https://priyankmodipm.github.io/image-reading` as their base URL.

<!-- ### Landing Page Light

![preview img](./assets/snaps/light.png)

### Landing Page Dark

![preview img](./assets/snaps/dark.png) -->
