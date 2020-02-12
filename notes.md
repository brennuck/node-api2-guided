## Design process

- gather requirements
- list of resources (nouns) [song, user, pets, exercises, routines]
- list of endpoints

## Endpoints

- avoid using verbs, it's not a URL, it's URI. (instead of create-song => /api/songs)
- actions are expressed with http methods

|Action|Method|Endpoint|

|List songs|GET|/api/songs|
|Create a song|POST|/api/songs|
|Update a song|PATCH/PUT|/api/songs/:id|
|Remove a song|DELETE|/api/songs/:id|
|Add song's album art|POST/PUT|/api/songs/:id/cover|