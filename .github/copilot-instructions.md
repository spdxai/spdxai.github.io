# Copilot instructions

## General language use

- [ ] Prefer clear, concise, and unambiguous sentences.
- [ ] Avoid words and phrases that may have more than one interpretation.
- [ ] Avoid overly long paragraphs; break text into shorter paragraphs,
      bullet points, or numbered lists to improve readability.
- [ ] Separate distinct concepts, processes, criteria, or categories to aid
      comprehension.
- [ ] Use parallel structures in lists and a consistent writing style for
      related content so readers can compare easily.
- [ ] When citing references, use Chicago style unless a different style is
      specified.
- [ ] When writing requirements, use verbal forms consistently. Prefer the
      ISO/IEC verbal form (ISO/IEC Directives, Part 2) or the IETF form (RFC
      2119 / RFC 8174) depending on the document: use IETF for internet/web
      work and ISO for SPDX-specific documents.
- [ ] Use either American or British spelling consistently.
  - [ ] SPDX default is American spelling.
- [ ] Use active voice where possible.
- [ ] Use gender-neutral language.
- [ ] Avoid idioms, colloquialisms, and culturally specific references to
      ensure clarity for a global audience.
- [ ] When using acronyms or abbreviations, define them on first use.
- [ ] Spell check the text to avoid typos and spelling mistakes.

## Naming conventions

- [ ] Follow standard naming conventions for the programming language
      and framework you are using.
- [ ] For URLs/IRIs, use lowercase letters and hyphens to separate words
      (e.g., `my-api-endpoint`) and follow W3C Cool URIs for the Semantic Web:
      <https://www.w3.org/TR/cooluris/>
- [ ] Consult Schema.org vocabularies when deciding about names.

## Tidy code and documentation

- [ ] Ensure that the code is well-formatted and adheres to the style
      guidelines of the programming language you are using.
- [ ] Use linters and formatters where applicable.
- [ ] Use "sentence case" for headings and titles in documentation.
- [ ] Write clear and concise comments and documentation for your code.
      For something obvious, avoid comments that just restate the code.
- [ ] After making changes, review the code and documentation to ensure
      they are up to date, correct, consistent, and clear.
- [ ] Ensure comments, APIs, and documentation reflect the current codebase.
- [ ] Keep documentation examples runnable and up to date.

## File header

- [ ] When possible, put relevant SPDX File Tags at file header.
      See <https://spdx.github.io/spdx-spec/v2.3/file-information/>
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
- [ ] Ensure styles are used and organized; avoid unused rules.

## Version

- [ ] When suggest dependencies, recheck the version; if the version exists,
- [ ] When suggesting dependencies, verify the version exists and is
      compatible with the system and other project dependencies.
- [ ] When managing a project, prefer Semantic Versioning.

## SPDX resources

- Official SPDX project website <https://spdx.dev/>
- SPDX 3.0 spec <https://spdx.github.io/spdx-spec/v3.0/>
- SPDX 3.0 model <https://spdx.org/rdf/3.0/spdx-model.ttl>
- SPDX 3.0 JSON Schema <https://spdx.org/schema/3.0/spdx-json-schema.json>
- SPDX 3.0 JSON-LD context file <https://spdx.org/rdf/3.0/spdx-context.jsonld>
- SPDX 3.1 spec (under development) <https://spdx.github.io/spdx-spec/v3.1-dev/>
- SPDX 3.1 spec terms and definition
  <https://spdx.github.io/spdx-spec/v3.1-dev/terms-and-definitions/>
- SPDX 3 JSON validation guide
  <https://github.com/spdx/spdx-3-model/blob/develop/serialization/jsonld/validation.md>
- SPDX 3 model format and style guide
  <https://github.com/spdx/spdx-3-model/blob/develop/docs/format.md>
- SPDX Examples <https://github.com/spdx/spdx-examples>
  Most of the examples there should be a valid SPDX document.
- Using SDPX <https://github.com/spdx/using>
  Guidelines on using SPDX in different contexts.
- NTIA Conformance Checker also provide a small corpus of SPDX documents for
  testing purposes. Some of them could be invalid or incomplete intentionally.
  <https://github.com/spdx/ntia-conformance-checker/tree/main/tests>
- Use spdx3-validate from PyPI <https://pypi.org/project/spdx3-validate/>
  (GitHub repo: <https://github.com/JPEWdev/spdx3-validate>) to validate SPDX 3
  document when applicable.
