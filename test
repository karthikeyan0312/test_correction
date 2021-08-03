from textblob import TextBlob
import streamlit as st
 
st.write("# Word Corrector")
test = st.text_input("Enter the senteance :")
text = TextBlob(test)
# using TextBlob.correct() method
text = text.correct()

st.write("#",text)
