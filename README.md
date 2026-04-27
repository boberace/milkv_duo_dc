# milkv_duo_dc
milkv-duo vscode dev container



Clone repository and include submodules:
git clone --recurse-submodules https://github.com/boberace/milkv_duo_dc.git


create a duo-projects-temp folder for work not to be tracked but used in the dev container.  must create or container will fail.

The devcontainer opens up in the /home/work directory created in milkvtech/milkv-duo:latest
It mounts duo-examples, duo-projects, duo-projects-temp, and .devcontainer folder in the same director for access
It also mounts the .bash_aliases file to /root from the .devcontainer folder with is run by .bashrc

Environments are loaded on conatiner open.  First run will download duo-sdk to duo-examples

