## SeaORM Tutorials

This repository contains step-by-step tutorials on how to use SeaORM to do CRUD operations from simple ones to very complex online applications in Rust Language.

The tutorial is based on a software system for managing fruits in a fruit market.

The tutorials are

1. **Simple CRUD operations** - This tutorials explains how to use SeaORM to do basic tasks like create a table in a database, insert a row into the table, update a column, delete operations and logging the results to the console. The database used is MySQL
2. **TODO Application** - This tutorial shows how to use SeaORM, SQLite and PostgreSQL to create a realtime sync TODO application where a user can buy fruits from the mango market.
3. **e-Commerce Market** - A complex application to manage a fruit market inventory, supplies, purchases and customers. It uses SeaORM, MySQL and SQLite and Rocket Web Framework. SQLite is used for the frontend embedded database and has a dekstop front.
4. **Web Frontend** - This tutorial ports the frontend of `tutorial 3` (***e-Commerce Market***) to the web using  [Mogwai](https://crates.io/crates/mogwai) which is a pure Rust frontend web framework with support for channels.

For additional help on **SeaORM** specific questions, join the support Discord chat [https://discord.com/invite/uCPdDXzbdv](https://discord.com/invite/uCPdDXzbdv)

### Running the tutorials

To run the tutorial code, switch to the directory of the turorial and run cargo

```sh
# Switch to tutorial directory
$ cd tutorial_folder_name

# Run cargo
$ cargo run
```



### Running the tutorial book

To run the tutorial book as local host first install [mdbook](https://crates.io/crates/mdbook)

```sh
$ cargo install mdbook
```

Then switch to the book folder in the current tutorial directory

```sh
$ cd tutorial_folder_name/book/
```

Then run mdbook

```sh
$ mdbook serve --open
```

This will open the book in your default browser. Alternatively, access it from any browser by visiting [http://localhost:3000](http://localhost:3000)

#### License

The information and examples provided in this repository are licensed under **Apache-2.0**

Cheers!