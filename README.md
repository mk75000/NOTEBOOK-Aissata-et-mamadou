# NOTEBOOK-Aissata-et-mamadou

Reconnaissance acoustique en milieu urbain pour personnes malentendantes 

 

#Introduction 

 

#Contexte 

La reconnaissance acoustique en milieu urbain constitue un défi technologique et sociétal majeur, particulièrement pour les personnes malentendantes. Dans les environnements urbains, une multitude de sons importants, tels que les klaxons de voitures, les sirènes d'ambulance, et les annonces publiques, jouent un rôle crucial dans la sécurité et l'information des habitants. Les personnes malentendantes peuvent rencontrer des difficultés considérables pour percevoir et interpréter ces sons, ce qui peut compromettre leur autonomie et leur sécurité. Afin de pallier ces limitations, le "Ministère du bien vivre en bonne santé" a lancé une initiative visant à développer des solutions innovantes pour améliorer la qualité de vie des personnes malentendantes en milieu urbain. 

Etudiants d'Epitech Digital School avons été mandaté pour développer un système de reconnaissance acoustique capable de détecter et d'identifier divers sons urbains. En utilisant des technologies de pointe telles que le deep learning et le framework PyTorch, nous visons à créer un modèle performant pouvant être intégré dans des appareils auditifs ou des dispositifs d'assistance, facilitant ainsi une meilleure perception de l'environnement sonore pour les personnes malentendantes. 

 

#Objectifs 

Notre projet a pour objectif principal de concevoir et de mettre en œuvre un système de reconnaissance acoustique utilisant des techniques de deep learning pour identifier divers sons urbains.  

En atteignant cet objectif, nous espérons non seulement répondre à une demande sociétale importante, mais aussi acquérir des compétences pratiques en deep learning, traitement du signal et développement embarqué. Nous visons également à contribuer à l'avancement de la recherche dans le domaine de l'acoustique urbaine, offrant ainsi des solutions tangibles pour améliorer la vie des personnes malentendantes. 

 

Pour réaliser ces objectifs, il est essentiel de s'appuyer sur les connaissances et les recherches existantes dans le domaine de la reconnaissance acoustique. Nous commencerons par une revue de la littérature afin de comprendre les progrès réalisés jusqu'à présent et d'identifier les technologies et méthodes les plus prometteuses pour notre projet. 

 

#Revue 

 

La reconnaissance acoustique a beaucoup évolué grâce au traitement du signal et au deep learning. Les premières méthodes utilisaient l'analyse spectrale et les modèles de Markov cachés, mais ces techniques avaient des limites. Les réseaux de neurones convolutifs (CNN) ont ensuite gagné en popularité pour extraire des caractéristiques à partir des spectrogrammes, surpassant les méthodes traditionnelles. Les réseaux de neurones récurrents (RNN) et les réseaux à longue mémoire à court terme (LSTM) permettent de capturer les dépendances temporelles, ce qui améliore la reconnaissance vocale et acoustique. 

Pour les personnes malentendantes, des systèmes de reconnaissance acoustique intégrés dans des appareils auditifs et des dispositifs d'assistance ont été développés. Ces systèmes utilisent plusieurs microphones et des algorithmes de séparation des sources pour mieux comprendre la parole et alerter sur des sons importants. 

 

#Technologies existantes 

Les technologies actuelles pour la reconnaissance des sons urbains incluent : 

Microphones et capteurs avancés : Captent les sons avec précision. 

Transformée de Fourier et Spectrogrammes : Convertissent les sons en images pour l'analyse. 

Réseaux de Neurones Convolutifs (CNN) : Identifient les caractéristiques des sons à partir des images de spectrogrammes. 

Réseaux de Neurones Récurrents (RNN) et LSTM : Traitent les sons dans le temps pour une meilleure reconnaissance. 

 

En s'appuyant sur ces avancées et technologies existantes, nous présentons ci-dessous la méthodologie utilisée pour notre étude sur la reconnaissance acoustique en milieu urbain. 

 

#Mise en Place de la Méthodologie 

 

Nous avons mis en place une méthodologie rigoureuse pour ce projet. L’'utilisation de BirdCLEF 2023, pour tester la généralisation de notre modèle. Nous prévoyons de convertir les fichiers audio en spectrogrammes, permettant ainsi aux modèles de CNN (neurones convolutifs) de traiter les données audio comme des images. Nous appliquerons également des techniques de normalisation et d'augmentation de données pour améliorer la robustesse du modèle. Ensuite, nous opterons pour un modèle de réseau de neurones convolutifs (CNN) avec plusieurs couches convolutives et entièrement connectées. Les hyperparamètres seront optimisés par une recherche par grille. Enfin, l'entraînement sera réalisé avec une validation croisée à k plis pour évaluer les performances de manière fiable, en surveillant des métriques telles que la précision, le rappel et le F1-score pour optimiser le modèle pour les sons urbains. 

 

 

#Attentes des Résultats 

 

Nous anticipons que notre modèle développé sera capable d'évaluer efficacement divers sons urbains, offrant ainsi une contribution significative à la qualité de vie des personnes malentendantes dans un environnement urbain. Nous espérons obtenir des métriques de performance solides, telles que la précision, le rappel et le F1-score, attestant de l'efficacité de notre système. De plus, nous comparerons les performances de notre modèle avec celles d'autres méthodes existantes dans le domaine pour contextualiser nos résultats. 

 

#Analyse des Résultats 

Nous prévoyons d'analyser en détail les conclusions de l'étude, mettant en évidence les insights significatifs sur l'efficacité du modèle et discutant des limitations rencontrées tout au long du processus. Nous identifierons et discuterons également des points faibles de notre étude, ainsi que des applications potentielles de notre système de reconnaissance acoustique dans le contexte urbain pour les personnes malentendantes, soulignant les avantages pratiques de notre approche et son impact sur la qualité de vie des personnes concernées. 

 

#Conclusion Anticipée 

 

En résumant les principales contributions de notre recherche, nous soulignerons l'importance de notre modèle de reconnaissance acoustique pour les personnes malentendantes en milieu urbain. Nous mettrons en évidence les avancées réalisées et les perspectives offertes par notre étude, tout en envisageant des directions pour des recherches futures et des améliorations possibles de notre modèle. Ces perspectives ouvriront la voie à de nouvelles opportunités de développement dans le domaine de la reconnaissance acoustique pour les personnes malentendantes en milieu urbain. 

 

Note book : inférence, résultats sur le datasetthe sound ai 

 

La précision, F-1 score => Mettre en FORMAT ARTICLE 

Présenter l’architecture différentes, mettre des graphiques 
