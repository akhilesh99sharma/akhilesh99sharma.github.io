Research page pictures
======================

Drop a picture here and it shows on the matching entry of the Research page.
No code change is needed. Rebuild (or restart `npm run dev`) after adding a file.

NAMING
  Name the file after the entry id, plus the extension:

    <entry-id>.png   or   .jpg   or   .jpeg   or   .webp

  If several exist for one entry, the first of png, jpg, jpeg, webp is used.
  An entry with no file stays text-only.

ENTRY IDS (see getResearchWork() in src/content/research.ts)
  maize-gxe
  root-segmentation
  longitudinal-water-stress
  weed-control-rating
  early-herbicide-response
  weed-seed-identification
  yolov9-preemergence-postemergence-efficacy
  multi-species-detector-benchmark
  palmer-amaranth-detector-benchmark

  Example: public/images/research/root-segmentation.jpg

SIZE
  Every picture is shown in a 2:1 (wide) box, about 260 px wide on a 1672 px screen.
  Use a wide image around 1040 x 520 px (2:1), under ~300 KB. Other shapes are cropped to
  fit the box, so keep the important part near the centre.

BEFORE YOU ADD ONE
  Only use figures you own and are allowed to share. Do not use figures from Bayer work
  unless it has been approved, and do not use placeholder or invented images.
  Add a meaningful picture to most entries, not just one or two, so the list looks even.

NOTE
  Files in this folder are public on the website, including this note.