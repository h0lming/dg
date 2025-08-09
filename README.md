# Dækningsgrad beregner (Streamlit)

Lille webapp til hurtig beregning af salgspris ud fra timepriser, materialekost og ønsket dækningsgrad.

## Kør lokalt
```bash
pip install -r requirements.txt
streamlit run daekningsgrad_app_v5.py
```
Adgangskode: `0000`

## Deploy (Streamlit Community Cloud)
1. Læg `daekningsgrad_app_v5.py` + `requirements.txt` i et offentligt GitHub-repo.
2. På https://streamlit.io → **Deploy an app** → vælg repo.
3. `Main file path`: `daekningsgrad_app_v5.py` → **Deploy**.
4. Del linket. På iPhone kan det gemmes via **Del → Føj til hjemmeskærm**.

## Ikoner (valgfrit)
Hvis du vil have ikon i browser/hjemmeskærm, læg disse filer i repoets rod:
- `apple-touch-icon.png` (180×180)
- `favicon_32.png`, `favicon_64.png`, `app_icon_512.png`

Appen forsøger automatisk at bruge dem, hvis de findes.
