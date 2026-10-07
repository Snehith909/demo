# FindIt – AI Lost & Found (prototype)
Single-page app, no build step.

Run: open index.html in a browser, or `python3 -m http.server` and visit http://localhost:8000

- Matching: 0.5 appearance + 0.3 text + 0.1 location + 0.1 time (see score() in index.html)
- Data is stored in browser localStorage (demo only)
- Next: FastAPI + MongoDB backend, CLIP image embeddings, real auth, admin dashboard
