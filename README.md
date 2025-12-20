This is a repository of the dual-stream transfer learning model for depression detection.

CPU: AMD Ryzen 9 (tested on Ryzen 9, 64 GB RAM)
GPU: Not required (all experiments runnable on CPU)
RAM: 64 GB
OS: Windows 10 / Linux (Ubuntu 20.04+ compatible)

Python 3.11
pip install -r requirements.txt

- Train/validation/test split applied before tokenization and embedding extraction
- 
- No participant overlap between splits
- 
- Labels shared across BERT and T5 embeddings
- 
- Each text instance corresponds to a unique participant-level record
- 
How to Run:

1. Clone the repository
2. Install dependencies using requirements.txt
3. Download E-DAIC and MODMA datasets following official data access procedures
4. Place preprocessed embeddings in the specified output directory
5. Run: Proposed_TL_two_stream_share.ipynb
