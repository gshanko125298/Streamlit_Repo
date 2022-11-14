# ![image](https://user-images.githubusercontent.com/43541659/201744387-7e7f8182-9eaa-4847-8bfa-0fed2327a7ab.png)Streamlit_Repo!


Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps. 
# Configure VSCode to run Streamlit apps

First create an app — something simple like this will do:

      import streamlit as st
      st.write("Hello from Streamlit")

When you first create this and save it as, for example, myapp.py, VSCode thinks it is just a normal Python file and if you try and run it from the Run menu it won’t do very much.

We need to tell VSCode how to run it. To do this click on the run/debug icon on the left of the window. This will bring up the Run/Debug pane where you will see a couple of options. The one we are interested in is create a launch.json file.
