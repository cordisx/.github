# Organization Configuration Rules

- Follow the [organization file-size rule](https://github.com/cordisx/cordisxmono/blob/main/.agents/rules/file-size.md) when adding or expanding files.
- Keep shared templates generic across CordisX repositories.
- Do not place product-specific implementation rules here.
- State clearly that CordisX is unofficial and is not an OpenAI product.
- Do not include private roadmap material in public organization files.

## Shared quality configuration

The local dprint entry points consume an exact formal
[Mono quality configuration](https://github.com/cordisx/cordisxmono/blob/c63c2e8c2ba7e11502934a52ad2ce3734e804cdc/.agents/docs/quality-tooling.md).
The Shared quality configuration CI job checks the installed configuration and
tracked-file coverage; inspect its report for excluded paths.
This documentation-only repository has no empty source-lint job.
Update the formatter reference and CI provider SHA together.
