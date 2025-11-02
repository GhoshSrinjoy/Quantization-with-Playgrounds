# 🎯 Interactive LLM Quantization Explorer

An interactive, educational web application for understanding Large Language Model (LLM) quantization techniques. Explore different quantization methods, experiment with parameters in real-time, and visualize their impact on memory, performance, and accuracy.

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://ghoshsrinjoy.github.io/Quantization-with-Playgrounds/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

## ✨ Features

### 📚 Comprehensive Learning Modules
- **Home**: Overview of quantization benefits and impact on LLM deployment
- **Transformers**: Deep dive into transformer architecture and memory usage
- **Weights & Activations**: Understanding what gets quantized and why
- **Quantization Basics**: Interactive demos of quantization principles
- **Categories**: Taxonomy of quantization techniques (PTQ, QAT, etc.)
- **Methods**: Detailed explanations of GPTQ, AWQ, SmoothQuant, LLM.int8(), QLoRA, and more

### 🎮 Interactive Playgrounds
Experiment with real-time parameter adjustments and see immediate results:

1. **GPTQ Playground** 
   - Adjust bit-width (2-8 bits) and block size
   - Visualize quantization levels and compression ratios
   - See memory savings and error estimates

2. **AWQ Playground**
   - Control salient channel protection percentage
   - Balance between memory and accuracy
   - Understand activation-aware quantization

3. **SmoothQuant Playground**
   - Tune smoothing alpha parameter
   - Configure weight and activation bits independently
   - Observe outlier reduction effects

4. **LLM.int8() Playground**
   - Set outlier detection thresholds
   - Scale model sizes (1B-175B parameters)
   - Understand mixed-precision quantization

5. **QLoRA Playground**
   - Configure LoRA rank and alpha
   - Toggle double quantization
   - Calculate trainable parameter percentage

6. **KV Cache Quantization**
   - Adjust context length and layer count
   - See real-time memory calculations
   - Optimize for batch processing

### 🎨 Additional Features
- **Dark/Light Mode**: Comfortable viewing in any environment
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Zero Dependencies**: Pure HTML, CSS, and JavaScript
- **No Backend Required**: 100% client-side, runs anywhere
- **Interactive Visualizations**: Charts, graphs, and visual representations

## 🚀 Quick Start

### Option 1: View Online (Easiest)
Visit the live demo: [https://github.com/GhoshSrinjoy/Quantization-with-Playgrounds.git](https://github.com/GhoshSrinjoy/Quantization-with-Playgrounds.git)

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/Quantization-with-Playgrounds.git

# Navigate to the directory
cd Quantization-with-Playgrounds

# Open in browser
open index.html
# Or for Windows: start index.html
# Or for Linux: xdg-open index.html
```

That's it! No build process, no installation, no dependencies.

## 📖 How to Use

1. **Navigate** using the top menu bar to explore different topics
2. **Learn** about quantization concepts in the educational pages
3. **Experiment** with interactive playgrounds to see real-time results
4. **Toggle** between light and dark themes using the theme button
5. **Link** directly from method cards to their corresponding playgrounds

## 🎓 What You'll Learn

- How quantization reduces model size and memory usage
- Different quantization techniques and when to use them
- Trade-offs between compression, speed, and accuracy
- Practical implementation considerations
- Memory calculations for different configurations
- Real-world impact on model deployment

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Custom properties (variables), animations, responsive design
- **JavaScript (ES6+)**: Interactive components, state management, calculations
- **Canvas API**: Real-time visualizations and charts

## 📱 Browser Support

Works on all modern browsers:
- Chrome/Edge (90+)
- Firefox (88+)
- Safari (14+)
- Opera (76+)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Bugs**: Open an issue describing the bug
2. **Suggest Features**: Share your ideas for improvements
3. **Submit PRs**: Fix bugs or add new features
4. **Improve Documentation**: Help make the content clearer
5. **Add Examples**: Contribute more interactive demonstrations

### Development Guidelines
```bash
# Fork the repository
# Create a feature branch
git checkout -b feature/amazing-feature

# Make your changes
# Commit with descriptive messages
git commit -m "Add amazing feature"

# Push to your fork
git push origin feature/amazing-feature

# Open a Pull Request
```

## 📚 References & Resources

This project synthesizes information from:
- [GPTQ Paper](https://arxiv.org/abs/2210.17323)
- [AWQ Paper](https://arxiv.org/abs/2306.00978)
- [LLM.int8() Paper](https://arxiv.org/abs/2208.07339)
- [SmoothQuant Paper](https://arxiv.org/abs/2211.10438)
- [QLoRA Paper](https://arxiv.org/abs/2305.14314)
- [Hugging Face Transformers](https://github.com/huggingface/transformers)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Inspired by the need for accessible LLM quantization education
- Built to help researchers, engineers, and students understand quantization
- Thanks to the open-source ML community for their research and tools

## 📞 Contact & Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/Quantization-with-Playgrounds/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/Quantization-with-Playgrounds/discussions)

---

<div align="center">

**⭐ Star this repo if you find it helpful! ⭐**

Made with ❤️ for the ML community

[View Demo](https://yourusername.github.io/Quantization-with-Playgrounds/) · [Report Bug](https://github.com/yourusername/Quantization-with-Playgrounds/issues) · [Request Feature](https://github.com/yourusername/Quantization-with-Playgrounds/issues)

</div>
