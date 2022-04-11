# Timele

[
    [Play Online](https://letterle-trg5503.vercel.app)
    |
    [Todo Board](https://github.com/trg5503/timele/projects/1)
]

Timele is a time-of-day guessing game, similar to [Wordle](https://nytimes.com/games/wordle) and
every other Wordle-based clone out there. The goal is to guess the time of day from 12:00 AM to
11:59 PM, with only 5 guesses to go.

## Project Architecture

This is a plain-JS application, using [Parcel](https://parceljs.org) to combine all of the JS files
into a single one. Code pushed to the `main` branch is automatically deployed with
[Vercel](https://vercel.com), mostly because I couldn't be bothered with getting a domain and
hosting it on my own.