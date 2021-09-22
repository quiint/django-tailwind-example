# Example TailwindCSS + Django project

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/quiint/django-tailwind-example)

### This is an edited version of [django-tailwind](https://github.com/timonweb/django-tailwind/)'s example (which can be found [here](https://github.com/timonweb/django-tailwind/tree/master/example))
To run the example project:<br><br>
Make sure `nodejs` and `npm` is installed on your device. If you are running on Windows, uncomment `NPM_BIN_PATH` in `settings.py` 
<br><br>

(Optional) Create a venv for dependency management

```bash
python -m venv env
```


Windows:
   
    cd env
    Scripts\activate.bat

MacOS/Linux:
   
    cd env
    source bin/activate
    

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
