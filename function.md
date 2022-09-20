# function
définition: 
- fonction : une function est un bloc de code qu'on peut réutiliser
- argument: un argument est ce qu'on passe lorsque qu'on utilise une fonction
- parametre: un parametre est ce qu'on veut qu'on passe lorsque qu'on execute une fonction
exemple: 
```jsx
// age est un parametre
function myFunction(age) {
    return age * 2;
}

// 16 ici est un argument car on execute une fonction
myFunction(16);
```

exemple:
```jsx
function myFunction() {
    instruction;
}
```

une fonction peut accepter plusieurs arguments
```jsx
function myFunctionWithArg(age,name) {
    console.log("mon age: + " " + age);
    console.log("mon prenom" + " " + name);
}
```

une fonction peut retourner quelque chose
```jsx
function myfunctionReturnDoubleAge(age) {
    let doubleAge = age * 2;
    console.log("mon age doubler:" + " " + doubleAge);
    return doubleAge;
}
```

pour executer une fonction
```jsx
// on crée une fonction
function myFunction(age) {
    let doubleAge = age * 2;
    console.log("mon age doubler:" + " " + doubleAge);
}

// on execute la fonction
myFunction(16);
```