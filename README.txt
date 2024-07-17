open cmd 
change directory to folder
cd folder name
python -m venv venv
venv\Scripts\activate

pip install Flask torch torchvision nltk

python
import nltk
nltk.download('punkt')
quit()

python train.py
python chat.py
