# elixir-beersearch

A simple Elixir module that searches for beers on [Untappd](https://untappd.com/).

## Installation

Add `beersearch` to your dependencies and application config in `mix.exs`:

```elixir
defp deps do
  [
    {:beersearch, "~> 0.0.2"}
  ]
end

def application do
  [applications: [:beersearch, :logger]]
end
```

Then run `mix deps.get`.

## Usage

`BeerSearch.search("Dogfish 60")`

Output:

```
["Dogfish Head Craft Brewery 60 Minute IPA (3.895)",
 "Mike's Tallybrew DogFishSkull 60 (0)",
 "Rambling Ridge Brewery DogFish 60 Clone (0)",
 "Alchemist Brewery Clone Dogfish Head 60 Minute (0)"]
```
