/* ============================================================
   ConstructMS — Shared Stylesheet
   style.css  (used by index.html for all views/pages)
   ============================================================ */

/* ── CSS VARIABLES ── */
:root {
  --white: #ffffff;
  --off-white: #f8f7f4;
  --surface: #f0eeea;
  --border: #e2dfd8;
  --text: #1a1814;
  --text-muted: #7a7670;
  --text-light: #b0ada8;
  --accent: #e85d26;
  --accent-light: #ff7a45;
  --accent-bg: #fff3ee;
  --blue: #2563eb;
  --blue-bg: #eff6ff;
  --green: #16a34a;
  --green-bg: #f0fdf4;
  --amber: #d97706;
  --amber-bg: #fffbeb;
  --purple: #7c3aed;
  --purple-bg: #f5f3ff;
  --red: #dc2626;
  --red-bg: #fef2f2;
  --teal: #0891b2;
  --teal-bg: #ecfeff;
  --shadow-sm: 0 1px 3px rgba(0,0,0,0.06), 0 1px 2px rgba(0,0,0,0.04);
  --shadow: 0 4px 16px rgba(0,0,0,0.08), 0 2px 6px rgba(0,0,0,0.04);
  --shadow-lg: 0 20px 60px rgba(0,0,0,0.12), 0 8px 24px rgba(0,0,0,0.06);
  --radius: 12px;
  --radius-lg: 20px;
  --radius-xl: 28px;
}

/* ── RESET ── */
* { box-sizing: border-box; margin: 0; padding: 0; }
body {
  font-family: 'Plus Jakarta Sans', sans-serif;
  background: var(--off-white);
  color: var(--text);
  min-height: 100vh;
  overflow-x: hidden;
}

/* ── PAGES (views) ── */
.page { display: none; }
.page.active { display: block; }

/* ── TOPBAR ── */
.topbar {
  background: var(--white);
  border-bottom: 1px solid var(--border);
  padding: 0 32px; height: 64px;
  display: flex; align-items: center; justify-content: space-between;
  position: sticky; top: 0; z-index: 100;
  box-shadow: var(--shadow-sm);
}
.topbar-left  { display: flex; align-items: center; gap: 20px; }
.topbar-right { display: flex; align-items: center; gap: 12px; }
.back-btn {
  display: flex; align-items: center; gap: 8px;
  padding: 8px 14px; background: var(--off-white);
  border: 1px solid var(--border); border-radius: 8px;
  cursor: pointer; font-size: 13px; font-weight: 500;
  color: var(--text-muted); text-decoration: none; transition: all 0.15s;
}
.back-btn:hover { border-color: var(--accent); color: var(--accent); }
.topbar-brand { display: flex; align-items: center; gap: 10px; }
.brand-icon {
  width: 36px; height: 36px; background: var(--accent); border-radius: 10px;
  display: flex; align-items: center; justify-content: center;
  font-family: 'Fraunces', serif; font-weight: 900; font-size: 14px; color: white;
}
.brand-icon.blue   { background: var(--blue); }
.brand-icon.green  { background: var(--green); }
.brand-name { font-family: 'Fraunces', serif; font-weight: 700; font-size: 16px; }
.page-breadcrumb { display: flex; align-items: center; gap: 8px; font-size: 13px; color: var(--text-muted); }
.breadcrumb-sep { opacity: 0.4; }
.breadcrumb-current { color: var(--text); font-weight: 600; }

/* ── SYNC PILL ── */
.sync-pill {
  display: flex; align-items: center; gap: 7px;
  background: var(--green-bg); border: 1px solid rgba(22,163,74,0.2);
  color: var(--green); padding: 6px 14px; border-radius: 100px;
  font-size: 12px; font-weight: 600; cursor: pointer; transition: all 0.15s;
}
.sync-pill.blue { background: var(--blue-bg); border-color: rgba(37,99,235,0.2); color: var(--blue); }
.sync-pill.orange { background: var(--accent-bg); border-color: rgba(232,93,38,0.2); color: var(--accent); }
.sync-dot { width: 6px; height: 6px; background: currentColor; border-radius: 50%; animation: pulse 2s infinite; }

/* ── BODY WRAP (sidebar + main) ── */
.body-wrap {
  display: grid;
  grid-template-columns: 260px 1fr;
  min-height: calc(100vh - 64px);
}

/* ── SIDEBAR ── */
.sidebar {
  background: var(--white); border-right: 1px solid var(--border);
  padding: 28px 20px; display: flex; flex-direction: column; gap: 4px;
  position: sticky; top: 64px; height: calc(100vh - 64px); overflow-y: auto;
}
.sidebar-section {
  font-size: 10px; font-weight: 700; color: var(--text-light);
  letter-spacing: 1.5px; text-transform: uppercase; padding: 14px 10px 6px;
}
.sidebar-section:first-child { padding-top: 4px; }
.nav-item {
  display: flex; align-items: center; gap: 10px;
  padding: 10px 12px; border-radius: 10px; cursor: pointer;
  text-decoration: none; font-size: 13px; font-weight: 500;
  color: var(--text-muted); transition: all 0.15s; border: 1px solid transparent;
}
.nav-item:hover { background: var(--off-white); color: var(--text); }
.nav-item.active { background: var(--accent-bg); color: var(--accent); border-color: rgba(232,93,38,0.15); font-weight: 600; }
.nav-item.active.blue   { background: var(--blue-bg);  color: var(--blue);  border-color: rgba(37,99,235,0.15); }
.nav-item.active.green  { background: var(--green-bg); color: var(--green); border-color: rgba(22,163,74,0.15); }
.nav-item-icon { font-size: 16px; width: 22px; text-align: center; }
.nav-badge { margin-left: auto; border-radius: 100px; padding: 2px 8px; font-size: 10px; font-weight: 700; }
.nav-badge.green  { background: var(--green-bg); color: var(--green); }
.nav-badge.orange { background: var(--accent-bg); color: var(--accent); }
.nav-badge.amber  { background: var(--amber-bg); color: var(--amber); }
.nav-badge.red    { background: var(--red-bg); color: var(--red); }
.sidebar-stats { margin-top: auto; padding-top: 20px; border-top: 1px solid var(--border); }
.sidebar-stats-title { font-size: 10px; font-weight: 700; color: var(--text-light); letter-spacing: 1px; text-transform: uppercase; margin-bottom: 12px; }
.stat-row { display: flex; justify-content: space-between; font-size: 12px; margin-bottom: 10px; }
.stat-row:last-child { margin-bottom: 0; }
.stat-row span { color: var(--text-muted); }
.stat-row strong { font-weight: 700; }

/* ── MAIN CONTENT ── */
.main-content { padding: 32px 40px; overflow-y: auto; }
.page-header { display: flex; align-items: flex-start; justify-content: space-between; margin-bottom: 32px; }
.page-eyebrow { font-size: 11px; font-weight: 700; color: var(--accent); letter-spacing: 1.5px; text-transform: uppercase; margin-bottom: 6px; }
.page-eyebrow.blue  { color: var(--blue); }
.page-eyebrow.green { color: var(--green); }
.page-title { font-family: 'Fraunces', serif; font-size: 32px; font-weight: 900; letter-spacing: -1px; margin-bottom: 6px; }
.page-desc  { font-size: 14px; color: var(--text-muted); }
.page-actions { display: flex; gap: 10px; align-items: center; }

/* ── BUTTONS ── */
.btn {
  display: inline-flex; align-items: center; gap: 8px;
  padding: 10px 20px; border-radius: 10px;
  font-size: 13px; font-weight: 600; cursor: pointer; border: none;
  font-family: 'Plus Jakarta Sans', sans-serif; transition: all 0.15s;
  text-decoration: none;
}
.btn-primary { background: var(--accent); color: white; }
.btn-primary:hover { background: var(--accent-light); box-shadow: 0 6px 20px rgba(232,93,38,0.3); transform: translateY(-1px); }
.btn-primary.blue  { background: var(--blue); }
.btn-primary.blue:hover { background: #1d4ed8; box-shadow: 0 6px 20px rgba(37,99,235,0.3); }
.btn-primary.green { background: var(--green); }
.btn-primary.green:hover { background: #15803d; box-shadow: 0 6px 20px rgba(22,163,74,0.3); }
.btn-ghost { background: var(--white); color: var(--text); border: 1.5px solid var(--border); }
.btn-ghost:hover { border-color: var(--accent); color: var(--accent); }
.btn-sm { padding: 6px 12px; font-size: 11px; }

/* ── TABLE CARD ── */
.table-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--radius-lg); overflow: hidden;
  box-shadow: var(--shadow-sm); margin-bottom: 28px;
}
.table-header {
  padding: 18px 24px; border-bottom: 1px solid var(--border);
  display: flex; align-items: center; justify-content: space-between; gap: 12px; flex-wrap: wrap;
}
.table-title { font-size: 15px; font-weight: 700; }
.table-count { background: var(--blue-bg); color: var(--blue); border-radius: 100px; padding: 3px 10px; font-size: 11px; font-weight: 700; }
.table-scroll { overflow-x: auto; }
table { width: 100%; border-collapse: collapse; }
thead th {
  padding: 11px 14px; text-align: left;
  font-size: 10px; font-weight: 700; color: var(--text-light);
  letter-spacing: 0.8px; text-transform: uppercase;
  background: var(--off-white); border-bottom: 1px solid var(--border); white-space: nowrap;
}
tbody td {
  padding: 12px 14px; font-size: 12px; color: var(--text);
  border-bottom: 1px solid var(--border); vertical-align: middle; white-space: nowrap;
}
tbody tr:last-child td { border-bottom: none; }
tbody tr:hover td { background: var(--off-white); }

/* ── TAGS ── */
.tag { display: inline-flex; align-items: center; padding: 3px 9px; border-radius: 100px; font-size: 10px; font-weight: 700; white-space: nowrap; }
.tag.green  { background: var(--green-bg);  color: var(--green); }
.tag.amber  { background: var(--amber-bg);  color: var(--amber); }
.tag.blue   { background: var(--blue-bg);   color: var(--blue); }
.tag.red    { background: var(--red-bg);    color: var(--red); }
.tag.orange { background: var(--accent-bg); color: var(--accent); }
.tag.purple { background: var(--purple-bg); color: var(--purple); }
.tag.teal   { background: var(--teal-bg);   color: var(--teal); }

/* ── PROGRESS BAR ── */
.prog-wrap { background: var(--border); border-radius: 100px; height: 5px; overflow: hidden; min-width: 70px; margin-top: 4px; }
.prog-fill { height: 100%; border-radius: 100px; transition: width 0.6s ease; }
.prog-fill.orange { background: var(--accent); }
.prog-fill.red    { background: var(--red); }
.prog-fill.green  { background: var(--green); }
.prog-fill.blue   { background: var(--blue); }

/* ── FORM CARD ── */
.form-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--radius-lg); overflow: hidden; margin-bottom: 24px; box-shadow: var(--shadow-sm);
}
.form-card-header {
  padding: 20px 28px; border-bottom: 1px solid var(--border);
  display: flex; align-items: center; gap: 12px; background: var(--off-white);
}
.card-header-icon { width: 40px; height: 40px; border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 18px; }
.card-header-icon.orange { background: var(--accent-bg); }
.card-header-icon.blue   { background: var(--blue-bg); }
.card-header-icon.green  { background: var(--green-bg); }
.card-header-title { font-size: 15px; font-weight: 700; margin-bottom: 2px; }
.card-header-sub   { font-size: 12px; color: var(--text-muted); }
.form-body { padding: 28px; }

/* ── FIELD GRID ── */
.fields-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; margin-bottom: 18px; }
.fields-grid.cols1 { grid-template-columns: 1fr; }
.fields-grid.cols3 { grid-template-columns: 1fr 1fr 1fr; }
.fields-grid.cols4 { grid-template-columns: 1fr 1fr 1fr 1fr; }
.fields-grid.cols5 { grid-template-columns: 1fr 1fr 1fr 1fr 1fr; }
.field { display: flex; flex-direction: column; gap: 7px; }
.field.full { grid-column: 1 / -1; }
.field-label { font-size: 10px; font-weight: 700; color: var(--text-muted); letter-spacing: 0.8px; text-transform: uppercase; }
.field-label .req { color: var(--accent); margin-left: 2px; }

/* ── INPUTS ── */
.input-wrap { position: relative; }
.field-input, .field-select, .field-textarea {
  width: 100%; padding: 10px 14px;
  background: var(--off-white); border: 1.5px solid var(--border);
  border-radius: 10px; font-family: 'Plus Jakarta Sans', sans-serif;
  font-size: 13px; color: var(--text); outline: none; transition: all 0.2s; appearance: none;
  text-transform: uppercase;
}
.field-input::placeholder { color: var(--text-light); text-transform: none; }
.field-input:focus, .field-select:focus, .field-textarea:focus {
  border-color: var(--accent); background: var(--white);
  box-shadow: 0 0 0 4px rgba(232,93,38,0.08);
}
input[type="date"], input[type="number"], input[type="tel"] { text-transform: none !important; }
.field-textarea { resize: vertical; min-height: 72px; }
.field-select {
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='%237a7670' stroke-width='2'%3E%3Cpath d='M6 9l6 6 6-6'/%3E%3C/svg%3E");
  background-repeat: no-repeat; background-position: right 12px center; padding-right: 36px;
  text-transform: none;
}
.input-prefix { position: absolute; left: 12px; top: 50%; transform: translateY(-50%); font-size: 13px; font-weight: 600; color: var(--text-muted); pointer-events: none; }
.has-prefix .field-input { padding-left: 28px; }

/* ── AUTO DISPLAY FIELD ── */
.field-auto {
  width: 100%; padding: 10px 14px;
  background: var(--blue-bg); border: 1.5px solid rgba(37,99,235,0.2);
  border-radius: 10px; font-size: 12px; color: var(--blue); font-weight: 700;
  cursor: default; user-select: all; letter-spacing: 0.3px;
  min-height: 40px; display: flex; align-items: center;
}
.field-auto.green { background: var(--green-bg); border-color: rgba(22,163,74,0.25); color: var(--green); }
.auto-badge {
  display: inline-flex; align-items: center; gap: 4px; padding: 2px 7px;
  background: var(--blue-bg); color: var(--blue); border-radius: 100px;
  font-size: 9px; font-weight: 700; letter-spacing: 0.5px; text-transform: uppercase;
  margin-left: 6px; vertical-align: middle;
}

/* ── SECTION DIVIDER ── */
.section-divider { display: flex; align-items: center; gap: 12px; margin: 22px 0 18px; }
.sd-line  { flex: 1; height: 1px; background: var(--border); }
.sd-label { font-size: 10px; font-weight: 700; color: var(--text-light); letter-spacing: 1px; text-transform: uppercase; white-space: nowrap; }

/* ── FORM FOOTER ── */
.form-footer {
  padding: 18px 28px; border-top: 1px solid var(--border); background: var(--off-white);
  display: flex; align-items: center; justify-content: space-between; gap: 12px;
}
.footer-hint { font-size: 11px; color: var(--text-light); display: flex; align-items: center; gap: 6px; }

/* ── LOCKED FIELDS ── */
.field-input:disabled, .field-select:disabled, .field-textarea:disabled {
  opacity: 0.42; cursor: not-allowed;
  background: var(--border) !important; border-color: var(--border) !important; box-shadow: none !important;
}
.edit-lock-banner {
  background: var(--amber-bg); border: 1.5px solid var(--amber); color: #92400e;
  padding: 12px 16px; border-radius: 10px; font-size: 12px; font-weight: 600;
  margin-bottom: 20px; display: flex; align-items: center; gap: 10px; line-height: 1.5;
}

/* ── SEARCH INPUT ── */
.search-input {
  padding: 7px 14px; background: var(--off-white); border: 1px solid var(--border);
  border-radius: 8px; font-size: 12px; font-family: inherit; outline: none; width: 240px;
}
.search-input:focus { border-color: var(--accent); }
.filter-select {
  padding: 6px 10px; background: var(--off-white); border: 1px solid var(--border);
  border-radius: 8px; font-size: 12px; font-family: inherit; outline: none; color: var(--text);
}
.filter-bar { display: flex; align-items: center; gap: 8px; }

/* ── SUMMARY STRIP ── */
.summary-strip { display: grid; gap: 14px; margin-bottom: 24px; }
.summary-strip.cols5 { grid-template-columns: repeat(5, 1fr); }
.summary-strip.cols4 { grid-template-columns: repeat(4, 1fr); }
.sum-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--radius); padding: 16px 18px; box-shadow: var(--shadow-sm);
}
.sum-label { font-size: 10px; font-weight: 700; color: var(--text-light); text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 6px; }
.sum-val { font-family: 'Fraunces', serif; font-size: 22px; font-weight: 900; letter-spacing: -0.5px; }
.sum-val.green  { color: var(--green); }
.sum-val.orange { color: var(--accent); }
.sum-val.amber  { color: var(--amber); }
.sum-val.red    { color: var(--red); }
.sum-val.blue   { color: var(--blue); }

/* ── AMOUNT PREVIEW ── */
.amount-preview {
  background: linear-gradient(135deg, var(--green-bg), rgba(22,163,74,0.05));
  border: 1.5px solid rgba(22,163,74,0.25); border-radius: 12px;
  padding: 16px 20px; display: flex; align-items: center; justify-content: space-between; margin-bottom: 18px;
}
.ap-label { font-size: 12px; font-weight: 600; color: var(--text-muted); }
.ap-val { font-family: 'Fraunces', serif; font-size: 26px; font-weight: 900; color: var(--green); letter-spacing: -0.5px; }

/* ── KPI GRID (Dashboard) ── */
.kpi-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; margin-bottom: 24px; }
.kpi-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--radius-lg); padding: 22px; position: relative; overflow: hidden;
  transition: all 0.2s; box-shadow: var(--shadow-sm);
}
.kpi-card:hover { box-shadow: var(--shadow); transform: translateY(-2px); }
.kpi-card::before {
  content: ''; position: absolute; top: 0; left: 0; right: 0;
  height: 3px; border-radius: var(--radius-lg) var(--radius-lg) 0 0;
}
.kpi-card.orange::before { background: var(--accent); }
.kpi-card.blue::before   { background: var(--blue); }
.kpi-card.red::before    { background: var(--red); }
.kpi-card.green::before  { background: var(--green); }
.kpi-icon { width: 40px; height: 40px; border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 18px; margin-bottom: 14px; }
.kpi-icon.orange { background: var(--accent-bg); }
.kpi-icon.blue   { background: var(--blue-bg); }
.kpi-icon.red    { background: var(--red-bg); }
.kpi-icon.green  { background: var(--green-bg); }
.kpi-label { font-size: 11px; font-weight: 600; color: var(--text-muted); text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 8px; }
.kpi-value { font-family: 'Fraunces', serif; font-size: 28px; font-weight: 900; letter-spacing: -1px; margin-bottom: 8px; }
.kpi-value.orange { color: var(--accent); }
.kpi-value.blue   { color: var(--blue); }
.kpi-value.red    { color: var(--red); }
.kpi-value.green  { color: var(--green); }
.kpi-change { font-size: 12px; display: flex; align-items: center; gap: 4px; font-weight: 500; }
.kpi-change.up   { color: var(--green); }
.kpi-change.down { color: var(--red); }
.kpi-change.neutral { color: var(--text-muted); }

/* ── DASHBOARD GRIDS ── */
.grid-2     { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 20px; }
.grid-60-40 { display: grid; grid-template-columns: 1.5fr 1fr; gap: 20px; margin-bottom: 20px; }
.card { background: var(--white); border: 1px solid var(--border); border-radius: var(--radius-lg); overflow: hidden; box-shadow: var(--shadow-sm); }
.card-header { padding: 18px 22px; border-bottom: 1px solid var(--border); display: flex; align-items: center; justify-content: space-between; }
.card-title { font-size: 14px; font-weight: 700; }
.card-action { font-size: 12px; color: var(--accent); font-weight: 600; cursor: pointer; text-decoration: none; }
.card-body  { padding: 20px 22px; }

/* ── P&L ROWS ── */
.pl-row { display: flex; align-items: center; justify-content: space-between; padding: 12px 0; border-bottom: 1px solid var(--border); }
.pl-row:last-child { border-bottom: none; }
.pl-row.total { border-top: 2px solid var(--border); border-bottom: none; padding-top: 16px; margin-top: 4px; }
.pl-label { font-size: 13px; color: var(--text-muted); }
.pl-label.bold { font-size: 14px; font-weight: 700; color: var(--text); }
.pl-amount { font-size: 14px; font-weight: 700; }
.pl-amount.cr { color: var(--green); }
.pl-amount.dr { color: var(--red); }
.pl-amount.big { font-family: 'Fraunces', serif; font-size: 22px; color: var(--green); }

/* ── COST BARS ── */
.cost-bar-item { margin-bottom: 16px; }
.cost-bar-item:last-child { margin-bottom: 0; }
.cost-bar-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 6px; }
.cost-bar-label { font-size: 13px; font-weight: 500; display: flex; align-items: center; gap: 8px; }
.cost-bar-dot { width: 8px; height: 8px; border-radius: 50%; }
.cost-bar-pct { font-size: 12px; font-weight: 700; }
.cost-bar-pct.orange { color: var(--accent); }
.cost-bar-pct.blue   { color: var(--blue); }
.cost-bar-pct.green  { color: var(--green); }
.cost-bar-pct.purple { color: var(--purple); }

/* ── SITE USAGE ── */
.site-row { padding: 14px 0; border-bottom: 1px solid var(--border); }
.site-row:last-child { border-bottom: none; }
.site-row-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 8px; }
.site-name { font-size: 13px; font-weight: 600; }
.site-pct  { font-size: 12px; font-weight: 700; }

/* ── ALERTS ── */
.alert-item { display: flex; align-items: flex-start; gap: 12px; padding: 14px 0; border-bottom: 1px solid var(--border); }
.alert-item:last-child { border-bottom: none; }
.alert-icon  { font-size: 20px; margin-top: 2px; }
.alert-title { font-size: 13px; font-weight: 600; margin-bottom: 3px; }
.alert-desc  { font-size: 12px; color: var(--text-muted); }

/* ── FLOW STEPS ── */
.flow-wrap { display: flex; align-items: center; flex-wrap: wrap; gap: 8px; padding: 4px 0; }
.flow-step { flex: 1; display: flex; flex-direction: column; align-items: center; text-align: center; padding: 14px 12px; border-radius: var(--radius); min-width: 90px; }
.flow-step-num   { font-size: 10px; font-weight: 700; letter-spacing: 1px; text-transform: uppercase; opacity: 0.6; margin-bottom: 4px; }
.flow-step-icon  { font-size: 22px; margin-bottom: 6px; }
.flow-step-label { font-size: 12px; font-weight: 700; }
.flow-step-sub   { font-size: 10px; opacity: 0.65; margin-top: 2px; }
.flow-arrow { color: var(--border); font-size: 20px; }
.fs-orange { background: var(--accent-bg); border: 1px solid rgba(232,93,38,0.2); color: var(--accent); }
.fs-blue   { background: var(--blue-bg);   border: 1px solid rgba(37,99,235,0.2);   color: var(--blue); }
.fs-green  { background: var(--green-bg);  border: 1px solid rgba(22,163,74,0.2);  color: var(--green); }
.fs-teal   { background: var(--teal-bg);   border: 1px solid rgba(8,145,178,0.2);   color: var(--teal); }

/* ── EMPTY STATE ── */
.empty-state { text-align: center; padding: 48px 20px; }
.empty-icon  { font-size: 36px; margin-bottom: 10px; opacity: 0.4; }
.empty-text  { font-size: 13px; color: var(--text-muted); }

/* ── TOAST ── */
.toast {
  position: fixed; bottom: 28px; right: 28px;
  padding: 14px 20px; border-radius: var(--radius);
  font-size: 13px; font-weight: 600; display: flex; align-items: center; gap: 10px;
  box-shadow: var(--shadow-lg); transform: translateY(80px); opacity: 0;
  transition: all 0.35s cubic-bezier(0.34,1.56,0.64,1); z-index: 999; min-width: 240px;
}
.toast.show { transform: translateY(0); opacity: 1; }
.toast.success { background: var(--text); color: white; }
.toast.error   { background: var(--red); color: white; }
.toast.info    { background: var(--blue); color: white; }

/* ── LOGIN PAGE ── */
.login-page-wrap { display: grid; grid-template-columns: 1fr 1fr; min-height: 100vh; }
.left-panel {
  background: var(--text); padding: 48px 56px;
  display: flex; flex-direction: column; justify-content: space-between;
  position: relative; overflow: hidden;
}
.left-panel::before {
  content: ''; position: absolute; top: -120px; right: -80px;
  width: 400px; height: 400px;
  background: radial-gradient(circle, rgba(232,93,38,0.25) 0%, transparent 70%);
  pointer-events: none;
}
.left-panel::after {
  content: ''; position: absolute; bottom: -80px; left: -60px;
  width: 300px; height: 300px;
  background: radial-gradient(circle, rgba(37,99,235,0.2) 0%, transparent 70%);
  pointer-events: none;
}
.brand-lg { display: flex; align-items: center; gap: 14px; position: relative; z-index: 1; }
.brand-icon-lg {
  width: 48px; height: 48px; background: var(--accent); border-radius: 14px;
  display: flex; align-items: center; justify-content: center;
  font-family: 'Fraunces', serif; font-weight: 900; font-size: 18px; color: white; letter-spacing: -1px;
}
.brand-name-lg { font-family: 'Fraunces', serif; font-weight: 700; font-size: 22px; color: white; }
.brand-tag { font-size: 11px; color: rgba(255,255,255,0.45); margin-top: 2px; }
.hero-text { position: relative; z-index: 1; }
.hero-label {
  display: inline-flex; align-items: center; gap: 8px;
  background: rgba(232,93,38,0.15); border: 1px solid rgba(232,93,38,0.3); color: var(--accent-light);
  padding: 6px 14px; border-radius: 100px; font-size: 12px; font-weight: 600;
  letter-spacing: 0.5px; text-transform: uppercase; margin-bottom: 24px;
}
.hero-label::before { content: ''; width: 6px; height: 6px; background: var(--accent-light); border-radius: 50%; animation: blink 2s infinite; }
.hero-heading { font-family: 'Fraunces', serif; font-size: 52px; font-weight: 900; line-height: 1.05; letter-spacing: -2px; color: white; margin-bottom: 20px; }
.hero-heading em { font-style: italic; color: var(--accent-light); }
.hero-sub { font-size: 15px; color: rgba(255,255,255,0.5); line-height: 1.7; max-width: 380px; }
.stats-row { display: flex; gap: 32px; position: relative; z-index: 1; }
.stat-val { font-family: 'Fraunces', serif; font-size: 32px; font-weight: 900; color: white; letter-spacing: -1px; }
.stat-label { font-size: 12px; color: rgba(255,255,255,0.4); margin-top: 2px; }
.stat-divider { width: 1px; background: rgba(255,255,255,0.1); }
.feature-pills { display: flex; flex-wrap: wrap; gap: 8px; position: relative; z-index: 1; }
.pill {
  display: flex; align-items: center; gap: 6px;
  background: rgba(255,255,255,0.07); border: 1px solid rgba(255,255,255,0.1);
  color: rgba(255,255,255,0.6); padding: 7px 14px; border-radius: 100px; font-size: 12px; font-weight: 500;
}
.right-panel { padding: 48px 56px; display: flex; flex-direction: column; justify-content: center; background: var(--white); }
.form-header { margin-bottom: 36px; }
.form-title  { font-family: 'Fraunces', serif; font-size: 34px; font-weight: 900; letter-spacing: -1.5px; color: var(--text); margin-bottom: 8px; }
.form-subtitle { font-size: 14px; color: var(--text-muted); }
.quick-nav { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 36px; }
.nav-card {
  display: flex; align-items: center; gap: 12px; padding: 16px 18px;
  border: 1.5px solid var(--border); border-radius: var(--radius); cursor: pointer;
  text-decoration: none; transition: all 0.2s ease; background: var(--white);
}
.nav-card:hover { border-color: var(--accent); background: var(--accent-bg); transform: translateY(-2px); box-shadow: var(--shadow); }
.nav-card-icon { width: 42px; height: 42px; border-radius: 10px; display: flex; align-items: center; justify-content: center; font-size: 20px; flex-shrink: 0; }
.nav-card-icon.orange { background: var(--accent-bg); }
.nav-card-icon.blue   { background: var(--blue-bg); }
.nav-card-icon.green  { background: var(--green-bg); }
.nav-card-icon.purple { background: var(--purple-bg); }
.nav-card-title { font-size: 14px; font-weight: 700; color: var(--text); margin-bottom: 2px; }
.nav-card-sub   { font-size: 11px; color: var(--text-muted); }
.divider { display: flex; align-items: center; gap: 16px; margin: 28px 0; }
.divider-line { flex: 1; height: 1px; background: var(--border); }
.divider-text { font-size: 12px; color: var(--text-light); font-weight: 500; }
.login-form { display: flex; flex-direction: column; gap: 16px; }
.input-group { display: flex; flex-direction: column; gap: 6px; }
.input-label { font-size: 12px; font-weight: 600; color: var(--text-muted); letter-spacing: 0.3px; text-transform: uppercase; }
.login-input-wrap { position: relative; }
.login-input {
  width: 100%; padding: 13px 16px 13px 44px; background: var(--off-white);
  border: 1.5px solid var(--border); border-radius: var(--radius);
  font-family: 'Plus Jakarta Sans', sans-serif; font-size: 14px; color: var(--text); outline: none; transition: all 0.2s;
}
.login-input:focus { border-color: var(--accent); background: var(--white); box-shadow: 0 0 0 4px rgba(232,93,38,0.08); }
.login-icon { position: absolute; left: 14px; top: 50%; transform: translateY(-50%); font-size: 16px; pointer-events: none; opacity: 0.5; }
.btn-login {
  display: flex; align-items: center; justify-content: center; gap: 10px;
  padding: 15px 28px; background: var(--accent); color: white;
  border: none; border-radius: var(--radius); font-family: 'Plus Jakarta Sans', sans-serif;
  font-size: 15px; font-weight: 700; cursor: pointer; transition: all 0.2s; margin-top: 4px;
}
.btn-login:hover { background: var(--accent-light); transform: translateY(-1px); box-shadow: 0 8px 24px rgba(232,93,38,0.3); }
.bottom-links { display: flex; justify-content: space-between; align-items: center; margin-top: 24px; }
.link-text { font-size: 13px; color: var(--text-muted); }
.link { color: var(--accent); text-decoration: none; font-weight: 600; }

/* ── ANIMATIONS ── */
@keyframes fadeUp   { from{opacity:0;transform:translateY(16px)} to{opacity:1;transform:translateY(0)} }
@keyframes pulse    { 0%,100%{opacity:1} 50%{opacity:0.3} }
@keyframes blink    { 0%,100%{opacity:1} 50%{opacity:0.3} }
.anim { opacity:0; animation: fadeUp 0.4s ease forwards; }
.a1{animation-delay:.05s} .a2{animation-delay:.10s} .a3{animation-delay:.15s} .a4{animation-delay:.20s} .a5{animation-delay:.25s}

/* ── RESPONSIVE ── */
@media (max-width: 768px) {
  .login-page-wrap { grid-template-columns: 1fr; }
  .left-panel { display: none; }
  .right-panel { padding: 32px 24px; }
  .body-wrap  { grid-template-columns: 1fr; }
  .sidebar    { display: none; }
  .main-content { padding: 20px 16px; }
  .kpi-grid   { grid-template-columns: 1fr 1fr; }
  .grid-2, .grid-60-40 { grid-template-columns: 1fr; }
  .fields-grid.cols3, .fields-grid.cols4, .fields-grid.cols5 { grid-template-columns: 1fr 1fr; }
}
