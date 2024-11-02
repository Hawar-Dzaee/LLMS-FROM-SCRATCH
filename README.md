# 🤖 GPT-2 Style Model Implementation & Learning Resources 

This repository contains implementations of GPT-2 style models at different abstraction levels, along with detailed learning resources and validation experiments.

## 📁 Repository Structure

| Folder | Description | Key Contents |
|--------|-------------|--------------|
| 📂 Models | End-to-end GPT-2 style implementations | - Model_level_0.ipynb <br> - Model_level_1.ipynb |
| 📂 Takeaways_from_each_chapters | Chapter summaries from "Build a Large Language Model (From Scratch)" | - Chapter-wise takeaway files |
| 📂 reproducing pytorch's functionality | PyTorch functionality reproduction | - MultiheadAttention_reproduction.ipynb |

## 🔍 Detailed Overview

### Models
Contains two different implementations of GPT-2 style architecture:

1. **Model_level_0.ipynb**
   - Complete implementation from scratch
   - All components written from ground up
   - Ideal for deep understanding of model internals
   - 📌 *Recommended for learning fundamentals*

2. **Model_level_1.ipynb**
   - End-to-end implementation using PyTorch's built-in modules
   - Uses `nn.MultiheadAttention` instead of custom implementation
   - 📌 *Recommended for practical applications*

### Takeaways_from_each_chapters
- Comprehensive notes from Sebastian Raschka's book
- Chapter-wise breakdown of key concepts
- Combined knowledge leads to understanding the complete model
- 📚 *Serves as theoretical foundation for the implementations*

### reproducing pytorch's functionality
- Contains validation experiments
- Focuses on `nn.MultiheadAttention` reproduction
- Includes result comparison between custom and PyTorch implementations
- 🔍 *Useful for verification and deep understanding*

## 🎯 Getting Started

1. Start with `Takeaways_from_each_chapters` to build theoretical foundation
2. Move to `Model_level_0.ipynb` for fundamental implementation understanding
3. Explore `Model_level_1.ipynb` for practical implementation approach
4. Use `reproducing pytorch's functionality` to validate understanding

## 📊 Suggested Additions

Consider adding:
- Architecture diagrams for both model implementations
- Performance comparison graphs between Level 0 and Level 1 models
- Code coverage and test results
- Requirements.txt or environment.yml
- Example outputs and use cases

## 🔗 References

- Sebastian Raschka's "Build a Large Language Model (From Scratch)"
- PyTorch Documentation
- [Add any additional references used]

## 📝 Notes

- This repository is focused on educational purposes and understanding transformer architectures
- Implementations follow the GPT-2 architecture style
- Code includes detailed comments and explanations

[Consider adding badges for Python version, PyTorch version, license, etc.]