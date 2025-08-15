## 📥 Cloning this project
---------------------------
This repository is a **parent project** that contains two Git submodules (frontend and backend).  
To make sure everything is pulled correctly, please use the following commands:

```bash
git clone https://github.com/abhinavbavos/Tijo.git
cd Tijo
git submodule update --init --recursive

--------------------------------------------------------------------------------------------------------------------

🔄 Pulling updates (including submodules)
-----------------------------------------
When you pull future updates, use these commands so that both the parent repo and the submodules stay up-to-date:

git pull --recurse-submodules
git submodule update --remote
