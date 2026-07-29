# Contributing to Awesome OpenAPI Specs

Thank you for helping improve the directory. Contributions should make it easier to find reliable, machine-readable OpenAPI definitions.

## Inclusion Criteria

A submission must:

- Link to an OpenAPI document or an official repository or directory that contains OpenAPI documents.
- Be published or maintained by the API provider or the provider's verified organization.
- Be publicly accessible without requiring a paid account.
- Use OpenAPI 3.x or Swagger/OpenAPI 2.0 in JSON or YAML.
- Describe an API that is usable beyond a demonstration or tutorial.
- Add material value beyond an existing entry.

Do not submit:

- Unofficial, reverse-engineered, or community-converted specifications.
- General API documentation without a confirmed machine-readable OpenAPI definition.
- GraphQL schemas, Postman collections, protobuf definitions, or JSON Schema files presented as OpenAPI.
- Affiliate, referral, tracking, or URL-shortener links.
- Abandoned links or specifications that cannot be downloaded or inspected.

## Adding an Entry

1. Choose the closest existing category.
2. Add one table row in alphabetical order by provider name.
3. Link directly to the specification when the provider publishes one stable file. Link to the official specification directory or repository when multiple APIs or generated variants are available.
4. Record the available format and OpenAPI version.
5. Add `official`, a concise domain tag, and `open-source` only when applicable.
6. Check that the Markdown table renders correctly and that every changed link works.

Use this row format:

```markdown
| Provider | [API specification](SPEC_URL) | YAML | 3.1 | `official` `category` |
```

## Pull Requests

Keep each pull request focused. In the description, include:

- The provider's official website.
- Evidence that the provider owns or maintains the linked specification.
- The specification format and OpenAPI version.
- The date on which you verified the link.

By contributing, you agree that your changes to this curated list are available under [CC0 1.0 Universal](LICENSE). The linked specifications keep their original licenses.

## Corrections and Removals

Open an issue or pull request when a link breaks, ownership changes, a specification becomes private, or an entry no longer meets the inclusion criteria. Include a replacement official source when one exists.
