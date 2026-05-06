# python-project-template

## Goal

Python 프로젝트를 생성할 때 빠르게 작성할 수 있도록 도움

## Setup

### macOS
macOS에서 가상환경을 설정하는 방법입니다.

#### Create Venv

```bash
python<version> -m venv venv
```

#### Manage Venv Status

```bash
# Activate Venv
source venv/bin/activate

# Deactivate Venv
deactivate
```

#### Install Libraries

```bash
pip install -r requirements.txt
```

### Windows
Windows에서 가상환경을 설정하는 방법입니다.

#### Create Venv

```bash
python -m venv venv
```

#### Manage Venv Status

```bash
# Activate Venv
.\venv\Scripts\activate

# Deactivate Venv
deactivate
```

#### Install Libraries

```bash
pip install -r requirements.txt
```

### Conda
OS 상관없이 conda 가상환경을 구성하는 방법입니다.

#### Create Venv
```bash
conda create -n <venv-name> python=<version>
```

#### Manage Venv Status
```bash
# Activate Venv
conda activate <venv-name>

# Deactivate Venv
conda deactivate <venv-name>
```

#### Manage Libraries
```bash
conda install <library-name>
```

>[!tip]
**Conda** 가상 환경이 충돌이 덜 생기고 폴더가 따로 생겨 깔끔하기 때문에 **Conda** 사용하는 것을 권장함



