

## Prerequisites

Before recreating the environment, ensure the following:

  ```bash
  pyenv install 2.7.18
  ```


## Steps to Recreate the Environment

####   Clone the Repository: Clone this repository to your local machine:
  ```bash
    git clone https://github.com/username/alpr-env-python2.git
    cd alpr-env-python2
  ```


#### Extract the Archived Environment: Extract the alpr-env.tar.gz into your pyenv environments directory:

  ```bash
  tar -xzvf alpr-env.tar.gz -C ~/.pyenv/versions/2.7.18/envs/
  ```
  This recreates the environment at:

  ``` ~/.pyenv/versions/2.7.18/envs/alpr-env ```

#### Verify the Environment: Check if the alpr-env virtual environment has been successfully recreated:

  ```bash
  pyenv versions
  ```
  You should see something like:

    ```bash
    2.7.18/envs/alpr-env
    ```

#### Activating the Environment

  Activate the recreated alpr-env environment using the following command:

  ```bash
  pyenv activate alpr-env
  ```
  You should see the environment name in your terminal prompt, e.g.:

  ```bash
  (alpr-env) ➜ ~
  ```
#### Verifying Dependencies

  After activating the environment, you can list the installed dependencies to ensure everything is intact:

  ```bash
  pip list
  ```
  This will display the packages and their versions.
