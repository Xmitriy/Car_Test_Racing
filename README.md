### Game Overview

The concept of the Racer game is based on a racetrack circuit where players can increase their speed when driving behind an opponent. In simple terms, the player can gain speed when following an opponent, allowing them to overtake quickly.

The goal of the game is to give the player the chance to accelerate before moving from one lap to the next. Players could reverse time if they went off track or made a mistake.

The game's rewind feature was not implemented due to time constraints.

The player was able to use the game’s turbo boost. The player could restore turbo speed.

The game was generally challenging, as players often needed to use the rewind feature, but this functionality was not available.

Initially, the plan was to have six sections of track: two rural roads, two city roads, and two coastal roads. However, the coastal roads were not included in the final version.

Additionally, there were plans to include a character named "Bob," who would accompany the player to the next lap and guide them along the way.

### Track Effects

The game’s track divides the entire world’s path into six rectangular segments. The starting line of the track is located at z=0. These lines are mapped to the display space in alignment with the player’s vehicle.

### Sprites

Initially, the car sprites were in PNG format, but they became too large due to high resolution and size. As a result, the cars were created using 2D polygons and drawn using the canvas fill() function.

### Graphical Inspiration

The game's title was inspired by the titles of the C64 game "Pitstop II."

### Sound

Initially, the car engine sound was intended to be easily recognizable, but difficulties arose during coding. The engine sound was changed at the last minute.

### Opponent AI

The opponent's car speeds up when it reaches the highest position. This allows the AI to find the closest opponent within a certain distance and take advantage of the proximity for overtaking.

### Bugs and Fixes

- **Lack of Time**: A lot of time was spent on images, graphics, and game systems, which made some ideas impossible to implement.
- **Players Not Reading Instructions**: Players often failed to understand certain game mechanics and were unable to progress beyond the first lap.

---

### Aperçu du jeu

Le concept du jeu Racer est basé sur un circuit où les joueurs peuvent augmenter leur vitesse lorsqu'ils conduisent derrière un concurrent. En termes simples, le joueur peut gagner de la vitesse lorsqu'il suit un concurrent, ce qui lui permet de dépasser rapidement.

L'objectif du jeu est de donner au joueur la possibilité d'accélérer avant de passer d'un tour à l'autre. Les joueurs pouvaient rembobiner le temps s'ils sortaient de la piste ou faisaient une erreur.

La fonction de rembobinage du jeu n'a pas été mise en œuvre en raison de contraintes de temps.

Le joueur pouvait utiliser le turbo du jeu. Le joueur pouvait restaurer la vitesse du turbo.

Le jeu était généralement difficile, car les joueurs devaient souvent utiliser la fonction de rembobinage, mais cette fonctionnalité n'était pas disponible.

Au départ, il était prévu d'avoir six sections de piste : deux routes rurales, deux routes urbaines et deux routes côtières. Cependant, les routes côtières n'ont pas été incluses dans la version finale.

De plus, il était prévu d'inclure un personnage nommé "Bob", qui accompagnerait le joueur lors du prochain tour et le guiderait sur la voie.

### Effets de la piste

La piste du jeu divise le parcours mondial en six segments rectangulaires. La ligne de départ est située à z=0. Ces lignes sont mappées à l'espace d'affichage en fonction de la position du véhicule du joueur.

### Sprites

Au départ, les sprites des voitures étaient au format PNG, mais ils sont devenus trop grands en raison de la haute résolution et de la taille. Par conséquent, les voitures ont été créées à l'aide de polygones 2D et dessinées en utilisant la fonction fill() du canevas.

### Inspiration graphique

Le titre du jeu a été inspiré par les titres du jeu C64 "Pitstop II".

### Son

Au départ, le son du moteur de la voiture devait être facilement reconnaissable, mais des difficultés sont survenues lors de la programmation. Le son du moteur a été modifié à la dernière minute.

### IA des adversaires

La voiture de l'adversaire accélère lorsqu'elle atteint la position la plus élevée. Cela permet à l'IA de trouver l'adversaire le plus proche dans un certain rayon et de tirer parti de la proximité pour le dépassement.

### Bugs et corrections

- **Manque de temps** : Beaucoup de temps a été consacré aux images, graphiques et systèmes de jeu, ce qui a rendu certaines idées impossibles à mettre en œuvre.
- **Les joueurs ne lisent pas les instructions** : Les joueurs ne comprenaient souvent pas certaines mécaniques du jeu et ne pouvaient pas passer au-delà du premier tour.  
## Тоглоомын товч тайлбар


Racer тоглоомын санаа нь өрсөлдөгчийн ард жолоодож хурд авах боломжтой замын тойргийн үндсэн дээр хийсэн. Энгийнээр хэлбэл, тоглогч өрсөлдөгчийн ард байгаа үед хурд нэмэгдэж, энэ нь хурдан давших боломжийг олгодог.

Тоглоомын зорилго нь тоглогчийг эхний тойргоос дараагийн тойрогт шилжихээс өмнө хурдасгах боломжийг олгох юм. Тоглогч нар бэрхшээлтэй замд буруу явсан тохиолдолд цаг хугацаагаа буцаах боломжтой байсан.

Тоглоомын буцаах функц нь цаг хүрэлцээгүй учраас ороогүй. 

Тоглогч нь тоглоомын турбо-г ашиглах боломжтой байв. Хэрэглэгчийн турбо хурдыг сэргээх боломжтой байсан. 

Тоглоом нь ихэвчлэн бэрхшээлтэй байсан, учир нь тоглогчид цаг хугацаа буцаах функцийг хэрэглэх шаардлагатай байсан ч энэ боломж хэрэгжээгүй.

Эхэндээ зургаан замын хэсэг байх төлөвлөгөө байсан бөгөөд хоёр нь хөдөө нутгийн зам, хоёр нь хотын зам, хоёр нь наран мандсан эргийн зам гэж хуваагдсан. Эцсийн мөчид эргийн зам ороогүй.

Нэмж хэлэхэд, тоглоомд “Bob” гэдэг дүрийг оруулах төлөвлөгөө байсан бөгөөд тэр тухайн өрсөлдөгчийн хамт дараагийн тойрогт явж, тоглогчийг зааж өгч байх байсан.

## Замын эффект

Тоглоомд зам нь дэлхий дээрх бүхэл бүтэн шугамыг ашиглан зургаан тэгш өнцөгт хэсэгт хуваагддаг. Замын эхлэлийн шугам нь z=0-т байрладаг. Эдгээр шугам нь тоглогчийн машинтай уялдаатай дэлгэцийн орон зайд хөрвүүлэгддэг.

## Спрайтууд

Эхэндээ машины спрайтууд нь PNG хэлбэрээр байсан ч өндөр чанар, хэмжээнээс болоод хэт том болсон. Тиймээс, машинуудыг 2D полигоноор бүтээж, эдгээрийг canvas-ийн fill() функц ашиглан зурдаг байв.

## Графикийн урам зориг

Тоглоомын титлүүд нь C64-ын Pitstop II тоглоомын титлээс санаа авч бүтээсэн.

## Дуу

Эхэндээ машины хөдөлгүүрийн дуу нь амархан ойлгомжтой байхыг хүссэн ч код бичихэд олон хүндрэл үүссэн. Тоглоомын хөдөлгүүрийн дууг сүүлчийн мөчид өөрчилсөн. 

## Өрсөлдөгчийн хиймэл оюун

Өрсөлдөгчийн машин хамгийн өндөр байрлалд орсон тохиолдолд хурд нь нэмэгддэг. Энэ нь тодорхой зайд байгаа хамгийн ойр өрсөлдөгчийг хайж, орон зайд орж давуу талыг ашиглах боломжийг олгодог.

## Алдаа болон засах зүйлс

- **Цаг хугацааны дутагдал**: Зураг, график, тоглоомын системд их цаг зарцуулсан бөгөөд зарим санаануудыг хэрэгжүүлэх боломжгүй болсон.
- **Тоглогчид зааварчилгаа уншихгүй**: Тоглогчид тоглоомын зарим механизмыг ойлгохгүйгээр анхны тойргоос хэтрэхгүй байх.

