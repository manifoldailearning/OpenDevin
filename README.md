# OpenDevin
```
git clone https://github.com/OpenDevin/OpenDevin.git
cd OpenDevin
export OPENAI_API_KEY={api-id}
export WORKSPACE_DIR="/Users/nachiketh/Desktop/author-repo/newproject/"
conda create -n opendevin python=3.10
conda activate opendevin
pip install -r requirements.txt
docker ps
docker pull ghcr.io/opendevin/sandbox
uvicorn opendevin.server.listen:app --port 3000

OpenDevin/

cd frontend
brew install npm
npm install
npm start -- --port 3001

```