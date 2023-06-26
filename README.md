# TRB Annual Meeting Template

<!-- ALL THE BELOW SHOULD BE IN YOUR README -->

This is a Quarto template that assists you in creating a manuscript for the Transportation Research Board Annual Meeting. You can learn more about the requirements for submission at [this webpage](https://trb.secure-platform.com/a/page/TRBPaperReview#LLM)

## Creating a New Article

You can use this as a template to create an article for an AFT journal. To do this, use the following command:

```bash
quarto use template byu-transpolab/trb-quarto
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension byu-transpolab/trb-quarto
```

## Usage

To use the format, you can use the format names `trb-pdf` and `trb-html`. For example:

```bash
quarto render article.qmd --to trb-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  trb-pdf:
    keep-tex: true    
```


## Format Options

This format does not have specific format option.