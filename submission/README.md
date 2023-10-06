# Proyek Analisis Data: Bike Sharing 
Link Streamlit Cloud : [Bike Sharing Dashboard](https://irfan77-bike-share.streamlit.app/)

## Preview
![Bike Sharing Dashboard Streamlit Preview](https://raw.githubusercontent.com//IrfanAliGit77/Belajar-Analisis-Data-dengan-Python--ID-Camp-X-Dicoding-Academy/blob/main/submission/Capture%20App.PNG)


## Project installation to personal virtual environment
The steps to create your virtual environment from this project is as follows:

1. Clone this repository
   ```
   git clone https://github.com/IrfanAliGit77/Belajar-Analisis-Data-dengan-Python--ID-Camp-X-Dicoding-Academy.git
   ```

2. Move to directory Dicoding-BADP
   ```
   cd Belajar-Analisis-Data-dengan-Python--ID-Camp-X-Dicoding-Academy
   ```

3. Move to directory Submission
   ```
   cd submission
   ```

4. Create python virtual environment
   ```
   python -m venv bike_sharing_venv
   ```

5. Active environment
   ```
   bike_sharing_venv\Scripts\activate
   ```

6. Install all the requirements inside "requirements.txt"
   ```
   pip install -r dashboard\requirements.txt
   ```

7. Install virtual environment
   ```
   python -m ipykernel install --name=bike_sharing_venv
   ```

8. Deactive Environment
   ```
   bike_sharing_venv\Scripts\deactivate
   ```

9. Run streamlit app
   ```
   streamlit run dashboard\dashboard.py
   ```

10. Stop the application program by `ctrl + c`.
