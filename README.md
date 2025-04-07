## Implement a ChatGPT-like LLM in PyTorch from scratch

### Text Preprocessing, Tokenization, Embedding Tensor
- Text Tokenization
- Converting Tokens to Token IDs
- Adding Special Context Tokens
- Byte Pair Encoding
- Data Sampling with Sliding Window
- Building the Embedding Layer
- Positional Encoding

### Implement Various Attention Mechanisms
- Simple Attention Mechanism
- Causal Attention Mechanism
- Multi-head Causal Attention Mechanism

### Developed Transformer-based Architecture
- Forward
- Normalization
- Shortcut
- Activation Layer
- Linear Layer
- Dropout
- Text Generation

### Pretrained the Model on Unlabeled Text Data Set
- Loss Function (Cross Entropy)
- Training LLM
- Decoding Strategies to Control Randomness of the Generation
- Saving the Trained Weights
- Loading OpenAI Weights into the Model

### Conducted Classifier Fine-tuning
- Preparing the Classification Dataset and Dataloader
- Adding a Classification Head
- Calculating Classification Loss and Accuracy
- Fine-tuning the Model with Supervised Data

### Conducted Instruction Fine-tuning
- Creating Data Loaders for the Instruction Dataset
- Fine-tuning the LLM with Instructions
- Extracting and Saving Responses
- Designed Automated Dialogue Benchmark Tests to Evaluate Model Performance and Conversational Capabilities

