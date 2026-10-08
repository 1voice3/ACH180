ACH180 Trainer - single file version
Upload index.html to the ROOT of a GitHub repo (delete old files first), then Settings > Pages > Deploy from a branch > main / root.
Open https://YOUR-USERNAME.github.io/YOUR-REPO/ in Safari, then Share > Add to Home Screen. Needs a connection to open.

Independent training simulator. Not ABB. It controls no equipment and does not replace the manuals.

Parameters: all 946 numbered parameters of firmware manual 3AXD50000955893 Rev B were extracted automatically from the PDF
(ID, name, description, default, range, unit, choices), listed 01 to 99. Extraction is not hand-verified.
About 50 parameters drive the simulation (filter "Simulated parameters only" on the Params tab); the rest are stored and shown only.

Wiring and parameters work together: start (20.01/20.03), reference (28.11, 12.15 to 12.20), constant frequencies (28.21 to 28.32),
interlock and permissive (20.40, 20.41, 20.45, 20.51), direction (20.21), external events (31.01 to 31.04), relay output (10.24),
analog output (13.12, 13.17 to 13.20), ramps, limits and AI supervision. A wired input does nothing unless a parameter selects it.
Not modeled: PID, AI2, DI5, timed functions, supervision functions, fieldbus, motor potentiometer, vector control,
application setup examples, the other 900 parameters' effects. Defaults use 60 Hz / 230 V / 1750 rpm values.
