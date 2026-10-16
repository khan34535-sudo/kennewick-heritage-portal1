# Kennewick-Heritage-Portal1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kennewick Man · The Ancient One · Indigenous Heritage Portal</title>
</head>
<body>

    <header>
        <h1>Kennewick Man · The Ancient One · 3D GIS Heritage Matrix</h1>
        <p><strong>Prototype Sample · Demonstrator Only · Not for Research Citation</strong></p>
        <p>An experimental interface exploring how archaeological, bioarchaeological, and tribal heritage data might be presented interactively — through satellite terrain, 3D anatomical/artifact models, and multi-proxy narratives honoring Indigenous sovereignty and the 2017 reburial.</p>
        
        <p><strong>Asia Khan, Hon. BA</strong> (McMaster University)<br>
        Behavioral UX Researcher &amp; Design Anthropologist</p>

        <p>🔗 <strong>Live Prototype</strong><br>
        → View the interactive prototype<br>
        <em>(If the link doesn't work, enable GitHub Pages in Settings → Pages → main branch → / (root))</em></p>
    </header>

    <hr>

    <section id="disclaimer">
        <h2>⚠ Disclaimer</h2>
        <p>This is a design prototype and demonstrator. It is intended to show how archaeological and tribal historical information could be presented respectfully, not to serve as a primary research source or a substitute for tribal consultation.</p>
        <ul>
            <li>Site names and APA citations point to real literature</li>
            <li>Coordinates, artifact descriptions, and numerical indices are illustrative examples</li>
            <li>All 3D models and artifact images are placeholders or generic anatomical/artifact references</li>
            <li><strong>Do not cite this prototype in academic work</strong> — consult original publications and the claimant tribes</li>
        </ul>
    </section>

    <hr>

    <section id="features">
        <h2>What This Demonstrates</h2>
        <ul>
            <li><strong>Spatial context</strong> — Real satellite imagery with 3D terrain, hosting sites as spatial anchors along the Columbia River and institutional repositories.</li>
            <li><strong>Living Land Acknowledgement</strong> — Foregrounding the sovereignty, oral histories, and reburial by the five claimant tribes (Colville, Nez Perce, Umatilla, Yakama, Wanapum).</li>
            <li><strong>3D specimen &amp; artifact models</strong> — Procedural Three.js models of skulls, spearpoints, DNA helices, and ceremonial bundles.</li>
            <li><strong>Multi-proxy integration</strong> — Radiocarbon dating, bioarchaeology, genetics, ritual objects, and legal histories side-by-side.</li>
            <li><strong>Resilience narratives</strong> — Explorable scenarios for scientific tension vs. Indigenous sovereignty, legal battles, and repatriation.</li>
            <li><strong>Readable citations</strong> — Every panel surfaces its own APA 7th reference.</li>
        </ul>
    </section>

    <hr>

    <section id="comparison">
        <h2>What's Real vs. Placeholder</h2>
        <table border="1" cellpadding="6" cellspacing="0">
            <thead>
                <tr>
                    <th align="left">Status</th>
                    <th align="left">Item</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>✅ Real</strong></td>
                    <td>Site names, regional contexts, and claimant tribes</td>
                </tr>
                <tr>
                    <td><strong>✅ Real</strong></td>
                    <td>APA 7th citations and legal/historical timeline</td>
                </tr>
                <tr>
                    <td><strong>✅ Real</strong></td>
                    <td>Bioarchaeological findings (healed trauma, 380+ bones)</td>
                </tr>
                <tr>
                    <td><strong>⚠ Partial</strong></td>
                    <td>Site coordinates (regional centroids only)</td>
                </tr>
                <tr>
                    <td><strong>❌ Placeholder</strong></td>
                    <td>All 3D specimen and anatomical models (generic references)</td>
                </tr>
                <tr>
                    <td><strong>❌ Placeholder</strong></td>
                    <td>Artifact images &amp; diagrams (placeholders/svgs)</td>
                </tr>
                <tr>
                    <td><strong>❌ Placeholder</strong></td>
                    <td>Site-level descriptive text</td>
                </tr>
            </tbody>
        </table>
    </section>

    <hr>

    <section id="running">
        <h2>Running Locally</h2>
        <p>To run the interactive GIS map and 3D models locally without CORS restrictions on tile loading:</p>
        <ol>
            <li>Open a terminal in the folder and run a local web server:
                <pre><code>python -m http.server 8000</code></pre>
            </li>
            <li>Open your browser and navigate to <code>http://localhost:8000</code></li>
        </ol>
    </section>

    <hr>

    <section id="ethics">
        <h2>Ethics &amp; Indigenous Heritage</h2>
        <p>The sites referenced are located on the ancestral and unceded lands of Indigenous nations along the Columbia Plateau. The Ancient One was repatriated and reburied in 2017 by the Confederated Tribes of the Colville Reservation, the Nez Perce Tribe, the Confederated Tribes of the Umatilla Indian Reservation, the Confederated Tribes and Bands of the Yakama Nation, and the Wanapum People.</p>
        <p>Any digital presentation of this heritage must be done with utmost respect, attribution, and consultation with descendant communities. This prototype strictly avoids displaying any photographs, scans, or depictions of the Ancient One's actual remains.</p>
    </section>

    <hr>

    <section id="tech-stack">
        <h2>Tech Stack</h2>
        <ul>
            <li><strong>MapLibre GL JS</strong> — satellite + terrain</li>
            <li><strong>Esri World Imagery</strong> — free public tiles</li>
            <li><strong>AWS Terrain DEM</strong> — elevation</li>
            <li><strong>Three.js r128</strong> — 3D interactive models</li>
            <li><strong>Tailwind CSS</strong> — layout &amp; styling</li>
            <li><strong>Google Fonts</strong> — Merriweather + Inter</li>
        </ul>
    </section>

    <hr>

    <footer>
        <h2>Credits &amp; License</h2>
        <ul>
            <li><strong>Prototype</strong>: Asia Khan, Hon. BA (McMaster University)</li>
            <li><strong>Imagery &amp; Tiles</strong>: Esri · AWS · OpenStreetMap contributors</li>
        </ul>

        <p>© 2026 Asia Khan · All Rights Reserved.<br>
        This prototype, including its source code, interface design, written content, and procedural 3D models, is the intellectual property of the author. No part of this work may be reproduced, distributed, modified, or transmitted in any form or by any means without prior written permission from the author.</p>

        <p>The prototype is provided "as is" for demonstration and educational viewing purposes only, without warranty of any kind. Third-party libraries (MapLibre GL, Three.js, Tailwind CSS, Google Fonts, Font Awesome, Esri imagery, AWS terrain tiles) are used under their respective licenses and remain the property of their original creators.</p>
    </footer>

</body>
</html>
