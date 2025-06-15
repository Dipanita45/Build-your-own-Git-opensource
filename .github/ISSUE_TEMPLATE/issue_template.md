---
name: Bug Report / Feature Request
about: Report issues or suggest features for the Build Your Own Git project
title: '[TYPE] Brief description of the issue'
labels: ''
assignees: ''
---

## Issue Type
<!-- Please select one by putting an 'x' in the brackets -->
- [ ] Bug Report
- [ ] Feature Request
- [ ] Git Command Implementation
- [ ] CodeCrafters Challenge Issue
- [ ] Documentation Issue
- [ ] Performance Issue
- [ ] Question/Help Needed

## Git Command Affected
<!-- If applicable, specify which Git command is having issues -->
- [ ] `init` - Repository initialization
- [ ] `cat-file` - Object content display
- [ ] `ls-tree` - Tree object listing
- [ ] `commit` - Commit creation
- [ ] `clone` - Repository cloning
- [ ] Object management (blobs, trees, commits)
- [ ] Other: ___________

## Environment
<!-- Please complete the following information -->
- **OS**: [e.g., macOS, Linux, Windows]
- **Java Version**: [e.g., OpenJDK 11, Oracle JDK 17]
- **Maven Version**: [e.g., 3.8.1]
- **IDE/Editor**: [e.g., VS Code, IntelliJ IDEA]
- **CodeCrafters Stage**: [e.g., Stage 1, Stage 5, etc.]

## Command/Steps to Reproduce
<!-- Provide the exact commands that cause the issue -->
```bash
# Compilation commands
javac -d out src/main/java/Main.java

# Execution command that fails
java -cp out src/Main/java/Main.java [command] [args]

# Or using the shell script
./your_program.sh [command] [args]
```

## Expected Behavior
<!-- What should happen according to Git specifications or CodeCrafters requirements -->

## Actual Behavior
<!-- What actually happens -->

## Error Output
<!-- Paste the complete error message or unexpected output -->
```
Paste error messages/output here
```

## Test Repository State
<!-- If the issue involves a specific repository state, describe it -->
- [ ] Empty repository (just initialized)
- [ ] Repository with staged files
- [ ] Repository with commits
- [ ] Cloned repository
- [ ] Repository with specific object types

**Repository structure (if relevant):**
```
.git/
├── objects/
├── refs/
└── ...
```

## Git Object Details
<!-- For object-related issues, provide hash and type if known -->
- **Object Hash**: [e.g., abc123...]
- **Object Type**: [e.g., blob, tree, commit]
- **Object Size**: [if known]

## Code Snippets
<!-- If you've identified the problematic code area -->
```java
// Relevant code from Main.java or other files
```

## Comparison with Real Git
<!-- How does the real Git handle this scenario? -->
```bash
# Real Git command
git [command] [args]
# Output from real Git
```

## CodeCrafters Specific
<!-- If this is related to CodeCrafters challenge -->
- **Stage Number**: [e.g., Stage 3]
- **Test Case**: [Brief description of failing test]
- **CodeCrafters Error Message**: 
```
Paste CodeCrafters test output here
```

## Additional Context
<!-- Add any other context about the problem -->
- [ ] This worked in a previous version
- [ ] This is a new feature implementation
- [ ] This affects multiple Git commands
- [ ] This is related to Git internals/object storage

## Proposed Solution
<!-- If you have ideas on how to fix the issue -->

## Related Issues
<!-- Link to any related issues or CodeCrafters discussions -->

## Checklist
<!-- Please check all that apply -->
- [ ] I have tested with the latest code
- [ ] I have compared behavior with real Git
- [ ] I have checked the CodeCrafters requirements
- [ ] I have included complete error messages
- [ ] I have provided the exact commands used
- [ ] I have searched existing issues to avoid duplicates