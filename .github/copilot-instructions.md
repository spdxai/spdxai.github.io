## General language use

- [ ] Prefer clear, concise, and unambiguous sentences.
- [ ] Avoid words and phrases that may have more than one interpretation.
- [ ] Avoid overly long paragraphs. Breaking up text into smaller paragraphs,
      using bullet points, or creating numbered lists to improve readability.
- [ ] Help reader's comprehension by separating distinct concepts, processes,
      criteria, or categories.
- [ ] Use parallel language structures in lists and documentation.
- [ ] Use a uniform writing style, particularly when presenting similar or
      related information, so the reader's compare easily.
- [ ] If not specified otherwise, use Chicago style for reference/citation.
- [ ] When writing on level of requirements, use the verbal forms consistently.
      Use either ISO/IEC verbal form (ISO/IEC Directives, Part 2 --
      Principles and rules for the structure and drafting of ISO and IEC
      documents) or IETF verbal form (RFC 2119 and RFC 8174).
      Try to detect the level of requirements from type/domain of the document.
      IETF is default for internet/web/semantic web projects in general.
      ISO is default for SPDX project.
- [ ] Use either American or British spelling consistently.
      Check for inconsistency.
      If not specified, or there is no clear existing example in the file or
      the repo, use British spelling as a default.

## Naming conventions

- [ ] Follow standard naming conventions for the programming language
      and framework you are using.
- [ ] For URLs/IRIs, use lowercase letters and hyphens to separate words
      (e.g., `my-api-endpoint`) and follow W3C Cool URIs for the Semantic Web:
      https://www.w3.org/TR/cooluris/
- [ ] Consult Schema.org vocabularies when deciding about names.

## Tidy code and documentation

- [ ] Ensure that the code is well-formatted and adheres to the style
      guidelines of the programming language you are using.
- [ ] Use linters and formatters where applicable.
- [ ] Use "sentence case" for headings and titles in documentation.
- [ ] Write clear and concise comments and documentation for your code.
      For something obvious, avoid comments that just restate the code.
- [ ] After making changes, review the code and documentation to ensure
      up-to-dateness, correctness, consistency, and clarity.
- [ ] Make sure that all code comments, APIs, and documentation are consistent
      with the current state of the codebase.
- [ ] Make sure that the examples in the documentation are runnable, up-to-date
      and reflect the current behavior of the code.      

## File header

- [ ] When possible, put relevant SPDX File Tags at file header.
      See https://spdx.github.io/spdx-spec/v2.3/file-information/
  - [ ] SPDX-FileContributor
  - [ ] SPDX-FileCopyrightText
  - [ ] Default SPDX-FileType for code is "SOURCE"
  - [ ] Default SPDX-FileType for documentation is "DOCUMENTATION"
  - [ ] Default SPDX-License-Identifier for code is "Apache-2.0"
  - [ ] Default SPDX-License-Identifier for documentation is "CC0-1.0"

## API endpoints

- [ ] API endpoints must use proper HTTP return code as suggested by IETF,
      W3C, and other best practices.

## JSON

- [ ] When serialize to JSON, always enclose decimal values
      (for example, xs:decimal) in quotes to guarantee correct type
      interpretation and preserve precision.
- [ ] Make sure JSON is valid and well-formatted.

## HTML

- [ ] Make sure HTML is valid and well-formatted.
- [ ] Make sure there is no trailing whitespace in the HTML file.
- [ ] Be conscious about accessibility. Consider to follow W3C web
      accessibility recommendations when possible.
- [ ] Use sensible and concise element IDs and names that allow code
      readability, name grouping also helps.

## CSS

- [ ] Make sure there is no unused styles.
- [ ] Use sensible and concise element IDs and names that allow code
      readability, name grouping also helps.

## Version

- [ ] When suggest dependencies, recheck the version; if the version exists,
      or if the version compatible with the system or other dependencies.
- [ ] When manage own's project, prefer a Semantic Version.

## SPDX resources

- Official SPDX project website https://spdx.dev/
- SPDX 3.0 spec https://spdx.github.io/spdx-spec/v3.0/
- SPDX 3.0 model https://spdx.org/rdf/3.0/spdx-model.ttl
- SPDX 3.0 JSON Schema https://spdx.org/schema/3.0/spdx-json-schema.json
- SPDX 3.0 JSON-LD context file https://spdx.org/rdf/3.0/spdx-context.jsonld
- SPDX 3.1 spec (under development) https://spdx.github.io/spdx-spec/v3.1-dev/
- SPDX 3.1 spec terms and definition
  https://spdx.github.io/spdx-spec/v3.1-dev/terms-and-definitions/
- SPDX 3 JSON validation guide
  https://github.com/spdx/spdx-3-model/blob/develop/serialization/jsonld/validation.md
- SPDX 3 model format and style guide
  https://github.com/spdx/spdx-3-model/blob/develop/docs/format.md
- SPDX Examples https://github.com/spdx/spdx-examples
  Most of the examples here should be a valid SPDX document.
- NTIA Conformance Checker also provide a small corpus of SPDX documents for
  testing purposes. Some of them could be invalid or incomplete intentionally.
  https://github.com/spdx/ntia-conformance-checker/tree/main/tests
- Use spdx3-validate from PyPI https://pypi.org/project/spdx3-validate/
  (GitHub repo: https://github.com/JPEWdev/spdx3-validate) to validate SPDX 3
  document when applicable.
