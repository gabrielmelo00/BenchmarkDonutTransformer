# Fine-Tuning Donut Transformer For Document Classification  📄🤖🍩

Here's the repo with the notebooks used to compare two Donut approaches for Document Classification: the traditional encoder-decoder approach and a more efficient encoder-only approach. The encoder-only method significantly reduces inference time while maintaining similar accuracy.

### Results 📈

| Metric                | Encoder-Only Donut | Donut + Add Tokens |
|-----------------------|--------------------|--------------------|
| Average Inference Time| ⏱️ 0.029618 s      | ⏱️ 0.311698 s      |
| Accuracy              | 🎯 51.875%         | 🎯 51.25%          |

Note that the accuracy of both models is low, as this is a toy experiment using a small subset of the dataset, intended for quick computation of metrics. However, this provides valuable insights for real use-cases.

### Medium Article  📑
For detailed methods and results, read the full article [here](https://medium.com/qantev/fine-tuning-donut-transformer-for-document-classification-f1db9739398f).  
