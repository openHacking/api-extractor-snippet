# API Extractor Snippet

## Introduction

Implemented code hints for [Doc comment syntax](https://api-extractor.com/pages/tsdoc/doc_comment_syntax/) when using API Extractor to generate API documentation

## Usage

1. Install the extension
2. Make sure `settings.json` contains the following configuration
   ```json
	// use tab to complete
   "editor.tabCompletion": "on",
   // Configure the order of snippets and other code hints
   "editor.snippetSuggestions": "top",
   // Support comment code hints
   "editor.quickSuggestions": {
     "comments": true
   }
   ```

## Feature
All tags below have been implemented
- @alpha
- @beta
- @defaultValue
- @deprecated
- @eventProperty
- @example
- {@inheritDoc}
- @internal
- {@link}
- @override
- @packageDocumentation
- @param
- @preapproved
- @privateRemarks
- @public
- @readonly
- @remarks
- @returns
- @sealed
- @typeParam
- @virtual