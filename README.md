Image-Text Similarity Analysis
This repository contains Python scripts for analyzing the similarity between images and corresponding textual descriptions. The code leverages the Sentence Transformers library for encoding text and utilizes the CLIP (Contrastive Language-Image Pre-training) model for computing similarity scores.

Getting Started
Prerequisites
Ensure you have Python installed
Install required dependencies by running:

Copy code
pip install sentence_transformers
Usage
Clone the repository:


Copy code
git clone https://github.com/your-username/your-repo.git
cd your-repo
Run the script:


Copy code
python similarity_analysis.py
Input the required CSV file paths and let the script compute similarity scores.

File Structure
similarity_analysis.py: Main Python script for analyzing image-text similarity.
dataimg_iclr_similaridad_stopwords.csv: Sample CSV file containing image and text data.
CSV_iclr_img: Folder containing additional CSV files for image and text data.
Results
The script generates a new CSV file (dataimg_con_similaridad_stop.csv) with added columns for word count (tamano) and similarity scores (similaridad).

Acknowledgments
The code uses the Sentence Transformers library: https://www.sbert.net/
CLIP model by OpenAI: https://openai.com/research/clip
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
