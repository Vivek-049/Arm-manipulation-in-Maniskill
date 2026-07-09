# Contributing to ManiSkill ACT Training Scripts

Thank you for your interest in contributing!

This project is maintained by [Vivek-049](https://github.com/Vivek-049) and welcomes contributions from the community.

## How to Contribute

### Reporting Bugs

If you find a bug, please open an issue with:
- **Clear title** describing the problem
- **Steps to reproduce** the issue
- **Expected vs actual behavior**
- **Environment details** (OS, GPU, ManiSkill version, etc.)
- **Error messages or logs** (if applicable)

### Suggesting Features

We love new ideas! Open an issue with:
- **Clear description** of the feature
- **Use case** - why is this useful?
- **Proposed implementation** (if you have ideas)

### Pull Requests

1. **Fork the repository**
   ```bash
   git clone git@github.com:Vivek-049/Arm-manipulation-in-Maniskill.git
   cd Arm-manipulation-in-Maniskill
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Follow existing code style
   - Add comments for complex logic
   - Test your changes thoroughly

4. **Commit with clear messages**
   ```bash
   git commit -m "Add feature: describe what you did"
   ```

5. **Push and create PR**
   ```bash
   git push origin feature/your-feature-name
   ```
   Then open a Pull Request on GitHub

## Code Style Guidelines

### Bash Scripts
- Use `#!/bin/bash` shebang
- Add comments for each major section
- Use color-coded output (RED, GREEN, YELLOW, CYAN)
- Include error handling with meaningful messages
- Prefer long-form flags (`--verbose` over `-v`) for clarity

### Python Code
- Follow PEP 8 style guidelines
- Use type hints where appropriate
- Add docstrings for functions
- Keep functions focused and modular

### Notebooks
- Include markdown cells explaining each step
- Clear cell outputs before committing (optional)
- Add section headers for organization
- Test all cells in order

## Testing Your Changes

Before submitting a PR:

1. **Test on a clean environment**
   ```bash
   # Create fresh conda environment
   conda create -n test-maniskill python=3.10
   conda activate test-maniskill
   ```

2. **Run the full pipeline**
   ```bash
   bash train_act.sh
   ```

3. **Verify outputs**
   - Check training completes successfully
   - Verify videos are generated
   - Ensure no errors in logs

## Priority Areas

We especially welcome contributions in:

- **Additional Tasks** - Scripts for other ManiSkill tasks
- **Performance Optimizations** - Faster training/eval
- **Documentation** - Tutorials, examples, troubleshooting
- **Bug Fixes** - Especially RunPod/cloud compatibility
- **Platform Support** - Windows/Mac compatibility improvements

## Resources

- [ManiSkill Documentation](https://maniskill.readthedocs.io/)
- [ACT Paper](https://arxiv.org/abs/2304.13705)
- [Our README](README.md)

## Questions?

- Open a [GitHub Discussion](https://github.com/Vivek-049/Arm-manipulation-in-Maniskill/discussions)
- Reach out through [GitHub](https://github.com/Vivek-049)

## License

By contributing, you agree that your contributions will be licensed under the same license as the project (MIT License, inherited from ManiSkill).

---

**Thank you for making robotics more accessible!**
