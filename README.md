# DHXbrochure
The business brochure of DHX webbing

## PDF downloads

The fixed download button follows the selected brochure language (English by default).
Original bilingual PDF files are served from `downloads/`:

| Language | File |
| --- | --- |
| Chinese + English | `DHXbrochure-zh_en.pdf` |
| Chinese + Indonesian | `DHXbrochure-zh_id.pdf` |
| Chinese + Vietnamese | `DHXbrochure-zh_vi.pdf` |
| Chinese + Malay | `DHXbrochure-zh_ma.pdf` |

`vercel.json` sets `Content-Disposition: attachment` on `/downloads/` so browsers
receive a file download. External download manager handling depends on the user's
browser and device settings. When replacing a PDF, update its displayed size in
`index.html` as well.
