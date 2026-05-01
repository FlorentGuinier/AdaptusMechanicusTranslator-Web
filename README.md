# MECHANICUS LINGUA CODEX — Web UI

> *"Knowledge is power, guard it well."*

**Sibling repo:** [AdaptusMechanicusTranslator](https://github.com/FlorentGuinier/AdaptusMechanicusTranslator) — local Flask server + CLI

Static web UI for the Adeptus Mechanicus text translator. Hosted on Vercel.  
**Live:** https://adaptus-mechanicus-translator-web.vercel.app

---

## USAGE

### Disconnected mode (no server)

Open the Vercel URL — the page works standalone with mock responses.

### Connected mode (live translation via local server)

1. On the host machine: `uv run python share.py` (starts server + tunnel, prints the URL)
2. Open the Vercel URL in any browser
3. Scroll to **COGITATOR LINK** at the bottom
4. Paste the `https://xxxx.trycloudflare.com` URL and click **CONNECT**

The URL is saved in localStorage — no need to re-enter it on the next visit.

---

*Fan creation. Not affiliated with or endorsed by Games Workshop.*
