# Muuvie Secrets

In order to have all API keys required they are encrypted and committed to the repository.

- This requires the `key.txt` file which can be obtained by contacting `nicholasadamouemail@gmail.com`. `key.txt` should be placed in this folder.

- Currently only files with `.json` extensions are supported.

- If you update or add a `json` file you'll need to run `yarn encrypt` and then commit the encrypted files.

- If you pull a branch that has a set of updated secrets, you'll need to run `yarn decrypt` if it isn't run automatically by the [husky web-hook](https://github.com/flyblackbird/blackbird-payments/blob/60030b682af45a1e6092d18a3412095f02a8a208/package.json#L8-L12).