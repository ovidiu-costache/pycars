# Comenzi Git si VENV - PyCars

Cititi asta inainte, va rog!

---

## Comenzi Git

* **Te muti pe branch-ul principal (proiectul la zi):**
    ```bash
    git checkout main
    ```

* **Descarci ultimele modificari de pe server:**
    ```bash
    git pull origin main
    ```

* **Creezi un branch nou (NU lucram niciodata pe main!):**
    ```bash
    git checkout -b <nume_branch>
    ```

* **Vezi ce ai modificat, ca un ls:**
    ```bash
    git status
    ```

* **Adaugi un fisier pentru salvare:**
    ```bash
    git add <nume_fisier>
    ```

* **Adaugi TOATE fisierele modificate pentru salvare:**
    ```bash
    git add .
    ```

* **Salvezi permanent (dai commit) cu un mesaj:**
    ```bash
    git commit -m "mesaj"
    ```

* **Publici branch-ul tau pe GitHub:**
    ```bash
    git push origin <nume_branch>
    ```

---

## Mediu Virtual (VENV)

* **Creezi mediul (doar o data, la inceput):**
    ```bash
    python -m venv .venv
    ```

* **Activezi mediul (de fiecare data cand lucrezi):**
    * Linux:
        ```bash
        source .venv/bin/activate
        ```

* **Iesi de pe mediul virtual:**
    ```bash
    deactivate
    ```

* **Instalezi o biblioteca in mediul tau:**
    ```bash
    pip install <biblioteca>
    ```

* **Instalezi toate bibliotecile din requirements (cand iei pull si vezi ca e nou):**
    ```bash
    pip install -r requirements.txt
    ```
