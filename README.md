# WPS office walkthrough concept

An interactive Three.js concept for Workplace Solutions. Scroll through six office stops (Arrive, Lounge, Focus, Connect, Create and Visit) or jump between chapters. Includes still-view mode.

This is an illustrative design prototype, not the production WPS website. Architecture and furniture finishes are conceptual. Cesto overall dimensions follow the Studio TK STGI drawing: 32 inches wide and deep, 33.5 inches high. Six Cesto lounge chairs use the mesh supplied in the project attachment.

`visual-direction.png` shows the intended visual finish; the walkthrough combines simplified procedural geometry with the optimized Cesto mesh (12,000 triangles shared across six chairs).

Three.js 0.160.1 is MIT licensed; see THREE-LICENSE.txt. WPS branding belongs to its respective owner.

Lounge sofas face the coffee tables and are proportioned to the Cesto seating.

Chapter clicks begin camera travel immediately. Default tour speed is 2x, with an adjustable, persistent slider. Lounge furniture rests on the measured rug surface.

Click furniture to inspect an enlarged 3D model over the faded office. Includes rotation, keyboard selection, Escape to close and exact tour-position restoration. Cesto links to Studio TK; other pieces are labeled conceptual.

When the tour is idle, the camera gently looks toward the mouse. Navigation recenters it; still-view and reduced-motion settings disable the effect.

Room text transitions: outgoing copy fades 36px left over 260ms; incoming copy fades in from 28px right over 480ms. Room labels follow the same transition; speed controls stay steady. Rapid chapter changes cancel stale updates. Reduced-motion preference uses an immediate text replacement.

Tour speed controls are collapsed by default behind an accessible sliders icon beside the room label. Click toggles the panel; outside click and Escape dismiss it. Existing speed preference and still-view behavior are preserved.
