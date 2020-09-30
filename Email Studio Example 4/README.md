# Example number 4: Bewitched Gaming - Simple Tag System

## How it works:
it's a custom tag system for Bewitched Gaming Tournaments. Transmitter Script is showing tournament with tags. After clicking tag link, user will be redirected to a page with Receiver Script that shows tournaments with that tag. Tag ID is passed via URL parameter. While on page, user can freerly loop through tags. (AMPScript)

***Remember to place working URLs (for example for your landing page hosted on Marketing Cloud Web Pages)!***

## Content:
### Data Extensions:
- **bg_active_tournaments** - data about active tournaments.
- **bg_tournaments_tags** - tags associated with active tournaments

### Scripts:
- **receiver_HTML_AMPScript_content** - URL parameter reciever. You can for example place it on landing page and let user infinitly loop through tags.
- **transmitter_HTML_AMPScript_content** - URL parameter transmitter. Shows users one of the tournaments and redirect the to another page. You can place it in email.

### Rendered Examples:
Few examples saved from actual emails/landing pages.
