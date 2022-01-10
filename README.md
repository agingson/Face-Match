1. download the data from kaggle
2. create folder for project and create environment(anaconda python3) - conda create --prefix ./envs python=3.7 -y
3. activate environment - conda activate ./env/
4. create requirement.txt file 
5. create setup.py file
6. install the packages in local pip install -r requirement.txt
7. run python src/01_generate_img_pkl.py
8. run python src/02_feature_extractor.py
9. streamlit run app.py