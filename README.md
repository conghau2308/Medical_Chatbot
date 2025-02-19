*** Chạy dự án nếu môi trường ảo vẫn còn ***

conda activate Medichatbot

### Nếu chạy dự án lần đầu

## Bước 1:

*** Mở Anaconda prompt ***

conda create -n Medichatbot python=3.10 -y

conda activate Medichatbot

## Bước 2:

pip install -r requirements.txt

## Bước 3:

*** Tạo API_KEY cá nhân của PINECONE và GROQ trong file .env ***

PINECONE_API_KEY = "your_pinecone_api_key"
GROQ_API_KEY = "your_groq_api_key"

## Bước 3:
python store_index.py

## Bước 4:
python app.py

---> Open up localhost:8080
