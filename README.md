# Generative-Deep-Learning-for-Drug-Discovery

Present drug discovery endeavors are hindered by a prolonged timeframe, typically spanning 10-15 years, particularly in the case of intricate neurological conditions such as Alzheimer’s disease. This prolonged duration is primarily attributed to the vast chemical landscape, encompassing approximately 10^60 potential drug-like molecules, necessitating extensive exploration. Conventional drug discovery practices often involve the empirical selection of candidate compounds from this expansive chemical space, a method deemed inefficient. However, advancements in deep learning present a promising avenue for expediting the drug discovery process. Recent studies have suggested leveraging deep learning techniques, particularly generative models, to accelerate chemical innovation through natural language processing (NLP) methodologies. Through innovative neural network architectures and natural language processing techniques, this project seeks to expedite the identification of promising therapeutic compounds, offering hope for faster development of treatments for complex diseases like Alzheimer's

II'll use chembl data, expecially BACE-1 inhibators, and other generic molecules.

BACE-1 inhibitors are compounds that inhibit the activity of the enzyme BACE-1 (Beta-site APP Cleaving Enzyme 1), which is involved in the production of amyloid-beta peptides. These peptides are associated with the development of Alzheimer’s disease

This project is a reproduction of a Stanford CS230 course Final project : https://github.com/Adriatogi/Chemical-Generative-Deep-Learning
I used the same Dataset published on the github.

The second part uses a VAE (Variational AutoEncoder) to learn the latent space structure and then generate new molecules through the decoder: 14 new molecules were found out of 10000 samples.
