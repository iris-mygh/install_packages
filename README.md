# Install packages
### Examples
```
pip wheel --use-deprecated=legacy-resolver -e TTS -w /d/temp_wheels
```
#### Note: 
pip wheel --use-deprecated=legacy-resolver -e <path/TTS>
- input folder: TTS
- output folder: /d/temp_wheels

### packages.txt
```
build-essential
python3-dev
libsndfile1
libsndfile1-dev
```

### requirements.txt
https://github.com/iris-mygh/install_packages/blob/main/TTS-0.22.0-cp310-cp310-linux_x86_64.whl
```
path/TTS-0.22.0-cp310-cp310-linux_x86_64.whl
torch==2.3.0
torchaudio==2.3.0
deepspeed==0.14.2
vinorm==2.0.7
cutlet==0.4.0
unidic==1.1.0
underthesea==6.8.0
gradio==4.29.0
deepfilternet==0.5.6
unidecode==1.3.8
```

