# Advent of Code Template: Typescript + Deno

This project uses Typescript on the [Deno runtime](https://deno.land/).

```sh
# To run the day
deno run -A ./index.ts run {day}

# To run part of the day
deno run -A ./index.ts run {day} {part}

# To create a new day
deno run -A ./index.ts create {day}
```

## How to find and set my session token?

1. Navigate to https://adventofcode.com/ and login
2. Press F12 to open developer tools
3. Click the Application-tab in the top ribbon (1)
4. Select the cookies belonging to the current domain (2)
5. Select the cookie with the name "session" (3)
6. Copy the token (4)
7. Set the "ADVENT_SESSION_TOKEN" field in the .env-file with the copied token

![Instructions](https://i.imgur.com/ygEUVE8.png "Instructions")