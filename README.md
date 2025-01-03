
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

Most modern code editors will use a schema definition to assisst in providing completion of
verification of the json file.

### Installing

Simply place the following line at the top of your json file. Append with a `,` and you should be
good to go. 

``` json
"$schema": "https://anoduck.github.io/timelinejs-json-schema/timelinejs.schema.json"
```

## Schema Versions

Currently using: http://json-schema.org/draft-07/schema
Previously was using: https://json-schema.org/draft/2020-12/schema

## Built With

- [JSON Schema](https://json-schema.org/learn/)
- [JSON Schema Docs](https://www.learnjsonschema.com/2020-12/)


## Versioning

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions
available, see the [tags on this repository](https://github.com/anoduck/timelinejs-json-schema/tags).

## Authors

- **Anoduck, The Anonymous Duck** - _Provided README Template_ - [Anoduck](https://github.com/anoduck)

## License

This project is licensed under the [MIT License](https://anoduck.mit-license.org)

## Acknowledgments

- Big thanks goes to [Elio Struyf](https://github.com/estruyf) who created the vscode package
  [FrontMatter](https://github.com/estruyf/vscode-front-matter/) and by doing so taught individuals
  like yours truly the beauty of JSON Schema.
