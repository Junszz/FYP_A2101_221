## FYP: Robustness of Semi-supervised Learning Against Backdoor Attack
### Project ID: A2101-221
### Nanyang Technological University, EEE

### This project conducted data-augmentation-based backdoor attack against supervised and semi-supervised model. The two main backdoor attacks conducted here are `Target Source Attack (TSA)` and `Untargeted Source Attack (USA)`.

### This repo is organized in the following structure:

    .
    ├── inputs                   # Contains both clean and backdoor datasets
    ├── outputs                  # Model checkpoints are saved here
    ├── src                      # Source files (Main training scripts)
        ├── clean_sl             # Clean supervised-learning
        ├── bd_sl                # Backdoor supervised-learning
        ├── clean_ssl            # Clean semi-supervised learning
        └── tsa_(NB)             # Targeted source attack at various `N<sub>B</sub>`
        └── tsa_dl               # Targeted source attack at different labeled size
        └── usa_(NB)             # Untargeted source attack at various `N<sub>B</sub>`
        └── ssl_bd_prep          # Script to generate backdoor samples from clean dataset


