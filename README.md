### Image Similarity Search

Image Similarity search is openclip based algorithm that helps to find the image by quering with text or uploading the image.

To Run this project first you need to clone the hasnaindev and create a python virtual envirnomnet.

Inside the virtual environment write.

```bash
pip install -r requirements.txt
```

After downlading and installing the dependencies,

Run console.py, make sure to select the images direcotry properly and the extension format i.e jpg or png.

Also set the collection names accordingly, if you didn't rename it next time, it will override the previous chromadb collection.

Now you are ready to use the streamlit app by running

```bash
streamlit run app.py
```
