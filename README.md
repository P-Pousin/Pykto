# Pykto
Pykto Stylus Framework

**Pykto** is a small and easy to use CSS framework for **Stylus**

# Functionnalities

## Reset & Normalize

#### Mayer-reset

Pour inclure le Reset.css dans la page

```stylus
Meyer-reset()
```

#### Normalize

Pour inclure Normalize.css dans la page

```stylus
Normalize()
```

##Font-face 

Pour inclure une font dans votre page 

```stylus
Font-face( name, font-src, weight, style, formats, svg-font-name)
```

les arguments weight, style, formats et svg-font-name sont facultatifs

##Flexbox

Pour déclarer un élément flex

```stylus
DisplayFlex()
```

Et appliquer les propriétés flexbox

```stylus
FlexDirection(direction)
FlexWrap(valeur)
FlexJustifyContent(valeur)
FlexAlignItems(valeur)
FlexAlignContent(valeur)
```

##Transition

Pour appliquer une transition rapide à toutes les propriétés d'un élément

```stylus
Transition(temps)
```

##Scale

Pour appliquer un scale sur un élément

```stylus
Scale(valeur)
```

##Blur

Pour appliquer un filtre blur sur un élément

```stylus
Blur(val)
```

##Box-Shadow

Pour appliquer un filtre blur sur un élément

```stylus
BoxShadow(x,y,blur,distance,couleur)
```

##BorderRadius(val)

Pour appliquer un border-radius sur un élément

```stylus
BorderRadius(valeur)
```

##Couleur opacité

Pour transformer une couleur code hexa en rgba()

```stylus
OpacityColor(couleur,opacité)
```

##Triangle 

Pour créer un élément triangle

```stylus
Triangle(direction,taille,couleur,couleurFond)
```

La couleur de fond est par défaut à transparent
Les valeurs possibles pour direction sont :
* up
* down
* right
* up-left
* up-right
* down-left
* down-right

##Placeholder

Pour appliquer une couleur de text à un placeholder

```stylus
input
  +Placeholder()
    color #333
```

##Keyframes

Pour préfixer les keyframes d'une animation

```stylus
Keyframes(name)
  from
    color #333
  
  to
    color #FFF
```

##Animation

Pour préfixer une animation

```stylus
Animation(name,time,type)
```

