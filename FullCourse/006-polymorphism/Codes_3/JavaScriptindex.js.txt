class Area {
    calculateArea(length, breadth = -1) {
        if (breadth != -1)
            return length * breadth;
        else 
            return length * length;
    }
    
}


let area = new Area;
console.log('Area of rectangle = ' + area.calculateArea(3, 4));
console.log('Area of square = ' + area.calculateArea(6));