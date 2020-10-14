# diegrammatikmacher-backend

## Documentation 
Unfortunately the backend was not touched implementation wise due to time constraints .
### Tech Stack
For the backend of the DieGrammatikMacher i would have made the decision to use following tech stack: 
- Node.js with express:
  - could be used as a business logic aggregator
  - i would expect that we would need some python machine learning services to perform "the magic" on the audio files itself

### Architecture
if time would allow i would use following structure
- App structure
  - api folder: all apis calls and handling
  - models: for database models if need be (e.g. saving which user has already send which file when...)
  - services: here all the business logic would be implemented. 
 - tests: unit tests

