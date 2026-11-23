# Thermal & Data Center Air-Cooling LLM Wiki Schema

## Core Rules
- `wiki/` 為編譯知識層，依 `sources/`、`concepts/`、`methods/`、`experiments/`、`reviews/` 拆頁，並以 `[[wiki-links]]` 互連。
- 每次新增或更新來源後，自動同步更新 `index.md` 與 `log.md`。
- 產出教學 HTML 簡報（`index.html`）前，須檢核來源數量（至少 5 篇）、散熱層級定位與初學者可讀性。
