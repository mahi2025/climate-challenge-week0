climate-challenge-week0

# Setup enviroment
### 1. Clone github repo
```bash 
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
### 2. Create virtual environment
```bash 
python -m venv venv
```
### 3. Activate the virtual enviroment
```bash 
source venv/Scripts/activate
```
### 4. Create requirements.txt file and add dependencies
```bash 
vi requirements.txt
```
### 5. Install dependencies
```
bash pip install -r requirements.txt
```
### 6 Add Github Actions workflow
```bash
.github/workflows/ci.yml 
```
