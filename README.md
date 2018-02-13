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
#### Boucle while
//Exemple 1
```c
int a=0;
while(a<50)
{
  a=a+3;
  prntf("%d",a);
}
```
//Exemple 2
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
int b=8;
if(b>0 && 

```
```c
switch
```

## Variables composées

```c

```
## Fonctions

```c

```
