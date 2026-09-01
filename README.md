# THT Legal Data — EU Regulatory Benchmark Public Sample

Limited public technical sample of a human-audited multilingual EU regulatory benchmark.

## What this is

THT Legal Data is a human-audited multilingual EU regulatory benchmark comprising more than 5,000 regulatory segments, each aligned across all 12 EU languages and based on official EU legal sources.

This repository provides a limited public technical sample illustrating the structure of the benchmark, its multilingual alignment, benchmark organization, source traceability, and potential mappings to evaluation workflows.

The public sample is intentionally small. It is designed to make the benchmark structure easier to inspect, not to distribute the full benchmark.

## What the public sample includes

This repository includes five illustrative alignment groups in English, French and German.

The sample shows:

- structured regulatory segment identifiers;
- references to official EU legal sources;
- article and paragraph-level organization;
- aligned multilingual segment examples;
- limited language coverage for illustration purposes;
- basic source traceability fields;
- examples of how benchmark entries may be mapped to evaluation workflows involving retrieval, grounding, faithfulness, translation fidelity and cross-language consistency.

The public sample uses only a very limited subset of the benchmark structure.

## What the public sample does not include

This repository does not contain:

- the full THT Legal Data benchmark;
- all 12 covered EU languages;
- the complete set of more than 5,000 regulatory segments;
- complete evaluation suites;
- standardized RAG test sets;
- production-ready input/output datasets;
- fully defined retrieval-context structures;
- framework-specific benchmark formats;
- legal conclusions;
- compliance determinations;
- model scores;
- leaderboard results.

The public sample is illustrative only.

## Benchmark scope

The full THT Legal Data benchmark currently combines:

- multilingual regulatory content;
- structured multilingual segmentation;
- multilingual alignment review;
- traceability to official EU legal sources;
- human-audited QA workflows;
- regulatory content aligned across 12 EU languages.

The benchmark is based on official EU legal sources and focuses on EU regulatory materials relevant to AI, data governance, digital regulation and related legal frameworks.

Each regulatory segment in the full benchmark is aligned across all 12 covered EU languages.

## Why multilingual EU regulatory evaluation is difficult

Multilingual legal and regulatory content presents challenges that are often underrepresented in general-purpose evaluation environments.

These challenges may include:

- preservation of regulatory meaning across language versions;
- terminology consistency across EU legal languages;
- cross-language semantic drift;
- structural differences between language versions;
- source traceability requirements;
- multilingual retrieval inconsistencies;
- quality assessment of legal and regulatory information in regulated contexts.

A benchmark based on aligned official EU legal content can provide a structured environment for examining these issues.

## Potential evaluation relevance

The benchmark may support evaluation workflows involving:

- retrieval quality;
- source grounding;
- faithfulness;
- cross-language consistency;
- multilingual consistency;
- regulatory QA;
- legal and regulatory information quality assessment;
- multilingual evaluation;
- translation fidelity;
- terminology consistency;
- preservation of regulatory meaning;
- AI reliability assessment in regulated contexts.

The benchmark may be relevant to teams working on AI evaluation, legal AI, regulatory intelligence, compliance AI, multilingual AI, translation quality evaluation, legal data infrastructure, policy intelligence, or source-grounded regulatory information workflows.

## What the benchmark is not

THT Legal Data is not:

- a legal AI application;
- a legal assistant;
- a compliance platform;
- a legal reasoning benchmark;
- a hallucination benchmark;
- a RAG benchmark;
- an agent benchmark;
- a benchmark for autonomous agents.

It does not produce legal conclusions, perform compliance determinations, validate regulatory compliance, measure agent autonomy, or provide legal advice.

It is an evaluation-oriented multilingual EU regulatory benchmark based on aligned official EU legal content, structured multilingual segmentation, source traceability and human-audited QA workflows.

## Public sample language coverage

The full benchmark covers 12 EU languages.

This public sample is intentionally limited to three languages for illustration:

- English;
- French;
- German.

This limited language subset is used only to illustrate benchmark structure and multilingual alignment. It does not represent the full language coverage of the benchmark.

## Repository structure

```text
README.md
DATA_NOTICE.md
docs/
  benchmark_structure.md
  sample_fields.md
  evaluation_mapping_examples.md
sample/
  sample_segments.csv
  sample_alignment_view.md
  sample_source_traceability.md
```

## Sample files

| File | Purpose |
|---|---|
| `sample/sample_segments.csv` | Machine-readable public sample with five alignment groups in EN / FR / DE |
| `sample/sample_alignment_view.md` | Human-readable view of the same aligned sample entries |
| `sample/sample_source_traceability.md` | Compact table linking sample entries to CELEX identifiers and official EUR-Lex URLs |
| `docs/sample_fields.md` | Explanation of the public CSV fields |
| `docs/benchmark_structure.md` | High-level explanation of benchmark organization |
| `docs/evaluation_mapping_examples.md` | Illustrative mappings to possible evaluation workflows |
| `DATA_NOTICE.md` | Data notice and reuse clarification |

## Example data fields

A public sample entry includes fields such as:

| Field | Description |
|---|---|
| `segment_id` | Public sample identifier for one language-specific segment entry |
| `alignment_group_id` | Identifier linking aligned language versions of the same regulatory segment |
| `celex_id` | CELEX identifier of the EU legal act |
| `legal_act_short_title` | Short title of the legal act |
| `legal_act_full_title` | Full regulatory act reference |
| `article` | Article number or identifier |
| `paragraph` | Paragraph number, where applicable |
| `fine_segment_order` | Order of the fine-grained segment within the selected structural unit |
| `language` | Language code |
| `segment_text` | Regulatory text for the selected language |
| `official_source_url` | Link to the official EU legal source |
| `public_sample_note` | Brief note explaining why the segment was selected for the public sample |

The full benchmark may contain additional internal fields, QA layers or methodological metadata that are not included in the public sample.

## Example evaluation mapping categories

The public sample illustrates potential mappings to evaluation workflows such as:

| Evaluation area | Possible relevance |
|---|---|
| Retrieval quality | Assess whether relevant regulatory segments can be retrieved from structured multilingual content |
| Source grounding | Review whether outputs remain traceable to official EU legal sources |
| Faithfulness | Compare generated, summarized or transformed outputs against source regulatory content |
| Cross-language consistency | Examine whether meaning is preserved across aligned language versions |
| Translation fidelity | Assess preservation of legal and regulatory meaning across language pairs |
| Terminology consistency | Examine whether key legal and regulatory terms remain consistent |
| Regulatory QA | Support review of legal and regulatory information quality in structured workflows |

These mappings are illustrative. They do not constitute complete evaluation suites or framework-specific benchmark formats.

## Sample Evaluation Pack

A Sample Evaluation Pack is available on request.

The Sample Evaluation Pack illustrates the structure of the benchmark, its multilingual alignment, benchmark organization, and potential mappings to evaluation workflows involving retrieval, grounding, faithfulness, translation fidelity and cross-language consistency.

Request the Sample Evaluation Pack here:

https://www.thtlegaldata.com/sample-evaluation-pack

## Main website

For more information about THT Legal Data:

https://www.thtlegaldata.com

## Contact

Francis Manson  
Founder, THT Legal Data  
PhD in Law  
Court-certified legal translator, France  

contact@thtlegaldata.com

## Data notice

This repository contains only a limited public technical sample.

The sample is provided for inspection and discussion of benchmark structure, multilingual alignment, source traceability and potential evaluation relevance. It is not the full benchmark and should not be treated as a production-ready dataset, evaluation suite, legal information product, compliance tool or legal advice resource.

For access to a broader Sample Evaluation Pack or to discuss licensing of the full benchmark, please contact THT Legal Data.
