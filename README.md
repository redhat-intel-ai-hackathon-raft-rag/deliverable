## Presentation

### Presentation Power Video

### Presentation Power Point

https://o365coloradoedu-my.sharepoint.com/:p:/g/personal/eiue6866_colorado_edu/EUBRdDg46vRFgqnp9h--MaMB5aDQBTNII862sLkkuBaJKA?e=7gbWbm

### Presentation Word Document

https://o365coloradoedu-my.sharepoint.com/:w:/g/personal/eiue6866_colorado_edu/EQsZ-Y21La5InOD0zfD_FPoBCLsDpgRQ28D77PuUy52aEA?e=Rjl9lq

### Presentation Data Architecture

https://docs.google.com/spreadsheets/d/1jk84Sn4sn6ghJS6IH5rgnMM4WV4KJmr_t9FFO5fv_lo/edit?gid=86025096#gid=86025096

## Screen Shot

### AMX and OpenVIVO

![alt text](<Screenshot from 2024-11-04 12-27-08.png>)

![alt text](<Screenshot from 2024-11-04 12-28-21.png>)

![alt text](<Screenshot from 2024-11-04 12-30-11.png>)

## Test Script

git clone https://github.com/redhat-intel-ai-hackathon-raft-rag/rag.git
git clone https://github.com/redhat-intel-ai-hackathon-raft-rag/finetuning.git
git clone https://github.com/redhat-intel-ai-hackathon-raft-rag/data-processing.git
git clone https://github.com/redhat-intel-ai-hackathon-raft-rag/infra
git clone https://github.com/redhat-intel-ai-hackathon-raft-rag/raft-inference.git

### Prepared models and dataset

cd rag

#### download dataset and model

```
pip install -r requirements.txt
./download_dataset_book.sh
./download_dataset_web.sh
./download_model.sh
```

#### run inference server

python -m app

### full pipeline

#### dataset

cd raft-inference

and follow README.md

cd dataset

and follow README.md

#### train

cd finetuning

and follow README.md

#### infra

cd infra

and follow README.md

#### inference

cd rag

and follow README.md
