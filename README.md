# Grade 12 farewell invitation

Open `index.html` and activate the Grow Up seal to preview the invitation. No build or dependencies are required; the Grow Up English mark is redrawn as an inline SVG. To share it online, publish `index.html` to a static host.

Append `?name=Nguy%E1%BB%85n%20H%C3%A0` to the invitation URL to personalize it. Use `URLSearchParams` or `encodeURIComponent()` to encode names. Omitting the parameter, leaving it empty, or supplying only whitespace shows the default group greeting. Names are normalized to NFC and use the embedded Source Serif 4 font (Adobe 4.005R, SIL OFL 1.1), without a remote font request.

## Design contract

- The opening screen follows the closed-envelope reference: cream paper, a central Grow Up wax seal, and a dark green backdrop. Click, tap or use the keyboard to open the flap and raise the branded letter like the open-envelope reference, then reveal the invitation automatically.
- Identify Grow Up English as the organizing language center and the host as the teacher and center owner. After opening, show the party title and guest, a note signed by the host, and the date and venue with the supplied Google Maps link.
- Keep the forest-green card, with an original illustration of students raising glasses under a Grow Up English banner. Use warm cream, apricot, and gold against the greens. Keep the art decorative and the host and event information selectable.
- At 390x844, 768x900 and 1440x900, the name and event details must wrap without horizontal scroll. On phones, show the date and venue before the poster.
- No request or permission is needed to display the invitation. With reduced motion, reveal the content immediately on activation. Without JavaScript, show the default invitation directly. If the name is blank, show the default greeting.
