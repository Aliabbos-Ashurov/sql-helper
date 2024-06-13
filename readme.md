# SQLHelper

SQLHelper is a Java utility class for handling SQL operations such as connecting to the database, executing queries, and retrieving generated keys. This class supports executing SQL statements and retrieving generated keys of type `Integer` or `UUID`.

## Features

- Connect to a database using JDBC.
- Execute SQL `INSERT`, `UPDATE`, `DELETE`, and `SELECT` statements.
- Retrieve generated keys (e.g., primary keys) from `INSERT` operations.
- Supports both `Integer` and `UUID` key types.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sqlhelper.git
    cd sqlhelper
    ```

2. Add the PostgreSQL JDBC driver to your project. If you are using Maven, add the following dependency to your `pom.xml`:
    ```xml
    <dependency>
        <groupId>org.postgresql</groupId>
        <artifactId>postgresql</artifactId>
        <version>42.2.20</version>
    </dependency>
    ```

### Explanation

- **Title and Description**: A brief description of the project and its features.
- **Installation**: Steps to clone the repository and add necessary dependencies.
- **Usage**: An example of how to use the `SQLHelper` class, including connecting to the database, executing inserts, and retrieving keys.
- **Methods**: A brief description of each method in the `SQLHelper` class.
- **License**: Information about the project's license.
- **Author**: The author's name.
- **Acknowledgements**: Acknowledges any libraries or tools used in the project.

This `README.md` provides a clear overview of the project and detailed instructions on how to use it.