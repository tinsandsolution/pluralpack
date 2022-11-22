# Pluralpack

polling and selves-management app for people with DID

# Setting up on your own server

```
cd frontend
npm install
```

# MVP, user stories

## Identities

Authenticated users will be able to create, read, and update identities for systems.

Operations will be logged for the user to observe.

Deletions are not possible, due to the inherent ambiguity and lack of finality of identities merging. Instead, there is an "active" toggle.

For example, take a system named Terry. Assume there are three identities within the system: Cindy, Sally, and Susie.

Sally and Susie attempt to merge. They remain merged for a week but then re-split. Both identities are more-or-less the same and identify with their respective past selves. 

Each identity may want to add other features for their specific profiles such as colors, profile pictures, and a short biography.

Operations will be logged for the user to observe.

## Polling

Authenticated users will be able to create a poll with a question. By default, the creator of the poll will be the System, not any individual identity. however, selecting the name of the identity will be possible.

There are resolved questions and open questions.

A question will automatically resolve when all identities have either abstained or voted on the question.

Possible questions:

1. Should I move to New York? (Yes/No/Abstain)
2. How much pain are you in, on a scale of 1-10?
3. How much pain are you in, on a clock scale?

Operations will be logged for the user to observe.

## History

# Later on

## Approval Voting

Take a question like, "Which system minister should we elect?"

The issues with first-past-the-post voting are [well-documented.](https://electionscience.org/library/the-spoiler-effect/).

Implementing system elections and approval voting will likely involve multiple modals.



## Toots

## Constitution/Bill of Rights

Twitter-style tweet with threading. 


Todo:

figure out how to get "login with google drive:

figure out how to do a docker container thing

figure out how to implement a backend