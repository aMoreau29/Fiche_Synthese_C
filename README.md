# Fiche Synthese C

## Variables

```c
int nb;  //entier
float reel;  //réel
char c;  //caractère
```

## Entrées-Sorties

type | indicateur | descricription
--- | --- | ---
int | %d | Entier
float | %f |réel
char | %c | caractere
char | %s | chaîne de caracteres

> Les printf et scanf doivent comporter autant de % que de virgules
### Affichage a l'écran
```c
printf("Le nombre entier est : %d", nb); 
```

### Lecture du clavier
```c
scanf("%f %d",&reel,&nb);
```

## Structure de controle
### Boucles
#### Boucle FOR
```c
int i;
for(i=5;i<=15;i++)
{
  printf("%d",i);
}
```
#### Boucle WHILE

```c
int a=0;
while(a<50)
{
  a=a+3;
  prntf("%d",a); //On peut sortir ce printf si l'on souhaite avoir seulement la valeur finale de a
}
```

```c
int entier;
do
{
printf("Veuillez rentrer un nombre entier positif");
scanf("%d",entier);
}
while(entier<0)
```
### Tests

```c
int Note=12;
if(b<=20 && b>=12) // on peut remplacer les '&&' (et) par des '||' (ou) 
{
  printf("Vous avez eu une bonne note");
}
else 
{
  printf("Vous n'avez pas eu une bonne note");
}
```
```c
printf("Combien d'enfant avez vous ?");
scanf("%d",&NbeEnfant),
switch(NbeEnfant)
{
case 0 :
   printf("Vous ne pouvez pas avoire de reduction");
   break;
case 1 :
   printf("Vous avez une reduction de 10%");
   break;
case 2 :
   printf("Vous avez une reduction de 30%");
   break;
default :
   printf("Vous avez une reduction de 50%");
   break;
}
```
## Variables composées

```c

```
## Fonctions

```c

```
