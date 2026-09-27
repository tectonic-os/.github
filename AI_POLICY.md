# AI use policy

This policy covers every tectonic-os repository.

## Contributions

You may use AI tools to write a contribution. You are its author, and you are
accountable for all of it.

- Review the whole change before you submit it, and be able to explain every
  part of it.
- Answer review in your own words.
- A commit with substantial AI assistance carries the trailer
  `Assisted-by: AI`. A commit that is effectively all generated carries
  `Generated-by: AI`. Neither trailer names a model or a tool, and no AI is
  listed as a co-author.
- Only a human adds `Signed-off-by`. The sign-off certifies the
  [Developer Certificate of Origin](https://developercertificate.org/) for the
  whole change.
- A generated change of more than about 500 lines starts as a design issue,
  before any pull request.
- The terms of the tool you use must not restrict its output from being
  contributed under the project's licence. The
  [Linux Foundation's generative AI policy](https://www.linuxfoundation.org/legal/generative-ai)
  sets the same requirement.

## Issues, reviews and discussions

Write issues, reviews, discussions and security reports in your own words. A
translation is the exception, and you say that it is one.

## Agents

Each repository carries an `AGENTS.md` that restates these rules for an AI
agent working in it.

## Sources

This policy follows the practice of two CNCF projects, in the project's own
words:

- bootc's [`AGENTS.md`](https://github.com/bootc-dev/bootc/blob/main/AGENTS.md).
- Podman's
  [`LLM_POLICY.md`](https://github.com/podman-container-tools/community/blob/main/LLM_POLICY.md).
  Its text is licensed CC-BY-ND-4.0, so this policy links it and does not
  adapt it.
