# Words API (words)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Words API is a RESTful English-language API that provides definitions, synonyms, antonyms, related words, syllables, pronunciation (IPA), rhymes, frequency, and hierarchical lexical relationships (typeOf, hasTypes, partOf, hasParts, memberOf, similarTo, also, entails, inCategory, inRegion, pertainsTo, etc.) for more than 150,000 English words. Distributed and metered through the RapidAPI marketplace.

**APIs.json:** [https://www.wordsapi.com/docs/](https://www.wordsapi.com/docs/)

## Tags

- Dictionaries
- Linguistics
- English
- Thesaurus
- Lexical Data
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Words API

RESTful English-language dictionary, thesaurus, and lexical-relationship API. One base resource — /words/{word} — plus 28 sub-resources for individual detail types (definitions, synonyms, antonyms, examples, rhymes, frequency, syllables, pronunciation, hasTypes, typeOf, partOf, hasParts, instances, instanceOf, similarTo, also, entails, memberOf, hasMembers, substanceOf, hasSubstances, inCategory, hasCategories, usageOf, hasUsages, inRegion, regionOf, pertainsTo) and a /words search/random endpoint with letter, sound, and part-of-speech filters.

- **Human URL:** [https://www.wordsapi.com/docs/](https://www.wordsapi.com/docs/)
- **Base URL:** `https://wordsapiv1.p.rapidapi.com`

#### Tags

- Dictionaries
- Thesaurus
- Linguistics
- English

#### Properties

- [Documentation](https://www.wordsapi.com/docs/)
- [API Reference](https://www.wordsapi.com/docs/#endpoints)
- [Authentication](https://www.wordsapi.com/docs/#authorization)
- [Sign Up](https://rapidapi.com/dpventures/api/wordsapi)
- [OpenAPI](openapi/words-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/words-word-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-definitions-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-synonyms-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-antonyms-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-examples-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-rhymes-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-frequency-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-syllables-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-pronunciation-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/words-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/words-word-entry-structure.json)
- [JSON Structure](json-structure/words-result-structure.json)
- [Example](examples/words-word-entry-example.json)
- [Example](examples/words-definitions-response-example.json)
- [Example](examples/words-synonyms-response-example.json)
- [Example](examples/words-frequency-response-example.json)
- [Example](examples/words-search-response-example.json)

## Common Properties

- [Website](https://www.wordsapi.com/)
- [Documentation](https://www.wordsapi.com/docs/)
- [Sign Up](https://rapidapi.com/dpventures/api/wordsapi)
- [Pricing](https://rapidapi.com/dpventures/api/wordsapi/pricing)
- [Blog](https://blog.wordsapi.com/)
- [Contact](mailto:support@wordsapi.com)
- [GitHub Organization](https://github.com/WordsAPI)
- [GitHub Repository](https://github.com/WordsAPI/wordfrequencies)
- [Marketplace](https://rapidapi.com/dpventures/api/wordsapi)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [Plans](plans/words-plans-pricing.yml)
- [Rate Limits](rate-limits/words-rate-limits.yml)
- [Fin Ops](finops/words-finops.yml)
- [Spectral Rules](rules/words-rules.yml)
- [Vocabulary](vocabulary/words-vocabulary.yml)
- [JSON-LD](json-ld/words-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
