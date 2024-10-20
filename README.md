# Kolmogorov-Arnold Network (KAN) - Experimentation
Here is the **Kolmogorov-Arnold Network (KAN)** project! This repository contains code and instructions for experimenting with the KAN deep learning architecture. KAN integrates structured external knowledge into neural networks, enhancing their reasoning capabilities, particularly for applications like natural language processing and recommendation systems. 

Kolmogorov-Arnold representation theorem states that if $f$ is a multivariate continuous function
on a bounded domain, then it can be written as a finite composition of continuous functions of a
single variable and the binary operation of addition. More specifically, for a smooth $f : [0,1]^n \to \mathbb{R}$,


$$f(x) = f(x_1,...,x_n)=\sum_{q=1}^{2n+1}\Phi_q(\sum_{p=1}^n \phi_{q,p}(x_p))$$

where $\phi_{q,p}:[0,1]\to\mathbb{R}$ and $\Phi_q:\mathbb{R}\to\mathbb{R}$. In a sense, they showed that the only true multivariate function is addition, since every other function can be written using univariate functions and sum. However, this 2-Layer width-$(2n+1)$ Kolmogorov-Arnold representation may not be smooth due to its limited expressive power. We augment its expressive power by generalizing it to arbitrary depths and widths.

<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
<summary>Table of Contents</summary>
<ol>
<li><a href="#about-the-project">About The Project</a></li>
<li><a href="#built-with">Built With</a></li>
<li>
<a href="#getting-started">Getting Started</a>
<ul>
<li><a href="#prerequisites">Prerequisites</a></li>
<li><a href="#installation">Installation</a></li>
</ul>
</li>
<li><a href="#usage">Usage</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#license">License</a></li>
<li><a href="#contact">Contact</a></li>
<li><a href="#acknowledgments">Acknowledgments</a></li>
</ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
The **Kolmogorov-Arnold Network (KAN)** experiment is focused on testing the capabilities of the KAN model, which uses a unique structure to embed knowledge graphs into deep learning models. This technique improves the model's ability to reason through complex data.

Key aspects of the project include:
- Implementation of a KAN model using Python and PyTorch.
- Training the model on generated data and performing evaluations.
- Investigating the impact of structured knowledge on the model's learning and performance.

For more information on the KAN architecture and its background, refer to the research paper ["Knowledge Graphs: Enhancing Neural Networks Through Structured Reasoning"](https://arxiv.org/abs/2404.19756).

## Built With
This project leverages various Python libraries to construct, train, and evaluate the KAN model. Below are the key technologies used:

### Programming Language: 
- Python

### Libraries: 
- PyTorch
- `pykan`
- Numpy
- Google Colab

<!-- GETTING STARTED -->
## Getting Started
Follow these steps to set up and run the project on your local machine.

### Prerequisites
Ensure that you have Python and the following libraries installed:
```bash
pip install torch pykan numpy
```

### Installation
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/kan-experiment.git
cd kan-experiment
```

Install the required Python packages:
```bash
pip install -r requirements.txt
```

<!-- USAGE EXAMPLES -->
## Usage
Once installed, you can start experimenting with the KAN model by running the notebook:

1. Open the Jupyter notebook (`kan_experiment_file.ipynb`) in Google Colab or Jupyter Lab.
2. Follow the step-by-step instructions in the notebook to train the KAN model on the dataset.
3. Run the code in a sequence to avoid errors.
4. Modify parameters like `width`, `grid`, and `k` to explore different configurations.

Example command to run in your local environment:
```bash
python kan_experiment.py
```

<!-- CONTRIBUTING -->
## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have suggestions or improvements.

<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact
Your Name - [686jashan@gmail.com](mailto:686jashan@gmail.com)
Project Link: [https://github.com/Jashan-1/Kolmogorov-Arnold-Networks](https://github.com/Jashan-1/Kolmogorov-Arnold-Networks)

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
- [KAN Architecture Research](https://arxiv.org/abs/2404.19756)
- PyTorch documentation
- The open-source community for valuable tools and libraries
