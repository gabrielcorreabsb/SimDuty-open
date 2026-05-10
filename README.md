## SimDuty Open Landing

Static landing page for SimDuty deep links.

### Purpose

- Host `https://open.simduty.com/open`
- Try to open SimDuty app protocol automatically
- Provide a clean fallback when protocol launch is blocked/unavailable

### Local preview

Use any static server from this folder, for example:

```bash
python -m http.server 8080
```

Then open:

- `http://localhost:8080/open/?payload=demo`
