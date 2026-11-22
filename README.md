# White Stone — Website

Marketing site for **White Stone**, a customer acquisition company (Meta advertising, cold email outreach, influencer partnerships).

The whole site is a single self-contained file: `index.html`. No build step.

## Editing common settings

Open `index.html` and find the `CONFIG` block near the top of the `<script>` section:

| Setting | What it does |
|---|---|
| `ratePctOfTicket` | White Stone price per qualified appointment, as a share of the client's average ticket (currently `0.06` = 6%) |
| `defaultTicket` | Starting value in the calculator's "Average Ticket Price" box |
| `agency*` / `inhouse*` | **Illustrative** assumptions for the comparison columns. These are not market quotes. |
| `bookingUrl` | Calendly event that powers every "Schedule" button |
| `leadPhone` | Number shown for text/call in the booking pop-up and footer |

## Booking

Available time slots are managed in Calendly, not in this code. Booked slots disappear automatically, and Calendly sends the notifications.

## Hosting on GitHub Pages

Repository **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`, then save. The site goes live at `https://jakegithubpro.github.io/white-stone-website/`. A custom domain can be added on the same page.
