# Example TailwindCSS + Django project

## Local development

To run the example project:

Make sure `nodejs` and `npm` is installed on your device. If you are running on Windows, add `NPM_BIN_PATH = r"[NPM PATH HERE]"` to `settings.py` (You can find the path on Windows by typing `where npm`)

(Optional) Create a venv for dependency management

```bash
python -m venv env
```

Windows: 
```bash
cd env
Scripts\activate.bat
```

MacOS/Linux:
```bash
cd env
source bin/activate
```
    

1. Install dependencies via `pip`:
   
    ```bash
    pip install -r requirements.txt
    ```

2. Install TailwindCSS depencies:
   
    ```bash
    python manage.py tailwind install
    ```
    
3. Start tailwind development server

   ```bash
   python manage.py tailwind start
   ```

4. Run development server:

    ```bash
    python manage.py runserver
    ```

5. Open `http://localhost:8000` in a browser. You should see the main page.   


### This is an edited version of [django-tailwind](https://github.com/timonweb/django-tailwind/)'s example.

