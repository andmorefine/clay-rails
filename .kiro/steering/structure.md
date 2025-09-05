# Project Structure

## Current Organization
```
.
├── .git/           # Git version control
├── .kiro/          # Kiro AI assistant configuration
│   └── steering/   # AI guidance documents
├── LICENSE         # MIT License file
```

## Directory Guidelines

### Root Level
- Keep root directory clean and organized
- Include standard files: README.md, LICENSE, .gitignore
- Configuration files should be at root or in appropriate config directories

### .kiro/steering/
- Contains AI assistant guidance documents
- Files are automatically included in AI context
- Use clear, descriptive filenames
- Keep documents focused and concise

## Future Structure Recommendations
When adding source code:
- Create `src/` or language-specific directories for source files
- Use `docs/` for documentation
- Include `tests/` directory for test files
- Add `examples/` for usage examples
- Consider `scripts/` for build/utility scripts

## Naming Conventions
- Use lowercase with hyphens for directories when possible
- Be consistent with file naming patterns
- Use descriptive names that indicate purpose
- Follow language-specific conventions for source files