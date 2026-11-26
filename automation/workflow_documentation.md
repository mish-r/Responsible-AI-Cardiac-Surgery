
# Automated Academic Paper Analysis Workflow

## Objective

To reuse and develop an existing Python-based text-mining and stylometric analysis workflow for academic literature relevant to cardiac surgery and responsible AI.

## Current Workflow

1. Academic papers are selected manually through browser-based searches.
2. PDFs are downloaded manually, allowing access through university subscriptions.
3. PDFs are uploaded to Google Drive.
4. The existing downstream text-mining and stylometric analysis process runs automatically after upload.

## PDF Download Testing

Automated PDF downloading was tested using the Europe PMC API.

Some publisher security restrictions returned HTTP 403 errors, preventing reliable automated downloads.

Manual browser-based downloading was therefore chosen as the current approach.

## Automation Status

- Manual paper selection and downloading: Current approach.
- Google Drive PDF upload: Part of the workflow.
- Downstream text mining and stylometric analysis: Automated.
- Testing with cardiac-surgery papers: Future work.
- Documentation and improvement of the workflow: Ongoing.

## Future Development

- Test the workflow using cardiac-surgery papers.
- Check the accuracy of PDF text extraction.
- Evaluate whether existing text-analysis features are suitable for the new research.
- Explore automated collection of paper metadata.
- Document the Python libraries and implementation.

## Important Limitation

Text-mining and stylometric analysis do not independently establish whether clinical information is factually correct or whether an AI system hallucinates. Additional evaluation methods will be needed for these research questions.
