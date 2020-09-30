# Example number 3: Bewitched Gaming

## Background:
Bewitched Gaming is an organisations which focus on orginising e-sport events and gaming tournaments.

## Content:
### Data extensions:
- **bg_transactional_email** - ***sendable*** Data Extension with example players data. Represents sign-ups for tournaments.
- **bg_marketing_test** - ***sendable*** Data Extension with example players data.
- **bg_tournaments** - Data Extenension with data about upcoming tournaments. (name, date, prize pool, game id etc.)
- **bg_user_interest** - Data Extension with data about players interests. (what games are users interested in)
- **bg_game** - Data Extension with data about games played on Bewitched tournaments (title, type, team size etc.)

### Email Content:
- **transactional_email.html** - transactional email which display data about sign-ups for tournaments. It's quering informations from two Data Extenions: bg_tournaments, and bg_game.
- **marketing_email.html** - marketing email which dynamically display data about upcoming tournaments depending on users city. If there is no tournaments in users location then online tournaments should be displayed.

### HTML rendered via Preview and Test
- **marketing_email_render_examples** - few examples how our example of transactional email renders
- **transactional_email_render_examples** - few examples how our example of marketing email renders
