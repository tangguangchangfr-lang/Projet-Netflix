# Netflix Content Strategy Analysis
Context:

Netflix, leader mondial du streaming, s’appuie sur un catalogue international riche et diversifié pour soutenir sa croissance et maintenir son avantage concurrentiel.
Dans un environnement marqué par une intensification de la concurrence (Disney+, Amazon Prime, HBO…), la compréhension de la stratégie de production et de distribution devient un levier clé de différenciation.
Ce projet se concentre sur l'analyse de la composition structurelle du catalogue Netflix via les données disponibles.


Problématique:

Comment les données du catalogue Netflix permettent-elles d’identifier les axes stratégiques de production, de saisonnalité et d’internationalisation ?

Objectifs d'analyse:

1. Quelle est la dynamique d’évolution du volume de contenus dans le temps ?
2. Existe-t-il des effets saisonniers dans la stratégie de sortie ?
3. Quels pays jouent un rôle structurant dans la production ?
4. Quels genres et classifications dominent le catalogue ?
5. Observe-t-on des adaptations locales dans le mix contenu ?

Jeu de données:

Dataset public du catalogue Netflix (format CSV)

Préparation & Modélisation:

Préparation des données sous Power BI (Power Query) : nettoyage, standardisation et création de variables temporelles.
Modélisation en schéma en étoile avec tables de dimensions (Date, Pays, Genre, Rating) et table de faits centrale, permettant une analyse multidimensionnelle performante.


Schéma étoile:
<img width="1092" height="753" alt="034156c0-5cec-4c54-a624-aa5ba0d74b2c" src="https://github.com/user-attachments/assets/c5d5881f-d36b-485e-b371-9040af8f2b71" />

Structure du dashboard:
Le dashboard est organisé autour de quatre axes d’analyse :
1. Tendance globale – Évolution du volume de contenus dans le temps
<img width="720" height="408" alt="image" src="https://github.com/user-attachments/assets/ef4dc172-3112-4774-ada5-7e23308ccc35" />

2. Saisonnalité – Répartition saisonnière et mensuelle des sorties
<img width="581" height="378" alt="image" src="https://github.com/user-attachments/assets/50e87c6a-b3aa-40c7-8b29-e8726e9d3a38" />
<img width="585" height="387" alt="image" src="https://github.com/user-attachments/assets/5abd142b-2181-4783-8ae6-ea39c66b431f" />

3. Répartition géographique – Pays producteurs et co-productions
<img width="768" height="536" alt="image" src="https://github.com/user-attachments/assets/26ce7290-bc75-4ebc-a51e-41cd02b04084" />
<img width="522" height="525" alt="image" src="https://github.com/user-attachments/assets/f36dd148-fc8e-4412-9477-27fb14d131b7" />

4. Segmentation des contenus – Type, genres et classifications
<img width="660" height="564" alt="image" src="https://github.com/user-attachments/assets/09b7752e-c2d2-4dda-876b-13b4b394c983" />
<img width="600" height="561" alt="image" src="https://github.com/user-attachments/assets/366c7748-1985-4518-ad50-0e83c463d10f" />
<img width="650" height="557" alt="image" src="https://github.com/user-attachments/assets/a4b00ced-4ec3-4711-b207-a6c05833fa26" />

Insights:
1. Une forte accélération à partir de 2015 et atteint le pic en 2019
2. L'été est la saison dont le volume de sorties est le plus élevé, surtout séries TV. Le un second pic est en décembre.
3. La co-production international occupe une place important dans le classement de la distribution des productions par pays.
4. Le filme occupe une place dominante, mais le série est le majoritaire dans le marché japonais et coréen du sud.
5. Les drames et les films internationaux sont les genres les plus présents
6. Les audiences principaux sont les adultes et les adolescents. Mais Netflixmais garde aussi les programmes variées pour les différents publics


Implications stratégiques:
1. Structurer une stratégie de sorties saisonnières: L’été et décembre sont des périodes fortes, Netflix pourrait optimiser ses lancements avec des campagnes plus ciblées.
2. Accélérer le développement dans les marchés asiatiques: Le dynamisme du Japon et de la Corée  suggère un potentiel important, surtout pour les séries.
3. Renforcer les co-productions internationales: Les contenus transnationaux sont déjà très présents, Netflix pourrait développer encore davantage de partenariats multi-pays.
4. Adapter plus finement les genres aux préférences locales: Les différences culturelles observées montrent que Netflix a intérêt à adapter encore davantage ses contenus selon les régions.

Outils utilisés
Power BI (modélisation et visualisation)
Power Query (transformation des données)
Modélisation en schéma en étoile
Git / GitHub

Limites de l’analyse:
1. Absence de données d’audience ou de performance réelle.
2. Analyse centrée sur la structure du catalogue et non sur le comportement utilisateur.














