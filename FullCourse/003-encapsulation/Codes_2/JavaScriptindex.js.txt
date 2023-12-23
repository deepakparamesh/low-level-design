class Movie {
    // constructor
    constructor(t = "", y = -1, g = "") {
        this.title = t;
        this.year = y;
        this.genre = g;
    }

    // getters setters
    get_title() {
        return this.title;
    }

    set_title(t) {
        this.title = t;
    }

    get_year() {
        return this.year;
    }

    set_year(y) {
        this.year = y;
    }

    get_genre() {
        return this.genre;
    }

    set_genre(g) {
        this.genre = g;
    }

    print_details() {
        console.log("Title: ", this.title);
        console.log("Year: ", this.year);
        console.log("Genre: ", this.genre);
    }

}

const movie = new Movie('The Lion King', 1994, 'Adventure');
movie.print_details();

console.log("---");
movie.set_title("Forrest Gump");
console.log("New title: ", movie.get_title());