# boxjourney-research

For keep all lib
python -m pip freeze > requirements.txt

For install all lib
python -m pip install -r requirements.txt

For clean all lib use
python -m pip uninstall -y -r <(pip freeze)

install torch torchvision torchaudio
pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu117

install detectron2
git clone https://github.com/facebookresearch/detectron2.git

python -m pip install -e detectron2
