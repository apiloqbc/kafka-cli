# Kafka Utils

`kafka-utils` is a command-line interface (CLI) tool designed to perform various operations on Apache Kafka. This tool provides functionalities such as adding replicas to topics and generating replica information.

## Installation

To install `kafka-utils`, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/kafka-utils.git
    ```

2. Navigate to the project directory:
    ```sh
    cd kafka-utils
    ```

3. Build the project:
    ```sh
    go build -o kafka-utils
    ```

4. (Optional) Install it globally:
    ```sh
    go install
    ```

## Usage

The `kafka-utils` tool offers several commands to interact with Kafka. Below are the available commands and their usage:

### `replica`

Manages operations related to Kafka replicas. This command includes the following subcommands:

#### `replica generate`

Generates replica information for specified topics and outputs it to a JSON file.

**Usage:**
```sh
kafka-utils replica generate --topics <list-of-topics> --output <output-file>
