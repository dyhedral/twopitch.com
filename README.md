# twopitch.com

Landing page for Twopitch, a shared assistant for two people and one home. The product is in development.

One static page, no build step. `tokens.css` holds the colours, type and spacing. The two fonts are served from `fonts/` under the SIL Open Font License; the page makes no requests to other sites.

## Preview

    python3 -m http.server 8791 --bind 127.0.0.1

Then open http://localhost:8791/.

## Waitlist

The waitlist is not open. The page gives an email address to write to. It has no form and no script, and sends nothing itself.

## Checks

CI validates the HTML, checks there is exactly one `h1` and fewer than 200 visible words, and checks links.

    python3 .github/scripts/check_html.py --max-words 200

## Still to do

- Add a `LICENSE` file.
- Confirm that mail to `hello@twopitch.com` is delivered.
