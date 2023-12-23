class Animal {
    printAnimal() {
        console.log("I am from the Animal class")
    }
    printAnimalTwo() {
        console.log("I am from the Animal class")
    }
}

class Lion extends Animal {
    printAnimal(){  // method overriding
        console.log("I am from the Lion class")
    }
}

const animal = new Lion
animal.printAnimal()
animal.printAnimalTwo()