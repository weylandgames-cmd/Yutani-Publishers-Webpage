<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Yutani House Publishers<\/title>
<meta name="description" content="Official author site and Yutani House Publisher imprint — books, world‑building, and submission guidelines." />
<meta property="og:title\" content=\"Yutani House Publishers\" />
<meta property="og:description" content="Official author site and Yutani House Publisher imprint — books, world‑building, and submission guidelines." />
<meta property="og:type" content="website" />
<meta property="og:image" content="/og-image.png" />
<link rel="icon" href="/favicon.ico" />
<style>
:root {
--bg: #0a0b10;
--bg-2: #101223;
--text: #e6e9f2;
--muted: #a6accd;
--brand: #7aa2ff;
--brand-2: #22d3ee;
--card: rgba(255,255,255,0.06);
--border: rgba(255,255,255,0.12);
--glow: 0 0 40px rgba(122,162,255,0.25);
}


* { box-sizing: border-box; }
html, body { height: 100%; }
body {
margin: 0;
font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji";
color: var(--text);
background:
radial-gradient(60vmax 60vmax at 10% -10%, rgba(34,211,238,0.12), transparent 60%),
radial-gradient(70vmax 70vmax at 110% 10%, rgba(122,162,255,0.12), transparent 60%),
linear-gradient(180deg, var(--bg) 0%, var(--bg-2) 100%);
background-attachment: fixed;
line-height: 1.6;
letter-spacing: 0.2px;
}


/* Header */
header {
position: sticky; top: 0; z-index: 50;
backdrop-filter: saturate(1.2) blur(8px);
background: rgba(10,11,16,0.65);
border-bottom: 1px solid var(--border);
}
.container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
.nav { display: flex; align-items: center; justify-content: space-between; height: 64px; }
.brand { display: flex; align-items: center; gap: 12px; text-decoration: none; color: var(--text); }
.brand-logo { width: 36px; height: 36px; border-radius: 10px; background: linear-gradient(135deg, var(--brand), var(--brand-2)); box-shadow: var(--glow); position: relative; }
.brand-logo::after { content: ""; position: absolute; inset: 6px; border: 2px solid rgba(255,255,255,0.4); border-radius: 8px; filter: blur(0.2px); }
.brand-title { font-weight: 700; letter-spacing: 0.5px; }


.nav-links { display: flex; gap: 20px; align-items: center; }
.nav-links a { color: var(--muted); text-decoration: none; font-weight: 600; font-size: 0.95rem; }
.nav-links a:hover { color: var(--text); }


.menu-btn { display: none; background: none; color: var(--text); border: 1px solid var(--border); padding: 8px 10px; border-radius: 8px; }


/* Hero */
.hero { padding: 96px 0 72px; position: relative; overflow: hidden; }
.hero-grid { display: grid; grid-template-columns: 1.2fr 1fr; gap: 32px; align-items: center; }
.eyebrow { text-transform: uppercase; letter-spacing: 4px; color: var(--brand-2); font-weight: 700; font-size: 0.8rem; }
h1 { font-size: clamp(2rem, 4vw + 1rem, 3.4rem); line-height: 1.1; margin: 12px 0 16px; }
.lead { color: var(--muted); font-size: 1.1rem; }


.cta { display: flex; gap: 12px; margin-top: 24px; }
.btn { display: inline-flex; align-items: center; gap: 10px; padding: 12px 16px; border-radius: 12px; text-decoration: none; font-weight: 700; letter-spacing: 0.4px; }
.btn-primary { color: #061220; background: linear-gradient(135deg, var(--brand), var(--brand-2)); box-shadow: var(--glow); }
.btn-ghost { color: var(--text); border: 1px solid var(--border); background: rgba(255,255,255,0.02); }
.btn:hover { transform: translateY(-1px); }


.chip-row { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 32px; }
.chip { font-size: 0.8rem; padding: 6px 10px; border: 1px solid var(--border); border-radius: 999px; color: var(--muted); background: rgba(255,255,255,0.03); }


.hero-card { background: var(--card); border: 1px solid var(--border); border-radius: 18px; padding: 18px; display: grid; grid-template-columns: 64px 1fr; gap: 16px; align-items: center; box-shadow: var(--glow); }
.hero-card svg { width: 64px; height: 64px; }


/* Sections */
section { padding: 80px 0; border-top: 1px solid var(--border); }
.section-title { font-size: clamp(1.4rem, 2.4vw + 0.6rem, 2.2rem); margin: 0 0 12px; }
.section-sub { color: var(--muted); margin: 0 0 28px; }


.grid { display: grid; gap: 20px; }
.grid-3 { grid-template-columns: repeat(3, minmax(0, 1fr)); }
.grid-2 { grid-template-columns: repeat(2, minmax(0, 1fr)); }


.card { background: var(--card); border: 1px solid var(--border); border-radius: 16px; padding: 18px; }
.card h3 { margin: 6px 0 8px; }
.card p { color: var(--muted); margin: 0 0 12px; }


.tag { display: inline-block; font-size: 0.75rem; padding: 4px 8px; border-radius: 999px; border: 1px solid var(--border); color: var(--muted); }


/* Gallery */
</html>
