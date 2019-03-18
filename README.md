# Samantar (Parallel Corpus)

Generating a parallel corpora to develop a assisted translation system for Pratham Books’ StoryWeaver.

## About Pratham Books

Pratham Books is a nonprofit publisher introducing children to the joy of reading.

Every second child in India cannot read at her grade level.1
This immense reading deficit comes from a variety of reasons, an important one being the dearth of reading material beyond textbooks in school. Without easy access to books in their mother tongue languages, children struggle to learn to read and practise their reading skills.

Since 2004, we have been creating engaging storybooks in multiple languages and formats to help children discover the joy of reading – in languages they can understand, set in locations they can recognise, featuring characters with whom they can identify, and telling stories that capture their attention and fuel their imagination.

Our books delight and enchant children, taking them on adventures and introducing them to new worlds.

## About StoryWeaver

Pratham Books launched StoryWeaver - an online, digital repository of multilingual children’s stories - on International Literacy Day, 2015. All the content on the platform is openly licensed under CC-BY4.0 - one of the most liberal Creative Commons licenses, giving the users not only the access to read stories in mother tongue languages for free, but also the power to create, translate and repurpose stories based on their own requirements, using the tools embedded on the platform. In over 3 years since StoryWeaver’s launch, the digital repository has grown from 800 stories in 24 languages to over 12,000 stories in 150 languages. The content is available in open formats to enable discoverability, accessibility and interoperability.

## Problem Statement

Around 70% of the 12,000+ stories on StoryWeaver have been contributed by the  platform’s global community of users. There is tremendous linguistic diversity on StoryWeaver and of the 150+ languages represented on platform there is  a healthy mix of mainstream and minority languages, the latter of  which is severely underrepresented in mainstream publishing.

Of the 8000+ community stories on the platform, 65% are translations. StoryWeaver is working with language organisations and champions from our community to create hyperlocal language libraries in mother tongue languages via collaborative engagements like translation hackathons, workshops for capacity building of language resources, video resources from senior editors and translators and more.

However, not all community translators have nuanced understanding of translating for children. Banhi, a student of linguistics, also a community translator on StoryWeaver shares; “I did not realise that translating for adults and translating for children could be two completely opposite poles of the same medium.”

We found these observations validated when we screened the community content on the platform for a health check. Spelling mistakes; grammatical, punctuation errors, translation errors were the single most reason for stories getting a low rating.

## Solution

We aim to develop a automated way of generate Parallel Corpus which is a corpus containing a collection of original texts in a language and their corresponding translations. Using StoryWeaver’s collection of books in various languages and few open external data sources, it would be feasible to create a parallel corpus with few Indian languages using which we can achieve the following:

* Provide translation suggestions to authors while translating books.
* Suggestions based on the grade level of the book being translated.
* Transliterations for both word & phrase level for various Indian languages.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Giza++](https://www.link.com/) - <usage>
* [Moses](https://www.link.com/) - <usage>
* [Others]

## Contributing

Please read [CONTRIBUTING.md](https://www.link.com/) for details on our code of conduct, and the process for submitting pull requests to us.

## Contributors

See also the list of contributors in [contributors.md](https://www.link.com/) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://www.link.com/) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc