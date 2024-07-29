
# Belgian Law Fine-Tuning

This repository contains code and data for fine-tuning the Mistral 7B language model on Belgian law. The goal is to create a language model that can understand and generate text related to Belgian legal contexts more effectively.

## Overview

The project uses the Mistral 7B model, which has been fine-tuned using a dataset of Belgian legal texts. This fine-tuning process aims to improve the model's performance in generating and understanding legal language specific to Belgium.

## Installation

To use this project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/naimsassine/Belgian-law-finetuning.git
cd Belgian-law-finetuning
```

## Usage

The main script for fine-tuning the model can be found in the `notebooks` directory. To start fine-tuning, simply run the Jupyter Notebook provided.

## Acknowledgements

This project would not have been possible without the help and resources from the following sources:

- **Niels Rogge's notebook**: A fantastic guide that helped throughout the fine-tuning process. You can find it [here](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/Mistral/Supervised_fine_tuning_(SFT)_of_an_LLM_using_Hugging_Face_tooling.ipynb).
- **Maastricht Law & Tech Lab**: Their dataset on Belgian law was instrumental. They do excellent work at the intersection of law and AI. Check out their work [here](https://huggingface.co/datasets/maastrichtlawtech/bsard).
- **Droits Quotidiens**: This Belgian NGO clarifies legal concepts for the public. Their work is invaluable for society. Learn more about them [here](https://www.droitsquotidiens.be/fr/droits-quotidiens-clarifie-le-droit).
- **Belgian Constitution and Legislation**: Fundamental sources for the legal texts used in this project.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
