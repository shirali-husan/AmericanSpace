# AmericanSpace
For Student to to watch the code.
Sudo docker run --privileged --name buffer-overflow -it shirali/project1_completed_castfileincluded


This will initialized the container and start with an interactive mode

STEPS: 1. Lab Setup: Disable Address Randomization: 
sudo sysctl -w kernel.randomize_va_space=0 sudo sysctl -w kernel.randomize_va_space=0 
Set a softlink to zsh for system shell: 
sudo ln -sf /bin/zsh /bin/sh sudo ln -sf /bin/zsh /bin/sh


export SHELL='/bin/sh'

env | grep "SHELL"

sudo sysctl -w kernel.randomize_va_space=0

sudo ln -sf /bin/zsh /bin/sh

Info registers 
python -c 'print("\x41" * 338)' > malfile

Is at the middle point.


