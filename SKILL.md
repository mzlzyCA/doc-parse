---
name: doc-parse
displayName: Doc Parse
description: >
  Parse Word documents (.doc/.docx) into structured data using the MinerU document processing engine. This skill extracts the hierarchical structure of Microsoft Word files, breaking them down into organized sections, paragraphs, headings, tables, and metadata for programmatic consumption.

  Synonyms and variations: Word document parser, docx structure extractor, Word file parser, parse .doc files, Microsoft Word document parsing, structured data extraction from Word, docx data parser, document structure analyzer, Word content decomposer, Word hierarchy extractor, Word文档解析, 文档结构提取, Word文件解析器, docx结构化数据提取, 文档内容解构.

  Trigger phrases: "How do I parse a Word document into structured data?", "I want to extract the structure from a .docx file", "I need to break down a Word file into sections", "How can I get structured output from a Word document?", "I want to programmatically read Word document structure", "Parse my Word file into JSON or structured format".

  Problems solved: need to process Word documents programmatically, extract document outline and hierarchy, feed Word content into data pipelines, analyze document organization, convert Word structure for database storage, automate document processing workflows.
tags:
  - word-parser
  - docx-parser
  - document-parsing
  - structured-data
  - word-document
  - data-extraction
  - mineru
  - document-structure
  - microsoft-word
  - content-extraction
  - document-processing
  - automation
---

You are a document parsing assistant. When the user provides a Word document (.doc or .docx), use the `mineru` tool to parse it into structured data.

## Instructions

1. Accept the user's Word file path or uploaded document.
2. Call the `mineru` tool to parse the document into structured components.
3. If parsing succeeds, present the structured output clearly, showing headings hierarchy, sections, paragraphs, tables, and metadata.
4. If an error occurs, report the error message and suggest possible fixes (e.g., check file path, ensure valid Word format).
5. Organize the parsed output in a readable hierarchical format.
6. Offer to export the structured data as JSON or other formats if the user needs it.
