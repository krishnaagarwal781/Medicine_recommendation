# Medicine-Recommendation-System 💊

![medicine-image](https://github.com/anurag-b72/medicine-recommendation-system/blob/main/images/medicine-image.jpg)

This recommendation system is supposed to recommend any medicine/drug on the basis of the search result.
The main aim is to recommend any alternative/substitute to be used in place of the searched medicine.

### Steps to Open Localhost for application: 🌐
1. Clone the GitHub Repository.
2. Extract the **pickle-files.rar** archive; it will extract "similarity.pkl" & "medicine_dict.pkl" pickle files. Make sure the files are present in the root directory where the `app.py` is located.
3. Download PyCharm IDE and open this application folder in it.
4. Open the terminal.
5. Import the necessary libraries: *streamlit*, *pandas*, and *pickle*.
6. Run the application by typing `streamlit run app.py`.
7. If the application does not start, you can try typing `python -m streamlit run app.py`.

**Note**: If the terminal throws an error "*streamlit is not recognized as an internal or external command*" even after importing all libraries, recreate a new Python project, then import all libraries (*streamlit*, *pandas*, and *pickle*) and include the `css` & `images` folder along with the extracted pickle-files.

---

## Video Demonstration:- ▶️
[Click Here for Application Demo](https://youtu.be/0bE4Na5Tk8Q "YouTube")

---

## Deployment and Data Files 📦

To facilitate deployment and address GitHub's file size limit of 100 MB, we have reduced the size of the `similarity.pkl` file. However, the original data files required for the application are available in the `pickle-files.rar` archive.

Here's how to handle the deployment and retrieve the original data files:

1. **Reduced `similarity.pkl` File**: The reduced `similarity.pkl` file is provided in the root directory of this repository. This file is optimized for deployment and may contain a smaller subset of data. It is suitable for running the application in a production environment.

2. **Original Data Files**: To obtain the original data files used for development and testing, you will need to extract them from the `pickle-files.rar` archive. These files, `similarity.pkl` and `medicine_dict.pkl`, should be placed in the same directory as the application script `app.py` for full functionality.

   You can extract the files using various tools such as WinRAR, 7-Zip, or the `unrar` command-line utility:


Make sure the extracted data files are present in the root directory alongside `app.py` to ensure the application works with the complete dataset.

By following these instructions, you can deploy the application with the reduced `similarity.pkl` file while having access to the original data files when needed.

---
## Kaggle Dataset 📊
[Click Here to Access Dataset](https://www.kaggle.com/code/mpwolke/medicine-recommendation/data "Kaggle Site")

---

## Contact 📝
Anurag Biswal - 
* [anurag.biswal0702@gmail.com](mailto:anurag.biswal0702@gmail.com "anurag.biswal0702@gmail.com")
* [LinkedIn](https://www.linkedin.com/in/anurag-biswal72/ "LinkedIn")
* [Portfolio](https://anurag-b72.github.io/MyPortfolio/ "Website")
* [Twitter](https://twitter.com/AnuragBiswal72 "Twitter")
