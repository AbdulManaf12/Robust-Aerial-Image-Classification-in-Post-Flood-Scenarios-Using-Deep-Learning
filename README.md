# Robust Aerial Image Classification in Post-Flood Scenarios Using Deep Learning

## Abstract

(Provide a brief description of the project objectives, methods, and key findings.)

![Methodology Diagram](<img/Classification(Focus).png>)

## Dataset

The datasets utilized in this study are comprised of aerial images categorized into flooded and non-flooded classes from multiple sources. The dataset breakdown is as follows:

| Source        | Train (70%) |             | Validation (15%) |             | Test (15%) |             | Total |
| ------------- | :---------: | ----------- | :--------------: | ----------- | :--------: | ----------- | ----- |
|               |   Flooded   | Non-Flooded |     Flooded      | Non-Flooded |  Flooded   | Non-Flooded |       |
| Floodnet      |     35      | 242         |        7         | 52          |     9      | 53          | 398   |
| AIDER         |     368     | 3073        |        78        | 658         |     80     | 659         | 4916  |
| A Dataset     |     403     | 3315        |        85        | 710         |     89     | 712         | 5314  |
| Google Images |     429     | 236         |        91        | 50          |     93     | 52          | 951   |
| B Dataset     |     832     | 3551        |       176        | 760         |    182     | 764         | 6265  |

## Results

Our evaluation of the models on two distinct datasets reveals varied performance in terms of accuracy and F1 scores. The summarized results are displayed below:

| Model          | Dataset | Accuracy | F1 Score (NF) | F1 Score (F) |
| -------------- | ------- | -------- | ------------- | ------------ |
| DenseNet169    | A       | 0.95     | 0.97          | 0.79         |
|                | B       | 0.79     | 0.86          | 0.61         |
| EfficientNetB3 | A       | 0.98     | 0.92          | 0.99         |
|                | B       | 0.95     | 0.79          | 0.87         |
| NASNetMobile   | A       | 0.91     | 0.95          | 0.29         |
|                | B       | 0.91     | 0.95          | 0.29         |

These results indicate that EfficientNetB3 consistently performs well across different datasets, particularly in classifying flooded areas.

## Citation

Under process, updates will follow.

## Contact

(Include contact information for further inquiries.)
