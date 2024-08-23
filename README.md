# Login Manager App

Basic login system: it can read users from a JSON file, creating a default if necessary. Logins are checked, passwords are hashed, and different login roles work. This Login Manager application provides a command-line interface to the login system allowing for creation of new users, listing current users, update user password, and deletion of user records.

To run the project move into the project directory and run `cargo run -- ` followed by one of the commands listed below, for example:

```bash
cargo run -- help
```

You can also run `help` on any of the commands listed:

```bash
cargo run -- list -h
```

## Commands

| Command           | Description                                               |
| ----------------- | --------------------------------------------------------- |
| `list`            | List all users                                            |
| `add`             | Add a user                                                | 
| `delete`          | Delete a user                                             |
| `change-password` | Change a password                                         |
| `help`            | Print this message or the help of the given subcommand(s) |

> This project demonstrates the learnings from the first week of the [Ardan Labs: Ultimate Rust Foundations](https://www.ardanlabs.com/training/individual-on-demand/rust-bundle/) course.