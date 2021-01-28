# LTOP
Python code for computing the Linear Theory for Orographic Precipitation (LTOP) in Barstad and Smith (2003). 

Method:
1. Select a moist airflow event with some evidence of precipitation
2. Select LTOP parameters ($𝑈, 𝑉, 𝑁, 𝐻_𝑊, 𝜏_𝐶, 𝜏_𝐹, 𝐶_𝑊$)
3. Fourier Transform the terrain:  ℎ(𝑥,𝑦) → ℎ(𝑘,𝑙)
4. Use master equation to compute: 𝑃(𝑘,𝑙) 
5. Inverse Fourier Transform to compute: 𝑃(𝑥,𝑦)
6. Drop negative values and add background precipitation
