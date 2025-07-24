# 🤖 Hate Speech Detection using Multimodal Fusion *(Under Review)*

A deep learning-based system that leverages both text and image modalities to detect hate speech in social media content. Designed to improve robustness by fusing linguistic and visual cues, enabling more accurate and context-aware detection.

---

## 🚀 Features

- 🧠 Multimodal model combining both text and image inputs  
- 🗣️ Text processing using transformer-based encoders (e.g., BERT)  
- 🖼️ Image processing via pre-trained CNN architectures (e.g., ResNet, VGG)  
- 🔗 Intermediate fusion of embeddings for joint learning  
- 📊 Outputs binary classification (hate / non-hate), with optional confidence scores

---

## 🧱 Tech Stack

- **Framework:** PyTorch  
- **Text Encoder:** BERT / DistilBERT  
- **Image Encoder:** ResNet-50 / VGG16  
- **Fusion Strategy:** Feature-level intermediate fusion  
- **Preprocessing:** Tokenization, image normalization, dataset loader utilities

---

## 📂 Project Structure

```
Multimodal-HateSpeechDetection/
│
├── /early_fusion                  # Contains code for early fusion
├── /intermediate_fusion           # Implementation of intermediate fusion
├── /late_fusion                   # Implementation for late fusion approach
└── README.md                      # Project documentation
```

---

## 📈 Output

The system provides:
- Binary labels: **`hate`** or **`non-hate`**  
- Optional confidence scores or attention maps for interpretability

---

## 🛠️ Use Cases

- Automated social media moderation  
- Research in multimodal toxicity detection  
- Real-time or batch-based hate speech filtering pipelines

---

## 🤝 Contributions

Pull requests are welcome!  
If you'd like to contribute new fusion strategies, data sources, or metrics, please open an issue to initiate the discussion before submitting a PR.

---

## 📚 Citation

If you refer to or build upon this work, please cite:

```
Yash Shukla et al., "Hate Speech Detection using Multimodal Fusion Techniques Leveraging Hypergraph Neural Networks", (Under Review, 2025).
```

---

