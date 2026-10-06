# Toolclove — privacy-first tools for AI, data and developer workflows

**Website: [toolclove.com](https://toolclove.com)**

Toolclove is a free collection of online tools that run **entirely in your browser**. Files are processed on your own device with WebAssembly and JavaScript and are **never uploaded**. No account, no signup, no watermarks.

> This repository is the public landing page and index for Toolclove. The site itself is closed-source.

## Highlights

### AI Data Lab — [toolclove.com/ai](https://toolclove.com/ai)
Cut LLM prompt tokens and generate schemas from JSON, locally.
- [JSON Token Optimizer](https://toolclove.com/ai/json-token-optimizer) — count tokens and compare JSON vs minified JSON, TOON, YAML, CSV and Markdown.
- TOON converter, JSON to Zod, JSON to Pydantic and a JSON structure analyzer.

### Dataset tools for computer vision — [toolclove.com/data](https://toolclove.com/data)
Validate and convert YOLO and COCO datasets without uploading images or labels.
- [Bounding Box Validator](https://toolclove.com/data/bounding-box-validator) — find bad boxes and labels.
- [COCO JSON Validator](https://toolclove.com/data/coco-validator) and [COCO to YOLO Converter](https://toolclove.com/data/coco-to-yolo).
- [Annotation Visualizer](https://toolclove.com/data/annotation-visualizer) — see YOLO and COCO labels drawn on images.
- [Class Distribution Analyzer](https://toolclove.com/data/class-distribution-analyzer) — check dataset balance.
- Dataset health checker, duplicate and leakage detection, image statistics.

### Developer tools — [toolclove.com/developer](https://toolclove.com/developer)
Everyday utilities for developers, running client-side.

### Also: PDF, image, video, security, text and finance tools
Merge/split/convert PDFs, compress and resize images, trim and caption videos, remove EXIF data, generate hashes and passwords — all in the browser.

## Why privacy-first?
- Processing happens on-device; each tool page states where its work happens.
- Lookup tools (such as DNS checks) send only the name you type, never a file.
- Limits come from your device's memory, not a server quota.

## Full tool list
### PDF tools
- [Edit PDF](https://toolclove.com/pdf/edit-pdf): Edit a PDF in your browser: add text, signatures and images, highlight, whiteout, rotate or delete pages. No uploads, no signup, no watermark.
- [Merge PDF](https://toolclove.com/pdf/merge-pdf): Combine multiple PDF files into a single document, in any order you choose. Runs entirely in your browser, with no uploads, no signup and no watermark.
- [Split PDF](https://toolclove.com/pdf/split-pdf): Split a PDF by page ranges, into fixed chunks, or into one file per page. Everything runs in your browser, with no uploads, signup or watermarks.
- [JPG to PDF](https://toolclove.com/pdf/jpg-to-pdf): Combine JPG, PNG and other images into a single PDF in your browser. Choose page size, order and quality. No uploads, no signup, no watermark.
- [PDF to JPG](https://toolclove.com/pdf/pdf-to-jpg): Convert PDF pages to JPG or PNG images at 72, 150 or 300 dpi. Runs entirely in your browser, with no uploads, no signup and no watermark.
- [PDF to Word](https://toolclove.com/pdf/pdf-to-word): Convert a PDF into an editable Word document, keeping its headings, paragraphs, alignment and lists. Scanned pages can be read with OCR. No upload, no signup.
### image tools
- [Beautify Screenshot](https://toolclove.com/image/beautify-screenshot): Add a gradient background, rounded corners and a shadow to any screenshot. Paste it straight in, and nothing is ever uploaded — it all happens on your device.
- [Compress Image](https://toolclove.com/image/compress-image): Compress images in your browser by quality or to an exact target size in KB. Batch compression with no uploads, no signup and no file limits.
- [Image to Text](https://toolclove.com/image/image-to-text): Extract text from any image in your browser. Screenshots, photos of documents, receipts and signs — nothing is uploaded, and it works offline after the first use.
- [Photo Editor & Design Studio](https://toolclove.com/image/photo-editor): Edit photos and design social posts, banners and thumbnails from templates. Filters, text effects, stickers and a background remover. Free, private, no watermark.
- [Background Remover](https://toolclove.com/image/remove-background): Remove the background from a photo in your browser. Compare before and after, crop, resize and save as PNG with transparency. Your photo is never uploaded.
- [Resize Image](https://toolclove.com/image/resize-image): Resize images by exact pixels, percentage or a ready-made preset. Batch resize in your browser with no uploads, no signup and no watermark.
- [Banner Maker](https://toolclove.com/image/banner-maker): Make website banners, Facebook and LinkedIn covers, YouTube channel art and display ads from templates. Add photos, text and shapes, then download free.
- [JPG to PNG](https://toolclove.com/image/jpg-to-png): Convert JPG images to PNG in your browser, one at a time or in batches. No uploads, no signup, no watermarks, and no limit on how many you convert.
- [PNG to JPG](https://toolclove.com/image/png-to-jpg): Convert PNG images to JPG in your browser with control over quality and the background colour behind transparent areas. No uploads and no signup.
- [Social Media Post Maker](https://toolclove.com/image/social-media-post-maker): Design Instagram posts and stories, Facebook, LinkedIn and Pinterest graphics from ready-made promo templates. Private, free and no watermark on downloads.
### video tools
- [Video Editor](https://toolclove.com/video/video-editor): Edit videos in your browser: merge clips, trim, change speed, fade, crop to 9:16 or 16:9, add captions and titles, export MP4. No upload, no watermark.
- [Add Subtitles to Video](https://toolclove.com/video/add-subtitles-to-video): Add subtitles to a video in your browser. Type captions, import an SRT or VTT file, or paste a script, pick a style and burn them in as MP4. Nothing is uploaded.
- [Add Text to Video](https://toolclove.com/video/add-text-to-video): Add text to a video online with ten animated templates — headlines, lower thirds, tags, neon, quotes and a subscribe button. Drag to place, export MP4. No upload.
- [Crop Video](https://toolclove.com/video/crop-video): Crop a video to 9:16, 16:9, 1:1 or 4:5 in your browser. Drag to choose what stays in frame, or fit it over a blurred background. No upload, no watermark.
- [Trim Video](https://toolclove.com/video/trim-video): Trim and cut videos online without uploading. Split at the playhead, drag clip ends to trim, delete parts and reorder the rest, then export MP4. No watermark.
### privacy and security tools
- [EXIF Remover](https://toolclove.com/security/exif-remover): Remove EXIF, GPS location and camera data from JPEG photos without re-encoding them. Shows what was hidden first. Nothing is uploaded.
- [Hash Generator](https://toolclove.com/security/hash-generator): Generate MD5, SHA-1, SHA-256, SHA-384 and SHA-512 hashes of text or any file, and verify a checksum you were given. Nothing is uploaded.
- [Password Generator](https://toolclove.com/security/password-generator): Generate strong random passwords, PINs and API tokens in your browser. Shows real entropy and crack time. Nothing is transmitted or stored.
- [Secret Scanner](https://toolclove.com/security/secret-scanner): Find leaked API keys, tokens, passwords and private keys in code, config and logs. Runs in your browser, so the secrets you check are never uploaded.
- [UUID Generator](https://toolclove.com/security/uuid-generator): Generate UUID v4, UUID v7 and short URL-safe IDs in bulk. Cryptographically random, produced in your browser and never transmitted.
- [Wi-Fi QR Code Generator](https://toolclove.com/security/wifi-qr-code): Create a Wi-Fi QR code that phones scan to join your network. Generated in your browser, so your network password is never transmitted.
- [HMAC Generator](https://toolclove.com/security/hmac-generator): Generate and verify HMAC signatures with SHA-256, SHA-384, SHA-512 or SHA-1. Runs in your browser, so your secret key is never transmitted.
- [Passphrase Generator](https://toolclove.com/security/passphrase-generator): Generate memorable passphrases from random words, with a real entropy figure. Runs in your browser, so nothing is transmitted or stored.
- [PDF Metadata Remover](https://toolclove.com/security/pdf-metadata-remover): Remove author, title, creator, producer and date metadata from PDF files. See what was there first. Runs in your browser with no uploads.
- [PII Scanner & Redaction](https://toolclove.com/security/pii-scanner): Scan text for emails, card numbers, IBANs, IP addresses and API keys, then redact them. Runs entirely in your browser with nothing uploaded.
### audio tools
- [Audio Cutter](https://toolclove.com/audio/cut-audio): Cut and trim audio in your browser. Keep a section or remove one, with a waveform to guide you. No uploads, no signup and no length limits.
- [MP3 to WAV](https://toolclove.com/audio/mp3-to-wav): Convert MP3 files to WAV in your browser. Lossless decoding, no upload, no signup and no length limit. Handles M4A, AAC, FLAC and OGG too.
- [Audio Waveform Generator](https://toolclove.com/audio/audio-waveform): Generate a waveform image from any audio file. Choose the size, colours, bar or line style and a transparent background, then export a PNG.
- [Audio Volume Normalizer](https://toolclove.com/audio/normalize-audio): Normalise audio volume in your browser. See the current peak and loudness, set a target level, and avoid clipping. Nothing is ever uploaded.
- [Remove Silence](https://toolclove.com/audio/remove-silence): Automatically detect and remove silent gaps from audio, with an adjustable threshold and padding. See how much will be cut before you commit.
### email tools
- [Email Header Analyzer](https://toolclove.com/email/header-analyzer): Analyse email headers to trace the delivery path, find slow hops and read the SPF, DKIM and DMARC verdicts. Runs in your browser, nothing uploaded.
- [Email Signature Generator](https://toolclove.com/email/signature-generator): Create a professional HTML email signature with a live preview. Table-based markup that works in Outlook. No signup, no tracking pixel, nothing uploaded.
- [Email to Text](https://toolclove.com/email/eml-to-text): Convert .eml email files to plain text in your browser. Decodes base64 and quoted-printable, lists attachments, and never uploads the message.
- [Email HTML Minifier](https://toolclove.com/email/html-minifier): Minify email HTML safely. Preserves Outlook conditional comments that ordinary minifiers destroy, and warns when you exceed Gmail clipping limits.
- [Email HTML Preview](https://toolclove.com/email/html-preview): Preview email HTML safely at different widths, with a plain-text fallback view. Renders in a sandboxed frame in your browser, with nothing uploaded.
### finance calculators
- [EMI Calculator](https://toolclove.com/finance/emi-calculator): Calculate your loan EMI, total interest and full repayment schedule. Free, instant, and calculated in your browser — your figures are never sent anywhere.
- [Mortgage Calculator](https://toolclove.com/finance/mortgage-calculator): Calculate your monthly mortgage payment including property tax, insurance and fees, plus total interest over the term. Runs in your browser, nothing uploaded.
- [Compound Interest Calculator](https://toolclove.com/finance/compound-interest): Calculate compound interest with regular deposits, any compounding frequency and a year-by-year breakdown. Runs in your browser, nothing is uploaded.
### developer tools
- [Code to Image](https://toolclove.com/developer/code-to-image): Paste code and get a syntax-highlighted image for a post, a slide or a README. Twelve languages, four themes, and nothing is ever sent to a server.
- [JSON Formatter](https://toolclove.com/developer/json-formatter): Format, validate and beautify JSON instantly in your browser. Get the exact line and column of any syntax error. Nothing is uploaded to a server.
- [JWT Decoder](https://toolclove.com/developer/jwt-decoder): Decode a JSON Web Token and read its header, claims and expiry. Optionally check the signature. The token never leaves your browser — nothing is uploaded.
- [Regex Explainer](https://toolclove.com/developer/regex-explainer): Paste a regular expression and read what it actually does, in plain English. Explains groups, quantifiers and lookarounds, and tests it against your own text.
- [Base64 Encoder & Decoder](https://toolclove.com/developer/base64): Encode and decode Base64 instantly in your browser. Handles Unicode, emoji, files and URL-safe output. Nothing you paste is ever sent to a server.
### text tools
- [AI Content Detector](https://toolclove.com/text/ai-content-detector): Check text for the patterns that mark AI writing: flat sentence rhythm, stock phrases, no contractions. Runs in your browser and shows its working.
- [Grammar Checker](https://toolclove.com/text/grammar-checker): Check grammar, spelling and style in your browser. Your writing never leaves your device, in five varieties of English, with no account and no upload.
- [AI Text Humanizer](https://toolclove.com/text/humanize-ai-text): Rewrite AI text to read like a person wrote it: cut filler openers, plain words, real contractions, no em dashes. In your browser, with a full change list.
- [Keyword Extractor](https://toolclove.com/text/keyword-extractor): Extract ranked keyphrases from any article, page or transcript. Finds multi-word phrases, not just common words, and runs entirely in your browser.
- [Word Counter](https://toolclove.com/text/word-counter): Count words, characters, sentences and paragraphs as you type. Includes reading time and keyword density. Your text stays in your browser, never uploaded.
### network tools
- [DNS Lookup](https://toolclove.com/network/dns-lookup): Look up A, AAAA, MX, TXT, NS, CNAME, CAA and SOA records for any domain in one go — with plain-English explanations and TTLs in words, not seconds.
- [What Is My IP?](https://toolclove.com/network/my-ip): See your IP address, network, location and connection details — and whether your browser settings match what your connection reveals. A quick VPN leak check.
- [Security Headers Check](https://toolclove.com/network/security-headers): Check any site’s security headers and get a graded report: CSP, HSTS, X-Frame-Options and the rest, each explained in plain English with what to do about it.
- [Internet Speed Test](https://toolclove.com/network/speed-test): Measure your download and upload speed, ping and jitter, and see what your connection is genuinely good for — 4K, video calls, big uploads.
- [Email Authentication Check](https://toolclove.com/network/spf-dkim-dmarc): Check a domain’s SPF, DKIM and DMARC records and find out whether it can be spoofed. Explains what each record does wrong, not just what it says.
### AI data tools
- [JSON to Pydantic Model Generator](https://toolclove.com/ai/json-to-pydantic): Generate Pydantic models from JSON samples: Optional and Literal fields, datetime and UUID types, snake_case aliases. Pydantic v2 or v1, Python 3.10+ or 3.9.
- [JSON to TOON Converter](https://toolclove.com/ai/json-to-toon): Convert JSON to TOON (Token-Oriented Object Notation) and TOON back to JSON with the official encoder. Comma, tab or pipe rows, token counts compared.
- [JSON to Zod Schema Generator](https://toolclove.com/ai/json-to-zod): Generate Zod schemas from JSON samples: optional and nullable fields, unions, enums, emails, UUIDs and dates detected. Zod 4 or 3 syntax, runs in your browser.
- [JSON Token Optimizer](https://toolclove.com/ai/json-token-optimizer): Count the tokens in JSON and compare it as minified JSON, TOON, YAML, CSV and Markdown. Exact GPT counts, optional clean-ups, nothing uploaded.
- [JSON Structure Analyzer](https://toolclove.com/ai/json-analyzer): Analyze a JSON document: depth, object and array counts, key frequency, null rates, giant strings and token cost, with tips to make it smaller. Runs locally.
### data tools
- [COCO to YOLO Converter](https://toolclove.com/data/coco-to-yolo): Convert COCO JSON to YOLO labels with a ready data.yaml. Boxes, polygons, RLE masks, OBB and keypoints, with category ids remapped. Runs in your browser.
- [Dataset Health Checker](https://toolclove.com/data/dataset-auditor): Audit a YOLO, COCO or Pascal VOC dataset in one go: labels, boxes, class balance, damaged files, duplicates and train/test leakage, with a health score.
- [Product Scraper](https://toolclove.com/data/product-scraper): Turn any shop listing into a spreadsheet, page by page. Finds the products on its own, pulls out names, prices and links, and exports to Excel or CSV.
- [YOLO to COCO Converter](https://toolclove.com/data/yolo-to-coco): Convert a YOLO dataset to COCO JSON in your browser. Reads image sizes, keeps your train/val splits, and handles detection, segmentation, OBB and pose labels.
- [YOLO Dataset Validator](https://toolclove.com/data/yolo-validator): Check a YOLO dataset for broken labels: wrong class ids, unnormalised boxes, bad lines, missing images and data.yaml mistakes. Detect, segment, OBB and pose.
- [Annotation Visualizer](https://toolclove.com/data/annotation-visualizer): View bounding boxes, polygons, masks, rotated boxes and keypoints on your images. Works with YOLO and COCO datasets, a folder, a ZIP or a single image.
- [Bounding Box Validator](https://toolclove.com/data/bounding-box-validator): Check every bounding box in a YOLO, COCO or VOC dataset: tiny, huge, duplicated, two-class and off-image boxes, each shown zoomed in. Download fixed labels.
- [Class Distribution Analyzer](https://toolclove.com/data/class-distribution-analyzer): Chart objects per class and per split for a YOLO, COCO or VOC dataset. Finds severe imbalance, rare and unused classes, and classes missing from validation.
- [COCO JSON Validator](https://toolclove.com/data/coco-validator): Validate a COCO annotation JSON: duplicate ids, missing images and categories, boxes outside the image, bad areas, RLE masks and keypoints. Nothing is uploaded.
- [Dataset Split Checker](https://toolclove.com/data/dataset-split-checker): Check a dataset for train/test leakage: identical and near-identical images across train, val and test, with a list to remove. YOLO, COCO and VOC. Runs locally.
- [Duplicate Image Finder](https://toolclove.com/data/duplicate-image-finder): Find exact and near-duplicate images in a dataset or photo folder using perceptual hashing. Grouped side by side, with a keep/remove list. Nothing uploaded.
- [Image Dataset Statistics](https://toolclove.com/data/image-dataset-statistics): Get statistics for an image dataset: resolutions, aspect ratios, megapixels, file sizes and formats, plus damaged and EXIF-rotated images. Nothing is uploaded.
### US location tools
- [ZIP Code Lookup](https://toolclove.com/location/zip-code-lookup): Look up any US ZIP code: city, county, FIPS, coordinates, plus population, median income and age from the Census. No account, nothing uploaded.
- [ZIP Code Radius Finder](https://toolclove.com/location/zip-code-radius): Find every US ZIP code within a radius of another. Filter by state, export as a comma list or CSV, and run it entirely in your own browser.
- [ZIP Code Validator and Cleaner](https://toolclove.com/location/zip-code-validator): Validate and clean a list of US ZIP codes in your browser. Restores the leading zeros Excel ate, splits ZIP+4, and appends city, state and county.
- [US Address Parser](https://toolclove.com/location/address-parser): Parse US addresses into separate fields — number, street, unit, city, state, ZIP. Bulk, in your browser, with no address database and no upload.
- [County FIPS Code Lookup](https://toolclove.com/location/fips-code-lookup): Look up US county FIPS codes by name or number, or convert a whole column at once. All 3,235 counties, in your browser, nothing uploaded.
- [US State Abbreviation Converter](https://toolclove.com/location/state-abbreviations): Convert US state names to two-letter codes and back, one at a time or a whole column. Handles Calif., N.Y., Mass. and the military codes.
- [Distance Between ZIP Codes](https://toolclove.com/location/zip-code-distance): Work out the distance between US ZIP codes in bulk. Paste two columns and get the miles for every row, with nothing leaving your browser.
### things to share
- [Circle Challenge](https://toolclove.com/fun/circle-challenge): Draw a circle by hand and find out how close to perfect it is. Free, no signup, works with a finger or a mouse, and runs entirely in your browser.
- [Your Life in Weeks](https://toolclove.com/fun/life-in-weeks): See your whole life as a grid of weeks, with the ones you have lived filled in. Your date of birth never leaves your device and is not stored anywhere.
- [Retro Poster Maker](https://toolclove.com/fun/retro-poster): Turn a name or a word into a retro poster — 80s retrowave, chrome, vapourwave, brutalist or arcade. Drawn in your browser, free, with no account and no upload.
- [Your Vibe as an Image](https://toolclove.com/fun/your-vibe): Answer four quick questions and get your vibe as a shareable card. No photo, no account, no upload — the whole thing runs in your browser.
### Blog
- [Toolclove Blog](https://toolclove.com/blog): Practical guides and how-tos, reviewed before publishing.
- [Blog sitemap](https://toolclove.com/blog/sitemap.xml): Every published article.
### About
- [About Toolclove](https://toolclove.com/about): Who runs the site and why the tools work locally.
- [Privacy policy](https://toolclove.com/privacy)
- [Terms of use](https://toolclove.com/terms)
- [All tools](https://toolclove.com/tools)

---

Links: [Website](https://toolclove.com) · [Blog](https://toolclove.com/blog) · [llms.txt](https://toolclove.com/llms.txt)

**Keywords:** privacy-first online tools, browser-based tools, LLM token optimizer, JSON to TOON, JSON to Zod, JSON to Pydantic, YOLO dataset validator, COCO to YOLO converter, bounding box validator, dataset health check, merge PDF online no upload, client-side tools, WebAssembly.
