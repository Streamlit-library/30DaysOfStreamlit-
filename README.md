# 30DaysOfStreamlit


# Day 1

- 1 Instalar conda
https://docs.conda.io/en/latest/miniconda.html 

- 2 Crear environment

~~~
conda create -n stenv python=3.9
~~~
- 3 Activar el environment

~~~
conda activate stenv
~~~
- 4 Instalar la librería Streamlit 

~~~
pip install streamlit
~~~
- 5 Ejecutar:

~~~
streamlit hello
~~~
![](./img/day1.png)

# Day 2
- Escribir las siguientes línea de código 
~~~python
import streamlit as st

st.write('Hello world!')
~~~
- Ejecutar:
~~~
streamlit run streamlit_app.py
~~~
![](./img/day2.png)

# Day 3
- st.button
~~~python
import streamlit as st

st.header('My first button')

if st.button('Say hello'):
     st.write('Why hello there')
else:
     st.write('Goodbye')
~~~
![](./img/day3.png)

#  Day 4
- Construir app con Ken Jee

https://www.youtube.com/watch?v=Yk-unX4KnV4
~~~
pip install plotly      
~~~
![](./img/day4.png)
# Day 5 
- st.write

~~~python
st.write('Hello, *World!* :sunglasses:')
~~~
![](./img/day5.png)