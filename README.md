# Words API (words)

Words API is a RESTful English-language API that provides definitions, synonyms,
antonyms, related words, syllables, pronunciation (IPA), rhymes, frequency, and
hierarchical lexical relationships (typeOf, hasTypes, partOf, hasParts, memberOf,
similarTo, also, entails, inCategory, inRegion, pertainsTo, etc.) for more than
150,000 English words. Distributed and metered through the RapidAPI marketplace.

**URL:** [Visit APIs.json URL](https://www.wordsapi.com/docs/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Dictionaries, Linguistics, English, Thesaurus, Lexical Data, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Words API

RESTful English-language dictionary, thesaurus, and lexical-relationship API. One
base resource — /words/{word} — plus 28 sub-resources for individual detail types
(definitions, synonyms, antonyms, examples, rhymes, frequency, syllables,
pronunciation, hasTypes, typeOf, partOf, hasParts, instances, instanceOf,
similarTo, also, entails, memberOf, hasMembers, substanceOf, hasSubstances,
inCategory, hasCategories, usageOf, hasUsages, inRegion, regionOf, pertainsTo)
and a /words search/random endpoint with letter, sound, and part-of-speech filters.

**Human URL:** [https://www.wordsapi.com/docs/](https://www.wordsapi.com/docs/)

#### Tags

- Dictionaries, Thesaurus, Linguistics, English

#### Properties

- [Documentation](https://www.wordsapi.com/docs/)
- [APIReference](https://www.wordsapi.com/docs/#endpoints)
- [Authentication](https://www.wordsapi.com/docs/#authorization)
- [SignUp](https://rapidapi.com/dpventures/api/wordsapi)
- [OpenAPI](openapi/words-openapi.yml)
- [NaftikoCapability — Word](capabilities/words-word.yaml)
- [NaftikoCapability — Definitions](capabilities/words-definitions.yaml)
- [NaftikoCapability — Thesaurus](capabilities/words-thesaurus.yaml)
- [NaftikoCapability — Examples](capabilities/words-examples.yaml)
- [NaftikoCapability — Phonetics](capabilities/words-phonetics.yaml)
- [NaftikoCapability — Frequency](capabilities/words-frequency.yaml)
- [NaftikoCapability — Hierarchy](capabilities/words-hierarchy.yaml)
- [NaftikoCapability — Categories](capabilities/words-categories.yaml)
- [NaftikoCapability — Search](capabilities/words-search.yaml)
- [JSONSchema — WordEntry](json-schema/words-word-entry-schema.json)
- [JSONSchema — Result](json-schema/words-result-schema.json)
- [JSONSchema — DefinitionsResponse](json-schema/words-definitions-response-schema.json)
- [JSONSchema — SynonymsResponse](json-schema/words-synonyms-response-schema.json)
- [JSONSchema — AntonymsResponse](json-schema/words-antonyms-response-schema.json)
- [JSONSchema — ExamplesResponse](json-schema/words-examples-response-schema.json)
- [JSONSchema — RhymesResponse](json-schema/words-rhymes-response-schema.json)
- [JSONSchema — FrequencyResponse](json-schema/words-frequency-response-schema.json)
- [JSONSchema — SyllablesResponse](json-schema/words-syllables-response-schema.json)
- [JSONSchema — PronunciationResponse](json-schema/words-pronunciation-response-schema.json)
- [JSONSchema — SearchResponse](json-schema/words-search-response-schema.json)
- [JSONStructure — WordEntry](json-structure/words-word-entry-structure.json)
- [JSONStructure — Result](json-structure/words-result-structure.json)
- [Example — WordEntry](examples/words-word-entry-example.json)
- [Example — DefinitionsResponse](examples/words-definitions-response-example.json)
- [Example — SynonymsResponse](examples/words-synonyms-response-example.json)
- [Example — FrequencyResponse](examples/words-frequency-response-example.json)
- [Example — SearchResponse](examples/words-search-response-example.json)

## Common Properties

- [Website](https://www.wordsapi.com/)
- [Documentation](https://www.wordsapi.com/docs/)
- [SignUp](https://rapidapi.com/dpventures/api/wordsapi)
- [Pricing](https://rapidapi.com/dpventures/api/wordsapi/pricing)
- [Blog](https://blog.wordsapi.com/)
- [Contact](mailto:support@wordsapi.com)
- [GitHubOrganization](https://github.com/WordsAPI)
- [GitHubRepository — Word Frequencies Dataset](https://github.com/WordsAPI/wordfrequencies)
- [Marketplace — RapidAPI Listing](https://rapidapi.com/dpventures/api/wordsapi)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Plans](plans/words-plans-pricing.yml)
- [RateLimits](rate-limits/words-rate-limits.yml)
- [FinOps](finops/words-finops.yml)
- [SpectralRules](rules/words-rules.yml)
- [Vocabulary](vocabulary/words-vocabulary.yml)
- [JSONLD](json-ld/words-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| 150,000+ English Words | Definitions, syllables, pronunciation, and lexical relationships across more than 150,000 English words. |
| Definitions and Parts of Speech | Per-sense definitions grouped by part of speech (noun, verb, adjective, adverb). |
| Thesaurus (Synonyms and Antonyms) | Interchangeable and opposite-meaning words for each sense of a word. |
| Lexical Hierarchies | typeOf, hasTypes, partOf, hasParts, instanceOf, hasInstances, memberOf, hasMembers, substanceOf, hasSubstances, inCategory, hasCategories relationships. |
| Pronunciation in IPA | International Phonetic Alphabet pronunciation, optionally split per part of speech. |
| Syllable Breakdown | Syllable count and the ordered list of syllables for each word. |
| Rhymes | Lists of rhyming words, distinguished by pronunciation variant where pronunciations differ. |
| Frequency Data | Zipf frequency (1–7), per-million occurrence rate, and corpus diversity score derived from large English subtitle corpora. |
| Examples | Sample sentences illustrating real usage for each sense. |
| Regional and Domain Usage | inRegion, regionOf, inCategory, hasCategories, usageOf, hasUsages relationships connect words to dialects and subject domains. |
| Random and Filtered Word Search | /words search endpoint supports letter count, letter pattern, phoneme count, IPA pattern, part of speech, and random selection. |

## Use Cases

| Name | Description |
|------|-------------|
| Dictionary and Thesaurus Applications | Power dictionary, thesaurus, and "word of the day" applications with definitions, synonyms, and related words. |
| Word Games and Puzzles | Drive crossword, Scrabble-style, and anagram games with filtered word search, rhymes, and difficulty-tunable random word selection. |
| Writing and Editing Tools | Build grammar, style, and writing assistants that suggest synonyms, antonyms, and frequency-aware alternatives. |
| Language Learning and Education | Provide IPA pronunciation, syllable splits, frequency, and example sentences for ESL and vocabulary-building apps. |
| NLP and Text Enrichment | Enrich downstream NLP pipelines with hypernyms, hyponyms, meronyms, and domain labels for entity expansion. |
| Voice and Speech Applications | Use IPA pronunciation and syllable data for speech synthesis, ASR vocabulary tuning, and pronunciation coaching. |
| Chatbots and Conversational Agents | Disambiguate user input by mapping words to their senses, hypernyms, and categories at runtime. |
| Content Generation and Rewriting | Drive paraphrasing and content-variation engines with synonym, similar-to, and pertains-to relationships. |

## Integrations

| Name | Description |
|------|-------------|
| RapidAPI | Words API is distributed, authenticated, and metered through the RapidAPI marketplace. |
| WordNet | Lexical relationships (typeOf, hasParts, memberOf, etc.) follow the WordNet relational model. |
| Subtitle Corpora | Frequency data is derived from large English movie and television subtitle corpora (see WordsAPI/wordfrequencies on GitHub). |

## Solutions

| Name | Description |
|------|-------------|
| Free Tier | 2,500 requests per day at no charge for prototyping, students, and small projects. |
| Pro | $10 / month, 25,000 requests per day for production applications and games. |
| Ultra | $49 / month, 250,000 requests per day for high-volume consumer applications. |
| Mega | $89 / month, 500,000 requests per day for very high-volume production workloads. |
| Data Purchase | One-time $629 purchase of the full Words API dataset for local hosting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Words API OpenAPI](openapi/words-openapi.yml) — 30 operations across 9 tags.

### JSON Schema

36 standalone JSON Schema files in [`json-schema/`](json-schema/) covering every response type — WordEntry, Result, DefinitionEntry, Pronunciation, Syllables, Frequency, and every detail-type response (Synonyms, Antonyms, Examples, Rhymes, Frequency, Syllables, Pronunciation, HasTypes, TypeOf, PartOf, HasParts, Instances, InstanceOf, SimilarTo, Also, Entails, MemberOf, HasMembers, SubstanceOf, HasSubstances, InCategory, HasCategories, UsageOf, HasUsages, InRegion, RegionOf, PertainsTo, Search).

### JSON Structure

36 JSON Structure files in [`json-structure/`](json-structure/) — one per JSON Schema, generated using https://json-structure.org/meta/core/v0/#.

### JSON-LD

- [Words API JSON-LD Context](json-ld/words-context.jsonld) — Linked-data context aligning Words API terms with schema.org and the words: namespace.

### Examples

36 realistic example payloads in [`examples/`](examples/) — one per JSON Schema.

## Capabilities

Self-contained Naftiko capabilities (one file per OpenAPI tag) — each declares an inline `consumes` block plus REST and MCP exposers.

| File | API | Tag | Operations |
|------|-----|-----|------------|
| [words-word.yaml](capabilities/words-word.yaml) | Words API | Word | 1 |
| [words-definitions.yaml](capabilities/words-definitions.yaml) | Words API | Definitions | 1 |
| [words-thesaurus.yaml](capabilities/words-thesaurus.yaml) | Words API | Thesaurus | 4 |
| [words-examples.yaml](capabilities/words-examples.yaml) | Words API | Examples | 1 |
| [words-phonetics.yaml](capabilities/words-phonetics.yaml) | Words API | Phonetics | 3 |
| [words-frequency.yaml](capabilities/words-frequency.yaml) | Words API | Frequency | 1 |
| [words-hierarchy.yaml](capabilities/words-hierarchy.yaml) | Words API | Hierarchy | 11 |
| [words-categories.yaml](capabilities/words-categories.yaml) | Words API | Categories | 7 |
| [words-search.yaml](capabilities/words-search.yaml) | Words API | Search | 1 |

## Vocabulary

- [Words API Vocabulary](vocabulary/words-vocabulary.yml) — Unified taxonomy mapping 14 resources, 3 actions, 9 workflows, and 11 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Words API Spectral Ruleset](rules/words-rules.yml) — 30 rules across 11 categories enforcing Words API conventions (camelCase paths/params, RapidAPI key auth, JSON-only, GET-only, Title-Case tags, etc.).

## Plans and Commercial Surface

- [Plans / Pricing](plans/words-plans-pricing.yml) — API Commons Plans description of Basic / Pro / Ultra / Mega tiers and the one-time Data Purchase.
- [Rate Limits](rate-limits/words-rate-limits.yml) — API Commons Rate Limits description (daily quotas per tier, gateway burst behavior).
- [FinOps](finops/words-finops.yml) — FOCUS-aligned FinOps view (meters, principles, charge categories).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
