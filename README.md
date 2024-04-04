# OpenDevin

git clone https://github.com/OpenDevin/OpenDevin.git
cd OpenDevin
conda create -n od python=3.10
conda activate od
pip install -r requirements.txt
docker ps
docker pull ghcr.io/opendevin/sandbox
export OPENAI_API_KEY={your key}
uvicorn opendevin.server.listen:app --port 3000

cd frontend
brew install npm
npm install
npm start -- --port 3001