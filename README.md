# Coding conventions and styling guide for React applications developed with Typescript

## Naming conventions

### General

- Use consistent names for all the symbols  
  **Reasoning:** Naming conventions help provide a consistent way to find content at a glance. Consistency within the project is vital. Consistency with a team is important. Consistency across a company provides tremendous efficiency. 
- Don't use abbreviations in the names.  
  **Reasonong:** Unabbreviated names such as .service are descriptive and unambiguous. Abbreviations such as .srv, .svc, and .serv can be confusing

### Files and folders

- Use the following pattern for the file names: `[feature-name].[type-suffix].[file-extension]`. For example `medical-records.service.ts` or `contact-list.component.ts`.
  Breakdown:
  - Use kebab-case (hyphen separated words) for feature name
    **Reasoning:** OS independent, fits into the bigger separate-by-symbol conception (path fragments are separated by `/` which is a symbol, files extensions are separated by `.` which is a symbol, words are separated by `-` which is a symbol).
  - Use suffixes to describe feature types
    **Reasoning:** Suffixes provide a consistent way to quickly identify what is in the file and also make it easy to find a specific file type. Suffixes also provide pattern matching for any automated tasks.
- If the file contains a single symbol (interface, class, enum etc.) match the file name to the symbol name. For example:
  - Symbol name: `ContactListComponent`
  - File name: `contact-list.component.ts`  
  
  If the file contains more than one symbol use a general feature description as a feature name. For example, for file that contains all the interfaces for customer feature: `customer.types.ts`  
  **Reasoning:** consistency and easier look up in IDE.
  

# Coming soon...
  
### Symbols

- Interfaces
- Classes
- Enums
- Variables
- Constants
- Functions and methods
- Something else...
