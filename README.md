# Yourco Front End Tech Interview

## Background

Your job is to build an application that allows the user to input a question and the possible answers to that question. This combination of a question and its possible answers is what we are going to define as a `poll`.

Polls should be able to be saved in state once the form is submitted. Once a poll is saved it should appear in some sort of UI next to the input form (or below it).

There will be no api calls. Save every `poll` to state.

**Below is an example of a possible Poll object.**

```
{
    question: 'What should we have for lunch on Friday?',
    options: ['Pizza', 'Salad', 'Sandwiches']
}
```

## Application Structure 

You have been provided with an already created React.js app in pure javascript.

To install dependencies, run:

```
npm i
```

To start the app, run:

```
npm run dev
```

## Considerations

#### Language

Please use Javascript, not Typescript.

#### Dependencies

The main dependencies needed to accomplish this task are defined in both projects package.json, but please feel free to install and use any other dependencies you want.

#### Design

The app does not need to be "pretty", but showing some level of css or style understanding is recommended.

#### Internet

It's perfectly fine to use the internet. The use of ChatGPT is also fine as long as it is used solely for technical questions and not for generating your code.
