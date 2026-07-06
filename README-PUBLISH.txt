TORII KADO WEBSITE v2.2.3.0 — REVISED
======================================

This is a complete static website. No build process, package manager or web server is required.

LOCAL PREVIEW
1. Double-click index.html, or run START-WEBSITE.bat.
2. All CSS and JavaScript are embedded in index.html.
3. Images and downloads use relative paths under assets/ and downloads/.

GITHUB PAGES
1. Upload every file and folder in this directory to the ROOT of the repository.
2. Keep .nojekyll in the root.
3. In GitHub: Settings > Pages > Deploy from a branch > main / root.
4. Do not upload index.html without the assets and downloads folders.

REVISED CONTENT
- Website palette matches the supplied Torii Kado app: #0d1117, #111720, #1f6feb, #388bfd and #58a6ff.
- Six interface screenshots were freshly captured from the supplied v2.2.3.0 Qt application.
- Eight English demo pages were loaded into a real Torii Kado project and rendered through its correction/editor lettering pipeline.
- The gallery defaults to the app-rendered pages and can switch to the matching Japanese originals.
- Three same-page comparison demos use aligned source and output crops.

FILES
- index.html: complete interactive website
- .nojekyll: prevents GitHub Pages/Jekyll from ignoring assets
- assets/: app screenshots, icon, original and app-rendered manga demos
- downloads/: installer, complete package, source archive and SHA-256 checksums
- TEST-REPORT.txt: validation results and execution limits
- browser-qa.json: desktop/mobile interaction checks
- START-WEBSITE.bat: Windows launcher for local preview

IMPORTANT
The app's separate automatic OCR + Ollama stage needs its Windows backend and local model. Those dependencies were not available in the Linux build environment used for this website revision, so the demo does not falsely claim that stage was executed here. The English pages were cleaned, boxed and lettered with Torii Kado's actual project/editor renderer and displayed inside the real app.
