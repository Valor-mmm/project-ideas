# Project Ideas

Ideas for programming projects.

## TOC

1. Modular logging interface
2. Regex Unit Testing (maybe for jest)
3. Automatic Test Data Generator
4. Tinder for movies and series
5. KI für Babygalarie der Thüringer Allgemeinen


## Modular Logging Interface
Can be used to log information from an npm package in a standardized way.
Separated in two parts:
  1. Interface for npm packages:
     - logging over a standardized interface (logger.warn, etc.)
     - customization limited to be standardized, but available
  2. Acess-point for programs using an npm packacke, that includes the interface
     - can use own logging functionality for logging
     - mapping between interface and own logging functionality (give function for warn, error, etc.) + logging format conversion function

## Regex Unit Testing
Unit testing possibility for regex like in regex101: https://regex101.com/
However for jest or easily integratable in projects using jest.

## Automatic Test Data Generator
Generator, which automatically generates an object/class from any given typescript type.
Can use something like faker.js to generate the basic types at the end of each chain.

Maybe provide a performant function callable at the beginning of each unit test (suite).


## Tinder for movies and series
Tinder-like app for movies and series to find something both you and your partner like.
Source: https://9gag.com/gag/aoP8Bom

## AI for the Babygalarie of the Thüringer Allgemeine
- Fetch babynames from the galeries
- Get the babynames of the artikles
- Functionality to save the best and funniest names
- AI to learn which names the user likes/finds funny
