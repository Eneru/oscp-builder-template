# oscp-builder-template

![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/Eneru/oscp-builder-template/main.yml) 
![GitHub tag (with filter)](https://img.shields.io/github/v/tag/Eneru/oscp-builder-template)
![GitHub forks](https://img.shields.io/github/forks/Eneru/oscp-builder-template)
![GitHub Repo stars](https://img.shields.io/github/stars/Eneru/oscp-builder-template)
![GitHub](https://img.shields.io/github/license/Eneru/oscp-builder-template)

The project aims to help building the report for the [OSCP certification](https://www.offsec.com/courses/pen-200/) in a CI/CD manner, without installing something on your computer neither needing to remember how to use pandoc.


## Environment Variables

To run the GitHub Actions from this project, you will need to add the following environment variables to your repository's settings

`INPUT_DIRECTORY_PATH`: where the .md files are (ex: inputs)

`OUTPUT_DIRECTORY_PATH`: where the .pdf file will be (ex: target/release)

`OUTPUT_FILENAME`: what is the pdf name (ex: result)

`ARTIFACT_NAME`: what is the name of the generated artifact (ex: release)

## Usage/Examples

Simply create .md file(s) inside the `INPUT_DIRECTORY_PATH` of your repo, and push to main to trigger the GitHub workflow.
## Acknowledgements

 - [Idea from Noraj template](https://github.com/noraj/OSCP-Exam-Report-Template-Markdown)
 - [With the help of pandoc action example](https://github.com/pandoc/pandoc-action-example)

## License

[The Unlicense](https://choosealicense.com/licenses/unlicense/)