
 
![banner_main](https://raw.githubusercontent.com/epicalekspwner/BigScaleAnalytics2021/main/Resources/groupAmazon_banner_main_v2.svg)

<p align="center">
  <img src="https://raw.githubusercontent.com/epicalekspwner/BigScaleAnalytics2021/main/Resources/groupAmazon_central_banner.gif" />
</p>

![banner_team](https://raw.githubusercontent.com/epicalekspwner/BigScaleAnalytics2021/main/Resources/groupAmazon_banner_team.svg)

### 🕵️ Project Description

<p align="justify"> 
  <strong>To improve one’s skills in a new foreign language, it is important to read texts in that language.</strong> But in order to make learning really effective, these text have to be at the reader’s language level. However, it is difficult to find texts that are close to someone’s knowledge level (A1 to C2).
</p>

<p align="justify"> 
  This project aims to build a model for English speakers that <strong>predicts the difficulty of a French written text</strong>. This can be then used, e.g., in a recommendation system, to recommend texts that are appropriate for someone’s language level. If someone is at A1 French level, it is inappropriate to present a text at B2 level, as she won’t be able to understand it. Ideally, a text should have many known words and may have a few words that are unknown so that the person can improve.
</p>

<p align="justify">
  This project is <strong>iterative</strong> and will be conducted in <strong>multiple milestones</strong> that are due throughout the semester:
</p>

- **Milestone 1** (due March 15) - Reading/Thinking & Gathering the data 
- **Milestone 2** (due April 13) - Creating/Evaluating the model
- **Milestone 3** (due May 10) - Iterate & Improve 

### Milestone 1 - Reading/Thinking & Gathering the data 

### 📚 Review of the Existing Literature

To be completed

### 💭 How do we intend to solve the problem?

After much thought, we plan to approach this project as a classification problem. The feature engineering we wish to explore are the following:

**Words**
- Counting words for each of the categories
- Create a dictionary for each level that contains the most frequent words
- Categorize the different types of words (POStag)
- Grouping of letters
- Deal with deceptive cognates (list of 139 words)
- Deal with cognates (2 possible options)
  - List of 58,000 english words (need to be translated into French and then lemmetized both to obtain similar roots)
  - Look at the suffixes (e.g. words ending by "tion" have a high probabilty to have a straightforward translation in English)

**Sentences**
- Measure the length of sentences
- Count punctuation (i.e. a more complex sentence will tend to contain more punctuation)
- Count the different types of words

**Libraries to use**
- NLTK Snowball (stemmer)
- Spacy French LEFFF
- French specific libraries
- And more ...

### 💾 Datasets
To be completed

📗 **Books**

- Barnes, Djurna. 1986. *Le Bois de la nuit*. Points roman.
- Césaire, Aimé. 1939. *Cahier d'un retour au pays natal*. Paris: Pierre Bordas.
- De Beauvoir, Simone. 1949. *Le Deuxième Sexe*. Paris: NRF.
- De La Fontaine, Jean. 1778. *Fables de La Fontaine*. Fides.
- De Maupassant, Guy. 1885. *Bel-Ami*. Paris: Victor Havard.
- De Maupassant, Guy. 1887. *Le Horla*. Paris: Paul Ollendorff.
- De Saint-Exupéry, Antoine. 1943. *Le petit prince*. Paris: Gallimard.
- Diome, Fatou. 2003. *Le ventre de l'Atlantique*. Paris: Anne Carrière.
- Flaubert, Gustave. 1857. *Madame Bovary*. Paris: Michel Lévy frères.
- Echenoz, Jean. 2001. *Jérôme Lindon*. Paris: Éditions de Minuit.
- Pennac, Daniel. 2007. *Chagrin d'école*. Paris: Éditions Gallimard.
- Proust, Marcel. 1913. *Du côté de chez Swann*. Paris: Bernard Grasset.
- Proust, Marcel. 1918. *À l'ombre des jeunes filles en fleurs*. Paris: Éditions Gallimard.
- Queneau, Raymond. 1947. *Exercices de style*. Paris: Gallimard.
- Rostand, Edmond. 1898. *Cyrano de Bergerac*. Paris: Charpentier et Fasquelle.
- Schmitt, Éric-Emmanuel. 2001. *Monsieur Ibrahim et les fleurs du Coran*. Paris: Albin Michel.
- Verne, Jules. 1896. *Vingt mille lieues sous les mers*. Paris: Hetzel.
- Voltaire. 1759. *Candide*. Genève: Gabriel Cramer.
- Zola, Émile. 1883. *Au bonheur des dames*. Paris:	Georges Charpentier.
- Zola, Émile. 1877. *L’Assommoir*. Paris:	Georges Charpentier.

🔬 **Studies**

- OECD. 2019. *Études économiques de l’OCDE : Sythèse sur la Suisse*.  
  http://www.oecd.org/fr/economie/etudes/Suisse-2019-OCDE-etudes-economique-synthese.pdf
- Office fédéral de la statistique. 2020. *Endettement : Arriérés de paiement en 2019*.  
  https://www.bfs.admin.ch/bfs/fr/home/statistiques/situation-economique-sociale-population/revenus-consommation-et-fortune/endettement.html
- Office fédéral de la statistique. 2019. *Énergie : Aspects économiques*.  
  https://www.bfs.admin.ch/bfs/fr/home/statistiques/energie/aspects-economiques.html
- Office fédéral de la statistique. 2020. *Enquête suisse sur la santé (ESS) 2017 : Santé et genre*.  
  https://www.bfs.admin.ch/asset/fr/213-1719
- Office fédéral de la statistique. 2020. *Le système d'indicateurs «Mesure du bien-être»*.  
  https://www.bfs.admin.ch/asset/fr/1877-2000
- Office fédéral de la statistique. 2020. *Panorama de la société suisse 2020*.  
  https://www.bfs.admin.ch/asset/fr/2016-2000
- Office fédéral de la statistique. 2020. *Transport routier, ferroviaire et aérien : Coûts et financement des transports 2017*.  
  https://www.bfs.admin.ch/asset/fr/812-1700

📰 **Online Articles**

- AFP. 2021. "Spotify se lance dans plus de 80 nouveaux pays." *Le Temps*, February 23, 2021.    
  https://www.letemps.ch/economie/spotify-se-lance-plus-80-nouveaux-pays
- ATS. 2021. "Plus d'un tiers des appartements suisses sont occupés par des personnes seules." *Le Temps* February 25, 2021.       
  https://www.letemps.ch/suisse/plus-dun-tiers-appartements-suisses-occupes-personnes-seules
- Bazin, Xavier. 2021. "Vaccin en Israël : des chiffres troublants." *FranceSoir* February 25, 2021.  
  https://www.francesoir.fr/opinions-tribunes/vaccin-en-israel-des-chiffres-troublants
- Colleu, Yannick. 2021. "COVID 19 : les données de Santé Publique France sont-elles fiables ?" *FranceSoir*, February 24, 2021.    
  https://www.francesoir.fr/opinions-tribunes/les-donnees-de-sante-publique-france-sont-elles-fiables
- Etienne, Richard. 2021. "Genève accorde un prêt historique de 200 millions à l’aéroport de Cointrin." *Le Temps*, February 25, 2021.      
  https://www.letemps.ch/economie/geneve-accorde-un-pret-historique-200-millions-laeroport-cointrin
- Favre, Laurent. 2021. "Novak Djokovic est imbattable, la preuve par neuf." *Le Temps*, February 21, 2021.    
  https://www.letemps.ch/sport/novak-djokovic-imbattable-preuve-neuf
- FranceSoir, AFP. 2021. "Pays-Bas : le couvre-feu, objet d'un bras de fer judiciaire." *FranceSoir*, February 17, 2021.    
  https://www.francesoir.fr/politique-monde/covid19-au-pays-bas-la-levee-du-couvre-feu-suspendue-une-decision-de-justice
- FranceSoir. 2021. "Les néonicotinoïdes : une menace pour les mammifères." *FranceSoir*, February 21, 2021.   
  https://www.francesoir.fr/societe-environnement/les-neonicotinoides-une-menace-pour-les-mammiferes
- Genecand, Marie-Pierre. 2021. "La médiation de voisinage, comme si vous y étiez." *Le Temps*, February 8, 2021.     
  https://www.letemps.ch/societe/mediation-voisinage-y-etiez



