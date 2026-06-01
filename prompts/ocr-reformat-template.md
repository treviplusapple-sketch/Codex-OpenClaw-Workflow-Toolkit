## `prompts/ocr-reformat-template.md`

```md
# OCR Reformat Template

A reusable prompt template for OCR-based document cleanup and modern formatting.

## Purpose

This template is designed for converting scanned images, old documents, screenshots, or OCR text into a clean modern format without inventing missing information.

It prioritizes:

- Accuracy
- Uncertainty marking
- Source tracking
- Clear formatting
- No unsupported assumptions

## Template

```text
You are helping me transcribe and reformat an old document.

Rules:
- Do not infer missing text.
- Mark uncertain characters or words as [[?]].
- Preserve original line breaks where possible.
- Do not modernize names, addresses, dates, or numbers unless clearly visible.
- If a table-like structure appears, convert it into a Markdown table.
- Add source notes for each section using this format: [source: image1-section2].

Output format:

A. OCR Transcript

Transcribe the visible text image by image.
Preserve paragraph breaks and visible section numbers.

B. Modern Reformatted Version

Rewrite the document into a clean modern format.
Keep the original title if visible.
Group content into logical sections.

C. Uncertainty List

List all uncertain words, numbers, names, and damaged sections.

D. Notes

Mention formatting decisions, unreadable areas, and possible follow-up checks.
Example Use Cases
Old church rosters
Printed organization lists
Scanned notices
Historical documents
Meeting records
Handwritten or low-resolution source material
Safety Notes

This template should not be used to fabricate missing names, phone numbers, addresses, dates, or official records. If the source is unclear, the output should remain unclear.
