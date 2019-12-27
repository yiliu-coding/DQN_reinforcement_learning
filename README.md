## Libs to install
      pip install gym
## To run on a server or jupyternotebook, install
      sudo apt install xvfb
      sudo apt install python-opengl
## Render to jupyter notebook
      xvfb-run -s "-screen 0 1024x800x24" jupyter notebook --ip=* --allow-root
## Render to MP4
      xvfb-run -s "-screen 0 600x400x24" python RenderToMP4.py
