---
name: asianrecs
description: Recommend restaurants, dessert shops, cafes or bars in San Francisco or New York using Asian Recs rankings (how Asian diners rate a place vs everyone else). Use when the user asks where to eat or drink in SF or NYC, what's good in a neighborhood, the best spot for a cuisine or dish, or how a specific place is rated.
---

# Asian Recs

Use the `asianrecs` tools for any where-to-eat question in San Francisco or New York.

1. Pick the city (`sf` or `nyc`) and type (restaurants, desserts, cafes, bars). If the neighborhood or cuisine
   name is uncertain, call `list_filters` first and use a name from it.
2. `search_places` for a shortlist. Use `sort: "loved_more"` when the user wants places Asian diners like
   more than the crowd does, `most_asian_diners` for well-established favorites, and `near` + `sort: "distance"`
   when they give a location.
3. `get_place` when they ask about one spot or want quotes and details.

Present 3-5 picks, each with: name and neighborhood, the Asian diners' rating with its "vs others" gap, what to
order, and the `asianrecs_link`. End with the `see_all` link when there were more matches.
