# skunkworks ideas

## gist.mongodb.land

- like [bl.ocks.org](http://bl.ocks.org/) but for mongo scripts instead of d3 scratch
- too many random untested javascripts in jira tickets
- want version control, sharing, syntax highlighting, search, community, etc
- lots and lots of people need and want this, for real.

### to help

- pass along scripts and mongo shell helpers you have hidden under a rock
- ask the guy working on mongoscope to add a "run in mongoscope" button

## skunkworks.mongodb.land

- aggregate all of the skunkworks projects like [nodeknockout](http://nodeknockout.com/)

## spreadsheet.mongodb.land

- Bidirectional sync collections and to Google spreadsheets
- See https://github.com/maxogden/dat

## Mongo query linter

- act as mongod proxy for dev and/or just throw some json at it

## Special comment field

- Allow adding comments to mongo queries for tracing
- `db.users.find({_id: 'joe', $trace: ['/user/joe', 'User.getByUsername']}`

## Emscripten: client side mongo

## Docs parser

- extract docs (eg commands reference) into reusable json
- ie mongoscope shell autocomplete

## GridS3

- expose gridfs as an s3 like api

## update server js

- Make shell js its own module on npm and update to modern style
- Update v8 and mongo interfaces
- Turn a bunch of js calls that just execute an aggregation pipeline

## "The ultimate MongoDB demo"

  - read remote data stream -> stream processing with aggregation framework -> stream into another collection

## imongo notebook

  - Enabled by datasets and gists
  - Don't need to build ui's
  - Easy to sit down with data science folks, get fast feedback and iterate
  - Save/share results as more gists you can just email to folks as a gist.mongodb.land url
  - Much more interesting than just "ipython for X language"
