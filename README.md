# molu 👧

The mail provider in the Skedulr stack. It is currently built to work with Google Mail. But, by implementing the required communication APIs, more providers can be added into the `molu` group.

## Running It

1. Install the requirements by running

   ```bash
   pip install -r requirements.txt
   ```

2. Get a `client-secret.json` file from the Google Console with access to the Gmail API. Name this file `credentials.json` in the project directory.

3. Start the app

   ```bash
   python main.py
   ```
