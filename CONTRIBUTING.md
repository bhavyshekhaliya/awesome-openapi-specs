# Contributing to Awesome OpenAPI Specs

Thank you for helping improve the directory and its community-maintained specifications. Contributions should make it easier to find reliable, machine-readable OpenAPI definitions.

## Inclusion Criteria

A submission must:

- Link to a provider-maintained OpenAPI document or include a community-maintained specification derived from the provider's public API documentation.
- Be publicly accessible without requiring a paid account.
- Use OpenAPI 3.x or Swagger/OpenAPI 2.0 in JSON or YAML.
- Describe an API that is usable beyond a demonstration or tutorial.
- Add material value beyond an existing entry.

Do not submit:

- Undocumented or invented API operations and fields.
- General API documentation without an accompanying machine-readable OpenAPI definition.
- GraphQL schemas, Postman collections, protobuf definitions, or JSON Schema files presented as OpenAPI.
- Affiliate, referral, tracking, or URL-shortener links.
- Abandoned links or specifications that cannot be downloaded or inspected.

## Adding an Entry

1. Choose the closest existing category.
2. Add one table row in alphabetical order by provider name.
3. For an `official` entry, link directly to the provider's stable specification, or to its specification directory or repository when multiple variants are available.
4. For a `community-maintained` entry, add `specs/<provider>/openapi.yml`, link to it and the provider's source documentation, and set `externalDocs` in the YAML to that documentation. Use a lowercase provider folder name.
5. Record the available format and OpenAPI version.
6. Add either `official` or `community-maintained`, a concise domain tag, and `open-source` only when applicable.
7. Check that the Markdown table renders, links work, and any local YAML parses with no unresolved local `$ref` pointers. Check community-maintained operations against the source documentation.

Use this row format:

```markdown
| Provider | [API specification](SPEC_URL) | YAML | 3.1 | `official` `category` |
| Provider | [Community specification](specs/provider/openapi.yml) · [source docs](DOCS_URL) | YAML | 3.2.1 | `community-maintained` `category` |
```

## Pull Requests

Keep each pull request focused. In the description, include:

- The provider's official website.
- For `official` entries, evidence that the provider maintains the linked specification. For `community-maintained` entries, the public documentation used as the source and any known gaps.
- The specification format and OpenAPI version.
- The date on which you verified the link.

By contributing, you dedicate original directory content and community-maintained specification content you have the right to license under [CC0 1.0 Universal](LICENSE). Do not copy protected provider documentation into local specifications. Linked provider specifications and documentation keep their original licenses and terms.

## Corrections and Removals

Open an issue or pull request when a link breaks, ownership changes, a specification becomes private, a community-maintained specification drifts from the provider's documentation, or an entry no longer meets the inclusion criteria. Include a replacement source when one exists.
