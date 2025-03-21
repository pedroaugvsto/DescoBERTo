# Hate Speech Detection in Portuguese

## Project Overview
This project aims to develop a **Portuguese-language tool for detecting hate speech**. The goal is to create a robust and reliable model that can be effectively employed in identifying and analyzing hateful content in textual data.

This project was developed by two students from UFPB: Pedro Augusto Medeiros ([GitHub](https://github.com/pedroaugvsto)) and Tales Nobre ([GitHub](https://github.com/talesnobre)).

## Datasets
The repository contains:
- **Original datasets** used in training.
- **Processed and concatenated versions** of these datasets.
- **Synthetic data** voluntarily contributed by other students from the Centro de Informática at UFPB.

## Training Logs
Below are the details of the training logs included in this repository:
- **`primeiro_log`**: Training conducted on a dataset created by merging two original datasets, trained for 10 epochs.
- **`segundo_log`**: Training performed on the same dataset as `primeiro_log`, but with a larger batch size.
- **`terceiro_log`**: Training performed on an augmented dataset, with fewer steps between each validation and trained for 5 epochs.
- **`quarto_log`**: Training performed on an augmented and post-processed dataset, trained for 5 epochs.
- **`log_tokenizador_pt`**: Training conducted using a pre-trained BERT tokenizer specifically for Portuguese.

## Model Information
The trained models are **not included in this repository** due to GitHub storage limitations. Instead, they are hosted on Google Drive. All models were trained using the **BERT base** model from the Hugging Face library.

The top-performing models are:
- **Top1**: Trained on the augmented and processed dataset, checkpoint **990**.
- **Top2**: Trained on the augmented dataset, checkpoint **820**.
- **Top3**: Trained on the non-augmented dataset, checkpoint **1230**.

For access to the models, please refer to the provided Google Drive link or contact the project maintainers.

---

### License
This project is released under an open-source license. Please review the LICENSE file for more details.

---

For any questions or further inquiries, please contact the project maintainers or contribute via GitHub.

