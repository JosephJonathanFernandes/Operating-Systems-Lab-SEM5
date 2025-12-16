# Contributing to Operating Systems Lab

Thank you for your interest in contributing to this educational repository! This document provides guidelines for contributing to make the process smooth and effective.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [Coding Standards](#coding-standards)
- [Commit Messages](#commit-messages)
- [Pull Request Process](#pull-request-process)

## 📜 Code of Conduct

This project adheres to a Code of Conduct that all contributors are expected to follow. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## 🤝 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When creating a bug report, include:

- **Clear title and description**
- **Steps to reproduce** the issue
- **Expected vs actual behavior**
- **System information** (OS, compiler version, etc.)
- **Code snippets** or screenshots if applicable

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- **Clear title and description**
- **Use case** explaining why this would be useful
- **Possible implementation** approach
- **Alternative solutions** you've considered

### Code Contributions

Contributions can include:

- **Bug fixes**
- **Algorithm optimizations**
- **Documentation improvements**
- **New experiment implementations**
- **Test cases**
- **Code comments and explanations**

## 🚀 Getting Started

1. **Fork the repository** to your GitHub account
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/your-username/Operating-Systems-Lab-SEM5.git
   cd Operating-Systems-Lab-SEM5
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** following the coding standards
5. **Test your changes** thoroughly
6. **Commit your changes** with clear messages
7. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
8. **Open a Pull Request** from your fork to the main repository

## 📝 Contribution Guidelines

### File Organization

- Place files in appropriate experiment folders
- Use descriptive filenames
- Include comments explaining complex logic
- Add README sections if adding new experiments

### Documentation

- Update README.md if adding new experiments
- Include inline comments for complex algorithms
- Add usage examples where applicable
- Document any prerequisites or dependencies

### Testing

- Test your code with various inputs
- Include edge cases
- Verify compilation without warnings
- Test on different platforms if possible

## 💻 Coding Standards

### C++ Code Style

```cpp
// Use meaningful variable names
int processCount;  // Good
int n;            // Avoid unless in mathematical context

// Include comments for complex logic
// Calculate waiting time for each process
for (int i = 1; i < processCount; i++) {
    waitingTime[i] = burstTime[i-1] + waitingTime[i-1];
}

// Use consistent indentation (4 spaces)
void calculateAverageTime() {
    // Function body
}

// Include header comments
/*
 * Function: calculateWaitingTime
 * Purpose: Calculates waiting time for all processes
 * Parameters: processes[] - array of processes
 *            n - number of processes
 */
```

### Shell Script Style

```bash
#!/bin/bash

# Use descriptive variable names
file_count=0

# Add comments for non-obvious operations
# Check if directory exists before processing
if [ -d "$directory" ]; then
    # Process files
fi

# Use proper error handling
if [ $? -ne 0 ]; then
    echo "Error: Operation failed"
    exit 1
fi
```

### General Guidelines

- **Indentation**: Use 4 spaces (not tabs)
- **Line length**: Aim for 80-100 characters
- **Naming conventions**:
  - Variables: camelCase or snake_case (be consistent)
  - Functions: camelCase
  - Constants: UPPER_CASE
- **Comments**: Write clear, concise comments
- **Error handling**: Include proper error checking

## 📨 Commit Messages

Write clear, descriptive commit messages following this format:

```
<type>: <subject>

<body>

<footer>
```

### Types

- **feat**: New feature
- **fix**: Bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting, etc.)
- **refactor**: Code refactoring
- **test**: Adding tests
- **chore**: Maintenance tasks

### Examples

```
feat: Add SRTF scheduling algorithm

Implemented Shortest Remaining Time First with preemption.
Includes test cases for edge conditions.

Closes #42
```

```
fix: Correct turnaround time calculation in RR

Fixed off-by-one error in round robin algorithm that caused
incorrect average turnaround time.
```

```
docs: Update README with SCAN algorithm explanation

Added detailed explanation of SCAN disk scheduling algorithm
with complexity analysis.
```

## 🔄 Pull Request Process

1. **Update documentation** reflecting your changes
2. **Ensure code compiles** without warnings
3. **Test thoroughly** with various inputs
4. **Update README.md** if adding new features
5. **Reference issues** your PR addresses
6. **Provide clear description** of changes
7. **Be responsive** to review feedback

### PR Description Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Code refactoring

## Related Issues
Closes #(issue number)

## Testing
Describe testing performed

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Comments added for complex code
- [ ] Documentation updated
- [ ] No new warnings generated
- [ ] Tested with multiple inputs
```

## 🔍 Code Review

All contributions go through code review. Reviewers will check:

- **Code quality** and style compliance
- **Correctness** of implementation
- **Documentation** completeness
- **Test coverage**
- **Performance** considerations

Be patient and respectful during the review process. Address feedback constructively.

## 🎓 Learning Focus

Remember, this is an educational repository. When contributing:

- **Prioritize clarity** over clever code
- **Add explanatory comments** for learning
- **Include references** to algorithms/concepts
- **Consider adding examples** or test cases
- **Think about other learners** who will read your code

## ❓ Questions?

If you have questions about contributing:

- Check existing issues and discussions
- Open a new issue with the `question` label
- Reach out to maintainers

## 🙏 Thank You!

Your contributions help make this a better learning resource for everyone. Every contribution, no matter how small, is valued and appreciated!

---

**Happy Contributing! 🚀**
