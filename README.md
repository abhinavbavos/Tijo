## 📦 Project Structure

This repository functions as a **parent project** and uses **Git submodules** to include the following two independent repositories:

| Folder                      | Description                          | Source Repository (submodule) |
|----------------------------|--------------------------------------|--------------------------------|
| `trophy-fullstack-frontend` | Frontend / UI (React)                | https://github.com/abhinavbavos/trophy-fullstack-frontend |
| `trophy-fullstack-backend`  | Backend / API (Node.js, Express)     | https://github.com/abhinavbavos/trophy-fullstack-backend |

---

## 🚀 How to Clone
To clone the parent repository **along with both submodules**, run:

```bash
git clone https://github.com/abhinavbavos/Tijo.git
cd Tijo
git submodule update --init --recursive
```
💡 This will automatically download both the frontend and backend code into their folders inside the parent directory.


🔄 How to Pull Future Updates
To update both the parent repository and the submodules, use:

```bash
git pull --recurse-submodules
git submodule update --remote
```
⚠️ Skipping these commands may result in outdated versions of the submodules.

