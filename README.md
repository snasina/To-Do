# To-Do
How to use Environment Variables keep your secret keys safe & secure!
Avoid (accidentally) committing (exposing) your private keys, passwords or other sensitive details(by hard-coding in them in your script) to GitHub by storing them as environment variables.

What is Environment Variable?
An environment variable is a KEY=value pair that is stored on the local system where your code/app is being run and is accessible from within your code.

How?
Follow these steps:

List all the Default Environment Variables
$ printenv
2. For storing our secret data like tokens, API keys, passwords create a file named app-env

export API_KEY="ABDJFdfrpf956irjglkfmgi5kgf"
export TOKEN="213j29rhdfn94htrfuh94"

3. Source this file into local environment using source command

$ source app-env
