# Advent of Craft 2025

## Solution DAY 03

- Contributor Discord Name : fbibonne
- Stack :  java (intellij)
- Fork : https://github.com/FBibonne/advent-2025/pull/3

## More feedback to share (optional)

- Phase 1 : extrem SOLID : apply SOLID principles systematicaly :
  - complexity increased ! :
    - from 3 classes to 10 classes : interfaces obsession !!!
    - complexity of Santa decreased from 14 to 8 but I added the ChildRepositoryImpl class with complexity 6
    - It is too much abstract because I added interfaces in front of all concrete classes : it is a nonsense !
    - Do not forgot KISS principles
    - I note that I want to keep a method in Santa class which represents business rules : it associates Behaviors with "something" which is able to choose a toy in Wishlist
- Phase 2 : peace with SOLID : simplification !
  - from 10 classes to 7 classes
  - Santa complexity is at 8. ChildrenRepository is at 4
  - My classes are closer to business concepts
- I learnt :
  - applying systematically SOLID leads to introduce too much abtraction (notion which does not exist in business)
  - it is more efficient to drive development with business notions (try to express business logic in the code)
  - SOLID (clean code, objects calisthenics, ...) principles are guidelines to improve locally code but are not designed to globally drive a refactor
