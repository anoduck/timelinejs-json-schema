
# TimelineJs Json Schema

A JSON Schema for validating timelinejs JSON files and for use with autocompletion systems. The
[timelinejs](https://timeline.knightlab.com) script enables website designers the ability to create
timeline elements that are truly dynamic and provide deep introspection. Currently, the developers
provide two means for creating a timelinejs with data, a google spreadsheet and a json file. Of the
two, the google spreadsheet is by far the easiest to work with and less prone to cause errors. This
schema is for use with the latter option of creating timelinejs elements with a local json file.

The project is experiemental at best, and a few features have not been included yet in this
implementation. 

## Getting Started

Using the schema should be as simple as including the link to the schema at the top of your
timelinejs json file and go.

``` json
{
	"$schema": "https://anoduck.github.io/timelinejs-json-schema/timelinejs.schema.json",
}
```

### Prerequisites

Requirements for the software and other tools to build, test and push: 
- More sleep than I got last night.
- More time than I have creating it.

Most modern code editors will use a schema definition to assist in providing completion of
verification of the json file.

### Installing

A step by step series of examples that tell you how to get a development
environment running

Say what the step will be

    Give the example

And repeat

    until finished

End with an example of getting some data out of the system or using it
for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Sample Tests

Explain what these tests test and why

    Give an example

### Style test

Checks if the best practices and the right coding style has been used.

    Give an example

## Deployment

Add additional notes to deploy this on a live system

## Built With

Mention the tools you used to build this project

- [Contributor Covenant](https://www.contributor-covenant.org/)
- [Creative Commons](https://creativecommons.org/)


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code
of conduct, and the process for submitting pull requests to us.

## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this
repository](https://github.com/PurpleBooth/a-good-readme-template/tags).

## Authors

See also the list of
[contributors](https://github.com/PurpleBooth/a-good-readme-template/contributors)
who participated in this project.

- **Billie Thompson** - _Provided README Template_ - [PurpleBooth](https://github.com/PurpleBooth)
- **Shaan Khan** - _Provided Created README Generator_ - [Shaan Khan](https://github.com/ShaanCoding)


## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details

## Acknowledgments

- Hat tip to anyone whose code is used
- Inspiration
- etc
