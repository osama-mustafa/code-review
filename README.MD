# Code Review Checklist

## What is the problem we are trying to solve?
- The merge request title or description
- The commit messages
- The code itself is self explanatory


## Code Structure
- DRY (Don’t repeat yourself) Principle
- KISS (Keep it simple, stupid!!) Principle
- YAGNI (You ain’t gonna need it) Principle
- SOLID Principles
    - The Single Responsibility Principle (SRP)
    - The Open-Closed Principle (OCP)
    - The Liskov Substitution Principle (LSP)
    - The Interface Segregation Principle (ISP)
    - The Dependency Inversion Principle (DIP)

## Design Smells
- [Long Method](https://refactoring.guru/smells/long-method)
- [Duplicate Code](https://refactoring.guru/smells/duplicate-code)
- [Magic Number](https://refactoring.guru/replace-magic-number-with-symbolic-constant)
- [Dead Code](https://refactoring.guru/smells/dead-code)
- [Comments](https://refactoring.guru/smells/comments)


## Naming & Formatting Conventions
- Avoid acronyms
- Avoid preserved keywords
- Avoid ambiguous names
- Consistent Naming Style
    - PascalCase
    - camelCase
    - snake_case
    - kebab-case
- Follow language standards

## Comments
- [ ] Are obvious comments avoided?
- [ ] Are pre- and post-conditions properly described?
- [ ] Are comments written in clear, understandable language and free from jargon?

## Security
- Input Validation
    - [ ] Are all user inputs properly validated?
    - [ ] Are input fields validated for appropriate data types and length?
- Authentication and Authorization
    - [ ] Are passwords securely stored using proper hashing techniques?

## Language Standards & Coding Style Guides
 - [PHP PSR](https://www.php-fig.org/psr/psr-12/)
 - [Python PEP8](https://peps.python.org/pep-0008/)
 - [VueJS Style Guide](https://vuejs.org/style-guide/)
 - [Laravel Best Practices](https://github.com/alexeymezenin/laravel-best-practices)

## Performance
## Data Structures

# Resources
- [Effective Code Review Session By Eng. Ahmed El-Alfy](https://youtu.be/w3pzzrgPAV0?si=LBEktlUJ0B-jjU7e)
- ChatGPT
- Bard