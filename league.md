# League Details

Returns information for a given league ID.

## Endpoint

`https://www.blaseball.com/database/league?id=:league_id`

## Response

```json
{
  "id":"d8545021-e9fc-48a3-af74-48685950a183",
  "subleagues": [
    "7d3a3dd6-9ea1-4535-9d91-bde875c85e80",
    "93e58443-9617-44d4-8561-e254a1dbd450"
  ],
  "name":"Internet League Blaseball",
  "tiebreakers":"72a618ed-c61c-4162-a455-3959a2d0e738"
}
```

## Field Descriptions

**`id`**: The ID of the league.

**`subleagues`**: The IDs of the subleagues that belong to the league.

**`name`**: The name of the league.

**`tiebreakers`**: The ID of a tiebreaker, which lists the rank order of teams for breaking ties.
