# GenERP Theme

Tiny Frappe app that injects global CSS to restyle the Desk/Workspace.
The CSS is loaded via `app_include_css` in `hooks.py`.  
Refs: Frappe hooks & asset bundling docs.

Install on Frappe Cloud:
1) Sites → Apps → **Install from Git** (paste repo URL).
2) After install, **Rebuild Assets**.
3) Hard refresh your browser (Cmd/Ctrl+Shift+R).
