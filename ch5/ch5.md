# Référentiel & Mouvement

Comme d’habitude, les grandes découvertes commencent par des questions
simples. Notre point de départ est alors la question suivante : Suis-je
en mouvement ou immobile ?

## Mouvement

Afin de mieux comprendre les enjeux, considérons un jour de la vie de
Jules, Gilles et Jacques (meilleurs amis depuis l’âge de 5 ans) :

Jules et Gilles sont assis dans le train du métro. Jacques – qui arrive
toujours en retard – est sur le quai. Le train commence de se déplacer.
Qui est en mouvement ?

<div class="leftbar">

- Du point de vu de Jules : $`\begin{cases}
      \text{Jacques est \textbf{en mouvement}} & \\
      \text{Gilles est \textbf{immobile}}
      \end{cases}`$

- Du point de vu de Gilles : $`\begin{cases}
      \text{Jacques est \textbf{en mouvement}} & \\
      \text{Jules est \textbf{immobile}}
      \end{cases}`$

- Du point de vu de Jacques : $`\begin{cases}
      \text{Jules est \textbf{en mouvement}} & \\
      \text{Gilles est \textbf{en mouvement}}
      \end{cases}`$

</div>

Quelles conclusions pouvons-nous en tirer alors?

<div class="shaded">

- Pour étudier un mouvement, il faut définir précisément le **système
  considéré**, c’est-à-dire le corps ou le point auquel on s’intéresse.

- Toute étude du mouvement d’un corps doit être faite **par rapport**
  <span style="color: purple">(= with respect to</span>) à un
  observateur. On peut prendre un **point de référence** sur
  l’observateur par rapport auquel on étudiera le mouvement. La
  description du mouvement d’un mouvement du système **dépend en effet
  du point de référence choisi**. Le mouvement est donc relatif à ce
  point de référence.

- Ce point de référence s’appelle un **Référentiel**
  <span style="color: purple">(= frame of reference</span>).
  (L’observateur est, naturellement, immobile dans ce référentiel).

- Un mouvement est donc un **déplacement**
  <span style="color: purple">(= displacement</span>) (changement de
  position) par rapport à un point fixe.

</div>

Si on revient alors à l’exemple précédent, on voit que :

- Jules et Gilles sont immobiles dans le référentiel du Train
  $`\mathcal{R_T}`$

- Jacques est dans le référentiel du quai $`\mathcal{R_Q}`$

et donc

<div class="leftbar">

- Jules et Gilles sont : $`\begin{cases}
      \text{immobile dans }\mathcal{R_T} & \\
      \text{en mouvement dans }\mathcal{R_Q}
      \end{cases}`$

- Jacques est : $`\begin{cases}
      \text{immobile dans }\mathcal{R_Q} & \\
      \text{en mouvement dans }\mathcal{R_T}
      \end{cases}`$

</div>

## Référentiels

<div class="leftbar">

**Définition : *Référentiel***  
Un référentiel est constitué de :

- un objet (ou point fixe) par rapport auquel on étudie le mouvement
  d’autres objets.

- une horloge permettant un repérage des dates.

</div>

Je vous entends déjà demander *Mais ... Pourquoi a-t-on besoin d’une
horloge?”*

C’est simple, car pour que la description d’un mouvement (ou plus
précisément d’un ‘événement’) soit précise, il faut indiquer la position
du point considéré dans l’espace, mais *aussi* dans le temps !

Le choix d’un référentiel est arbitraire. C’est à nous de choisir le
point de référence. Par conséquent, le mouvement du système étudié
dépendra de ce choix.

<figure>
<img src="img/5/heliogeo.png" />
</figure>

Naturellement il y une infinité de référentiel possible, mais en
pratique il y en a quelques un qui sont plus utilisé et plus importants
:

- Les **référentiels Terrestres** sont construits à partir de n’importe
  quel **point de référence lié à la Terre**, c’est-à-dire un point fixe
  par rapport à la Terre. Ce sont les référentiels les plus naturels
  pour les êtres humains, et pour étudier des mouvements sur la Terre.

- Le **Référentiel Géocentrique** est souvent utilisé afin de décrire
  les mouvements des satellites de la Terre (e.g. la lune). Dans ce
  référentiel on peut imaginer une boîte que l’on découpe pour n’en
  garder qu’un coin. Supposons que le sommet du coin coïncide avec le
  centre de la Terre, et une de ses arêtes avec l’axe des pôles
  terrestre. Les deux autres arêtes du coin sont dirigées vers des
  étoiles fixes (les étoiles qui ne se déplacent pas dans le ciel). Ce
  coin représente le point de référence attaché au référentiel
  géocentrique. N.B. La Terre n’est pas immobile dans ce référentiel,
  car elle tourne autour d’une des arêtes du coin.

- Le **Référentiel Héliocentrique**, comme le référentiel géocentrique
  sauf que maintenant que le commet du coin coïncide cette fois avec le
  centre du Soleil. Une des arêtes est perpendiculaire au plan des
  orbites planétaires. Les deux autres sont dirigées vers les étoiles
  fixes. Ce coin représente le point de référence.

## Trajectoire

<div class="leftbar">

**Définition : *Trajectoire***

- La trajectoire d’un mobile est **une ligne ou courbe** décrite par
  n’importe quel point d’un objet en mouvement

- c’est l’**ensemble des positions successivement occupés** par ce
  point, dans l’espace

- la trajectoire dépend du mouvement, et le mouvement dépend du
  référentiel, **la trajectoire aussi donc dépend du référentiel**.

</div>

<div class="shaded">

**Exemple:** Considérons un point $`P`$ sur la roue d’un vélo. On peut
imaginer trois référentiels différents : $`\mathcal{R_C} =`$ Le cadre du
vélo ; $`\mathcal{R_T} =`$ La Terre ; $`\mathcal{R_R} =`$ La roue.

Voici donc le mouvement du point $`P`$ dans chacun de ces référentiels :

- Le point $`P`$ est dans $`\mathcal{R_C}`$ $`\longrightarrow`$ sa
  trajectoire est un point.

- Le point $`P`$ est dans $`\mathcal{R_T}`$ $`\longrightarrow`$ sa
  trajectoire est un cercle.

- Le point $`P`$ est dans $`\mathcal{R_R}`$ $`\longrightarrow`$ sa
  trajectoire est un cycloïde.

</div>

La description de la trajectoire dans un mouvement dépend de sa forme
géométrique. Si dans un référentiel la trajectoire est :

- Un segment de droite, le mouvement est dit rectiligne
  <span style="color: purple">(= rectilinear</span>).

- Une portion de cercle, le mouvement est dit circulaire.

- Une courbe, le mouvement est dit curviligne
  <span style="color: purple">(= curvilinear</span>).

# Vitesse

On a appris – j’espère – que la **vitesse moyenne**
<span style="color: purple">(= average speed</span>) d’un mobile est
donnée par l’équation :

``` math
v=\dfrac{d}{t} \text{ \quad   où \quad }
\begin{cases}
v \text{ est valeur de la vitesse moyenne, en }\; m\cdot s^{-1}&\\
d \text{ est la distance parcourue, en }m &\\
v \text{ est durée du parcours }(t_{arrivé} - t_{départ}) \text{ en } s
\end{cases}
```

Cette équation nous donne la valeur de la vitesse moyenne parcourant la
distance $`d`$ pendant l’intervalle $`t`$.

On a déjà établi, dans la partie précédente, que la distance parcourue
(qui dépend de la trajectoire) dépend du référentiel, c’est donc clair
que la **vitesse d’une point *aussi* dépend du référentiel**. Quand la
vitesse d’un mobile est constante, le mouvement est appelé **uniforme**.
Donc, par exemple, on objet qui trace un cercle avec une vitesse
constante a un mouvement **circulaire uniforme**.

Mais la vitesse d’un mobile n’est pas caractérisée par sa valeur
<span style="color: purple">(= magnitude</span>), mais aussi par sa
direction : il s’agit d’une grandeur dite **vectorielle**
<span style="color: purple">(= vectorial</span>) (i.e. une grandeur qui
as une valeur ainsi que qu’une direction). Dans le cas de la vitesse,
cette grandeur s’appelle le **vecteur** <span style="color: purple">(=
vector</span>) vitesse.

On peut étudier l’évolution de la vitesse d’un mobile, en comparant les
distances $`d`$ consécutives parcourues pendant la même durée $`t`$ :

- Les distances $`d`$ restent **constantes** = vitesse **constante**
  $`\longrightarrow`$ mouvement **uniforme**

- Les distances $`d`$ **augmentent** = la vitesse **augmente**
  $`\longrightarrow`$ mouvement **accéléré**
  <span style="color: purple">(= accelerated</span>)

- Les distances $`d`$ **diminuent** = la vitesse **diminue**
  $`\longrightarrow`$ mouvement **ralenti/retardé**
  <span style="color: purple">(= decelerated</span>)

<figure>
<img src="img/5/xo1.jpg" />
</figure>

<figure>
<img src="img/5/xo2.jpg" />
</figure>

<figure>
<img src="img/5/xo3.jpg" />
</figure>
