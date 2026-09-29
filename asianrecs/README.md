# Asian Recs

Ask Claude where to eat and drink in San Francisco and New York, and get restaurants, dessert shops, cafes
and bars ranked by how Asian diners rate them, beside how everyone else rates the same place. Rankings come
from public Google and Yelp reviews and refresh weekly, the same as [asianrecs.com](https://asianrecs.com).

This plugin connects Claude Code to the Asian Recs MCP server (`https://asianrecs.com/api/mcp`, read-only,
no sign-in) and adds a skill that tells Claude when to use it and how to present picks.

## Tools

- `search_places`: search by city, kind of place, neighborhood, cuisine, dish or distance, sorted by Asian
  diners' rating, the gap above everyone else, or the number of Asian diners.
- `get_place`: one place's ratings, what to order, quotes from Asian diners, Google and Yelp ratings, and links.
- `list_filters`: the neighborhoods and cuisines covered in each city.

## Examples

- "Where should I get soup dumplings in Flushing? I want the places Asian diners rate highest."
- "Which Korean restaurants in New York do Asian diners like far more than everyone else?"
- "Boba within a mile of Union Square in Manhattan?"
- "Tell me about Dim Sum Club in San Francisco. What should I order?"

More at [asianrecs.com/claude](https://asianrecs.com/claude). Privacy: [asianrecs.com/privacy](https://asianrecs.com/privacy).
Support: [GitHub issues](https://github.com/raymond-raymond/asianrecs-claude/issues).
