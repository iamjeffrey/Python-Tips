# Python-Tips

# Windows pycrypto 설치를 위한 Visual C++ Build Tools
  https://visualstudio.microsoft.com/vs/older-downloads/?rr=https%3A%2F%2Fdololak.tistory.com%2F520

- Image processing with pillow
  https://auth0.com/blog/image-processing-in-python-with-pillow/
  python3 -m pip install --upgrade Pillow

  Pillow와 같이 쓰면 편한 라이브러리 python-resize-image : resize crop, cover/contain/width/height/thumbnail resize
  
- PySide6, QT6
  python3 -m pip install --upgrade PySide6 pr pip install PySide6
1) 최신 Version Qt Designer Mac에서는 PySide6 패키지 인스톨 하면 pyside6-designer 같이 설치, 콘솔에서 pyside6-designer 실행
2) Qt Designer 앱 다운로드, V5.9.6
  : 1) 최신 버전이고 콘솔 기반 실행
  : 2) 앱 기반, 구 버전, 최신 버전과 차이는 추가 위젯 정도, UI는 둘다 올드
  https://www.pythonguis.com/tutorials/pyside6-first-steps-qt-designer/

# jupyterlab
https://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html

- pip install jupyterlab
- TO launch : jupyter lab
- macOS : export PATH="$HOME/.local/bin:$PATH"
- Jupyverse : FastAPI 기반 Jupyter server, JupyterLab 기본 jupyter server 대신 사용 가능 (단, jupyter server extensions은 동작하지 않음)
  pip install "jupyverse[auth,jupyterlab]"
  To run : jupyverse

- Configure npm to not use SSL
  npm set strict-ssl False

- Install pandas (without SSL)
  pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org pandas
